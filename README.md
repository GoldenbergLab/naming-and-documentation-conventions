# Naming Conventions

**NOTE: Document in progress. Please make a feature request for things you 
would like to see here.**

Conventions are helpful practices that teams follow to write code together. There are
many types of conventions that a lab strives to adhere to, such as _naming conventions_
or _data management conventions_.

<!-- toc -->

  * [GitHub](#github)
    + [Repository Names](#repository-names)
      - [Use all lowercase letters.](#use-all-lowercase-letters)
      - [Use hyphenated spaces.](#use-hyphenated-spaces)
      - [Use versionless phrases.](#use-versionless-phrases)
    + [Branch Names](#branch-names)

<!-- tocstop -->


## GitHub

### Repository Names

A lab's GitHub organization hosts many repositories that we use to collaborate. Each
repository name should represent the most general possible description for that
project. Some examples:

- count-cats-survey-analysis
- three-body-problem-download
- ameeting-model

**First & Last Word**

In the Goldenberg Lab, all repositories **must end with** one of the following terms:

- `task`: refers to JavaScript/MATLAB/Python tasks
- `analysis`: all sorts of analysis and data processing
- `model`: a computational model 
- `download`: scripts for downloading data
- `class`: code and data associated with classes that were taken by the lab
- `tools`: general tools associated with the lab

And, they **should start with** the name of the project.

**Body**

The rest of the repo's name should include information that would help an outside observer identify the project content of the repo. 
Please follow these guidelines: 

#### Use all lowercase letters.

- :white_check_mark: `my-new-repository`
- :no_entry_sign: `My-New-Repository`

#### Use hyphenated spaces.

- :white_check_mark: `twitter-survey-client`
- :no_entry_sign: `twitter_survey_client` or `twitterSurveyClient`

#### Use versionless phrases.

If you find yourself wanting to version your repository name, you
probably are interested in [releasing tagged versions](https://docs.github.com/en/github/administering-a-repository/managing-releases-in-a-repository)
of the project instead.

- :white_check_mark: `amplification`
- :no_entry_sign: `amplification-10-02` or `amplification-v1`

### Branch Names

Within a repository, you will have a minimum of one _default_ branch. A default
branch should be considered the _most stable_ branch, meaning the least likely to
contain bugs, errors, badly-written code, etc. In GitHub, the `main` branch is
the default branch (or `master` if created prior to late 2020; update the default
to `main` if so, [see why here](https://github.com/github/renaming)).

