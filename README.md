# Git commits
To make our commits straightforward and easy to understand, ideally we use the following format ( whenever is possible ) : 
​
`[ref] [context] - [subject/title/featureName] : [shortMsg]`
​
- `[ref]` reference the Jira ticket (if available) 
- `[context]` 
  - NEW: new piece of code
  - RFC: refactoring of an existing piece of code
  - BUG: fixing an existing bug
  - TEST: added/updated tests for a specific feature
  - STYLE: code restyling
​
> examples : 
> - `[#102] NEW - ZVTServer: enabled connection from terminals to server`
> - `[#138] BUG - Encoding: fixed encoding for diagnosis messages`
> - `RFC - Dockerfile: updated java version to java 17`
​
​
# Git branches
ideally the name of the branch should have the name/number of the ticket
​
# Pull requests
- [ ] the PR should have a significant description along with the Jira ticket id 
- [ ] Squash the commits to one single commit with an appropriate message ( ideally same format as commit messages)
- [ ] Remove source branch from local branches ( if you keep it will be automatically pushed to remote again later)
​
# Deployment ( staging / prod ) 
- [ ] add a tag with version name.
​
​
# Backend codeStyle 
- [ ] setup Code formatter in ur IDE [(we use Java Google Style Guides)](https://github.com/google/styleguide/tree/d9e72e63a97f86ebd4b32ede869ec75579b21d65) J
