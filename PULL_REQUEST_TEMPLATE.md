<!-- Instructions: -->

<!-- Please ensure your title is in the correct format, e.g. FEATURE: Update widget A --> 
<!-- Please ensure you have tidied up your branch commits before creating a PR. If you have lots of small commits -->
<!-- please use `git rebase -i HEAD~x` where x is the number of commits you want to squash. Then squash all the -->
<!-- commits into one (or a few) commit(s) and make an appropriate comment for that/those commit(s). Then make sure -->
<!-- subsequent commits pushed to the PR have good comments. The commit comments will be added to the master in the -->
<!-- squashed commit -->

<!-- Please do not submit updates to dependencies unless it fixes an issue. --> 
<!-- Please try to limit your pull request to one type, submit multiple pull requests if needed. --> 

<!-- ========================================================================================= -->

## Pull request checklist

Please check if your PR fulfils the following requirements:
- [ ] Tests for the changes have been added (for bug fixes/features)
- [ ] Docs have been reviewed and added/updated if needed (for bug fixes/features)
- [ ] Build (`npm run build` or appropriate build command) was run locally and any changes were pushed
- [ ] Lint (`npm run lint` or appropriate lint command) has passed locally and any fixes were made for failures
- [ ] PR Title starts with one of the following: FEATURE:, FIX:, DOCUMENTATION:, BREAKING_CHANGE:
- [ ] Your branch commits are tidy and descriptive


## Pull request type

Please check the type of change your PR introduces:
- [ ] Bugfix
- [ ] Feature
- [ ] Code style update (formatting, renaming)
- [ ] Refactoring (no functional changes, no api changes)
- [ ] Build related changes
- [ ] Documentation content changes
- [ ] Other (please describe): 

Closes #


## What is the new behaviour?
<!-- e.g. This PR updates the authentication logic to check for users who are not logged in. -->


## Does this introduce a breaking change?

- [ ] Yes
- [ ] No
<!-- If this introduces a breaking change, please describe the impact and migration path for existing applications below. -->


## Other information
<!-- Any other information that is important to this PR such as screenshots of how the component looks before and after the change. -->
