---
title: using git on mac
---

Creating this for myself to remember the various commands that you need to use in git and what they do. 

## adding stuff

You add the changes to the repo. Then you commit those changes. Then you push those changes up into the great big cloud in the sky. 

so its add --> commit --> push, and here are the actual commands. 

git add .
git commit -m "add a message here"
git push

## grabbing stuff from the internet repo

git pull 


# authenticating 

## adding your personal password

The best way I've found to authenticate: 

**Create Personal Access Token on GitHub**
From your GitHub account, go to Settings => Developer Settings => Personal Access Token => Generate New Token (Give your password) => Fillup the form => click Generate token => Copy the generated Token, it will be something like ghp_sFhFsSHhTzMDreGRLjmks4Tzuzgthdvfsrta

**Add token to your keychain on mac**
Click on the Spotlight icon (magnifying glass) on the right side of the menu bar. Type Keychain access then press the Enter key to launch the app => In Keychain Access, search for github.com => Find the internet password entry for github.com => edit or add an entry for github.com and copy that password into there. 

Make sure you then quit any open terminal apps - once you do and restart them, everything should work babyyyee. 

