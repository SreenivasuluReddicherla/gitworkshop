# Git Tutorials Repository

Welcome to the Git Tutorials repository! This repository contains a series of tutorials and resources to help you learn and master Git.

## Table of Contents

- [Introduction to Git](#introduction-to-git)
- [Installation](#installation)
  - [Windows](#windows)
  - [macOS](#macos)
  - [Linux](#linux)
- [Basic Git Commands](#basic-git-commands)
- [Branching](#branching)
- [Merging](#merging)
- [Collaboration Workflow](#collaboration-workflow)
- [Resources](#resources)
- [Contributing](#contributing)

## Introduction to Git

Git is a distributed version control system that helps you track changes to your codebase, collaborate with others, and maintain project history. Whether you're a beginner or an experienced developer, these tutorials will guide you through the essentials of Git.

## Installation

To use Git on your local machine, you need to install it first. Here are the installation instructions for different operating systems:

### Windows

1. Visit the [Git for Windows](https://gitforwindows.org/) website.
2. Download the installer and follow the installation instructions.

### macOS

1. Open Terminal.
2. Install Git using Homebrew:
   ```bash
   brew install git

### For Ubantu

## How Start Git & GitHub
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
## Now time to start to Create a  gitHub account
	1. Go the browser and gitHub	: Choose link-> https://github.com/
		if your don not have account go to Sing Up and create an github account by providing your details
		if you have github account then go to Sign in by providing login credentials 
	Once you provided login credentials it redirected to your gitHub landing page.
Create a new repository in your gitHub by providing necessary details 
Create a folder in your local to do your activities
	Go to Terminal change to your working directory and create a text file $ touch test.txt

## SetUp the GitHub Authentication (First time user only)
On the terminal follow commands as mentioned below
	$git config    # It display the configuration commands
	$git --global config  #It display configuration details
	$git config --global user.email "usermail@gmail.com" 	#To establish the connection by providing user email
	$git config --global user.name "username" 		#To establish the connection by providing user name
	$git config user.name    #checks the username
	$git config user.email   #checks the user email

## SetUp is Completed Successfully.

## Now Time to Start Git environment
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

