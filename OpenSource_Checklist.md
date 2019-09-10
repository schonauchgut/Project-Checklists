# Open Source Project Checklist

## Documentation
*	Project has a LICENSE file with an approved open source license
*	Project has basic documentation (README, CONTRIBUTING, SECURITY)
*	Try building the project. Are the instructions easy to follow and working?
*	The name is easy to remember, gives some idea of what the project does, and does not conflict with an existing project or infringe on trademarks
*	The issue queue is up-to-date, with issues clearly organized and labeled
*	Run project FOSSA to ensure license compliance
* Appropriate Badges are applied (Tektronix, Keithley, CodeFactor, LGTM, etc.)

## Code
*	Project uses consistent code conventions and clear function/method/variable names
* Check code quality with CodeFactor
* Check code security using lgtm
*	The code is clearly commented, documenting intentions and edge cases
*	There are no sensitive or proprietary materials in the revision history, issues, or pull requests (for example, passwords or other non-public information)
*	It doesn’t include anything linked to our Company’s “secret sauce”
*	That any non-Company code is in a third_party directory.
*	That it is in license compliance with any third-party dependencies.
*	There are no patent issues. There are no privacy issues. A legal review will be required if your code collects any data about users and transmits it back to us or if it affects or transmits third-party content.
* Create a code owners file so that reviewers are automatically assigned on new Pull Requests. See [GitHub Blog: Introducing Code Owners](https://github.blog/2017-07-06-introducing-code-owners/)

## People
*	Close any issues with legal
*	Determined that we won’t want to sell this in the future
*	You have a marketing plan for announcing and promoting the project (optional)
*	A Community Manager is identified and documented in your README and committed to managing community interactions
*	A Project Maintainer is identified and documented in your README and committed to managing code changes and direction 
*	At least two people have administrative access to the project
*	Sharing the project helps users, not just our competitors.

## Post Approval
*	Add project to codefactor.io so that defect metric tracking is enabled
*	Publish on github.com/Tektronix 
* Advertise Internally (Sharepoint, Newsletter, etc.)
* Track project metrics and health
* Add maintainers to #maintainers Slack channel to help them solve each others problems

