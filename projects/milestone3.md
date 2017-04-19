## IA4580 Final Project Milestone (Milestone 3): Exploring user stories, Packaging, and Release
**Assigned: Thursday 4/6/17**

### Due Date
Thursday May 4th (4/4/17) at class time (5:30pm)  
**No Extensions will be given!!!**

### Overview
This project milestone tasks you with exploring your last two user stories and polishing your work. For makers - you will be creating features to support your last two user stories, polishing your overall application, and packaging your product for release. For breakers, you will continue conducting penetration testing and other relevant threat assessment procedures that fit into the your last two user stories. Breakers will also prepare an overall assessment report by combining the generated documentation into a report format. The components of the Final Milestone include:

- [Activity Diagrams for last two user stories](#activity-diagrams) - Identifies a workflow that describes the operation of your product.
- [User story realization](#user-story-realization) - Document and describe what was done.
  - Identify tasks achieved from your backlog
  - Document the product increments (an agile term for the things you produce) generated in this milestone
  - Bind tasks, code artifacts, and documentation together
- [Packaging and Release](#packaging-and-release) - Package your code or assessment documentation for release
- [Presentation](#presentation) - Final Presentation

### Activity Diagrams
You should create activity diagrams for features that you are creating or exploring. I expect to see at least two activity diagrams for processes of relevance in your last two user stories.

Each diagram should clearly identify the workflow your product/app follows to achieve the end goal of the activity (typically the same as the feature goals in a user story). An activity diagram workflow begins with a start point (a black circle) and ends with a termination point (a black circle with a ring around it). In the flow may be process bubbles (ovals), and condition checks (diamonds).

For more information about activity diagrams, see:
* [http://www.agilemodeling.com/artifacts/activityDiagram.htm](http://www.agilemodeling.com/artifacts/activityDiagram.htm)
* [http://www.uml-diagrams.org/activity-diagrams.html](http://www.uml-diagrams.org/activity-diagrams.html)

#### Submission materials
You should create your diagrams using an architectural tool such as Lucidchart, MS Visio, or similar tools. You should include the diagram in your README.md file, in your github repo, as an image and/or link to lucidchart.

#### Grading Criteria
You should have 2 activity diagrams, each will be graded as follows:

| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
|Connected to a user story| The activity diagram is connected to a user story | The activity is only loosely connected to a user story. | The diagram is unrelated to a user story. |
|Identifies relevant process elements| The diagram identifies important processes in the activity. | Some process elements are missing. | Process is incomplete or inarticulate. |
|Descriptive| The activity diagram clarifies the interoperation or operation of a feature of interest. It provides descriptive clarity. | The diagram provides limitied descriptive clarity. | The diagram doesn't help the viewer understand the process. |

**Total 60 points.**

### User story realization
Once you've created activity diagrams for your last two user stories, begin drilling into actually realizing (or completing) them. For makers, that means actually start coding and working to develop the features to support the stories. For breakers, that means actually crafting penetration and other tests to explore the operating and implementation of the selected user stories. As you do this, just keep basic documentation to connect your work to the ideas that created it.

#### Submission materials
For this submission, the submission materials are different depending on if you are a breaker or maker.

##### Makers
Makers should prepare refine their prototype application/product from Milestone 2 by including features that support the last two selected user stories. They should also document their code, link completed trello cards to code artifacts using the github integration, and be prepared to Demo their prototype.

##### Breakers
Breakers should create writeups for each testing procedure they use to explore their selected user stories. They should also link completed trello cards to each testing procedure. A testing procedure, should identify:
* which component(s) were tested in the architecture
* what the purpose of the test was
* how the test was conducted
* results discovered from the test

#### Grading Criteria
Your team will be graded as follows:

##### Makers
| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
|Effort and progress| It is clear that the team has made non-trivial effort and progress towards user story realization.| There is some evidence of effort and progress, but more could have been done in the time. | Little effort or progress was made towards user story realization.|
|Documentation| Code artifacts and tasks are documented well. Documentation is clear and illustrative. | Some code is documented, but large portions are not. | Little or no documentation.|


##### Breakers
| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
|Effort and progress| It is clear that the team has made non-trivial effort and progress towards user story investigation.| There is some evidence of effort and progress, but more could have been done in the time. | Little effort or progress was made towards user story realization.|
|Documentation| Testing procedures and tasks are documented well. Documentation is clear and illustrative. | Some tests and tasks are documented, but large portions are not. | Little or no documentation.|

**Total 90 points.**

### Packaging and Release
An important part of developing or assessing a product is making the product or results accessible to those that might want to use it or them. This part of the final milestone tasks makers with preparing their product and code for release by using relevant deployment strategies and by creating appropriate companion documentation. Breakers, on the other hand, will prepare a final assessment report that summarizes their findings, connects findings to assessment activities, and packages everything for release and review.

#### Submission materials
For this submission, the submission materials are different depending on if you are a breaker or maker.

##### Makers
Makers will:
 * Polish their product by squashing as many bugs as possible and cleaning up the user interface.
 * Package their code and/or deployment environment for release using relevant deployment solutions such as [github](https://github.com/), [docker](https://www.docker.com/), [npm](https://docs.npmjs.com/getting-started/creating-node-modules), [bower](https://bower.io/docs/creating-packages/), [apt-get](https://help.launchpad.net/Packaging/PPA), [Python pip](https://packaging.python.org/distributing/), etc. The simplist deployment solution is creating a github repository that is cloneable and has a few short install instructions. Other solutions like docker can be helpful in situations where the deployment environment context is complex or depends on certain versions of supporting software. Others like npm, bower, apt-get, or pip are useful for libraries that others might want to install or add to their own projects.
 * Create ```installation``` and ```getting started``` instructions using markdown in their repository or documentation to detail what an end-user must do to setup their app or product.

##### Breakers
Breakers will:
 * Summarize their assessment activities and the threat landscape investigated in the project.
 * Summarize their assessment findings in a tabular or graphical format.
 * Prepare a final report document that links their assessment artifacts to their summary.
   * The report should be in markdown, PDF, or other online-readable format.
   * The report should arrange documentation generated over the project timeline in a logical way that supports the summary. Think of the final report as a compilation of all of your work over the semester.
   * The report should be linear file (probably markdown) with a summary page containing your executive summary, the assessment summary, and the result summary. The rest of the document should contain links to each assessment activity and its findings. The links should point to existing artifacts in your project repo.


#### Grading Criteria
##### Makers
| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
|Polish|Team has made clear efforts to prepare the product/app for release. | Some bugs or user interface oddities are present, but overall the product is reasonably polished. | The product is not ready for release. |
|Packaging and Deployment| The product is packaged and ready to be shipped using one or more deployment solutions. | Some effort has been made to package code and resources, but the deployment isn't fully successful. | Little to no effort has been made to package the product/code for release. |
|Installation and Getting Started Documentation| Installation and Getting started instructions work as stated without error. | Some instructions are missing or incorrect. | Installation and getting started instructions are missing or do not work.|


##### Breakers
| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
|Assessment Activity Summary| Assessment activities conducted over the project lifespan are summaried at a high level. | Some assessments are missing from the summary. | Little to no effort has been made to summary assessment acitivities. |
|Findings Summary| Findings from assessment activities have been summaried at a high level and are presented in a tabular or graphical format that is easy to read and understand. | Findings are missing from the summary or are difficult to read and understand as presented. | Little or no efforts were made to summarize findings. |
|Final Report|The team prepares an overall report from existing documentation generated during the project. The report includes the assessment and finding summaries and connects the findings to existing documentation in the project repository. |Some report items are missing, or the report does not link to all testing and assessment activities and findings. | Little effort has been made to compile results of semester-long assessment activities and results.|

**Total 120 points.**

### Presentation
You will be expected to present your Final Milestone to the class on our final day. There may be external guests present as well. A project presentation agenda will be released before the presentation day. Team projects will have 22 minutes to present. Solo projects will have 15 minutes to present.

#### Submission Materials
Submit your slides to Dr. Hale as part of your overall submission on the day of the presentation. Submit them by uploading them in your project github repository.

#### Grading Criteria
| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
| Enthusiasm and clarity | Presenter exhibits enthusiasm about the work and speaks clearly and confidently. | Some issues with clarity and enthusiasm. | Presenter has mumbles, is not clear, and/or does not demonstrate any enthusism. |
| Understanding of product | Presenter understands all aspects presented about the project. | Some gaps in understanding when questioned by audience or routinely looks at team slides |Poor understanding of project. |
| Relevant information | Engaging relevant information is presented about the project. | Valuable information is presented but there are multiple tangents. | Little valuable information is presented |
| Quick Re-cap of high level goal(s) | Overall goals are briefly recapped. | Too much time is spend on the goals | Way too much time is spent or goals are not covered at all. |
| Quick Re-cap of user stories | User stories are quickly re-capped. | Too much time is spent reading off user stories | Way to much time spent or no coverage at all. |
| Quick Re-cap of architecture | Overall architecture is briefly discussed in terms of important components or (for breakers) where tests were conducted. | Too much time is spent on the architecture. | Way too much time is spent or no coverage of architecture. |


| | Meets expectations (17-20) | Some Issues (10-16) | Does not meet expectations (0-9)|
|---|---|---|---|
| Demo* | Deliverable is demonstrated with accompanied explanation of outcomes and success. Product functionality is successfully demoed (makers) or important select tests are successfully demoed (breakers). | Demo is mildly successful. | Demo fails or is not included in the presentation | 
| Results | Results are overviewed, summaried, and relayed to the audience. For breakers that means covering significant findings. For Makers it means discussing your overall product results. | Limited results are presented or too much time is spent on minor results. | No results are presented or presenters waste a lot of time on minor results, missing time to present significant findings. |

* Note that Demos may include videos if the conditions necessary to replicate the demo cannot be re-created in a live in-class demo.

**Total 100 points.**

#### License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CYBER4580 and related works</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://faculty.ist.unomaha.edu/mlhale" property="cc:attributionName" rel="cc:attributionURL">Matt Hale</a> are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
