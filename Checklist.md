# PR Checklist
Please consider the following points when reviewing PRs
## Improves Codebase
- [ ] Does the change improve the overall codebase quality?
- [ ] Does the change have impact on the users?
    - [ ] If the code impacts users on the frontend have you checked the UI to see that it makes sense?
## Complexity
- [ ] Has the code gotten more complex?
This includes checking the following:
    - [ ] functions
    - [ ] individual lines
    - [ ] classes
## Tests
- [ ] Does the change include new or updated test cases to test the change?
Do the test cover any of the following and should there be others:
    - [ ] Unit Test
    - [ ] Integration Testing
    - [ ] End to End Tests
- [ ] Do the tests meet the code review standards outlined in this checklist?
## Naming
- [ ] Has the developer chosen good names which communicate what the item does without being too long?
## Comments
- [ ] Are any included comments clear and easy to understand
- [ ] Are all the comments necessary? They should explain why the code exists and not what the code does. Except Regex and complex algorithms
- [ ] Are any existing comments updated that need to be with this change?
## Style
- [ ] Does the change meet the style guide standards?
## Documentation
- [ ] Does the change include any updates to Docs, READMEs etc.
- [ ] If code has been deleted have the matching docs been deleted / updated as well?
## Context
- [ ] Has the code been checked out to ensure methods/classes haven't gotten too long and doesn't need to be broken up further.
## Good Points
- [ ] Does the PR include things that the reviewer is impressed with? Can you add this praise to the PR review comments.
