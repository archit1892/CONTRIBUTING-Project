# Contribution guide

Welcome to your Benzinga contribution. :beaker:

#### Table Of Contents
- [Getting Started](#getting-started)
- [Code of Conduct](#code-of-conduct)

### Getting Started

1.  If you are new to Git and Github, it is advisable you go through [this
    link](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)
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

6.  Commit your changes using a descriptive commit message.

    ```shell
    git commit -m "Brief Description of Commit"
    ```

7.  Push your commits to your Github Fork:

    ```shell
    git push -u origin branch-name
    ```

8.  Submit a pull request.

    Within GitHub, visit this main repository and you should see a banner
    suggesting to make a pull request. While you're writing up the pull
    request, you can add `Closes #XXX` in the message body where `#XXX` is the
    issue you're fixing. So an example would be `Closes #42` would close issue
    `#42`.

### Submitting a Pull Request

What is a pull request?
[Visit link](https://yangsu.github.io/pull-request-tutorial/)

If you decide to fix an issue, it's advisable to check the comment thread in
case there's somebody already working on a fix. If no one is working on it at
the moment, kindly leave a comment stating that you intend to work on it so
other people don't accidentally duplicate your effort.

## Code of Conduct
If you want to contribute, you need to know a few things.
[Code of conduct](https://benzinga.atlassian.net/wiki/spaces/DFES/pages/178651202/Contributing+Code+Standards)

Thanks! :beaker:
