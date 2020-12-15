# Code Review

## Iterative approach

### Iteration 1

Validating if the pull request is created in compliance with company established standards. The goal is to validate if the pull request is created and documented properly:

* Validate if you’re the right person to review it
* Validate if the source and target branches are correct
* Check if required reviewers are added \(if it’s not automated in your source control\)
* Check if build and unit tests are passing \(if it’s configured in your source control\)
* Validate if pull request description is added \(PR comments, work item, etc\)

### Iteration 2

Validating if code solves the problem it is supposed to:

* Carefully read the problem description \(comment, bug, user story, etc\) code is aiming to solve and get an understanding of the context
* Compare line-by-line if the described problem is solved and try to figure out what lines of code solve what parts of the problem
* If necessary - download the code and run a quick test locally

### Iteration 3

Code design:

* Verify if code is not relying on libraries/components that are not approved within your organization
* If available, verify if the code matches the defined architecture and specifications
* If applicable, verify if the code is not introducing new patterns unless communicated and approved by the senior staff
* Verify if introduced custom solutions can be replaced with framework/library features
* Verify if edge-cases are covered and risk is minimized. Come up with the theoretical scenarios for breaking the system
* Exceptions should be as concrete and detailed as possible and logged
* Verify if the code complies with OOD/Functional principles

### Iteration 4

* Validate is necessary performance optimizations are done. May require more attention depending on the frequency of usage and performance expectations
* Validate the solution against your company's security standards

### Iteration 5

* Verify if all of the code is following company code style \(naming conventions, spacings, structure, etc\)
* Verify if the code is readable and easy to understand
* Code style is consistent within the module
* Make sure that created functions aren’t too large and have clear namings and purpose
* No commented out code introduced
* No “magic” numbers introduced
* Introduced hacks are commented with reasoning
* Unit tests are updated/created
* Validate if PR is not introducing code duplication
* Validate if changed areas have the impact analysis performed and documented
* Loop through remaining “todo”s in the code and remind to address them

## 

