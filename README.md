# MGG-HTML-CSS

## Set up Github pages for the first time
A respository for material for the September 2017 intro to HTML/CSS/Github event

To set up git on your computer, see Github's instructions here: https://help.github.com/articles/set-up-git/

To set up a copy of these files on your own GitHib account, the easiest way to do this is to:

* Download the files by clicking on Clone or Download then Download Zip
* Create a repo in your own GitHub account: Click on the + by your profile picture, and then click on Create New Repository
  * Give it a name and a URL
  * Check the box next to Initialize this repository with a README
* Copy the URL on the next screen (It will be in the format https://github.com/GemHill/test.git )
  * Go to a terminal, type `cd Desktop` to move to your computer's desktop (or  `cd Documents`, or another folder)
  * Type in `git clone <URL you copied>`
This will set up a folder for your repository on your computer
* Copy and paste the files for your site into the new folder (this can be done however you normally move files)
* In your terminal, type `git status`
This should show you a list of files in red. This is expected
* Type `git add .`
  * You may see a message asking you to write a commit message. Write a message describing what you've added (or committed) to the repo. 'Initial commit' is fine here. This will add your files to the git respository
* Make changes to the files on your computer, and save as you would normally
* In the terminal, make sure you're in the new directory `cd <repository name>`, then try git status
 * You should see a message about there being some changes not staged for commit.
* Type `git add <filename>` or `git add .` to add all files
 * You can type `git status` again here, which will tell you that there are changes to commit
* Type `git commit -m "describe your change here"`
 * You can type `git status` again here, which will tell you to push your changes
* Type `git push` 
 * You may be asked to enter your GitHub undername and password here
* Type `git status`, you should see the following message 
> On branch master
> Your branch is up-to-date with 'origin/master'.
> nothing to commit, working directory clean
* Go to your Github repo, and click on the Settings tab
* Scroll down to the 'Github pages' section, select master branch from the dropdown, click save
* Your site will be available at https://username.github.io/repositoryname (change username to your gitbug username and repositoryname to the name of your github repo

## Edit files in an exisitng repo
### Through github

If you are the owner of the github repo, then you can edit directly through Github
* In your repo, click on the file you wish to edit
* Click the pencil icon near the top right hand corner 
* You can then edit the file straight in github
* When you're done, scroll down, keep the 'Commit directly to the master branch' selected
* Click Commit changes

### Through the command line

If you want to edit the files on your computer and push them to git using the command line, you can do so
* Edit the files on your computer as you would any other file
* Open terminal and type `cd Desktop/HTMLCSS/yourfoldername` or `cd Downloads/HTMLCSS/yourfoldername` (or CD whereyourfolderis)
* Type `git status` and press enter. You should see a message about changes not staged for commit
* Type `git add .` and press enter
* Type `git commit -m "commit message here"` and press enter
 * Examples of git commit messages are `git commit -m "Added links"` or `git commit -m "Fixed typo"`
* Type `git push` and press enter
* Your changes should be live on the site

## Resources and tips

* These can be found in the resouce file, which can be viewed on Github
* If you want to add another page, make another file with the extension .html (contact.html for example). Open notepad or notepad++ or sublime and create a new file, saving it as filename.html. 
 * Copy the section between the `<head>` and `</head>` tag in your index.html file and then put the rest of the copy in as you wish between `<body>` and `</body>` tags
