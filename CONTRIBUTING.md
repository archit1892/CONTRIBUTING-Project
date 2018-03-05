# Contribution guide

Welcome to your Benzinga contribution. :smiley:

#### Table Of Contents
- [Getting Started](#getting-started)
- [Code of Conduct](#code-of-conduct)

### Getting Started

1.  If you are new to Git and Gitlab, it is advisable you go through [this
    link](https://docs.gitlab.com/ce/gitlab-basics/README.html)
    before moving to the next step.

2.  Clone the project.
3.  Create a branch specific to the issue you are working on.

    ```shell
    git checkout -b update-readme-file
    ```

    For clarity to yourself and others on the issue you're working on, name
    your branch something like `update-xxx` or `fix-xxx` where `xxx` is a short
    description of the changes you're making. For example `update-readme` or
    `fix-typo-on-contribution-md`.

4.  Open up the project in your favourite text editor, select the file you want
    to contribute to and make your changes.

5.  After making your changes in the new git branch then add your modified
    files to git, [How to add, commit, push and
    go](http://readwrite.com/2013/10/02/github-for-beginners-part-2/)

    ```shell
    git add path/to/filename.ext
    ```

    You can also add all unstaged files using:

    ```shell
    git add .
    ```

    Note, using a `git add .` will automatically add all files. You can do a
    `git status` to see your changes, but do it before `git add`.

6.  Commit your changes using a descriptive commit message with JIRA issue ID.

    ```shell
    git commit -m "EVENTS-125: BZ Awards Competition Leveling the Playing Field"
    ```
    Where **EVENTS-125**: would be ID of issue on JIRA.

7.  Push your commits to your Gitlab repo:

    ```shell
    git push -u origin branch-name
    ```

8.  Submit a merge request.

    Within Gitlab, visit this main repository and you should see a banner
    suggesting to make a merge request. While you're writing up the merge
    request, you can add `Closes #XXX` in the message body where `#XXX` is the
    issue you're fixing. So an example would be `Closes #42` would close issue
    `#42`.

### Submitting a Merge Request

What is a merge request?
[Visit link](https://docs.gitlab.com/ee/gitlab-basics/add-merge-request.html)

## Code of Conduct
If you want to contribute, you need to know a few things.
[Code of conduct](https://benzinga.atlassian.net/wiki/spaces/DFES/pages/178651202/Contributing+Code+Standards)

Thanks! :smiley:
