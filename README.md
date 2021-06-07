# Pilot (PoC) Framework

## Goals
* document the agreements --> .md files
* track the progress --> milestones
* Q&A --> issues

## Conventions
- Individual requirements are documented in **user stories** (the smallest unit of work). The common structure for a user story addresses the “who, what, and why” of a feature: “As a *user type*, I want to *task* so that *goal*”. For example: “As a *customer*, I want to *create an account* so that *I can make purchases*”

- Requirements belonging to the same context are united as **epic**, which is a "big" user story. Difference: time and complexity. User stories should be completed in the smallest amount of time possible. If an issue will take weeks or months to finish, it should probably be an Epic.

- GitHub Issues have labels, which tag the content: epic, story, question, documentation, help wanted:

## Labels
Label| Description | Comments
--- | --- | ---
Epic | contains a list of user stories | markdown Checklist to track the progress, closed after all checkboxes are checked
User story | describes the smallest unit of work in the context or the epic | open/closed
Question | requires a brief description and images if needed, issue title start with Q&A| open/closed
Documentation | requests for improvements or additions to documentation | open/closed
Need help | high priority, extra attention is needed | open/closed


## Templates
File name | Description | Comments
--- | --- | ---
0_poc_details | Goals, risks, threats, success crierias, tasks, data sources | put in folder planing, split in details and tasks if needed, tasks will be taken over to requirements
1_poc_prerequisites | HW, SW, Platforms, Connectivity  | put in folder architecture with images, pdfs, configs
2_architecture | Images, Layouts, Data Sources | put in folder architecture with images, pdfs
4_poc_requirements | Epics (Boarder context requirements, agile epics) | each requirement is described in a separate doc, images put into a subfolder IMAGES



## Project Folder Structure
Folder name | Description | Comments
--- | --- | ---
architecture | to bind information about arch decisions | mds, pdfs, images 
planing | to put notes, minutes, other docs | mds, pdfs, images
requirements | to document epics (broarder context requirements, agile epics) and/or single user stories | document taxonomy in 0_poc_details, mds, configs, images