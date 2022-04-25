# Git Flow when using Instructor Code or Open Source

1. FORK the repo to create a copy of it on your own account. Click the fork button in the top right hand corner
if you have forked correctly, you should now see your username instead of Instructors name at the top of the repo
2. Clone your repo - this will pull the files down to your local machine so you can work on them and make changes - to do this click to green code button on the right.
3. Inside your terminal or git-bash navigate to where you want to put these files on your computer and type git clone and paste the url and then press enter
4. cd into your new repository by typing cd and then the repo name
5. Create a branch by typing git checkout -b branch-name (This is so the base code remains the same)
6. Open your project up in VS code by using the code . command or by opening it manually in VS code. Note if this is the first time you are using the code . command you may need to install that command in vs code - please reference these docs
7. You may now start working on your project
8. When you are ready to push some changes back up to git hub you will need to go through the following commands (you should be doing this every 20 mins or whenever you get a major feature working):
git add . - adds all changes you've made so far to the staging area
git commit -m 'message' commits changes - you should be writing clear commit messages to let the next developer know what changes you've made
git push origin branch-name - this creates your branch remotely and pushes the changes to that branch - please note that branch-name should be whatever you've named your branch in step 6 (if you add -u before origin then it will always push to this branch and next time you can just do git push)
9. Once you are finished, you can go ahead and create a pull request. The purpose of a pull request is to let your team know that there are changes to review. Please do not merge your own pull requests.
click on the button that says compare and pull request
10. Once you've clicked the compare and pull request button it will take you to the pull request screen. Click on the drop down and choose your repository as the base
11. Make sure you are comparing 'master' or 'main' to your branch and then go ahead and click on the button to create pull request
