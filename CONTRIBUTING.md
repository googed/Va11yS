#Contributing to Va11yS

### Welcome

We welcome contributions to the Va11yS Project in many forms, and there's always plenty to do!

First things first, please review the Va11yS Project's [Code of Conduct](CONDUCT.md) before participating. It is important that we keep things civil. 

### Getting help
If you are looking for something to work on, need some expert assistance in debugging a problem or working out a fix to an issue, our community is always eager to help. We hang out on [Slack](https://dwopen.slack.com); look for the [#open_a11y](https://dwopen.slack.com/messages/open_a11y/) channel. To join, visit the IBM developerWorks [Slackin](https://developer.ibm.com/open/slackin/) page.

### Reporting bugs
If you are a user and you find a bug, please submit an [issue](https://github.com/IBMa/ta11y/issues). Please try to provide sufficient information for someone else to reproduce the issue. One of the project's maintainers should respond to your issue within 24 hours. If not, please bump the issue and request that it be reviewed.

### Fixing issues and working stories
Review the [issues list](https://github.com/IBMa/Va11yS/issues). and find something that interests you. You could also check the ["help wanted"](https://github.com/IBMa/Va11yS/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) list. It is wise to start with something relatively straight forward and achievable. Usually there will be a comment in the issue that indicates whether someone has already self-assigned the issue. If no one has already taken it, then add a comment assigning the issue to yourself, eg.: ```I'll work on this issue.```. Please be considerate and rescind the offer in comments if you cannot finish in a reasonable time, or add a comment saying that you are still actively working the issue if you need a little more time.

We are using the [GitHub Flow](https://guides.github.com/introduction/flow/) process to manage code contributions. If you are unfamiliar, please review that link before proceeding.

To work on something, whether a new feature or a bugfix:
  1. Create a [fork](https://help.github.com/articles/fork-a-repo/) (if you haven't already)

  2. Clone it locally
  ```
  git clone https://github.com/yourid/REPO.git
  ```
  3. Add the upstream repository as a remote
  ```
  git remote add upstream https://github.com/ORG/REPO.git
  ```
  4. Create a branch

  Create a descriptively-named branch off of your cloned fork ([more detail here](https://help.github.com/articles/syncing-a-fork/))
  ```
  cd fabric
  git checkout -b issue-nnnn
  ```
  5. Commit your code

  Commit to that branch locally, and regularly push your work to the same branch on the server.

  6. Commit messages

  Commit messages must have a short description no longer than 50 characters followed by a blank line and a longer, more descriptive message that includes reference to issue(s) being addressed so that they will be automatically closed on a merge e.g. ```Closes #1234``` or ```Fixes #1234```.

  7. Pull Request (PR)

  When you need feedback or help, or you think the branch is ready for merging, open a pull request (make sure you have first successfully built and tested your changes.

   _Note: if your PR does not merge cleanly, use ```git rebase master``` in your feature branch to update your pull request rather than using ```git merge master```_.

  9. Any code changes that affect documentation should be accompanied by corresponding changes (or additions) to the documentation and tests. This will ensure that if the merged PR is reversed, all traces of the change will be reversed as well.

After your Pull Request (PR) has been reviewed and signed off, a maintainer will merge it into the master branch.

<!--## Coding guidelines

\[TODO] document your project's coding conventions and guidelines-->

<!---Becoming a maintainer - currently not maintaining a set of maintainers. : )
Projects or sub-projects will be lead by a set of maintainers. New projects can designate an initial set of maintainers that will be approved by the Technical Steering Committee when the project is first approved. The project's maintainers will, from time-to-time, consider adding a new maintainer. An existing maintainer will post a pull request to the [MAINTAINERS.txt](MAINTAINERS.txt) file. If a majority of the maintainers concur in the comments, the pull request is then merged and the individual becomes a maintainer.
--->

### Legal stuff
We have tried to make it as easy as possible to make contributions. This applies to how we handle the legal aspects of an original contribution. We use the same approach&mdash;the [Developer's Certificate of Origin 1.1 (DCO)](DCO1.1.txt)&mdash;that the Linux&reg; Kernel [community](http://elinux.org/Developer_Certificate_Of_Origin) uses to manage code contributions.
We simply ask that when submitting a pull request, the developer must include a sign-off statement in the pull request description.

Here is an example Signed-off-by line, which indicates that the submitter accepts the DCO:

```
Signed-off-by: John Doe <john.doe@domain.com>
```
If the contribution was derived from a WCAG Technique, please instead add the following sign-off line:
```
Signed-off-by: Jane Doe <jane.do@domain.com>. This contribution was derived by samples provided by WCAG techniques. 
```
Please see [Notice of copyright and disclaimers applied](NOTICE.md).
