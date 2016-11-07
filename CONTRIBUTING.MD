# Contributing to Red Guide Community Resources

Thanks for being interested in contributing to resources managed by the Chef Red Guide community. The following information will help guide you in the process to helping us.

Contributions come in a variety of formats whether through documentation, code, or illustrations to convey information.

## Setting up your environment 

## Submitting Issues

### Is this a security issue?

We take security seriously. Please contact us via X to report a potential security issue with full information about the version of cookbook or tool that is impacted, the version of chef-client that you are using, and the specific platform details (operating system and cloud provider if running on cloud instances). Describe what you were trying to do and what happened. Include the steps to reproduce the issue. 

### Report other issues

Each repository within the organization will have an Issues tab on the Github website. We use this Issues functionality to submit, confirm and triage problems for each project. 

## Process for contributing to a project

(Do we want to follow the Chef model of Developer Certificate of Origin (DCO))

1. Fork the project of interest.
2. Clone the project locally.
3. Create a branch that informs the change you are making. If you are fixing a specific issue, issue_NUMBER is an example.
 * Example: git checkout -b issue_1.
4. Add code or documentation.
5. Validate tests.
6. Commit your code back to your fork.
7. Create a pull request describing your changes and any potential issues resolved.

## Merging Contributions

1. Do tests pass?
2. Does new functionality include testing?
3. Has new or changed functionality include updates to documentation?
4. Has one other person contributed a :+1:?

If the above is true, merge the changes into master. Remember that we are seeking to be nimble in our reviewing and merging of contributions, so if something is really broken, let's get the fix in and add an issue or secondary pull request to add the testing or documentation.

## Obvious Fixes

Small contributions that are obvious fixes do not require additional :+1: to be merged. These are based off the [official Chef community cookbook guidelines](https://github.com/chef-cookbooks/community_cookbook_documentation/blob/master/CONTRIBUTING.MD#chef-obvious-fix-policy).

Obvious fixes include the following:

* Spelling/grammar fixes
* White space and formatting changes
* Comment clarification or clean up
* Moving source files from one directory or package to another
* Adding logging or debugging output

## Chef Red Guide Community

Find us on the [Chef Community Slack](https://community-slack.chef.io/) in the Red Guide Channel, #redguide.
