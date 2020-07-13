To get started:

Click on fork, scroll up. It is by the right top corner

Click on clone or download and copy the url link there

Head to your terminal.

git clone pasteTheUrlYouJustCopied

cd Team-12-devcareers-manage-landing-page

Step 6: To start your work, work the directory that contains the project files.

Step 7: git remote add upstream https://github.com/maxahmad/team-12-devcareers-manage-landing-page.git

Run: git checkout -b <nameOfBranch>

Don't forget the naming convention of branch.

Note: <nameOfBranch> should be replaced with the feature you are working on (i.e feat/signup-page-design), use hypen when you will normally use space

For example,
git checkout -b feat/sign-page-design ✅
git checkout -b feat/sign page design ❌

Branch can either be: feature or bug or chore

Now, once done writing code and you have tested it and everything is working fine.

Run: git add .
Run: git commit -m "feat: design signup page"

Note: when writing commit message, use present-tense

DO:
git commit -m "feat/design login page" ✅
git commit -m "bug/fix login page header bug" ✅

DON'T:
git commit -m "feat/designed login page" ❌
git commit -m "bug/fixed login page header bug" ❌

git push origin feat/-page-design - (Note how it ends with a branch).

Creating Pull requests

PR === Pull request

When making a PR, your PR is expected to have the following:

What is the task completed ?
What the PR actually does ?
How can this PR be manually tested ?
Any background contexts? (maybe something a tester might not notice and be useful for testing)

Please note: The commit messages should follow a consistent pattern:
Remember,

chore, feature, bug

For a feature:
git commit -m "feat: implemented user log-in For a bug: git commit -m "
For a bug:
git commit "bug: fix inconsistency in log in screen"
For a chore:
git commit -m "chore: update read me to include API endpoints"

Thanks!
