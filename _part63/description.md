---
type: description
---
Using QA Project
----------------
One of the central functionalities of the U-QASAR platform is the management of quality projects.  shows an example of a Quality Project at the U-QASAR Platform. Each project is structured as tree-like structure where Quality Objectives, Indicators and Metrics are presented in relationship to the project. U-QASAR user can add or delete new items, edit existing ones, move the item's locations in the tree etc. In the section to the right the fields of the item are shown, can be viewed and further edited. To make it less painful to search for relevant information there are fields used for filtering data in the upper part of the screen.

Creating QA Projects
--------------------
The user may create quality projects from scratch or use the import functionality to make existing projects available to the platform. 
The user selects the option of creating a new QA project. The project details are requested by the platform from the user: name, acronym, start date, end date, target value, LC Stage, method for the quality average calculation (weighted or not) and description. The user fills in the information and saves it. This results in a new QA project. Alternatively, if the user wishes to cancel the creation, no data is saved.


<img src="qp_create.png " width="760" alt="Quality Project: Creating a new Quality Project" />


Creating a new QO/QI/Metric for QA Project
------------------------------------------
In order to calculate the quality of a project, several elements are needed in Project's Tree: Quality Objectives, Quality Indicators and Metrics. These elements should be created depending hierarchically from the Project. There are two ways of doing that: the first one, which consists on selecting a subset of the active Quality Model, has been explained in chapter  Creating QA Projects; the second one, consists on creating one by one the needed elements in Projects' Tree. To do that the user needs to click on the "+" icon at the bottom of the Tree and select which type of element wants to be created, as shown in the following figure:

<img src="qp_createQO.png " width="760" alt="Quality Project: Creating a Quality Objective for a Quality Project" />

By doing that a new window will appear for the user to enter element's details, which in general are: Name, Description, Thresholds, Target value, Weight and Formula
A Quality Objective is an aggregation of one or more Quality Indicators. At the same time, a Quality Indicator is an aggregation of a set of metrics. In the field named Formula, which exists only for quality objectives and indicators, the mathematical formula for calculating the value of the element using its children's values is entered. The hierarchy of elements is established by creating each element depending on the corresponding parent in the Tree.
Once all the needed elements are created, they will appear in Projects' Tree: Each time the user needs to edit the details of an element he/she can do it by clicking on the "Edit" icon which appear on the right side of the screen when the element is selected in the Tree.
