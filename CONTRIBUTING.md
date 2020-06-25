# Contributing

## Introduction

This manual is a living document that improves with the contribution of others.
In order to be exhaustive, data modalities need to be added as they are
identified. There are many ventures, projects, and data streams that are
valuable to ETI and deserve to be included. Readers are
encouraged to add missing information if they believe something should be added.
Since this manual exists on GitHub, there are several methods for contribution.
This repository can be forked, edited, and contributors can send pull requests
for review. Alternatively, issues can be raised for identifying errors. For
more information on collaborating with GitHub, please refer to the [GitHub
help page](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests).

## How to contribute

The following instructions provide details on how to add content to the manual:

1. Request access to edit the private repository. Development occurs here to avoid
sharing details on sensitive data that is under privacy rules. Access is granted
by first filling out the form [here](https://forms.gle/j6RzKrsrQSTQWFFw6).

2. [Make a fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
of the private repository.

3. [Create a branch](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches) off `main`, which
should be up-to-date with the currently published version of the manual.

4. Make your contributions to the branch:

- Make sure to add a row to the data table, it should look like this:
| Data Source Name  | | | x | x | |
Where each modality is marked with an `x`.

- If the data source introduces a new modality, add that column to the data table.
Then, add a section in `Data Modes` briefly describing the type of data.

- Add a section to `Data Streams` describing the data source. This should
include links to documentation for the source, how the source was collected,
and any expectations for data use.

- If the addition is a multi-modal data set. Make a separate markdown page
detailing the project or venture as a whole. See `MINOS.md` for an example.

5. [Commit and push](https://help.github.com/en/github/using-git/pushing-commits-to-a-remote-repository) your changes.

6. [Create a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) for your changes
and it will be reviewed!