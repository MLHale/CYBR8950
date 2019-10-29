# CYBR4580/8950 Final Project Milestone (Milestone 3): Final Delivery Increment, Packaging, and Release

380 Total Points

## Due Date
Tuesday December 17th at 5pm (class presentation time)
(Grad student only) Research paper due December 17th at 11:59PM
<!-- Thursday May 2nd (5/2/19) at 11:59pm  
Presentations Tuesday May 2nd (5/2/19) at 5 pm  
(Grad student only) Research paper due Friday May 3rd (5/3/19) at 11:59PM   -->
**No Extensions will be given!!!**

## Overview
This project milestone tasks you with producing your final major deliverable. Since every project is different the requirements stated below are as stated as generally as possible.

- [Project realization Progress Report](#project-realization-progress-report) - Clearly document your efforts towards achieving the project methodology since last milestone (Milestone 2).
  - Identify tasks achieved from your backlog
  - Document the product increments (an agile term for the things you produce) generated in this milestone
  - Bind tasks, code artifacts, and documentation together
- [Final Report: Packaging and Release](#packaging-and-release) - Package all of your product deliverables, results, and outcomes for release
  - The Final report should be non-trivial and list out all accomplishments across the project, pulling together the plan from milestone 1 and the deliverables achieved in Milestones 2 and 3.
  - The Final report should be delivered as-if you were preparing it for release to your customer. This means including sufficient supporting documentation to understand and fully interpret your results, install needed tooling, etc.
- [Presentation](#presentation) - Present your project to the class, your external partner (where applicable), and others in Cybersecurity
- [Graduate student paper](#graduate-student-paper) - If you are a graduate student, you must complete the additional paper as specified below.


## Project realization Progress report
Here, you should identify the tasks you have achieved in milestone 3, document the product or other intellectual/applied outcomes that have resulted from your efforts, and bind your tasks to the outcomes and documentation you have produced so far.

Be productive, work towards completing your process, and document what you do.

Documentation towards project realization will come in the form a project report. Your project report should be placed on GitHub in the same repository you used for Milestones 1 and 2. Create a new markdown file called `milestone-3.md` that contains the following.

```markdown
# Progress Report (insert date here)
## Overview
(insert brief overview of efforts made)

## Outcomes
(brief overview of outcomes - what did you achieve?)

also list them out like this:
* outcome 1
* outcome 2

## Hinderances
(insert brief discussion of challenges encountered)


```

### Submission materials
For this submission, you should submit your progress report as a `.md` file in your project GitHub repository

#### Grading Criteria
Your team will be graded as follows:

| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
| Effort and progress | It is clear that the team has made non-trivial effort and progress towards project realization.| There is some evidence of effort and progress, but more could have been done in the time. | Little effort or progress was made.|
| Documentation | Code artifacts and tasks are documented well. Documentation is clear and illustrative. | Some code is documented, but large portions are not. | Little or no documentation.|

**Total 80 points.**


## Final Report: Packaging and Release
An important part of developing or assessing a product is making the product or results accessible to those that might want to use it or them. This part of the final milestone tasks you with preparing your product, code, processes, and/or other relevant results for release by using relevant deployment strategies and by creating appropriate companion documentation. It is expected that every team will create a final report for release and review by partnering companies and organizations. All projects with code or other requirements must prepare a list of installation instructions and run instructions necessary to install and run any required apps. All projects examining existent systems must prepare a list of steps to reproduce their analysis.

### Code artifact Expectations
Expectations:
 * Polish your product by squashing as many bugs as possible and cleaning up the user interface.
 * Package your code and/or deployment environment for release using relevant deployment solutions such as [github](https://github.com/), [docker](https://www.docker.com/), [npm](https://docs.npmjs.com/getting-started/creating-node-modules), [bower](https://bower.io/docs/creating-packages/), [apt-get](https://help.launchpad.net/Packaging/PPA), [Python pip](https://packaging.python.org/distributing/), etc. The simplest deployment solution is creating a GitHub repository that is cloneable and has a few short install instructions. Other solutions like docker can be helpful in situations where the deployment environment context is complex or depends on certain versions of supporting software. Others like npm, bower, apt-get, or pip are useful for libraries that others might want to install or add to their own projects.
 * Create ```installation``` and ```getting started``` instructions using markdown in their repository or documentation to detail what an end-user must do to setup their app or product.

### Results and findings Expectations
 * Summarize your results discovered over the life of the project.
 * Summarize findings as they relate to the original proposal in milestone 1. What worked, what didn't work? Where would future work be most useful?
 * The report should arrange documentation generated over the project timeline in a logical way that supports the summary. Think of the final report as a compilation of all of your work over the semester. 
 
A suggested format for the final report is as follows:

```markdown
# Project name
## Executive Summary
(overview of project, reuse from milestone 1, update if scope changed)

## Project Goals
(high level project goals, reuse from milestone 1, update if scope changed)

## Project Methodology
(specific methodology followed in the project, reuse from milestone 1/2, update if scope changed)

## Results / Findings
(brief overview of outcomes - what did you achieve?, list milestone 1/2/3 outcomes, make an effort to logically collect and organize the findings)

(bulleted lists can also be helpful to structure your results discussion)
* outcome 1
* outcome 2

## Install Instructions (if applicable)
### Requirements
(list of any software / hardware requirements necessary to run the code/app/etc)

### Installation Instructions
(list of steps to install the product/app/code/etc)

### Getting started
(list of any steps to run the code after installation and/or manage the apps over their lifecycle)


```

### Submission materials
For this submission, you should submit your final report as a `.md` file called `finalreport.md` or `README.md` (to make it your default page) in your project GitHub repository. You should also convert the md file to pdf and upload it as `finalreport.pdf` for use on other non-web-based file stores. 

### Grading Criteria
| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
|Polish|Team has made clear efforts to prepare the results/product/app/etc for release. | Some bugs / user interface oddities / inconsistency of results are present, but overall some polish is evident. | The results/product/app are incomplete or inconsistent and/or not ready for release. |
|Packaging and Deployment| The results/product/app/etc is packaged and ready to be shipped to the customer as appropriate (i.e. results are documented well, products/apps are in a deployable / packaged state. | Some effort has been made to package results / code / resources / etc, but the packaging/deployment isn't fully successful making it difficult for the consumer to use the results of the project. | Little to no effort has been made to package the results/product/code for release and it is unusable by the customer. |
|Documentation Accuracy| Documentation is consistent and accurate. Assumptions are stated appropriately and/or getting started/installation instructions work as stated without issue. | Some documentation is missing or incorrect. | Many documentation artifacts are missing or inaccurate.|
|Activity and Findings Summary| Findings from project activities have been summarized at a high level and are presented in a tabular or graphical format that is easy to read and understand. Diagrams and visual aids are used effectively where needed. | Findings are missing from the summary or are difficult to read and understand as presented. | Little or no efforts were made to summarize findings and results are very difficult to read and understand. |
|Final Report Structure|The team prepares an overall report from existing documentation generated during the project. The report includes the assessment and finding summaries and connects the findings to existing documentation in the project repository. The final report is comprehensive. | Some report items are missing, or the report does not link to all activities and findings. | Little effort has been made to compile results of semester-long activities and results.|

**Total 200 points.**

## Presentation
You will be expected to present your Final Milestone to the class on our final day. There may be external guests present as well. A project presentation agenda will be released before the presentation day. Project teams will have 25 minutes to present, this time should include a few minutes (2-5 mins) to address questions. 

Your presentation should cover:
 * High level goals, initial scope, and adjustment to scope (keep it succinct)
 * Project methodology followed over the project
 * Principle Project findings and outcomes
 * Demos of any relevant tooling / code / attacks / etc that resulted from the work and/or findings
 
### Submission Materials
Submit your slides to Dr Hale as part of your overall submission on the day of the presentation. Submit them by uploading them in your project github repository and linking to canvas.

### Grading Criteria
Presentations will be graded using the following rubric. Each student on a team is expected to contribute to and help deliver the presentation.

| | Meets expectations (80-100% | Some Issues (50-80%)| Does not meet expectations (0-50%)|
|---|---|---|---|
| Organization of Presentation (20pts) | Team presents information in a logical, interesting sequence which the audience can easily follow. | Audience has some difficulty following presentation because of non-sequitur jumps of logic and sequencing. | Audience cannot understand or follow the presentation because there is poor or no sequencing of information |
| Comprehensive context coverage (20pts) | Team overviews relevant elements of the project (including goals, findings, outcomes, etc) succinctly, while using time well to focus on the most important and salient project outcomes. | Team misses some context but the project is presented in a broadly understandable way. | Team misses many elements of the project making it difficult for audience to understand their work without more context. |
| Demonstration of Outcomes (20pts) | The team provides an effective demo or representation of their project outcomes. | Team partially demonstrates outcomes. | Team does not demonstrate project outcomes. |
| Subject Knowledge (10pts) | Thorough understanding and grasp of the project is demonstrable. Students answer all questions with explanations and elaboration as appropriate. | Some gaps in knowledge are evident. Students fail to answer some questions with appropriate detail. | Large gaps in knowledge are evident. Students fail to answer most questions or fail to provide sufficient detail. |
| Graphics (10pts) | Graphics are used effectively to explain and reinforce screen text as appropriate. | A few graphics are used, but some areas of the presentation are missing graphics when they could be key to better understanding. | Few or no graphics are used. Team relies too much on text in slides. |
| Professional (10pts) | Slides have few or no misspellings, grammatical errors, or unprofessional content. No inappropriate memes or things of this nature are present. | A few misspellings, grammatical errors, or unprofessional items are included in the content. | Large reliance on inappropriate memes, multiple misspellings or grammatical errors are evident. |
| Eye contact and flow (10pts) | Team maintains eye contact with the audience, seldom or never returning to notes, and maintains good presentational flow between team members. | Team refers to some notes or a few hand-off pauses exist, but it does not interrupt the flow of discussion | Team must constantly refer to notes or there are long pauses that demonstrate poor practicing. |

* Note that Demos may include videos if the conditions necessary to replicate the demo cannot be re-created in a live in-class demo.

**Total 100 points.**

## Graduate student paper
If you are a graduate student, you must, in addition to your team work contributions, also complete a research paper about your project work. The research paper may be completed independently or working with other graduate students in your group (where applicable). In either case, the paper must address the following questions:

- What is the focus of your project, at a high level?
- How is your project significant within cybersecurity? 
- What findings from your project relate to cybersecurity best practices or on-going academic / industrial research and development? How might other practitioners or researchers use your work in the field?
- Contextualize the research literature as it relates to your project - What are other people / companies / labs doing that is similar to your work?

### Submission materials
You will submit a paper as a word document (.doc or .docx) to Dr. Hale. Format your paper using the [ACM paper template](https://www.acm.org/binaries/content/assets/publications/word_style/interim-template-style/interim-layout-.docx). This template is a two column format. Your paper should be somewhere between 5-10 pages in length (including figures). Your paper should include the following sections:

- Abstract
- Introduction
- Background
- (your sections go here) e.g. Methodology, Results 
- Conclusion

### Grading Criteria
Your paper will be graded on a 100 point scale (from 0 to 100). It will not be graded via rubric, but the following guidelines will be used to assess the paper.

- Does the abstract succinctly summarize the work? Does it state the high level problem and address how the work contributes to solving the problem?
- Claims made by the authors should be supported by appropriate research in the literature. References and citing should be used as appropriate. A works-cited set of references should be maintained and accurately included in the paper.
- Introduction - The paper should overview a problem, summarize effort by others towards addressing the problem, and identify how the project work contributes to filling gaps in other efforts.
- Background - Sufficient and relevant literature should be summarized and properly cited - including use of appropriately formatted referencing, as appropriate. 
- Sections addressing the problem and outcomes of the project should be well stated and overview the contributions of the authors. These might include, as an example a methodology section followed by a results section. 
- A conclusion section should highlight the salient outcomes of the paper and reinforce the findings with appropriate analysis or conclusive synthesis. 
- Grammar and spelling - The paper should be free of grammar and spelling errors. 
- Writing style - The paper should have a cohesive narrative flow that maintains the reader's interest. 

The quality of submission is understood to be a class paper. I do recognize that time is a limiting factor. If students decide to submit a shared graduate student paper among their teammates, I will expect the quality to be higher, given the reduced time burden associated with the group work.

#### License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CYBER4580 and related works</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://faculty.ist.unomaha.edu/mlhale" property="cc:attributionName" rel="cc:attributionURL">Matt Hale</a> are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
