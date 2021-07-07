# Naming Conventions

**NOTE: Document in progress. Please make a feature request for things you 
would like to see here.**

Conventions are helpful practices that teams follow to write code together. There are
many types of conventions that a lab strives to adhere to, such as _naming conventions_
or _data management conventions_.

<!-- toc -->

  * [GitHub](#github)
    + [Repository Names](#repository-names
      - [Use all lowercase letters.](#use-all-lowercase-letters-1)
      - [Use hyphenated spaces.](#use-hyphenated-spaces-1)
      - [Use versionless phrases.](#use-versionless-phrases)
    + [Branch Names](#branch-names)

<!-- tocstop -->


## GitHub

### Repository Names - first word

A lab's GitHub organization hosts many repositories that we use to collaborate. Each
repository name should represent the most general possible topic description for that
project. All repositories **must** start with one of the following terms:

task: refers to javascript/matlab/python tasks.
analysis: all sorts of analysis and data processing.
model: a computetional model. 
download: a script for data download.
class: code and data associated with classes that were taken by the lab.
tools: general tools associated with the lab.

### Repository Names - last word

The last word in the reporsitory names shoudl **always** include the name of the person who created the repo. 


### Repository Names - rest of text

The test of text should include information that would help an outside observer identify the specific meaning of the repo. 
In addition, please follow these guidelines: 

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

