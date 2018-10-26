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

Issues would be used to request content. Issue labels ("lecture request" etc) allow easy sorting of work, and assigning the issue to the corresponding project automatically moves it through a To Do - In Progress - Done workflow on the Kanban board. 

**Use case 1**: 
* Dr. Marshall submits issues for each lecture topic the fellows need to cover. 
* The issues appear in the To Do list on the Lecture Content project board. 
* Fellows are notified of the new requests and claim a topic by assigning the issue to themselves. 
* This automatically moves the issue to the "In Progress" list. 
* When the fellow submits the lecture, the task is dragged to the "Done" list and the issue is automatically closed. 

**Use case 2**: 
* Darshan learns that the ED is trying to fix a broken widget in FirstNet, and no-one knows how to fix it.
* Darshan submits an issue with the "need info" label to the MHSG project; the request moves to the "To Do" list
* Justin knows part of the fix, and comments directly on the issue without claiming it
* Darshan claims the issue (moving it to "In Progress"), comes up with the solution, and moves it to "Done"
* Darshan creates a wiki page to document our new FirstNet knowledge
