# COMSC230 Friendly Eats

COMSC230-friendlyeats:

This repository is based on the source code that accompanies the Firestore Android Codelab:
https://codelabs.developers.google.com/codelabs/firestore-android

---------- Create your own Github Repository for this project --------------

Here are the steps to make a copy of this repo and point it to a new repository in your github:

Step 1: Clone this repository
Step 2: Point this project to a repo on your Github:

In VSCode terminal:

// Command to see the origin url:

git remote show origin

// After you clone it you should see:

(base) friendlyeats-android tnewman $git remote show origin
* remote origin
  Fetch URL: https://github.com/rhodyapps/Comsc230-friendlyeats
  Push  URL: https://github.com/rhodyapps/Comsc230-friendlyeats
  HEAD branch: master
  Remote branch:
    master tracked

// In your Github, create a new repository for this project.
// copy the url to your repo for this project
// then remove the origin (if it is pointing to rhodyapps)

git remote rm origin

// now you can re-point the local repo to your new github repo:

git remote add origin <paste in the url of your github repo for this project>

// Check it again
git remote show origin

// Make a change in one of the files (ie: add a blank line to MainActivity.java) and
// Use the VSCode github function (icon on the left) to push the change to github.
// Since this is the initial commit, it will push all of the code.

------------------------ Codelab -----------------

The codelab will walk you through developing an Android restaurant recommendation
app powered by Cloud Firestore.

Step 6
After you complete step 6 in the codelab, you will have a working app that allows you to browse restaurants in the database.
At this point you will be able to click on the Add Rating dialogue but your rating will not be saved until you complete the next step. In this repo, the master branch contains the working code from step 0 through step 6.

Step 7 Add rating
branch1-ratings contains the code (RestaurantDetailActivity.java) that you need to make the add rating dialogue work. 


<img src="docs/home.png" width="300"/>

If you don't want to do the codelab and would rather view the original (codelab) completed
sample code, see the Firebase Android Quickstart repository:
https://github.com/firebase/quickstart-android


## Build Status

[![Build Status](https://travis-ci.org/firebase/friendlyeats-android.svg?branch=master)](https://travis-ci.org/firebase/friendlyeats-android)
