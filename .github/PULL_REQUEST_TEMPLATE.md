<!---
This file outlines a list of common things that should be addressed when opening a PR. It's built from previous issues we've seen in a lot of pull requests. If you notice something that's being noted in a lot of PR's, it should probably be added here to help save people time in the future.
-->

## Please fill out the following before requesting review on this PR

### Description
*Give a high-level description of the changes in this PR*

### Testing Done
*Outline any testing that was done for these changes. This could be unit tests, integration tests, etc.*

### Resolved Issues
*Link any issues that this PR resolved. Eg `resolves #1, #2, and #5` (note that they MUST be specified like this so Github can automatically close them then this PR merges)*

### Review Checklist
*(Please check every item to indicate your code complies with it (by changing `[ ]`->`[x]`). This will hopefully save both you and the reviewer(s) a lot of time!)*
***It is the reviewers responsibility to also make sure every item here has been covered***
- [ ] **Start of document comments**: each `.cpp` and `.h` file should have a comment at the start of it. See files in `src/sample_package` for examples.
- [ ] **Function comments**: All function definitions (usually in the `.h` file) should have a javadoc style comment at the start of them. For examples, see the classes defined in `src/sample_package`
- [ ] **Remove all commented out code**
- [ ] **Remove extra print statements**: for example, those just used for testing
- [ ] **Resolve all TODO's**: All `TODO` (or similar) statements should either be completed or associated with a github issue
***Feel free to make additions of things that we should be checking to this file if you think there's something missing!!!!***


