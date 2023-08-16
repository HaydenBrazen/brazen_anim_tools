# Brazen Anim Tools #

A Public Repo for our animation artists to submit cusotm tools that they would like to be added to the pipe

### What is this repository for? ###

* Repo for Animation/layout tools and scripts

### Contribution and Setting Up ###

* Create a github account
* From the command line, clone this repo by entering  
`git clone https://github.com/HaydenBrazen/brazen_anim_tools.git`
* Create a branch off of the main branch, following the instructions and naming conventions below.
* From the terminal use `git pull` or `git fetch`, to locally learn about the newly created branch then transition into it by typing  
`git checkout <BRANCH-NAME>`
* Now, add your script into the repo by dragging your new file into the folder you created, or writing a new file in the
* new folder.
* Once you are done, return to the cmd and type `git add <FILE-NAME>` for each file you added/updated
* Next, type `git commit -m "<SHORT-SENTENCE-SUMMARIZING FILES/CHANGES>"`
* Then type `git push` for the code to be pushed onto the remote branch.
* The Next Step is Creating a Pull Request and undergoing Code Review See the section below
### Creating a Branch ###
* Navigate to https://github.com/HaydenBrazen/brazen_anim_tools/branches
* In The top Right corner of the screen hit the button that says New branch
* Name the branch one of the following  
`<UPDATE-TYPE>/<JIRA-TASK-IF-APPLICABLE>-<DESCRIPTION>`
* **Update Type Options**
  * feature
  * bugfix
* **Examples**
  * feature/PR-37-euler-curve-bake
  * bugfix/purge-excessive-keys-on-mirror

### Collaboration and Code Review ###
* After you have pushed all your code to the repository, navigate to  
https://github.com/HaydenBrazen/brazen_anim_tools/pulls
* Click `New Pull Request`
* In the top, there is a dropdown for base and compare, leave base as  master but change compare to your new branch
* Click `Create Pull Request`
* Name the Pull Request Appropriately
* In the Description leave a detailed description with Pictures and attachments describing what the new tool will do
* Set yourself as the Assignee, and the members of the tech team as the reviews _(This should be automated)_
* When you are done, click `Create pull request`
* From here the tech team should be able to review the code and comment on it. This is to ensure that the code matches the brazen standard.  
* Once You have made any changes that they give you through comments, and your code is reviewed, hit merge pull request
* If the branch is not deleted, delete the branch, _but it should be_

### Who do I talk to? ###

* Hayden Staples <hayden.staples@brazenanimation>
* Josh Carey <josh.carey@brazenanimation.com>
* Bryce Gattis <bryce.gattis@brazenanimation.com>
* Zane Hedges <zane.hedges@brazenanimation.com>
* Andrei Osypov <andrei.osypov@brazenanimation.com>