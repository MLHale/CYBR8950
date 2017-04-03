## IA4580 Project Milestone 2: Exploring your top three user stories
**Assigned: Wednesday 3/8/17**

### Due Date
Monday Apr. 5th (4/5/17) at 11:59PM

### Overview
This project milestone tasks you with exploring your top three User stories. For makers - that means you will be creating features to support three of your user stories. For breakers, it means you should be conducting penetration testing and other relevant threat assessment procedures that fit into the first three user stories you've identified that are relevant. It also tasks you with generating relevant documentation associated with design and implementation (Features or attacks).

- [Architectural Diagram](#architectural-diagram) - How will you build your product (or how is your product built)?
- [Activity Diagrams](#activity-diagrams) - Identifies a workflow that describes the operation of your product.
- [User story realization](#user-story-realization) - Document and describe what was done.
  - Identify tasks achieved from your backlog
  - Document the product increments (an agile term for the things you produce) generated in this milestone
  - Bind tasks, code artifacts, and documentation together
- [Next Milestone planning](#next-milestone-plan) - Create a plan on trello for your next milestone
- [Presentation](#presentation) - Present your milestone 2 work to the class

### Architectural Diagram
An architecture diagram clearly identifies the various components and connectors that comprise a product. For this part of Milestone 2, you should create a diagram that shows how your product is composed together. If you are a maker, this means you should identify which components fit into your design, how you plan to connect them together, and how other (third party, etc) components fit into the design. Think about questions such as "What layers exist in my application?, Are components cleanly seperated from one another and are they appropriately coupled and cohesive?, How is data passed between components or external resources (e.g. are APIs being used appropriately)?" For breakers, your architecture diagram represents an exploration of the product you are evaluating. You should try, to the best of your ability to find or reverse engineer how the product is structured. Think about the same set of questions above, but from the perspective of identifying how it is designed, instead of how it *should be* designed. 

#### Submission materials
You should create your diagram using an architectural tool such as Lucidchart, MS Visio, or similar tools. You should include the diagram in your README.md file, in your github repo, as an image and/or link to lucidchart.

It should contain the following:

1. Components, represented as a box or a small picture. Each component must have a label that names it. Each component should identify input and output interfaces. On a seperate note (in markdown), you should briefly list and explain what each component does.
1. Connectors, represented as arrows with approrpriately labeled data sent over the connectors. 
1. Other grouping concepts, as necessary. In some cases, components may have sub components, systems might be part of a larger system of systems, or there could be other needs for identifying clusters of concepts. Use these where necessary.

**Follow UML or UML-like conventions to build your diagram**
For more information on component diagrams, see: 
* [http://www.uml-diagrams.org/component-diagrams-reference.html](http://www.uml-diagrams.org/component-diagrams-reference.html)
* [http://agilemodeling.com/artifacts/componentDiagram.htm](http://agilemodeling.com/artifacts/componentDiagram.htm)

### Grading criteria
Your architecture diagram will be graded as follows:

| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
|Approrpriate Components| Identifies relevant components in your product design | some components are tangential to user stories | components are not relevant to user stories |
|Component descriptions| Each component is described in accompanying text (in markdown). | Some descriptions are missing. | Components are not described in text.|
|Component labels| Each component is labeled and the labels are relevant. | Some components are not labeled, or are labeled poorly. | Many components are not labeled, or labeled poorly.|
|Coverage| Diagram containes a reasonable number of components for your user stories and product | Some obvious components are missing from the diagram | Many components are missing from the diagram|
|Usage of interfaces| Components clearly identify the input and output interfaces that make available | Some interfaces between components are undefined or unidentified | Many missing interfaces.|
|Approprpriate grouping and clustering| Concepts are grouped according to function or how they appear in the product. | There are some issues of grouping and clustering concepts.|  There are multiple issues with clustering and grouping concepts.|
|Clear and understandable| The diagram clearly and unambigously conveys the structure of the application or product. | The diagram leaves some concerns open for interpretation.| The diagram is not clear or understandable.|

**Total 70 pts**

### Activity Diagrams
In addition to a component-based architectural diagram, you should create activity diagrams for features that you are creating or exploring. I expect to see at least three activity diagrams for processes of relevance in your three chosen user stories.

Each diagram should clearly identify the workflow your product/app follows to achieve the end goal of the activity (typically the same as the feature goals in a user story). An activity diagram workflow begins with a start point (a black circle) and ends with a termination point (a black circle with a ring around it). In the flow may be process bubbles (ovals), and condition checks (diamonds).

For more information about activity diagrams, see:
* [http://www.agilemodeling.com/artifacts/activityDiagram.htm](http://www.agilemodeling.com/artifacts/activityDiagram.htm)
* [http://www.uml-diagrams.org/activity-diagrams.html](http://www.uml-diagrams.org/activity-diagrams.html)

#### Submission materials
You should create your diagrams using an architectural tool such as Lucidchart, MS Visio, or similar tools. You should include the diagram in your README.md file, in your github repo, as an image and/or link to lucidchart.

#### Grading Criteria
You should have 3 activity diagrams, each will be graded as follows:

| | Meets expectations (9-10) | Some Issues (6-8) | Does not meet expectations (0-5)|
|---|---|---|---|
|Connected to a user story| The activity diagram is connected to a user story | The activity is only loosely connected to a user story. | The diagram is unrelated to a user story. |
|Identifies relevant process elements| The diagram identifies important processes in the activity. | Some process elements are missing. | Process is incomplete or inarticulate. |
|Descriptive| The activity diagram clarifies the interoperation or operation of a feature of interest. It provides descriptive clarity. | The diagram provides limitied descriptive clarity. | The diagram doesn't help the viewer understand the process. |

**Total 90 points.**

### User story realization
Once you've created activity diagrams for your user stories, begin drilling into actually realizing (or completing) them. For makers, that means actually start coding and working to develop the features to support the stories. For breakers, that means actually crafting penetration and other tests to explore the operating and implementation of the selected user stories. As you do this, just keep basic documentation to connect your work to the ideas that created it.

#### Submission materials
For this submission, the submission materials are different depending on if you are a breaker or maker.

##### Makers
Makers should prepare a prototype application/product that demonstrates the three selected user stories. They should also document their code, link completed trello cards to code artifacts using the github integration, and be prepared to Demo their prototype to Dr. Hale.

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
|Prototype Demo| The product is successfully demoed for Dr. Hale. The team addresses and handles questions well. | The demo partially works, but there are some significant issues. | Many significant issues or non-functional prototype.|

##### Breakers
| | Meets expectations (33-40) | Some Issues (25-32) | Does not meet expectations (0-24)|
|---|---|---|---|
|Effort and progress| It is clear that the team has made non-trivial effort and progress towards user story investigation.| There is some evidence of effort and progress, but more could have been done in the time. | Little effort or progress was made towards user story realization.|
|Documentation| Testing procedures and tasks are documented well. Documentation is clear and illustrative. | Some tests and tasks are documented, but large portions are not. | Little or no documentation.|
|Results Discussion| The team discusses results with Dr. Hale and adequately answers questions. The team addresses and handles questions well. | Some results are discussed, but there are some significant issues. | Many significant issues or inability to discuss results or handle questions.|

**Total 120 points.**

### Next Milestone planning
Plan the next milestone. In the next (and final milestone) - you will explore your last two user stories and either 1) polish your product and prepare it for release (makers) or 2) integrate your tests and aggregate your results into a single assessment report for release to vendors or other relevant entities.

#### Submission materials
This part of the milestone is strictly captured by Trello. Make sure Dr. Hale has been added to your project Kanban boards. In your Kanban board, create a board following the structure discussed in Lecture 4. Use this structure to identify the tasks that you will tackle in your next sprint. Put those tasks in the **Sprint To-do** category. 

#### Grading Criteria
**Total 30 points.**

### Presentation
You will be expected to present your Milestone 2 achievements to the class following the deadline. It is important that you use this time to both inform your classmates of your activities and to practice for your final presentation. Things to be considered are 1) conveying a sense of interest and excitement about your project 2) cool product demos, and 3) interesting findings of conducting your projects.

#### Submission Materials
Submit your slides to Dr. Hale by 11:59pm on the day of the presentation. Submit them by posting and pinning them in your team slack channel.

#### Grading Criteria
You will be graded by a rubric TBA. 
**Total 60 points.**

#### License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CYBER4580 and related works</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://faculty.ist.unomaha.edu/mlhale" property="cc:attributionName" rel="cc:attributionURL">Matt Hale</a> are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
