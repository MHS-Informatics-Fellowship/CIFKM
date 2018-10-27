# CIFKM
Clinical Informatics Fellows Knowledge Management

This is a demonstration / sandbox with actual informatics content. The "real" version would have additional repositories for projects, for example:
* Knowledge Management repository
* *some project repository*
* *another project repository*

This keeps the organizational fuss to a minimum. The knowledge management repository would need a higher level of organization (including thoughtful use of issue labels, projects (like "Wiki Content"), and directory structure. On the other hand, there'd be only one repository with any real maintenance requirements. With a good initial setup and joint management by the fellows, this should be workable. The main drawback is the single wiki. I expect the wiki mostly to be used for MHSG info, but the case could be made that MHS Genesis should have its own repository.

The knowledge management repository would be communally owned, so to speak; all fellows would have administrative access. Project repositories would be adminned by the fellow heading the project, allowing a measure of access/team control. 

# Use of Issues and Knowledge Management Projects
Projects would be set up for each content type (lectures, journal clubs, MHS Genesis stuff, etc).

Issues would be used to request content. Issue labels ("lecture request" etc) allow easy sorting of work. 

**Automation With Project Boards**:
* New issues assigned to a project automatically show up on its To Do list.
* Issues that are closed are automatically moved to its Done list.
* Closed issues that are re-opened are automatically moved to its In Progress list.

**Use case 1**: 
* Dr. Marshall submits issues for each lecture topic the fellows need to cover. 
* The issues appear in the To Do list on the Lecture Content project board. 
* Fellows are notified of the new requests and claim a topic by assigning the issue to themselves and moving it to the "Assigned" list.
* The fellow submits the lecture and closes the issue, automatically moving it to the "Done" list.

**Use case 2**: 
* Darshan learns that the ED is trying to fix a broken widget in FirstNet, and no-one knows how to fix it.
* Darshan submits an issue with the "need info" label to the MHSG project; the request moves to the "To Do" list
* Darshan claims the issue and moves it to "In Progress"
* Justin knows part of the fix, and comments directly on the issue without claiming it
* Darshan and Justin discuss the problem in the issue comments
* A solution is found, and Darshan closes the issue (automatically moving it to "Done").
* David creates a wiki page to document our new FirstNet knowledge from Darshan's issue comments

# Other GitHub Capabilities To Look Into
**[GitHub Desktop](https://desktop.github.com/)**: opensource, cross-platform GUI for working with Git/GitHub without the command line

**[GitHub Pages](https://pages.github.com/)**: we're allowed to have one [website per organization/account and unlimited project websites](https://help.github.com/articles/user-organization-and-project-pages/). [Jekyll](https://help.github.com/articles/about-jekyll-themes-on-github/) is supported for themes and blogs, and naturally it supports whatever you can pull off in HTML/CSS.
* The Good: it's free and hosted in the repository, making it easy to update
* The Bad: it's statically hosted and doesn't support server-side scripting

**[Webhooks](https://developer.github.com/webhooks/)**: GitHub supports a variety of webhooks, though I'm not sure what we would use them for. Here's a [good primer](https://codeburst.io/whats-a-webhook-1827b07a3ffa). 

**[GitHub Apps](https://developer.github.com/apps/differences-between-apps/#about-github-apps/)**: These integrate GitHub with third party services. Apps can be found at the [marketplace](https://github.com/marketplace), including a [project management page](https://github.com/marketplace/category/project-management). This would allow integration with Jira, for example, or [CodeTree](https://github.com/marketplace/codetree), which would allow us to manage issues from multiple repositories in a single screen. This might be useful as we accumulate project repositories. However, most of the third-party services have their own fees.
* [ImgBot](https://github.com/marketplace/imgbot) losslessly compresses images in your repository and is free!
