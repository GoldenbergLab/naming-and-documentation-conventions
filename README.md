# Repository Naming and Documentation Conventions

**NOTE: Document in progress. Please make a feature request for things you 
would like to see here.**

Conventions are helpful practices that teams follow to write code together. There are
many types of conventions that a lab strives to adhere to, such as _naming conventions_
or _data management conventions_.

<!-- toc -->

  * [GitHub](#github)
    + [Sample](#sample)
    + [Repository Names](#repository-names)
      - [Use all lowercase letters.](#use-all-lowercase-letters)
      - [Use hyphenated spaces.](#use-hyphenated-spaces)
      - [Use versionless phrases.](#use-versionless-phrases)
    + [Branch Names](#branch-names)
    + [Descriptions](#descriptions)
    + [Releases](#releases)

<!-- tocstop -->


## GitHub


### Example

See an example of a well-named and documented repository [here](https://github.com/GoldenbergLab/task-rl-phone-inspection-zi).

### Repository Names

The general structure of repository names is:

[KEYWORD]-general-description-of-project-[LEADNAME]

Some examples:

- `analysis-count-cats-survey-jonas`
- `download-three-body-problem-data-zi`
- `model-ameeting-amit`

**Sturcture of name**

Starting keywords include:

- `task`: refers to JavaScript/MATLAB/Python tasks
- `analysis`: all sorts of analysis and data processing
- `model`: a computational model 
- `download`: scripts for downloading data
- `class`: code and data associated with classes that were taken by the lab
- `tools`: general tools associated with the lab


Here are some examples for bad names:
- Joes-happiness
- joe-version1
- r-analysis-cats

Here are some examples for good names: 
- `task-happiness-stanford-network-longetudinal-amit`
- `analysis-emotion-regulation-intevention-covid-zi`

#### Use all lowercase letters.

- :white_check_mark: `my-new-repository-class`
- :no_entry_sign: `My-New-Repository-Class`

#### Use hyphenated spaces.

- :white_check_mark: `twitter-survey-client-data`
- :no_entry_sign: `twitter_survey_client_data` or `twitterSurveyClientData`

#### Use versionless phrases.

If you find yourself wanting to version your repository name, you
probably are interested in [releasing tagged versions](https://docs.github.com/en/github/administering-a-repository/managing-releases-in-a-repository)
of the project instead.

- :white_check_mark: `amplification-analysis`
- :no_entry_sign: `amplification-analysis-10-02` or `amplification-analysis-v1`

### Branch Names

Within a repository, you will have a minimum of one _default_ branch. A default
branch should be considered the _most stable_ branch, meaning the least likely to
contain bugs, errors, badly-written code, etc. In GitHub, the `main` branch is
the default branch (or `master` if created prior to late 2020; update the default
to `main` if so, [see why here](https://github.com/github/renaming)).

### Descriptions
Repository descriptions should include:
- Project Name (as the title)

- **Project goal:** [state the purpose] *The goal of this project is to...*
- **Important files:** [files you need to run the task] *index.html*
- **Papers:** [cite papers here]
- **To use this task:** *Clone repository and use the main task file. You may have to comment out the consent (line XYZ) to run the task locally.* 

### Commit names
Every github commit should start with one of the following words:
- `modification`: when a new code is added or removed. Designate the file and the purpose of the modification. 
- `fix`: when a specific bug is fixed. 
- `file change`: if files are added or removed. 

### Releases

Every **task** must have a release. 

1. To draft a new release you need to click on the right hand side of the GitHub repository and then press the releases button. 
2. Next you need to title your release; title it based off of the name of the repository. 
3. Give your release a tag, we typically use the tag V number, which corresponds to the version and number of the test that you are creating (`v1.0`)
4. Then describe your release, you can copy and paste to read me and any other relevant information. 

Making releases of your task is critical to allow other people to easily access them.
