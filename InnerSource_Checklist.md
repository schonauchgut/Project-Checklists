### Inner Source at Tektronix <a href="#note1" id="note1ref"><sup>1</sup></a>

****

Inner Source means sharing and developing software internally across traditional product line and business unit boundaries. It runs on the same principles as Open Source (e.g. universal access, transparency, community focused), but is considered proprietary since the projects are only allowed to operate within the company's firewall. Inner Source can be a great mechanism to help break down knowledge silos, encourage internal collaboration, accelerate new-hire onboarding, and identifying opportunities to contribute software back to the open source world. 

#### Project Check list 
This document is meant to be a guideline for starting an Inner Source project. Please contact [opensource@tektronix.com](email:opensource@tektronix.com) for any questions or assistance with any of the items in the checklist. 
***

##### Visibility:

Transparency is a core tenet of Inner and Open Source. It improves collaboration, and aides in the decision making process. This section of the checklist aims to help your project be successful by providing: Information, Access, and Permission. 

* The source code is in a place where it is visible and discoverable to all employees. This means at a minimum Read access is granted for all US authorized employees. 
* At least two people have administrative access to the project. 
* The issues board is in a place where it is visible and discoverable to all employees. This means Read and Write access is granted for all US authorized employees.
* The communication channel is public and discoverable to all employees in the organization. (e.g. Email Distribution List, Slack Channel, Microsoft Teams)
***

##### Documentation 

This part of the checklist will ensure your project is providing the right information, and how to create it. Visible documentation is part of transparency. Keep the documentation with the project as much as possible.

* Project has basic documentation (README, CONTRIBUTING, CHANGELOG, GETTINGSTARTED)
* Have a clear mission statement
* Apply the proper InnerSource Badges to project Documentation
* Issue queue is up-to-date, with issues clearly organized and labeled (future Road Map items are prioritized)
* Have a document that explains Coding style & Test conventions
* Have a document explaining Community guidelines
* Have the Branching Conventions publicly posted
* Display contact information for key members of the project
* Utilize a USERS.md file for counting project reuse
* Sprint schedule is posted (if applicable)
* Inform all stakeholders on the apportioned time that key members are able to commit to this project 
* Road Map, or link to issues board
* HOW TO guides on: 
    * How to submit a bug report/feature request
    * How to create a new pull request (CONTRIBUTING)
    * How to write documentation
    * How to build the project
    * How to use the test system
***

##### Automated Testing
Automated Testing provides the foundation for trust and scalability, and therefore is a key component of any Contributing Agreement. It should be in place before opening up the project to a wider audience. 
* Some form of unit tests or code coverage exists
* Builds are automated
* Tests are deployed against an automated build
* Every commit to a baseline branch (e.g. master) must be built and tested
* Anyone can see the results of the latest build
***

##### Versioning
* Consider a versioning scheme that guarantees a stable and latest revision of your project.

  Suggested versioning: <Major.Minor.Build.Revision>
***

##### Vision
* Key members for the project have been identified (maintainers, trusted contributors, etc.)
* The organization has a vision for the project that is both realistic and shared across all involved teams. 
***

##### Marketing Plan
* Is there a mechanism for making announcements that anyone in the organization can follow and search? (Email, slack, etc.)
* You have a plan for announcing and promoting the project. 
***

##### Legal
* Apply the proper Inner Source LICENSE file
* That any non-Company code is in a third_party directory.
* That it is in license compliance with any third-party dependencies.
***

##### Post Approval Steps
* Send Maintainer a Company sponsored "Thank You" (ie. Branded gear, inspire awards, thank you notes, etc.)
* Track project health and metrics
* Add Maintainers to #maintainers channel on Slack so that they can help solve eachothers problem
* Advertise project, contant info, communication channel, and maintainers inside the company (Newsletter Announcement, Sharepoint Page, etc.)
***

<a id="note1" href="#note1ref"><sup>  1</sup></a> Read more about inner source [here](http://paypal.github.io/InnerSourceCommons/)


