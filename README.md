# Conventions

**NOTE: Document in progress. Please make a feature request for things you 
would like to see here.**

Conventions are helpful practices that teams follow to write code together. There are
many types of conventions that a lab strives to adhere to, such as _naming conventions_
or _data management conventions_.

The **easiest** conventions are **naming** conventions. We agree to a pattern of naming
for any given topic of work we do because consistent, predictable names help us find
what we're looking for. Named entities that we share are everywhere: Slack channels, GitHub repositories,
Amazon S3 bucket names, RMarkdown file names, and so many more.

<!-- toc -->

- [Tool Conventions](#tool-conventions)
  * [Slack](#slack)
    + [Channel Names](#channel-names)
      - [Use all lowercase letters.](#use-all-lowercase-letters)
      - [Use hyphenated spaces.](#use-hyphenated-spaces)
      - [Use descriptive phrases.](#use-descriptive-phrases)
      - [Use the minimum necessary words.](#use-the-minimum-necessary-words)
      - [Use category prefixes for nested channel naming.](#use-category-prefixes-for-nested-channel-naming)
  * [GitHub](#github)
    + [Repository Names](#repository-names)
      - [Use all lowercase letters.](#use-all-lowercase-letters-1)
      - [Use hyphenated spaces.](#use-hyphenated-spaces-1)
      - [Use versionless phrases.](#use-versionless-phrases)
    + [Branch Names](#branch-names)
- [Code Conventions](#code-conventions)
  * [JavaScript](#javascript)

<!-- tocstop -->

# Tool Conventions

## Slack

### Channel Names

A lab's Slack channels represent virtual rooms in which we can collaborate
on various topics. Our channel names should:

#### Use all lowercase letters.

- :white_check_mark: `code` or `language-analysis`
- :no_entry_sign: `Code` or `Language-Analysis`

#### Use hyphenated spaces.

- :white_check_mark: `language-analysis`
- :no_entry_sign: `language_analysis`

#### Use descriptive phrases.

- :white_check_mark: `reinforcement-learning`
- :no_entry_sign: `rl`

#### Use the minimum necessary words.

- :white_check_mark: `papers`
- :no_entry_sign: `papers-we-recommend`

#### Use category prefixes for nested channel naming.

Nested channel naming is useful for designating teams to work on a specific
project or stage of project that has sibling channels, such as two different studies,
which are category `studies`, or five different analysis-focused channels, which are
`analysis`-categorized.

- :white_check_mark: `studies_twitter-survey` or `analysis_emotion-amplification`
- :no_entry_sign: `studies-twitter-survey` or `emotion-amplification_analysis`


## GitHub

### Repository Names

A lab's GitHub organization hosts many repositories that we use to collaborate. Each
repository name should represent the most general possible topic description for that
project. Our repository names should:

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

# Code Conventions

## JavaScript

Anytime you use JavaScript, you should follow tried and true code style guidelines,
and especially so when that code is shared. While we will adopt a set of lab-specific
conventions for writing JavaScript over time, arguably the best style guide is the
[Airbnb JavaScript Style Guide](https://airbnb.io/javascript/).
