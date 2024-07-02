# How to migrate MS Access forms to Angular
GoatSwitch AI can be used to migrate MS Access forms to Angular.
## Setup
To start migrating code make sure you are using Visual Studio Code with the GoatSwitch AI extension installed.
Additionally, you need to export your MS Access forms to *.txt files to migrate them.

## Selecting a project
First pick the MS Access file you want to migrate. Right click it and press "TODO". [TODO IMAGE]

## Exploring the GoatSwitch AI activity bar
The activity bar in VS Code is located on the very left of the UI and enables you to go to the GoatSwitch AI extension[TODO].
[TODO] image
This is the main way to interact and observe the code migration process.
On the left you can see 5 views:
- Projects
- Translated Code
- Generated Tests
- Migration Instructions
- Migrate Using GoatSwitch

Those views enable you to interact with the migration process, fix errors and verify the outcome.

### View 1: Projects

View 1 contains a selection of pre-migration and post-migraiton projects. You can click these to select them.
Once selected the project becomes the focus project and all other views contain things related to this project.

### View 2: Translated Code

In view 2 you see all the files for your current project. Before migration this will show an MS-Access file, but as you migrate the project you will find the angular code here.

### View 3: Generated Tests

This is empty. The UI elements are tested by compiling them. If compiled successfully the test passed.

### View 4: Migration Instructions

This view can be used to instruct the AI to make changes to the code. You can enter things like "Please add comments to every function" or "Please translate all the comments into german" here.

### View 5: Migrate Using GoatSwitch

The button "Start the next stage" is the main way to interact with GoatSwitch AI. You can select a project in view 1 and start the migration with it or enter instructions in view 4 to make changes to the code.


