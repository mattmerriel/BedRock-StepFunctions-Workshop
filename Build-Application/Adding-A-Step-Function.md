# Adding A Step Function to our Project

In order to add a **Step Function** to our project we need to do two things:
1. Add a **Definition File** to the project that will contain all of the configuration details of the **Step Function**.
2. Add the **Step Function** to our template.yaml file which is basically just a **cloudformation** template and will be responsible for deploying what's defined in the **Definition File**.

## Adding A Definition File
To start off with we'll add a very simple, bare bones definition that just deploys a **Step Function** that does nothing. 

But before we start, we should take a look at the folder structure of the current project.

![Project Structure](folder-structure.png)

As you can see if the above screenshot, we have a number of files and folders already residing in our project. We will be changing the layout of this as we progress, otherwise you can find that things get a little messy and confussing.

For the time being, we need to create a new folder to host our **definition file**.
1. Start by creating a **src** folder in the root of the project and a **StepFunctions** folder under that so that you end up with something looking like this:

![folders-created](folders-created.png)

2. Next we can create the **Definition File** which is a modified JSON file
