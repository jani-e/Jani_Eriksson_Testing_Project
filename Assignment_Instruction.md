# Assignment guidelines

Last modified: 10.08.2021

> Note: This assignment guideline can stay in your submission. Kindly do not modify the guideline.

# Table of content
[ToC]

# Download Template
- **Step1:** Download the Project_Tmplate.zip file.
- **Step2:** Unzip the Project_Template.zip file on your computer.
- **Step3:** Open the Test files one by one from the PageObject folder
- **Step4:** Edit the Test file as per the Assignment instruction describing below in the Assignment Task section or Assignment_instruction.md file.
- **Step:5** Write a bug report 
- **Step6:** Edit the Learning Reflection file as per the Assignment instruction describing below in the Assignment Task section or Assignment_instruction.md file.
- 
# Assignment Deliverables

- [ ] Create Test cases for all pages which are already there in PageObject folder
  - [ ] 03_RegisterPage
  - [ ] 04_ProjectPage
  - [ ] 05_IssuePage
- [ ] Perform all TODO: tasks describe in each above pages
- [ ] Create bug report for one test case which are already there in BugReport folder
  - [ ] 02_ProjectPageReport
- [ ] Write Learning Reflection page and upload in LearningReflection folder with name "Firstname_Lastname_LearningReflection"
- OR write in the file 01_LearningReflection.md
  
# Assignment Evaluation

> Evaluation will be based on the following targets:

- Projects and learning reflection are evaluated base on the below criteria total of 100%
- Documentation for test suits 10%
- Write process test steps with the human-readable sentences 20%
- Clearly define variables 10%
- Clearly define validation and assertion 10%
- File for bug report 10%
- Learning reflection 40%

# Assignment overview

### Functionality overview

The example application GitLab is a complete DevOps platform that enables professionals to perform all the tasks in a project—from project planning and source code management to monitoring and security. Furthermore, it allows teams to collaborate and build better software.

URL: https://gitlab.com


## Home page

- URL: https://gitlab.com/ 
- Precondition: login
- List of projects
- Pagination for list of projects

## Sign-in page

- URL: https://gitlab.com/users/sign_in

## Sign up page

- URL: https://gitlab.com/users/sign_up

## Profile page

- URL: https://gitlab.com/-/profile

## Project page

- to create a project
- URL: https://gitlab.com/projects/new
- Create a new blank project: https://gitlab.com/projects/new#blank_project
- Create a new project from template: https://gitlab.com/projects/new#create_from_template

## Issue page

- Precondition: project
- URL: https://gitlab.com/group-slug-here/project-slug-here /-/issues/new
- Delete issue (click on pencil-icon for Edit or Delete issue)


## How to write Testcase

- Open PageObject/01_TestSuit_template.txt, guide you through the sections where you need to write detail about the test case and test suit.
- Learn from Canvas Workspace page 7.2 | How to write Test case and each detail

## Sample Test Cases for Login page

- Open web application URL: https://gitlab.com/users/sign_in
- Open PageObject/02_LoginPage.txt
- Notice the sections in the above file, Settings, Variables, Testcases, and their fields Description, Tags, Precondition, Postcondition, Data, Testcase steps, section and understand each step when you log in to the web application
- Check out each scenario's steps as described in the 02_LoginPage test suit.

## Assignment Tasks

1. Open Application for Test
2. Open the Test text file from the PageObject folder
3. Edit the Test text file as per the instruction
4. Write predefined fields 
   - Settings
   - Variables
   - Description
   - Tags
   - Precondition
   - Postcondition
   - Data
   - Testcases and process steps
5. Start Testing the application as described in `TODO:` tasks by writing manual test cases for a given app
6. Write Testsuit predefined fields
7. Write Testcase title
8. Write each step for the test case and used test data besides that or write variable name
9. Repeat for the rest of the files of the PageObject folder
   - 03_RegisterPage.txt
   - 04_ProjectPage.txt
   - 05_IssuePage.txt
11. Check out bug reports from the folder
   BugReport/01_Template_BugReport.txt
11. Write down bug report for the page Project creation
12. zip all folders and text files
13. Upload to the Canvas platform as Assignment return
14. Remember to write down the name of the folder as define on the assignment page.
15. “Firstname_Lastname_Testing_Project.zip” 
16. Or Upload your project file on Github and share your repository link or give collaboration access to the teacher
17. When you submit your assignment on the Canvas learning platform then kindly share your git repository into the text box or comment field.
18. Good luck!

   