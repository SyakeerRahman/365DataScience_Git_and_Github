# 365DataScience_Git_and_Github

<img width="488" alt="image" src="https://github.com/SyakeerRahman/365DataScience_Git_and_Github/assets/105381652/f5d1584d-61a6-4abf-a30b-2364dfa7976e">

## Course Introduction

• Introduction - Git and GitHub

## Introduction To Git

• Installing Git 

https://git-scm.com/downloads

• Configure Git

set name, email (github email), set favorite editor -- (atom, vim, nano, notepad)
``
git --global user.name "name"
git --global user.email "email"
git --global core.editor "notepad"
notepad test.txt
git config --list
``
• Basic commands

create directory, initialized git, create txt file, remove, create again, check status, start track, comment why start track, check log
``
mkdir shop (make directory)
cd shop (get inside)
git init (initiate)
ls -A (show list)
touch list.txt (create)
rm list.txt (remove)
git status (check)
git add list.text (start track)
git commit -m "Create shopping list" (comment)
git log (history)
``
• Exploring Git log

<img width="345" alt="image" src="https://github.com/SyakeerRahman/365DataScience_Git_and_Github/assets/105381652/f57a57a0-e56f-483a-b328-bf79c675bfb3">

``
git status (check status)
git diff (check what has changed)
git add list.text (start track)
git commit - "Add fruit adnd vegetables
git log (check all history)
git log -1 (check latest history)
``
<img width="368" alt="image" src="https://github.com/SyakeerRahman/365DataScience_Git_and_Github/assets/105381652/aebdfd08-8558-4485-9815-c75e9b6c8603">


• Git diff (no difference between staging and working file)
``
git diff --staged (get staged thing)
``

• HEAD

<img width="404" alt="image" src="https://github.com/SyakeerRahman/365DataScience_Git_and_Github/assets/105381652/61c0a15e-1fa0-42d5-951b-79ba89d808c6">

``
git diff 12345 (first 5 digit, to check the file lookalike)
git checkout HEAD list.txt (to updated the file to the latest version)
git checkout HEAD~1 list.txt (to updated the file to the latest - 1 version)
git checkout HEAD~2 list.txt (to updated the file to the latest - 2 version)
notepad list.txt (open notepad to see which version)
``
• Making corrections Git reset

``
git reset HEAD~1 --soft (reset back to the last commmit meaning the latest commit will be cleared (check thru git log) but git diff staged will still show the latest one)
git reset HEAD~1 --mixed (removes commit and also makes the changes unstaged but the file still have the wrong tagging)
git reset HEAD~1 --hard (removes commit, changes unstaged and reset the file to the last save)
``
• Branching

``
git branch dairy (add new branch which is dairy)
git branch (check all branch list)
git checkout dairy (using dairy branch)
git checkout master (using master)
git merge dairy (combine list in dairy to master list)
``

## GitHub

• GitHub
• GitClone 
