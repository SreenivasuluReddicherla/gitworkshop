<h1>How Start Git & GitHub<h1>
For Ubantu
Go command prompt and type git
	if exits :
		it display lot commands
	else:
		command not found
if not git:
	1. Go to the terminal type $ sudo apt install
		Enter your password and then type Y then git is going to be installing into your system
After Completion
	On terminal : Check the version of git $ git --version   # It display the version of git
<h1>Now time to start to Create a  gitHub account<h1>
	1. Go the browser and gitHub	: Choose link-> https://github.com/
		if your don not have account go to Sing Up and create an github account by providing your details
		if you have github account then go to Sign in by providing login credentials 
	Once you provided login credentials it redirected to your gitHub landing page.
Create a new repository in your gitHub by providing necessary details 
Create a folder in your local to do your activities
	Go to Terminal change to your working directory and create a text file $ touch test.txt

<h1>SetUp the GitHub Authentication (First time user only)<h1>
On the terminal follow commands as mentioned below
	$git config    # It display the configuration commands
	$git --global config  #It display configuration details
	$git config --global user.email "usermail@gmail.com" 	#To establish the connection by providing user email
	$git config --global user.name "username" 		#To establish the connection by providing user name
	$git config user.name    #checks the username
	$git config user.email   #checks the user email

<h2>SetUp is Completed Successfully.<h2>

<h1>Now Time to Start Git environment<h1>
	Go to Terminal of your current working directory and do as follows
	$git init   #It initialized empty Git in your working directory and it's hidden
	$git status  # it checks status of directory and display the what are the files available need to be update
	$git add filename	# Add a file to ready to commit 
	$git add .    		# Adds the multple files to ready to commit
	Once file is updated check again git status   $git status 
	$git commit -m "Write your comment"         #Everything is ready in the stageing environment and ready to provided into GitHub
	$git branch 		# It display master branch of your gitHub
	$git remote add origin repositorypathlink      #To everything is ready to push into githublive
	$git remote -v     #It display the the path where you are going to update your files
	$git push origin main #Push into gitHub   (For the first time it is asking username and password)

