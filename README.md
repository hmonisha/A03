# A03

Assignment 3 - IS117-001

PART 1: Directions on Using Webstorm 

_Webstorm is an Integrated Development Environment (IDE) used for Javascript, HTML, CSS, and other modern web technologies_

INSTALL WEBSTORM:
- Begin by downloading Webstorm from https://www.jetbrains.com/student/
- Scroll down and click on "Apply Now" under "individual license for students and teachers"
- Register with your UCID ID and email. Verify your account by using the link sent to your email, follow the instructions, and download Webstorm by finding the latest version

INSTALL GIT:
- Next, install Git from https://git-scm.com/downloads 
- Under "Downloads", choose your Operating System
- Find the download file and install it by double clicking the file

NEXT, ENTER WEBSTORM:
- Check if you installed the latest version:
   - select "configure" from the bottom of the screen (next to the screw icon), and click "check for updates" for latest updates

NEXT, GITHUB:
- Go to https://github.com/join and sign up for Github with your UCID

CONNECT GITHUB & WEBSTORM:
- Enter Webstorm again and press CTRL+ALT+S on your keyboard for System Preference 
- Select "Version Control Git" from the left menu 
- Enter the path to your GIT.exe into the empty space next to "Path to GIT executable"

  - _How do you locate your path to GIT.exe? (Windows only) :_ 
     - enter "File Explorer"
     - find and select "this pc"
     - select "Windows (C:)"
     - find and double click "program files"
     - find and double click "Git"
     - find and double click "bin"
     - once the terminal opens, your .exe file will be labeled on the top left
     - please do additional research online if this process does not work for you

NOW we also have to add our Github password to Webstorm
- In System Preference, select "Appearance and Behavior" from the drop down 
- Click "System Settings" and then "password"
- Add a location for the password file and click "OK"
- Select "Version Control" from the left menu and then "Git" 
- Paste your GIT.exe path (as done previously) into the box next to "Path to GIT executable" and click on "Test". 
    - If Git and Webstorm are connected successfully, you will receive the message “Git Executed Successfully.”

LET'S GO BACK TO GITHUB (NOT GIT):
- Sign in to your account you made previously (UCID+EMAIL)
- Click the "+" Icon from the top right, to the left of your profile
- Select "New repository" from the drop down menu
- Under "Repository Name", name it something convenient, such as "TestRepositoryIS117"
    - *Tip* : Use your course number (IS117) to make it easier to find your reposotories in the future
- Under "Description", write what the repository is about or anything that will help you remember why the repository was created
- Make sure to select "public", not "private"
- Select the "Add a README file" option
- Select "Create repository" at the bottom, highlighted in green

A NEW PAGE:
- You will brought to a new page where you can see "README.md" in the middle of your screen
- Bolded in the color white, you will see the name of your repository
- Next to your repository name, click the pencil shaped icon 
- This is your README file where you can write a description about your repository
- This is only a test, so for now write something like "This is my first repository". It could be anything, just something to help you remember what it is the next time you visit
- Finally, click "commit changes"

NOW, LET'S EDIT AN HTML TEST FILE AND UPLOAD TO GITHUB! 
- In Webstorm, from the top left corner, select "File", hoover over "New", and click "New Project"
- Make sure "Empty Project" is selected for now
- Near "Location", choose where you want to put your first HTML file and then click "Create" from the bottom right
- A new window will appear with text in the middle describing some shortcuts of Webstorm, such as "Search Everywhere Double Shift", etc.
- Locate "File" from the top left, hoover over "New", and this time select "HTML File"
- In the new pop up window, make sure "HTML 5 File" is selected and name your file, such as "MyfirstHTMLfile" or "FirstHTMLfile"

LET'S GET TO CODING! (JUST KIDDING, WE'RE NOT THERE YET):
- An HTML file will open in a new window
- You will see the word "Title", highlighted in blue in the middle of the screen, in between <title> & <title>
   - It will look like this: <title>Title<title>
- Replace the word "Title" with any word or sentence of your choice. For example: <title>"Hi, my name is Alex"<title>
   

RUN THE FILE TO TEST IF IT WORKED:
- When you're done typing, put your mouse on that window and right click on your mouse
- Under "Generate", click on "Run"......" the name of your HTML file that you named should appear next to "run"
   - OR press CTRL+SHIFT+F10 for shortcut
- Now, you should be redirected to a page on your web browser. The title of the web browser should be what you typed in between "<title><title>"

CREATE A REPOSITORY FROM WEBSTORM:
- Select "VSC" from the top and "Import into Version Control"
- Give it a name and click "OK"

IMPORT A REPOSITORY FROM GITHUB:
- Click on "VSC" again, then "Checkout from version control", and then "Git"
- On the empty box next to "URL", you will need to paste the URL from your Github repository
   - To do this, sign into Github
   - Click on the black and white cat from the top left corner to access repositories
   - Select your repository, highlighted in blue
   - Click on "Code", highlighted in green from the right
   - Under "HTTPS", copy the code 
- Go back to the pop up window in Webstorm and paste the link inside the box next to "URL"
- Add the local path to your PC on the empty box next to "Directory"

ADD FILES TO GIT & COMMIT YOUR CHANGES:
- Right click on the window where your HTML file is open, as we did in the previous step
- Locate and hoover over "Git", then "Add". OR press CTRL+ALT+A
- Right click again, then "Git", and this time click "Commit" or "Commit file", whichever shows up
- Click "Commit" from the bottom

NOW...
- After the previous step, a new window will open
   - It will direct you to sign into Github. Follow the steps
- Click "VSC" from the top again, then 'Import Version Control", and "Share Project on Github"
- Click "Share"
   - If successful, you will receive this message: "Successfully shared project on GitHub"
   
PUSH CHANGES TO REMOTE REPOSITORY:
- Locate "VSC" from the top on Webstorm, then "Git", and "Push" OR press Ctrl+Shift+K for shortcut

_Visit your repository to see the new file_
   
SETUP GITHUB PAGES:
- Click "setting" from the right, then check your repository name
- Locate "Master Branch" and you will see the published URL

FINAL STEP:
- Test you URL by pasting your Github URL into a new browser
   
   
Part 2: Glossary to include these terms in a bulleted list

__Branch__ : The purpose of a branch in Github is to separate other codes without it being affected. Other "branches" or say pages can be created within a repository without the code in one page affecting another. Each repository has one main branch and can have various other branches as well. For example, my IS117-001 course can be called a repository (which we will define later) and the homeworks or projects required for that course can be viewed as branches. Each homework and project is different and requires different answers so I will have to make separate submissions. So, IS117 is my repository and my submissions for that course is known as my branches.
   
__Clone__ : This word means "copy" or "duplicate". In Github, we use the clone command to create a copy (or download) of a repository OR a branch. This also gives us the ability to make changes locally, instead of directly.
   
__Commit__ : We can understand this command by thinking of the words "history" or "revision" because this command is used for saving your work and keeps a copy of every changes. It sends the newest changes to a repository. However, it only saves changes to our local repository.
   
__Fetch__ : This command downloads objects from another repository, such as branches, files, refs. This commands gives us the ability to view all of our current branches or changes in our remote repository without making local changes.

__GIT__ : This is an Open Distributed Version Control System that is used for tracking changes in files. It helps people, or specifically developers, or those who share and coordinate their work, stay organized and up to date on their work. Various commands can be made in GIT to view different files, make changes, pull data, etc.

__Github__ : This is a Git repository hosting service, which means it works with GIT. It also has features of its own. It provides access control and features, such as task management tools for projects. It provides cloud storage for soure code and supports all programming languages.

__Merge__ : Helps integrate changes from one branch to another and can combines two branches together. It helps protects the code history by adding a new commit. 
   
__Merge Conflict__ : Occurs when merging or pulling from a branch because commits that you have in your current branch does not match the commits in the other branch. Github becomes confused as to which changes should be put into the final merge. Before making a pull request, all merge conflicts should be resolve.

__Push__ : Uploads data and transfers commits from the local repository to the remote repository. It can also overwrite changes. 

__Pull__ : It fetches and downloads data from the remote repository to the local repository.This is another method that inform others of changes made to your repository. 

__Remote__ : A remote place where code is stored. It is hosted on a server or the internet where everyone in a team have the ability to access the same information. In Remote, everyone can push changes from their local repository and also pull changes to their local repository. 

__Repository__ : Can be viewed as a place where things are stored. So, in Github, repositories are created to store code and other branches can be created for a repository to store more code or even images without each any information being affected by another. 

 
   
REFERNECE:
https://digital.gov/resources/an-introduction-github/
https://guides.github.com/activities/hello-world/
https://www.edureka.co/blog/how-to-use-github/
