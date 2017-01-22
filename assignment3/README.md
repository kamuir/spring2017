# Assignment 3: Refactoring & Validation

#### Table of Contents 

[Problem Description](#problem-description)

[Requirements](#requirements)

[Design Specifications](#design-specifications)

[Deliverables](#deliverables)

[Working on the Assignment](#working-on-the-assignment)

## Problem Description
In this lab assignment, you are given a program written by someone else. This program was designed to provide the user with the ability to create, view, and edit grocery lists. As often happens to programs as more features are added, the code has become bloated and disorganized. It is now difficult to understand the code or extend the functionality of the program. You are facing a common problem referred to as **code debt**.

Your job is to redesign the program in accordance with good software engineering practices. This is a process known as **refactoring**. Refactoring may involve tasks such as renaming variables (many IDEs like Eclipse have built-in tools to refactor variable/function names) for better readability or reducing duplicated code through **functional decomposition**. Furthermore, you must ensure the program meets its requirements.

## Requirements

1. Eliminate redundant code
2. Improve the structure and organization of the code
3. Improve readability
4. Validate the functionality of the program (see program's [original requirements](GroceryListRequirements.pdf))
5. Adhere to Google's style guidelines

## Design Specifications

1. Eliminate redundant code by creating small, reusable functions.
2. Ideally, each `case` of the `switch` statement should invoke a method
3. Make the `main()` method as short as possible

You are not required to create additional packages, classes and/or objects. It is sufficient to have all the code in the GroceryList.java file.

### Secondary (bonus) objectives:

In addition to basic refactoring and validation, the program would benefit from a number of improvements:

1. Javadocs
2. Unit tests

Completion of each secondary objective will be worth bonus points.

## Deliverables

The refactored program (the GroceryList.java file).

### Deadline

The program must be submitted prior to the start of the next lab.

## Working on the Assignment
### Getting access to your repository
You will receive an email link to access the assignment repository via your mix account. You will be prompted to create a Team to work on assignment 3. If you choose to work with a partner, then only one of you should create the team, and the other person should join it. If you decide to work individually, you must still create a team. You will then be given a link to your team's private repository containing the starter code for the assignment.
### Importing the Project into Eclipse
The version of Eclipse on the lab computers comes with a Git plugin. If your own computer's Eclipse does not, you can install the EGit plugin for Eclipse.
1. Open Eclipse
2. Click File -> Import
3. Select Git -> Projects from Git. Click Next.
4. Select "Clone URI". Click Next.
5. Enter your team's repository URI. It will have the form `https://github.com/wvu-cs111/lab-assignment-3-<your-team-name>.git` then Click Next.
6. Ensure the `master` branch is selected. Click Next.
7. Choose an empty directory for this repository. For example `code/cs111/lab_assignment_3`. Click Next.
8. Select Import existing Eclipse Projects. Click Next.
9. Ensure Eclipse has found the assignment 3 project. Click Finish.
### Uploading Changes back to Github
### Synchronizing with your Partner
