## CoreValue GitHub rules:

### Commits:
* **JIRA ticket code:** Always add JIRA ticket code wraped in square brackets to the end of your commit message, example: "CoreBase: Redesign Lists page **[CB-75]**".
* **Sub-project's name prefix:** If project consists of several sub-projects like iOS app, Android app, web app, etc, use sub-project's name as a prefix of commit message, for example: "**Android:** Add login screen [CB-101]", "**iOS:** Time reporting screen redesign [CB-102]", "**CoreBase:** Redesign phase 1 [CB-103]", etc.
* **Clean commits:** Commits must only contain changes related to the task/feature you are working on.
* **No commits straight to develop**

### Branches:
* **Name:** Branch name should always be the same as a corresponding JIRA ticked code, ex. `CB-100`. In case your branch has no JIRA ticket (which shouldn't happen), make sure to give it a short hyphen separated name that makes sense, ex. `android-billing-refactoring`.
* **Rebase:** If you are working on your feature branch alone, make sure to always pull with `--rebase` to avoid unneccessary merge commits.

### Pull Requests:
* **Name:** Pull request's name must start from project name prefix and have JIRA ticket code wraped in square brackets at the end, for example: "CoreBase: Your new feature name [CB-100]". Pull request's description must contain a link to corresponding JIRA ticket.
* **Single pull request for a feature:** There always must be separate pull request for every single feature, bug fix, any kind of refactoring. Also, every pull request shoud correspond to single JIRA ticket/user story.
* **Pull requests discussions:** Feel free to actively review and comment open pull requests. Your eyeballs could help us to avoid of merging code with smells from one side, and from another side you will improve your skill of reading code and thinking of how you could implement feature/fix/refactoring under review.
