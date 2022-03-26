# Project 1: Personal Website

In project 1, you will build a personal webpage. You will include some information about yourself, such as work/education experiences and contact info. You will code only in HTML and apply some of the skills gained from the worksheet. If you already have a personal website, then keep learning more about HTML/Bootstrap or explore front-end frameworks like React.

## Instructions
1. Visual Studio Code (VS Code) code editor is a lightweight and user-friendly tool to edit code. If you already have it installed, skip this step. Otherwise, download and install VS Code for your particular OS [here](https://code.visualstudio.com/Download).
2. Fork this repo to your own GitHub account (Don't know what fork is or how to fork? Check [this](https://docs.github.com/get-started/quickstart/fork-a-repo#forking-a-repository) out)
3. Clone the forked repo with HTTPS to your computer, just like how you do in CSC226 and CSC236.
4. Based on what terminal/OS you use, do the following:
  
    Windows:
      If you have Ubuntu Terminal, use that. Otherwise, use PowerShell.
      Ubuntu Terminal:
      * Navigate to the cloned directory on your terminal
      * Run the following commands: 
        * `sudo apt-get update`  # updates your Ubuntu/Linux package manager
        * `sudo apt-get install virtualenv`   # installs a virtual environment tool
        * `virtualenv venv`  # creates a virtual environment (venv)
        * `source ./venv/bin/activate`  # activates the venv
      PowerShell:
      * Navigate to the cloned directory on your terminal
      * If you have `pip` installed, run the command `pip install virtualenv`. If not, run `python -m venv venv` OR `python3 -m venv venv`. This step creates a virtual environment
      * Run `.\venv\Scripts\activate` to activate the virtual environment
    Mac:
      Use the Mac terminal.
      * Navigate to the cloned directory on your terminal
      * 

5. Create a virtual environment
6. Navigate to `flask-app/templates/`
7. Open `index.html` in Visual Studio Code
8. For this project, **ALL** of the coding will be in HTML inside the `index.html` file (No need to create more files)
9. Before you start coding, it's a good idea to complete the HTML section of Worksheet 1 to have a basic understanding of the language.


## Requirements:
- [ ] Your page has a title (e.g. Alice's Personal Page) (hint: use `<h1>` tags)
- [ ] Your page should have the following sections: bio (about), skills, experience, projects, contact info (hint: for each section name, use `<h2>` or `<h3>` tags)
- [ ] Add some relevant content to each of your sections (hint: you can use `<p>` tags for writing content)
  - [ ] For instance, in the bio section, add some information about yourself
- [ ] Create a button named 'Resume' in the bio section (no need to actually link your resume to the button - that's an optional challenge below) (hint: use the `<button>` tag)
- [ ] Add hyperlinks to your GitHub and/or LinkedIn profiles; this could be in the contact info section (hint: use `<a>` tags)
- [ ] (optional challenge) Add a picture (e.g. profile picture) (this could be in the bio section)
- [ ] (optional challenge) link the `Resume` button to your resume so that when the button is clicked, the user can view your resume (hint: you can get a google doc link to your resume and make the button redirect you to that link when it is clicked)
- [ ] (optional challenge) User can navigate the site from the hyperlinks in the _navigation bar_
- [ ] (optional challenge) Footer


## Optional Content (No need to read further)

What's a user story?
Software engineers use the term 'user story' to refer to the features the users want. That helps engineers see the development process from the users' point of view. Therefore, in our projects, we call the requirements/features user stories.  

A sample user story: "User can navigate the site from the hyperlinks in the _navigation bar_"

Meaning: this user story tells you, the developer, to build a navigation bar with hyperlinks to different parts of the website. 
