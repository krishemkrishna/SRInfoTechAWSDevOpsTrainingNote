# SRInfoTechAWSDevOpsTrainingNote


30/09/2025_Demo::
================

In Demo session we have Overview the all CI/CD tools 

![image](https://github.com/user-attachments/assets/8f472413-8ba3-45ae-85c0-a391ec46886a)


07/10/2025_Tools Overview::
==============================

1. Overview about the all CI/CD & AWSDevOps Training flow

2. Discussed about the all the DevOps roles

DevOps::
======

DevOps is a software development and operations (DevOps) methodology that combines these two to improve efficiency and speed up project deliverables, It's very important because it helps businesses/deliver software faster and with higher quality.

What is the key purpose of DevOps?
The primary goal of DevOps is to bridge the gap between development and operations teams. It creates a streamlined, efficient workflow that delivers software faster and with higher quality.
DevOps is a set of practices,tools that automate and integrate the processes between software development and IT teams.

Devops engineer is a key role responsibility::
================================================

<img width="1129" height="606" alt="image" src="https://github.com/user-attachments/assets/40e07512-2fd0-41c2-a4ff-af183dc4dd47" />


1)The devops engineer was responsibility to release the product to the market as soon as possible

2)  release the product speed to the market

3)Devops engineer was give continues feedback to the developers

4) Devops engineer responsibility start from git and end with production

Benefits of DevOps ::
===================

•	Faster software delivery: Reduces lead times and speeds up the software delivery process 

•	Higher software quality: Addresses bugs quicker and improves software quality 

•	Better collaboration: Unifies development and operations teams, enhancing collaboration and efficiency 

•	Competitive advantage: Creates a more nimble software development lifecycle that gives businesses an advantage over their competitors 




What is Git?

Git is a free, open-source version control system (VCS) that helps developers manage their code. It's the most widely used tool VCS(version control system) Git is fast for committing, branching, merging, and comparing past versions Git is very high Performance and Flexibility,Security.



Install Git in you local machine::
====================================

https://git-scm.com/downloads/win

Please download the ---64-bit Git for Windows Setup.

Once download the git .exe file , double click and install the git on your machine

once installed right click on your local machine you can found Open Git batch here option, means git is installed successfully in your machine.

![image](https://github.com/user-attachments/assets/46c6f47d-55f2-4df7-83ae-14a7bbeab67e)


GitHub account creation::
=============================

For creating github account EmailId is Required

go to link --https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Enter Email & password ,Username click continue ---Account will create successfully image


![image](https://github.com/user-attachments/assets/4f0bd13c-21df-42f0-9ad0-e4671b367cfb)


![image](https://github.com/user-attachments/assets/44333ed2-0d4a-41b2-9bb5-66c7c5456551)


Github::Github is a one of the SCM(Source code management) tool and store the Project code.

Repository: storage area of your source code. Create a Repository on GitHub

click Repositories

![image](https://github.com/user-attachments/assets/725cdcfb-7472-46d8-b7a8-46de06f3cbf6)


Click New

![image](https://github.com/user-attachments/assets/e9a689f5-7c6e-4b7f-9442-96d8a17021f5)


Enter Repository Name::SRINFOTECHDEMO

![image](https://github.com/user-attachments/assets/f230a5b0-b1b4-4b46-8def-ebd601347749)


Public:: Anyone on the internet can see this repository.


![image](https://github.com/user-attachments/assets/9fb81a79-9cc9-4428-96cd-c9bd3d17e37b)


Private:: You choose who can see and commit to this repository.

select Add a README file 


![image](https://github.com/user-attachments/assets/4ba5ac39-6736-412c-906d-ebed138f8a86)


Click Create Repository


![image](https://github.com/user-attachments/assets/6a91de9f-a2f3-4b03-9740-a870bf2cb972)



08/10/2025::
=============



Github Introduction::
===============

GitHub is a web-based platform for version control and collaboration, allowing developers to store and manage their code in repositories.

Version Control: ::
GitHub uses Git, a distributed version control system, to track changes in code. This allows multiple people to work on the same project without overwriting each other's contributions.

Repositories::: where you can store your project files and track the history of changes made to those files.Public and private repos can be created depending on accessibility needs.



Git & Github Integration::
============================


git and github communication happend via SSH keys

<img width="1196" height="614" alt="image" src="https://github.com/user-attachments/assets/81279a05-8039-4e4c-899c-68d1e15d6f19" />


Generate SSHKeys::
====================
 
 
 open gitbash and run the below command

 ![image](https://github.com/user-attachments/assets/0e42b0cc-0ee2-4cac-8cb9-dbbcbe23189a)


syntax::
========

>ssh-keygen -t ed25519 -C "your_email@example.com"

>ssh-keygen -t ed25519 -C "srinfotechbatch4@gmail.com"

![image](https://github.com/user-attachments/assets/b802d3d8-d678-425e-9bcf-1a8e59dfa35b)

HP@DESKTOP-E518Q66 MINGW64 ~
$ ssh-keygen -t ed25519 -C "srinfotechbatch4@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/HP/.ssh/id_ed25519):
/c/Users/HP/.ssh/id_ed25519 already exists.
Overwrite (y/n)? y
Enter passphrase for "/c/Users/HP/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/HP/.ssh/id_ed25519
Your public key has been saved in /c/Users/HP/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:CqROf7Z/FpbjGWy8/vMYGCS6Uq1ttFi/dKY2iAuBprg srinfotechbatch2@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|                 |
|                 |
|    .   . .      |
|   +   o o       |
|  = o o So..     |
|.= . + O oXo     |
|o . + B.+=+*+    |
| .   =.o..O=.o   |
|E     oo.=+ooo.  |
+----[SHA256]-----+


Please follow below links for more understanding::
===================================================

https://docs.github.com/en/authentication/connecting-to-github-with-ssh

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Once genearted the keys (public/private) and copy public key to Github Account::
================================================================================

steps::

Your public key has been saved in /c/Users/HP/.ssh/id_ed25519.pub


![image](https://github.com/user-attachments/assets/3655eb5a-3b08-4644-98b2-cea22ecfaacd)

right click and open id_ed25519.pub, and copy public key to Github Account

Go to -->Your Copilot click your copilot


![image](https://github.com/user-attachments/assets/ac133e40-b38c-4483-bfbb-fde5d729747d)


Click SSH and GPG Keys

![image](https://github.com/user-attachments/assets/bde7e964-cbbe-42d1-aced-a1646d6bf5d3)


click New SSH Key


![image](https://github.com/user-attachments/assets/f2996ed0-5afc-494c-a45f-eebc5b78b8e4)


Add new SSH Key and click Add SSH Key

![image](https://github.com/user-attachments/assets/1b229cda-b319-4565-b937-7a259dbd2f2a)


ssh public key is added in github account


![image](https://github.com/user-attachments/assets/1a327a82-3df8-41ea-994b-cc9aa20dd582)



Clone repository/Project from github to local machine steps::
==================================================================

Fork::
============

Fork means to make a copy of the repository into my own github account A fork is a copy of a repository


first we need to create the repository

Go to Repositories

![image](https://github.com/user-attachments/assets/c295c1cb-8690-49db-93cf-766d695d0526)

Click New

![image](https://github.com/user-attachments/assets/c0ba9848-bb5c-461e-8f9b-c1cd332ab5dd)

Enter Repository Name

![image](https://github.com/user-attachments/assets/cd6ae1c3-6160-4a5e-a159-5347469fb1b6)


select public

select Readmefile.md

![image](https://github.com/user-attachments/assets/e631f9a4-eda5-4e93-8f31-629cda9e6d17)

Click Create Repository


Empty repository Created

![image](https://github.com/user-attachments/assets/a838f321-7d0a-46a8-bc1c-e90d12ba5acf)


Now I'm Going to clone the Empty Repository from Remote to Local::
====================================================================
Steps::
=======



1.git clone git@github.com:srinfotechbatch4/hello-world-java.git

2.cd SRINfotechDemo

3.git status

4.git add --all

5.git status

6.git commit -m "i have added hellow world project files"

7.git push   ---->from local changes pushed to remote

8.git pull   --->remote to local

above steps to push some changes from Local to remote repository


Session Note::
===========

>ssh-keygen -t ed25519 -C "your_email@example.com"

>ssh-keygen -t ed25519 -C "srinfotechbatch4@gmail.com"

>git clone <URLof your project>

>git clone git@github.com:srinfotechbatch4/hello-world-java.git

>cd hello-world-java

>git status

>git add --all

>git status

>git commit -m "updated helloworld java file"

>git config --global user.email "srinfotechbatch4@gmail.com"
>git config --global user.name "srinfotechbatch4"

>git commit -m "updated helloworld java files"

>git push


Lab Practice::
==============

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4
$ git clone git@github.com:srinfotechbatch4/hello-world-java.git
Cloning into 'hello-world-java'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 16, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 16 (delta 3), reused 3 (delta 3), pack-reused 10 (from 1)
Receiving objects: 100% (16/16), done.
Resolving deltas: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4
$ cd hello-world-java

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   HelloWorld.java
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   HelloWorld.java
        modified:   README.md


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git commit -m "updated helloworld java files"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HP@DESKTOP-3GU6R56.(none)')

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git config --global user.email "srinfotechbatch4@gmail.com"

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git config --global user.name "srinfotechbatch4"

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git commit -m "updated helloworld java files"
[master 657da56] updated helloworld java files
 2 files changed, 2 insertions(+), 2 deletions(-)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/hello-world-java (master)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 428 bytes | 214.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch4/hello-world-java.git
   4947e1e..657da56  master -> master




   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f8de6bc5-3b66-4584-ae2f-832200c557c8" />






09/10/2025::
=============


Github Branching Model::
=======================

A GitHub branching model is a structured way of organizing branches in a Git repository to manage development workflows effectively. It helps teams work collaboratively, isolate features, manage releases, and deploy code more efficiently.


<img width="1798" height="749" alt="image" src="https://github.com/user-attachments/assets/8965c1f6-c445-4909-8998-50cd188c211b" />


<img width="1483" height="751" alt="image" src="https://github.com/user-attachments/assets/a7975faa-5e61-460d-a2d3-d145d5211d31" />



Sample Repository Hello-World Project::
=========================================

https://github.com/srinfotechbatch4/srinfotechbatch4demo.git

Branches:
==========
main (or master): Always production-ready.

feature/*: Used for new features.

release/*: Prepares for a new production release.

main or master branch:: This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically.
main or master branch always stable and live code 

feature branch:: It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: feature/YYYY.MM.DD
 feature/2025.06.22

release branch:: Based on the release we have created release branch accourdingly and starts the next release cycle.
always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.07.20

hotfix branch:: always created from main or master branch only for production fixes.once production fix done we should merged directly to main or master branch only.

always created this hotfix branch for production issues fixes

bugfix:: this branch is created from release branch to fix the LLE(lower level environemnt)/Pre-Prod/UAT/Non-Prod issues and once LLE issues fixed ,we should pushed their changes to release branch only.


Raise PR (Pull Request) ::
=========================

Merge the code from one branch to another branch that is called pull request

below are the steps to raise PR::

Go to -->Pull requests and click

![image](https://github.com/user-attachments/assets/f2848a77-e095-4f56-917c-af9105d1e0bb)

Click New Pull Request::

![image](https://github.com/user-attachments/assets/1369f202-d7fd-4279-ac9d-b4b2eb7702ed)

Compare & pull Request

![image](https://github.com/user-attachments/assets/bac984dd-12b1-4cf0-b00d-e5b49db165f6)

select base & compare options

![image](https://github.com/user-attachments/assets/13e46ee9-db46-4eb0-a505-e4580e4a92ff)


Raise PR(Pull Request) from feature to release branch


![image](https://github.com/user-attachments/assets/e4e939a3-a286-4264-a51d-3c1c7df59be4)


please select base & compare branches so here base branch is release/2025.06.29 and compare branch is feature/2025.06.22

i'm going to merge code changes from feature branch to release branch 



![image](https://github.com/user-attachments/assets/15c01632-b97a-4ede-bb55-2ef0bcea5105)


click create pull request

![image](https://github.com/user-attachments/assets/6b91e62d-9aee-4328-b759-bd20ec6f2a1d)

![image](https://github.com/user-attachments/assets/60876946-a09b-4245-bc4b-835bff15fe87)

click merge request

confirm merge

![image](https://github.com/user-attachments/assets/3ae9c358-accc-4a73-92c5-4aa21b2d78c4)


merged 1 commit into release/2025.06.29 from feature/2025.06.22  Copied!

![image](https://github.com/user-attachments/assets/fc0f68b5-b263-4267-ad07-0ea7a2bcf026)



Session Note::
================

>git checkout <branchname>

>git checkout 


2.github model  ---->master-->feature--->release

git flow model --->master-->develop-->feature--->release


>git pull    ---->pull the changes from remote to local machine

=============

Lab Practice::
============

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4
$ git clone git@github.com:srinfotechbatch4/srinfotechbatch4demo.git

Cloning into 'srinfotechbatch4demo'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
Receiving objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4
$

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4

$ cd srinfotechbatch4demo

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (master)
$ git checkout feature/2025.10.12
branch 'feature/2025.10.12' set up to track 'origin/feature/2025.10.12'.
Switched to a new branch 'feature/2025.10.12'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git status
On branch feature/2025.10.12
Your branch is up to date with 'origin/feature/2025.10.12'.

nothing to commit, working tree clean

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git status

On branch feature/2025.10.12
Your branch is up to date with 'origin/feature/2025.10.12'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        submit new user.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git status

On branch feature/2025.10.12

Your branch is up to date with 'origin/feature/2025.10.12'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        modified:   README.md
        new file:   submit new user.java


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)
$ git commit -m "i have added new user submit functinality"
[feature/2025.10.12 3e4a24b] i have added new user submit functinality
 3 files changed, 41 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 submit new user.java

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 781 bytes | 195.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch4/srinfotechbatch4demo.git
   1c55b10..3e4a24b  feature/2025.10.12 -> feature/2025.10.12

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git status

On branch feature/2025.10.12
Your branch is up to date with 'origin/feature/2025.10.12'.

nothing to commit, working tree clean

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git checkout bugfix/2025.10.12

error: pathspec 'bugfix/2025.10.12' did not match any file(s) known to git

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git checkout bugfix/2025.10.12

error: pathspec 'bugfix/2025.10.12' did not match any file(s) known to git

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git pull

remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (2/2), 1.75 KiB | 112.00 KiB/s, done.
From github.com:srinfotechbatch4/srinfotechbatch4demo
 * [new branch]      bugfix/2025.10.12  -> origin/bugfix/2025.10.12
   1c55b10..fb0e3f6  master             -> origin/master
 * [new branch]      release/2025.10.12 -> origin/release/2025.10.12
Already up to date.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (feature/2025.10.12)

$ git checkout bugfix/2025.10.12

branch 'bugfix/2025.10.12' set up to track 'origin/bugfix/2025.10.12'.
Switched to a new branch 'bugfix/2025.10.12'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git status

On branch bugfix/2025.10.12
Your branch is up to date with 'origin/bugfix/2025.10.12'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   submit new user.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git status

On branch bugfix/2025.10.12
Your branch is up to date with 'origin/bugfix/2025.10.12'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   submit new user.java


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git commit -m "added new user class"

[bugfix/2025.10.12 61c1366] added new user class
 1 file changed, 7 insertions(+)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git push

Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 375 bytes | 187.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:srinfotechbatch4/srinfotechbatch4demo.git
   3e4a24b..61c1366  bugfix/2025.10.12 -> bugfix/2025.10.12

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git checkout hotfix/2025.10.12

error: pathspec 'hotfix/2025.10.12' did not match any file(s) known to git

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git pull

remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 902 bytes | 112.00 KiB/s, done.
From github.com:srinfotechbatch4/srinfotechbatch4demo
   3e4a24b..2984d57  feature/2025.10.12 -> origin/feature/2025.10.12
 * [new branch]      hotfix/2025.10.12  -> origin/hotfix/2025.10.12
Already up to date.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (bugfix/2025.10.12)

$ git checkout hotfix/2025.10.12

branch 'hotfix/2025.10.12' set up to track 'origin/hotfix/2025.10.12'.
Switched to a new branch 'hotfix/2025.10.12'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (hotfix/2025.10.12)

$ git status

On branch hotfix/2025.10.12
Your branch is up to date with 'origin/hotfix/2025.10.12'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   submit new user.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (hotfix/2025.10.12)

$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (hotfix/2025.10.12)

$ git commit -m "added srinfotech user"

[hotfix/2025.10.12 9a2194d] added srinfotech user
 1 file changed, 11 insertions(+)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/srinfotechbatch4demo (hotfix/2025.10.12)

$ git push

Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 375 bytes | 187.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:srinfotechbatch4/srinfotechbatch4demo.git
   eeccc6a..9a2194d  hotfix/2025.10.12 -> hotfix/2025.10.12




   
10/10/2025::
===========

Avoide conflicts in RealTime Scenarious::
=============================================


If multiple developers OR DevOps Engineers are working on same Project/MOdules, if they tried to commits thier code changes to Repository, it will faces the conflicts issues and how to resolved those conflicts issues in real time projects


<img width="1827" height="647" alt="image" src="https://github.com/user-attachments/assets/f1bcdc84-5d1b-42a0-b00e-559d85eead6a" />


git pull::
============

git pull command is use, copies changes from a remote repository directly into your working directory (local directory) and merged code changes from remote repository to local repository 

git fetch::
=============

The git fetch command only fetch the changes into your local Git repo and it will not merged anything. just fetch the details

Please create developer1,developer2,developer3 directories in your local machine and clone the project code separately


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4bedee0-2e25-469d-b04a-ba3241cd5869" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0d77ddf9-1fd3-4ebe-b021-3aea557e2cf8" />



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/82e5f642-f316-41d0-9efa-0525a3788953" />

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$ git push
To github.com:srinfotechbatch4/DevTeamAviodConflicts.git
 ! [rejected]        feature/2025.10.10 -> feature/2025.10.10 (fetch first)
error: failed to push some refs to 'github.com:srinfotechbatch4/DevTeamAviodConflicts.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


resolved conflicts::
==========================

>git pull

opend the editor

1.presh the i from your keyboard

2.esc

3.swift+:

4.wq

5.enter



Developer1 Activity::
=====================

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1
$ git clone git@github.com:srinfotechbatch4/DevTeamAviodConflicts.git\
>
Cloning into 'DevTeamAviodConflicts'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1
$ cd DevTeamAviodConflicts/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (main)
$ git checkout feature/2025.10.10
branch 'feature/2025.10.10' set up to track 'origin/feature/2025.10.10'.
Switched to a new branch 'feature/2025.10.10'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git status
On branch feature/2025.10.10
Your branch is up to date with 'origin/feature/2025.10.10'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello-world-java-master/

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git add --all
warning: in the working copy of 'hello-world-java-master/.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'hello-world-java-master/HelloWorld.java', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'hello-world-java-master/README.md', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git status
On branch feature/2025.10.10
Your branch is up to date with 'origin/feature/2025.10.10'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   hello-world-java-master/.gitignore
        new file:   hello-world-java-master/HelloWorld.java
        new file:   hello-world-java-master/README.md


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git commit -m "updated the developer1 activity"
[feature/2025.10.10 8c63975] updated the developer1 activity
 3 files changed, 47 insertions(+)
 create mode 100644 hello-world-java-master/.gitignore
 create mode 100644 hello-world-java-master/HelloWorld.java
 create mode 100644 hello-world-java-master/README.md

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 890 bytes | 296.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch4/DevTeamAviodConflicts.git
   9964975..8c63975  feature/2025.10.10 -> feature/2025.10.10

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git fetch
remote: Enumerating objects: 16, done.
remote: Counting objects: 100% (16/16), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 12 (delta 6), reused 7 (delta 3), pack-reused 0 (from 0)
Unpacking objects: 100% (12/12), 1.93 KiB | 17.00 KiB/s, done.
From github.com:srinfotechbatch4/DevTeamAviodConflicts
   8c63975..1a00b3d  feature/2025.10.10 -> origin/feature/2025.10.10

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git pull
Updating 8c63975..1a00b3d
Fast-forward
 .gitignore                              |  2 ++
 HelloWorld.java                         | 11 +++++++++++
 README.md                               | 35 ++++++++++++++++++++++++++++++++-
 hello-world-java-master/HelloWorld.java |  6 ++++++
 4 files changed, 53 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 HelloWorld.java

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git pull
Already up to date.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git commit -m "updated the developer1 activity"
[feature/2025.10.10 e94720a] updated the developer1 activity
 1 file changed, 7 insertions(+)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer1/DevTeamAviodConflicts (feature/2025.10.10)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 299 bytes | 99.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch4/DevTeamAviodConflicts.git
   1a00b3d..e94720a  feature/2025.10.10 -> feature/2025.10.10



Developer2 Activity::
====================

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2
$ git clone git@github.com:srinfotechbatch4/DevTeamAviodConflicts.git
Cloning into 'DevTeamAviodConflicts'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2
$ cd DevTeamAviodConflicts/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (main)
$ git checkout feature/2025.10.10
branch 'feature/2025.10.10' set up to track 'origin/feature/2025.10.10'.
Switched to a new branch 'feature/2025.10.10'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$ git status
On branch feature/2025.10.10
Your branch is up to date with 'origin/feature/2025.10.10'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$ git add --all
Merge branch 'feature/2025.10.10' of github.com:srinfotechbatch4/DevTeamAviodConflicts into feature/2025.10.10

remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 6 (delta 0), reused 6 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (6/6), 870 bytes | 18.00 KiB/s, done.
From github.com:srinfotechbatch4/DevTeamAviodConflicts
   9964975..8c63975  feature/2025.10.10 -> origin/feature/2025.10.10
Merge made by the 'ort' strategy.
 hello-world-java-master/.gitignore      |  2 ++
 hello-world-java-master/HelloWorld.java | 11 +++++++++++
 hello-world-java-master/README.md       | 34 +++++++++++++++++++++++++++++++++
 3 files changed, 47 insertions(+)
 create mode 100644 hello-world-java-master/.gitignore
 create mode 100644 hello-world-java-master/HelloWorld.java
 create mode 100644 hello-world-java-master/README.md

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 1.06 KiB | 270.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To github.com:srinfotechbatch4/DevTeamAviodConflicts.git
   8c63975..5cfcaf7  feature/2025.10.10 -> feature/2025.10.10

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$ git commit -m "updated the developer2 activity"
[feature/2025.10.10 ac8d4fa] updated the developer2 activity
 1 file changed, 2 insertions(+)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$ git push
To github.com:srinfotechbatch4/DevTeamAviodConflicts.git
 ! [rejected]        feature/2025.10.10 -> feature/2025.10.10 (fetch first)
error: failed to push some refs to 'github.com:srinfotechbatch4/DevTeamAviodConflicts.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer2/DevTeamAviodConflicts (feature/2025.10.10)
$


Developer3 Activity::
=====================

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3
$ git clone git@github.com:srinfotechbatch4/DevTeamAviodConflicts.git
Cloning into 'DevTeamAviodConflicts'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3
$ cd DevTeamAviodConflicts/

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3/DevTeamAviodConflicts (main)
$ git checkout feature/2025.10.10
branch 'feature/2025.10.10' set up to track 'origin/feature/2025.10.10'.
Switched to a new branch 'feature/2025.10.10'

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3/DevTeamAviodConflicts (feature/2025.10.10)
$ git pull
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 11 (delta 3), reused 9 (delta 1), pack-reused 0 (from 0)
Unpacking objects: 100% (11/11), 1.40 KiB | 11.00 KiB/s, done.
From github.com:srinfotechbatch4/DevTeamAviodConflicts
   9964975..5cfcaf7  feature/2025.10.10 -> origin/feature/2025.10.10
Updating 9964975..5cfcaf7
Fast-forward
 .gitignore                              |  2 ++
 HelloWorld.java                         |  5 +++++
 README.md                               | 35 ++++++++++++++++++++++++++++++++-
 hello-world-java-master/.gitignore      |  2 ++
 hello-world-java-master/HelloWorld.java | 11 +++++++++++
 hello-world-java-master/README.md       | 34 ++++++++++++++++++++++++++++++++
 6 files changed, 88 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 HelloWorld.java
 create mode 100644 hello-world-java-master/.gitignore
 create mode 100644 hello-world-java-master/HelloWorld.java
 create mode 100644 hello-world-java-master/README.md

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3/DevTeamAviodConflicts (feature/2025.10.10)
$ git status
On branch feature/2025.10.10
Your branch is up to date with 'origin/feature/2025.10.10'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   hello-world-java-master/HelloWorld.java

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3/DevTeamAviodConflicts (feature/2025.10.10)
$ git add --all

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3/DevTeamAviodConflicts (feature/2025.10.10)
$ git status
On branch feature/2025.10.10
Your branch is up to date with 'origin/feature/2025.10.10'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   hello-world-java-master/HelloWorld.java


HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3/DevTeamAviodConflicts (feature/2025.10.10)
$ git commit -m "updated the developer3 activity"
[feature/2025.10.10 53d723c] updated the developer3 activity
 1 file changed, 6 insertions(+)

HP@DESKTOP-3GU6R56 MINGW64 ~/Documents/Batch4/Developer3/DevTeamAviodConflicts (feature/2025.10.10)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 435 bytes | 217.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch4/DevTeamAviodConflicts.git
   5cfcaf7..53d723c  feature/2025.10.10 -> feature/2025.10.10



Please be practice above 3 developers activity in real time bases

git fetch--->just fetch

git pull -->fetch+merged



Session Note::
==================

>git pull    ---->pull the changes from remote to local machine

if you faces any conflicts issues during the code changes push from local to remote, 

we need to follow the below steps to resove the conflicts

1.press the i from your keyboard

2.press the esc from your keyboard

3.swift+: from your keyboard

4.wq

5.press enter

to avoide the conflicts please make sure should perform >git pull 


1.git push   ---->local to remote

2.git pull   -->fetch the details + merged the changes

3.git fetch  --->just the details






13/10/2025::
=============


Git All the Commands::
==========================

Git commands::
==============


1. git clone git@github.com:srinfotechbatch4/srinfotechbatch4demo.git

2.cd srinfotechbatch4demo

3.git checkout feature/2025.10.10

4.git status

after modified the some files

5.git status

6.git add --all  OR git add <give specific filename>

7. git commit -m "message"

8. git push 

9.git pull

10. git fetch

11.git checkout -b feature/2025.10.13


clone      Clone a repository into a new directory

add        Add files

status     Show the working tree status

commit     Record changes to the repository

 pull       Fetch from and integrate with another repository or a local branch
 
 push       Update remote refs along with associated objects


 1.install git

2.introcuction about git-->VCS

3.github-->SCM

4.introduction about github

5.github account

6.create repositories

7.integarte git & github via SSH keys--->ssh-keygen -t ed25519

8.how to created branch in github

9.how to rasie PR-->pull requests--->feature branch to release

10.git commands::

1.git clone

2.cd 

3.git checkout 

4.git status

5.git add -all

6.git commit

7.git push

8.git pull

9.git fetch

10.>git pull

opend the editor

1.presh the i from your keyboard

2.esc

3.swift+:

4.wq

5.enter

10.how to resolved the git conflicts

11.github branching model/stargety

12.end to end flow of git & github


Jenkins Introductiion::
============================


Jenkins is a free and open source automation server/tool. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

Jenkins is a Orchestration tool

Jenkins is a CI/CD tool

Jenkins is a Schedular

Jenkins is a crone job schedular


<img width="1516" height="727" alt="image" src="https://github.com/user-attachments/assets/634d9a74-58fa-4fa0-9b21-abad792f482f" />



Roles And Responsibilities::
================================


1)The devops engineer was responsibility to release the product to the market as soon as possible 

2)release the product speed to the market 

3)Devops engineer was give continues feedback to the developers 4) Devops engineer responsibility start from git and end with production

A) when your activity start from git and end with production environment(production servers)Continues deployment 

when your activity start from git to LLE(lower level environment,testing environment,pre-prod…et) environment(pre-production servers)Continues delivery non-production environment

Tutorials::

https://www.tutorialspoint.com/jenkins/jenkins_overview.htm https://www.geeksforgeeks.org/jenkins-tutorial/#prerequisites





14/10/2025::
============


Download JDK 17 ::

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

Windows x64 Installer 153.92 MB

Windows x64 Compressed Archive	172.87 MB	
https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.zip (sha256 )

JDK 17 Environment setup::
==============================

Go to Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: JAVA_HOME

Variable Value:: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12

![image](https://github.com/user-attachments/assets/5743966a-8e88-4502-bd3a-904f1a839a01)

Click OK

![image](https://github.com/user-attachments/assets/1af67329-3601-4e23-855e-b69cf5763d95)


System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://github.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give Java Installed path till \bin

C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12\bin

![image](https://github.com/user-attachments/assets/d918df00-9c10-424f-b155-7a22e925d291)

Click OK

You Can verify Java is Installed Or Not

Go to command Prompt

![image](https://github.com/user-attachments/assets/773f6318-d8a5-4d2c-803b-e504d84e24e1)

![image](https://github.com/user-attachments/assets/aee76eab-4f27-4fce-af69-f28a872d37dc)


>java --version

C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

![image](https://github.com/user-attachments/assets/92e49e72-2f7c-464c-b8f1-2a30e6ebe702)

Above Screeenshot JDK17 setup is done




Installed jenkins in Windows::
================================

https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.515 for:

![image](https://github.com/user-attachments/assets/eaac3392-c1ce-498f-8a85-7a5fecabeb6b)

Jenkins.war file is downloaded

![image](https://github.com/user-attachments/assets/70e676a4-9a05-4748-b8d5-2373bf8ac189)



MAven Environment setup::
==============================

Maven::
=========

Maven is a powerful build automation tool used primarily for Java projects. Developed by the Apache.

it helps developers manage a project's build, dependencies, documentation, and more—all using a single configuration file called pom.xml

![image](https://github.com/user-attachments/assets/7455b09b-d334-4974-84da-60c76c45cdc0)


Common Maven Commands OR Maven Goals::
======================================


1) mvn clean	  ------------> Deletes target/ directory (clean build).

2) mvn compile	-----------> Compiles the source code.
   
3) mvn test	   ------------> Runs tests.
   
4) mvn package	------------> Creates a JAR/WAR.
  
5) mvn install	------------> Installs package into your local repository.
  
6) mvn deploy	-------------> Deploys package to a remote repository.



Installed jenkins in Windows::
================================

Please follow the below link steps to installed jenkins in your windows machines

https://www.jenkins.io/doc/book/installing/war-file/


https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.515 for:

![image](https://github.com/user-attachments/assets/eaac3392-c1ce-498f-8a85-7a5fecabeb6b)

Jenkins.war file is downloaded

![image](https://github.com/user-attachments/assets/70e676a4-9a05-4748-b8d5-2373bf8ac189)


Steps::

https://www.jenkins.io/download/

1. First download the jenkins.war file and right click -->open gitbash here
   

 ![image](https://github.com/user-attachments/assets/77ca0550-974b-463f-953a-d81c9603d69a)

  
2. run the command  -->java -jar jenkins.war --httpPort=9090

![image](https://github.com/user-attachments/assets/93cc2393-8a20-485f-ab8c-23451a64ccd3)

![image](https://github.com/user-attachments/assets/75e03c2f-0ccf-4da0-90cf-d92de22903c3)

we can see Jenkins is fully up and running

![image](https://github.com/user-attachments/assets/b0e26f12-f202-4e69-8672-223e6947d379)


Browse to http://localhost:9090 and wait until the Unlock Jenkins page appears

Installed the default suggested plugins

![image](https://github.com/user-attachments/assets/081c44fc-a6a3-46fa-82e3-7b34c2dc2dd6)

click on continue 

Need to create jenkins user profile 

USER Name--->admin (any name you can provide)

PASSWORD  -->admin  (any password as your wish but make sure you should remembered the these credentials)

Jenkins Dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/149d77a4-9f16-434a-8b07-cab848ea574e" />




15/10/2025::
==============


Maven Download link

https://maven.apache.org/download.cgi

Please download below zip file

Binary zip archive	apache-maven-3.9.10-bin.zip

![image](https://github.com/user-attachments/assets/819bec59-4a6d-4eca-a0da-dffe83019b34)

Downloaded Zip file

![image](https://github.com/user-attachments/assets/e719ecd4-e291-4e4e-a8d7-f4f947b2723c)

Please extract the file

![image](https://github.com/user-attachments/assets/b12246c2-8695-4494-a801-837540cf1bc2)


Go to Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: MAVEN_HOME

Variable Value:: C:\Users\HP\Downloads\apache-maven-3.9.10

![image](https://github.com/user-attachments/assets/0f7829be-f1c7-4e96-b2ed-51aea69c0497)


Click OK

![image](https://github.com/user-attachments/assets/0c8f1a15-fc5f-4073-98f5-5416df90f071)



System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://githubmvn -v.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give maven Installed path till \bin

C:\Users\HP\Downloads\apache-maven-3.9.10\bin


![image](https://github.com/user-attachments/assets/27d2d50a-845d-4c0f-9559-50e7779c08b2)


Click OK

![image](https://github.com/user-attachments/assets/7dd7e183-7d6d-424a-8b95-5b288e859af0)


You Can verify maven is Installed Or Not


Go to command Prompt

![image](https://github.com/user-attachments/assets/bf6571b4-cd62-4899-969b-abaec6d0ef8c)

>mvn -v

![image](https://github.com/user-attachments/assets/93472b9c-b6b0-4bd4-acac-41d28e2031d9)

C:\Users\HP>mvn -v


Apache Maven 3.9.10 (5f519b97e944483d878815739f519b2eade0a91d)
Maven home: C:\Users\HP\Downloads\apache-maven-3.9.10
Java version: 17.0.12, vendor: Oracle Corporation, runtime: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12
Default locale: en_IN, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

![image](https://github.com/user-attachments/assets/cc1d10c5-9c62-498f-9a58-b0f14e84438f)


Above Screeenshot maven setup is done



Steps::

1.first we need to create New repository in Github

2.please Clone the Empty Repositoy in your local system

3.copy the Spring-petclinic project code to in your repository 

4.once done we need to push project code to github repository 

5. we need to integarte Github to Jenkins

we need to create Sample demo Project in Jenkins

Create sample Freestyle project::
============================

Click New Item

![image](https://github.com/user-attachments/assets/d9e7f707-aa00-4c74-b9ca-30489ded6f55)


Configuration stages::

1.General

2.Source code management (SCM)

3.Triggres

4.Environment

5.Build Steps

6.Post Build Actions


![image](https://github.com/user-attachments/assets/b7b5caf1-3d81-4de0-aebc-c2dc5080f916)


General Section provide the Project/job description 


At SCM stage level select the Git and provide the github details

Below url is spring-petclinic Project and everyone Should please Fork to your github account

Github Project URL::
=====================

https://github.com/srinfotechbatch4/spring-petclinic.git

https://github.com/srinfotechbatch4/onlinebookstore.git

![image](https://github.com/user-attachments/assets/827c5b34-8a6e-41ad-b6e1-4899348730d6)

Branches to build

![image](https://github.com/user-attachments/assets/51cf678c-afbd-40bc-bbb5-fae55e4c5537)


![image](https://github.com/user-attachments/assets/7bab6e2d-7868-460e-bd42-b2697195f3fe)

Build steps::select the Invoke top-level Maven targets
Goals section
>mvn clean install

Maven goals::

>mvn test

>mvn install


>mvn clean install


>mvn clean


>mvn package

![image](https://github.com/user-attachments/assets/53d49170-9dfe-4cad-abc0-50bf268e96c7)


Job will be created

Click Build Now


Buils is Inprogress

![image](https://github.com/user-attachments/assets/c6e399ce-ac52-47de-94a3-b4d6d156dce5)

Success Builds

![image](https://github.com/user-attachments/assets/df198c5f-ce69-45a8-a9e5-607ba2e39b34)





16/10/2025::
==============


Poll SCM ::
=============

Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 


<img width="1663" height="684" alt="image" src="https://github.com/user-attachments/assets/4f831f81-ab6b-42b4-8e73-752076df2cbe" />


POLL SCM ----* * * * * --every minute when every commit 

Chrone JObs Formate LInk::
=============================

https://crontab.guru/examples.html


Create one sample POLL SCM jenkins job::
===========================================

Go to jenkins Dashboard

click New Item

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/098730bb-4882-4e6e-9627-2670dbff097a" />


Description

![image](https://github.com/user-attachments/assets/8385086f-ae72-4630-baa2-38e16e9866c2)



Provide the Git URL

Onlinebookstore Project::
=========================

https://github.com/srinfotechbatch4/onlinebookstore.git


![image](https://github.com/user-attachments/assets/647ef983-c76e-4c48-b928-e43ab5d47570)



Branch buiild

![image](https://github.com/user-attachments/assets/cd011371-c6c5-40d6-a44a-b51186d0e3af)


POLL SCM:: * * * * *

every minute build was trigger when new commits happend in github repository


![image](https://github.com/user-attachments/assets/899495ff-ce8c-4381-a012-5d058584809a)



Build Steps::

Select Invoke top-level Maven targets


![image](https://github.com/user-attachments/assets/8a818614-ba02-45d5-a98d-8d94adbe68f7)



Once New Commits Happend in Github , Automatically Build is triggered in The Jenkins Server this Called CI (Continuous Integration)



Check Your Workspace::
========================== 

once build success we can bale to see the /target folder under the Workspace


![image](https://github.com/user-attachments/assets/d860064f-6f5f-4ef2-aa93-363bf45e47c5)


1.To check a job's workspace:

2.Navigate to the job in the Jenkins UI.

3.Click on "Workspace" in the left sidebar.

![image](https://github.com/user-attachments/assets/f5ab670a-e7aa-4372-bbea-c3a1c130fe3a)



Under Target Folder we can able to see the all .ear/war/jar/zip Artifacts Formates


![image](https://github.com/user-attachments/assets/369fe791-fb6e-4a59-8fb1-99a14df190c3)


PLease try to execute the Project with below Maven Goals and see the difference 


Common Maven Commands OR Maven Goals::
======================================

https://github.com/srinfotechbatch4/spring-petclinic.git

https://github.com/srinfotechbatch4/onlinebookstore.git

1) mvn clean	  ------------> Deletes target/ directory (clean build).

2) mvn compile	-----------> Compiles the source code.
   
3) mvn test	   ------------> Runs tests.
   
4) mvn package	------------> Creates a JAR/WAR.
  
5) mvn install	------------> Installs package into your local repository.
  
6) mvn deploy	-------------> Deploys package to a remote repository.




Execute the Jobs in Parallel::
==============================


1.By Default execute the Jenkins build jobs are sequence way,one by one 

2.Don’t do 2 projects build parallel  this is real time scenario but we can do parallel builds as well one job

Jenkins build parallel setup

Go job ---> configure ----> Generall ---> Execute concurrent builds if necessary


![image](https://github.com/user-attachments/assets/3216a68f-b10b-44cd-83b5-b62c27525296)


![image](https://github.com/user-attachments/assets/909edd87-548d-4ded-a862-29cf850fac05)


Executors::
=============

Go to Manage Jenkins  ----> System ----># of executors



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0d817873-45e7-4354-a0e9-8a1783ce338a" />



Here 10 builds execute parallel ,I kept executor is 10 this is same machine 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bf2c18d8-3ab8-4f8d-b465-e7de1449d4a7" />




17/10/2025::
==============


Poll SCM ::
================

Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 

<img width="1629" height="686" alt="image" src="https://github.com/user-attachments/assets/63643206-be1e-43da-92bd-03d50cabf97b" />


POLL SCM ----* * * * * --every minute when every commit 

Build Periodically:::	
============================

H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


Please create a New Jenkins jobs both POLL SCM & Build Periodically 

https://github.com/srinfotechbatch4/spring-petclinic.git

https://github.com/srinfotechbatch4/onlinebookstore.git


Automatically Discard Old Builds:::
==============================
To automate the process of discarding old builds, you can configure the job’s settings to automatically delete old builds based on criteria such as the number of builds to keep or the age of the builds.

Follow these steps:

Open the Jenkins job (project).
Click on Configure (on the left-hand side).
Scroll down to the Build Discarder section (usually under the Build Triggers section).
Check Discard old builds.
Specify the following options:
Max # of builds to keep: Set the maximum number of builds to keep.
Max days to keep builds: Set the maximum age for builds to keep.
Save the configuration by clicking Save.


![image](https://github.com/user-attachments/assets/8d8c9cf9-988a-41e4-b052-539ef601171f)



Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


Create Sample Build peridiocally jenkins job::
=============================================

Description


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4827b662-c7e4-47ad-8cbc-65ded11d095b" />


Git url::


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5f0da0e6-fcd7-4ad2-b854-3df9af2393a7" />


Build the branch

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4f0ac907-c4ab-4ae9-b632-e8ddf71a7160" />


every 1 minute build will trigger

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cf65d287-5c0a-4855-8ddc-9b26be1c7a26" />


every 5 mints build will trigger

Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ed08304-1831-4a27-af65-f17da5117e05" />


click save 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/57d8ccdb-34a8-43b0-a5f0-1f0538a0fc10" />




21/10/2025::
==============


Email Notifications::
=======================

1.Setting up Jenkins Email Notifications allows you to alert your team when a build passes, fails, or encounters issues. Here's a step-by-step guide to configure it

2. give continues Feedback to the Dev team via Email when a build passes, fails

<img width="1739" height="576" alt="image" src="https://github.com/user-attachments/assets/0b411df9-85d9-4f47-9837-60566f223acf" />


Steps::

Go to mail 


![image](https://github.com/user-attachments/assets/e6764012-c4e8-43ab-bea7-0fcf11c61f5e)

Click manage your google account

![image](https://github.com/user-attachments/assets/b2b0e9e5-66ff-4713-b95b-0cc3cc2ecf42)


Click Security


![image](https://github.com/user-attachments/assets/acc069d3-2944-43d7-a0d0-a0ae17b478d6)


Click protect your account


![image](https://github.com/user-attachments/assets/a80aa65d-210c-4920-ac59-bff59d001048)

Click Add phone number

![image](https://github.com/user-attachments/assets/d3839125-e302-40a0-a942-497f50f2e08a)

Click add phone

![image](https://github.com/user-attachments/assets/758cb87d-c0df-43d1-890a-6539046b86f7)

![image](https://github.com/user-attachments/assets/e532e1dd-fef8-4ed6-b46c-075d97cdd10d)

![image](https://github.com/user-attachments/assets/96dde956-0cb9-4125-bc16-9b18b5a47883)

Make sure your account is protected 

![image](https://github.com/user-attachments/assets/ef101b4f-f98a-4941-83bb-e99c98a7b583)


Make sure 2-steps Verification is ON


![image](https://github.com/user-attachments/assets/eb82b19f-0ae0-4df4-8c79-463769e0f2cf)


Credentials:

In search box App Password


![image](https://github.com/user-attachments/assets/20789330-ae4d-407d-b55c-201452435d33)

![image](https://github.com/user-attachments/assets/45634fa0-7198-4a55-9ce3-bd5c7c7b4c2d)


![image](https://github.com/user-attachments/assets/d9e2b041-0e63-42de-96be-0b2406113328)


![image](https://github.com/user-attachments/assets/814dc39c-290f-4035-bec8-6871cfd44467)


 we should provide this password in Jenkins Email configuration level


![image](https://github.com/user-attachments/assets/b1cde092-d3ed-4ae8-b9fb-e3fd32095fce)


Go to Jenkins  ---> Manage Jenkins

System configurations


![image](https://github.com/user-attachments/assets/e3467726-c6f8-45f5-b728-5012e2e906f3)



Go to Extended E-mail Notification



![image](https://github.com/user-attachments/assets/11351c43-ecf5-4327-86d9-a4bcde391589)


SMTP server  :: smtp.gmail.com

SMTP Port:: 465

Credentials::
Username:: Your Email
Password::Zvqxxvplduhrlffv

![image](https://github.com/user-attachments/assets/7e8c5e1a-785f-4b0e-b85c-f37b6f1123ce)



Select Use SSL

Default content type HTML

![image](https://github.com/user-attachments/assets/742a4252-a704-4a0c-ad2b-ae35e9c2a2e0)


Default Triggers

![image](https://github.com/user-attachments/assets/67d1fe48-b3f0-4d59-a842-054b11a3ed70)

E-mail Notification


![image](https://github.com/user-attachments/assets/dc3dfcd8-1454-434b-a88b-44acf32a3f56)


![image](https://github.com/user-attachments/assets/37414d6d-d388-4f21-840e-899b8c3e3bf1)


Use SMTP Authentication? –should selected

Use SSL select

Port 465

![image](https://github.com/user-attachments/assets/0c8e8c73-69bc-4a2b-a19e-f130e81f8c16)


Test configuration by sending test e-mail

![image](https://github.com/user-attachments/assets/b48d366e-5a52-458c-b80d-1c45b803e3ce)


Connection success

![image](https://github.com/user-attachments/assets/28f7fd8a-c85e-486a-b2f4-64af53b1db0a)


 Post build action


![image](https://github.com/user-attachments/assets/d386a9c7-a5cf-4a48-a6ab-5030c96288e0)


![image](https://github.com/user-attachments/assets/d200565f-7356-4470-b080-8ba7f731837c)


![image](https://github.com/user-attachments/assets/7cddd9fa-8498-47fa-a86b-5066ae058700)


![image](https://github.com/user-attachments/assets/60b129a8-5adf-43b1-9639-a293c59d929c)







22/10/2025::
==============




Published Artifacts & Test Results::
=============================

![image](https://github.com/user-attachments/assets/591cddf5-eb86-4942-91a7-1dc5bfbb0f72)


![image](https://github.com/user-attachments/assets/23f6cd8e-1aac-4597-9900-a4c759ad4b8a)

Post build Action i want to published artifacts & test results

![image](https://github.com/user-attachments/assets/fcd3ea28-a352-431f-8e1b-86758787fe7a)

I'm going to created one free style job and configured Post-build Actions

In post build Action select the option Archive the artifacts

>target/*.war  OR target/*.jar  OR target/*.zip  OR target/*.ear

![image](https://github.com/user-attachments/assets/44f88d03-d9c8-4800-88e2-06217f721d5c)

![image](https://github.com/user-attachments/assets/7ed9efc9-6a45-4eff-a789-0b7fe50c6024)


In post build Action select the option Publish JUnit test result report for to published the test results

>target/surefire-reports/*.xml


![image](https://github.com/user-attachments/assets/e3c17557-410c-4915-bec3-2ec5edee6526)



I want to show test results ::
=================================


>ls target 

Post build action stage

Select archive the artifact
--target/*.jar

Junit test results::
--target/surefire-reports/*.xml

See test results & antifactory ::
===================================


![image](https://github.com/user-attachments/assets/819809c2-3611-45e0-abd0-0139b29d166b)




3.For every company will do sequence build on one project this is recommended approach



General  ---just descriptin

SCM

where is your project--github, bitbucket

Triggere

whenever code changes i want build the project given time

Environmant

--all about workspaces folders

Build Steps

dev team will tell which tool we are using in current project


Post Build

devops engineer is aim is given continue feedback to dev team via email notification



Parameterized Jenkins Jobs ::
===============================

Run the same job with different inputs without modifying the configuration manually

Go To New Item

![image](https://github.com/user-attachments/assets/695a7137-6283-462b-8ff7-37ffb4f6ff68)


Enter Job Name, Free style project and click ok

![image](https://github.com/user-attachments/assets/da12fe42-db98-40e1-af80-1ba335b50596)



Enter the description

![image](https://github.com/user-attachments/assets/cd3c1d8f-d403-4694-a830-1084796c80ad)


Select the option This project is parameterised

![image](https://github.com/user-attachments/assets/e2fb86d9-ea5b-4981-a3ee-81d4645d06c1)


Click Add Parameter

![image](https://github.com/user-attachments/assets/2702952d-1e31-4432-a405-88f509bfc58c)


Select optiions String parameter or choise parameter or boolean parameter you can select the ny options based on your requirement 

![image](https://github.com/user-attachments/assets/1b18b622-c141-4988-bdc3-785359a04e99)


select string parameter

![image](https://github.com/user-attachments/assets/33215729-9b13-46bf-bbbb-b08416979dd6)


Select Choise Parameter

![image](https://github.com/user-attachments/assets/59b8db99-1196-4024-9cdf-b3a80a358f81)


choise parameter

![image](https://github.com/user-attachments/assets/952de313-ebde-4b39-be7b-c31c6b0ca283)


Click Save

![image](https://github.com/user-attachments/assets/4f19f2ba-c85b-4adf-9dd0-16da436011dd)


You Can observed this project is parameterized 

![image](https://github.com/user-attachments/assets/fef0f526-c9f2-4dec-8d0e-960efc94d09c)


Click Build with parameter

![image](https://github.com/user-attachments/assets/1cbeb32c-bd23-4d87-87be-8e6d010bb968)


select deployment environment

![image](https://github.com/user-attachments/assets/af62b4d7-b107-4856-b567-d010efb3a11a)


select which versioj you want to deployment like tis you can configured real time parameterized project in jenkins

![image](https://github.com/user-attachments/assets/506da743-2efd-4e19-8082-67592c3c24b1)


Click Build

![image](https://github.com/user-attachments/assets/9554cd4a-ba9a-4821-af2e-638d554632a8)


![image](https://github.com/user-attachments/assets/28afabd9-1c84-4313-95c6-1ec8bd50488d)



I want Build a 3 projects ::
===========================

I want a build 3 projects ,one project build is success then it will start 2nd project & once 2nd project build is success then it will start 3rd Project, without manually interventions we need setup these 3 projects configurations.


<img width="1761" height="685" alt="image" src="https://github.com/user-attachments/assets/4f646e77-20ae-477c-b7aa-6aea1534ca50" />




23/10/2025::
============


I want Build a 3 projects ::
===========================

I want a build 3 projects ,one project build is success then it will start 2nd project & once 2nd project build is success then it will start 3rd Project, without manually interventions we need setup these 3 projects configurations.

![image](https://github.com/user-attachments/assets/5d043ea2-97c3-4b8f-8b56-95703e1adf95)



![image](https://github.com/user-attachments/assets/b2dfde9d-e397-46b8-a8cb-67ab3711b141)


Project-A, Projec -B, Projec - C 

Once Project-A build is done, then it will start Project-B build and once Project-B build SUccess then it will start Project-C build ---for this we need to select Add post-build action and select "Build other projects" in drop down and provide Project-B details.


![image](https://github.com/user-attachments/assets/048a99bc-bcf6-47ca-9b27-ef23152eab97)


Projec A is  (Downstream project is ---Projec B)

Projec B is (UP Stream project is ----Projec A)

Projec C is (downstream project of --Projec B)

i created 3 free style project in jenkins 

Project-A ::
==============

Github URL::: https://github.com/parasa7358/spring-petclinic.git

![image](https://github.com/user-attachments/assets/e8073061-b815-4945-bd7f-c20b3a6576e2)


Post Build Action , select the option Build Other Project  Project-B


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4b24fde-a3a9-4b98-882b-69dc46a4e9e6" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b792995-005a-4175-9cdb-4cd8524fea60" />


Project -B ::
=============

Github URL:::https://github.com/parasa7358/onlinebookstore.git


![image](https://github.com/user-attachments/assets/2ee62e92-e677-4717-93be-77d6dd1ecbf9)


Post Build Action , select the option Build Other Project Project-C


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b94f430d-2173-4d08-8432-f7e86ec9b47c" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/efa90369-f73d-4b25-bcc9-72841cb42c4f" />



Project-C::
============


Github URL:::https://github.com/srinfotechbatch2/devOpsWeb.git



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/69efc57e-2857-46d7-a3ab-34a58b5b0aae" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/256cac24-5476-4b71-8079-adb194559549" />




Pipelines Introduction:::
=============================

A Jenkins pipeline is a series of automated steps or stages that define the process of continuous integration/continuous delivery (CI/CD) for your code. Jenkins, being a popular open-source automation server, uses pipelines to automate tasks like building, testing, and deploying code.

There are two types of Jenkins pipelines:

1. Declarative Pipeline

2. Scripted Pipeline

1. Declarative Pipeline::
The declarative pipeline syntax is simpler and more structured. It's the recommended style for most users because it's easy to read and maintain

Create Pipeline Project::
=======================

Steps

Click +New Item


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3ac406d8-9a29-4e2f-9711-226ff8806524" />


Enter the Project Name And Click OK

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/339a329c-47d6-41e0-b008-6128965033c5" />


At General Section Provide the Description


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cb474edb-bcaf-42f9-9d1d-b51da6333b74" />


At Definition, We need to select the Pipeline Script 


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5dc25001-3022-4d7a-8772-64c2bf85c55e" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/58d97da8-8baa-43e2-b25f-ad8c60fd0c32" />



Here's an example of a simple declarative pipeline: Syntax

pipeline{

agent any

stages{

Stage ('Clone'){

steps{

// write code
}
}

Stage ('Build'){
steps{

// write code
}
// write code

}

Stage ('Test'){

steps{

// write code
}
// write code

}
Stage ('Execute test casea and get the results'){

steps{

// write code
}
// write code

}

Stage ('Generated Artifact'){

steps{

// write code
}
// write code

}

Stage ('Deploy'){

steps{

// write code
}
// write code

}

// write code

}

}



pipeline {
   
    agent any

    stages {
       
        stage('Clone') {
           
            steps {
              
                echo 'Hello World'
            }
        }
        stage('Build') {
           
            steps {
              
                echo 'Hello World'
            }
        }
        stage('Test') {
           
            steps {
               
                echo 'Hello World'
            }
        }
        stage('Generate the test reports') {
          
            steps {
               
                echo 'Hello World'
            }
        }
        stage('Publishered Artifacts') {
           
            steps {
              
                echo 'Hello World'
            }
        }
        stage('Deploy') {
          
            steps {
              
                echo 'Hello World'
            }
        }
    }
}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/661f0dc6-aeb3-4a06-9a7c-b66c55e431bb" />



Pipeline: Stage View::
========================

Pipeline: Stage View Plugin in Jenkins The Pipeline: Stage View plugin is a visualization tool in Jenkins that allows users to see a graphical view of each stage in a pipeline. It provides a real-time and historical overview of pipeline execution per stage, making it easier to debug, monitor, and analyze performance.





24/10/2025::
=============


Pipeline: Stage View::
=================

Pipeline: Stage View Plugin in Jenkins
The Pipeline: Stage View plugin is a visualization tool in Jenkins that allows users to see a graphical view of each stage in a pipeline. It provides a real-time and historical overview of pipeline execution per stage, making it easier to debug, monitor, and analyze performance.


Click the Build Now and we can triggered the pipeline








Success all the stages & Steps


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40a1524f-7926-4d0c-b294-c43ede8350f2" />



Key elements in the declarative pipeline:::
======================================

pipeline: This is the top-level structure.

agent: Specifies where the pipeline will run, such as on any available agent, a specific node, or a Docker container.

stages: Defines the different steps or stages in the pipeline (e.g., Build, Test, Deploy).

steps: Commands to be executed in each stage.



Please try to create one pipeline job in jenkinsfile and execute the below Declarative pipeline example:;

pipeline {

agent any

stages {
    stage('Clone') {
        steps {
            git branch: 'main', url: 'https://github.com/srinfotech7358/spring-petclinic.git'
        }
    }
    
      stage('Build') {
        steps {
           bat 'mvn clean install'
        }
    }
      stage('Test') {
        steps {
           bat 'mvn test'
        }
    }
    
      stage('Generate Junit Test Results') {
        steps {
           junit 'target/surefire-reports/*.xml'
        }
    }
    
      stage('Generate Artifacts') {
        steps {
           archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
        }
    }
}
}


See test results & antifactory ::
================================

archive the artifact :: target/*.jar

Junit test results:: target/surefire-reports/*.xml


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b216b582-74a9-47de-9351-1fcd88930af4" />



Pipeline as Code::
===================

Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.


![image](https://github.com/user-attachments/assets/7d3b20e8-e72f-41ff-94ce-0c912f51a93d)



![image](https://github.com/user-attachments/assets/edd96e0c-ac4d-438e-8a5b-97ae99ed1fda)




Pipeline as Code::
==================
Both declarative and scripted pipelines are stored as Jenkinsfiles, which you place in your source code repository. This allows you to version control your pipeline and keep it aligned with your application code.

Declarative pipeline with Jenkinsfile::
===============================

pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'git@github.com:parasa7358/spring-petclinic.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Test Results Reports') {
            steps {
                junit 'target/surefire-reports/*.xml'
            }
        }
        
        stage('Artifacts') {
            steps {
                archiveArtifacts artifacts: 'target/*.war', followSymlinks: false
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}


This pipeline:::

1 Checks out the source code from your Git repository.

2. Builds the project using Maven.
   
3.Runs unit tests.

4.Deploys the application using a custom script.

JOb creation::

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/edec9bbf-3656-4edb-b80f-46661524dcaa" />

Branches to build


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/062ed8d1-560c-49d7-9668-d91f7a901706" />


Script Path::: This path is Jenkinsfiles where we maintained in github source code level



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c423564b-85df-44b8-a366-c2738ec4b22e" />



Scripted pipeline with Jenkinsfile::
===============================


node{

    stage('clone'){
        git branch: 'main', url: 'https://github.com/srinfotechbatch2/spring-petclinic.git'

    }

     stage('build'){

        bat 'mvn clean install'
    }

     stage('Test'){
      bat 'mvn test'
        
    }
     stage('Artifacts'){
     archiveArtifacts artifacts: 'target/*.jar', followSymlinks: false
        
    }
     stage('generated test reports'){
    junit 'target/surefire-reports/*.xml'
        
    }
}



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aaa9e47f-71a3-46e8-876b-f26d9faba86c" />



github sourcecode jenkinsfile 



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d17ef94-2780-42b3-8e61-d7fce9b4d15e" />




28/10/2025::
=============


Tomcat Web Server: Introduction
=============================

Apache Tomcat is an open-source web server and servlet container developed by the Apache Software Foundation. It is primarily used to serve Java applications and is one of the most popular servlet containers in the world.

Tomcat is an essential tool for anyone working with Java web applications. It provides a simple, reliable platform for deploying and managing Java Servlets and JSPs and is widely used in both development and production environments. Its ease of use, combined with powerful features and flexibility, makes it an ideal choice for many developers working on Java-based web applications.

Apache Tomcat is an open-source web server and servlet container that is primarily used to serve Java-based web applications. It implements several Java EE (Enterprise Edition) specifications, such as Java Servlet, JavaServer Pages (JSP), and WebSocket, among others. Tomcat is often used to run Java applications on the web because it's lightweight, easy to configure, and widely supported.

Here are some key points about Tomcat:

1. **Servlet Container**: Tomcat is a servlet container, meaning it manages the lifecycle of Java Servlets, which are small Java programs that run on a web server.
  
2. **JSP Support**: Tomcat also supports JavaServer Pages (JSP), a technology that allows for embedding Java code within HTML pages.

3. **Configuration**: It’s highly configurable through XML files, like `server.xml` for server settings, `web.xml` for application settings, and others.

4. **Lightweight**: Unlike full-fledged application servers like WildFly (formerly JBoss) or GlassFish, Tomcat is primarily a servlet and JSP container, which makes it lighter and easier to deploy for simpler Java web applications.

5. **Performance**: It’s known for good performance in handling static content, making it a popular choice for Java web developers.



Integrate Tomcat  with Jenkins::
==============================


<img width="1827" height="737" alt="image" src="https://github.com/user-attachments/assets/32ac9cfd-8681-4110-8a3a-53a4b49b13f7" />





Tomcat Download link::
--------------------

https://tomcat.apache.org/download-90.cgi


64-bit Windows zip


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/17a4f6bb-d883-4507-9ecd-eba5c04e4418" />



Integrate Tomcat Jenkins::
==============================



![image](https://github.com/user-attachments/assets/7155f817-58cd-4f85-93e8-405b7c96fd7b)






Integrating Tomcat with Jenkins is a common use case for automating the deployment of Java-based web applications. Jenkins can be set up to deploy a web application to a Tomcat server whenever a new build is triggered.

Prerequisites:

Apache Tomcat should be installed and running on your server.

Jenkins should be installed and running.

Steps to integrate Jenkins with Tomcat:

1. Install the "Deploy to Container" Plugin in Jenkins:
The easiest way to deploy to Tomcat from Jenkins is by using the Deploy to Container plugin. This plugin allows Jenkins to deploy WAR files to a Tomcat server.

Go to your Jenkins dashboard.

Click on Manage Jenkins > Manage Plugins.

In the Available tab, search for Deploy to Container Plugin and install it.

Once installed, restart Jenkins to apply the plugin.

2. Configure Tomcat Server in Jenkins:
Now you need to tell Jenkins where your Tomcat server is running.

In Jenkins, go to Manage Jenkins > Configure System.

Scroll down to the Deploy to container section.

Click Add Tomcat Server.

Provide the necessary information:

Name: Give the Tomcat server a name (Tomcat9).

URL: The URL of your Tomcat server (e.g., http://localhost:8080).

Username: The username for Tomcat's manager app (usually admin).

Password: The password for that username (set in Tomcat's tomcat-users.xml).

Save the configuration.

3. Configure Tomcat’s tomcat-users.xml:

Make sure Tomcat is set up to allow Jenkins to deploy the application by editing the tomcat-users.xml file.

https://stackoverflow.com/questions/7763560/401-unauthorized-error-while-logging-in-manager-app-of-tomcat

tomcat-users.xml file::
=========================




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c3d43081-1646-4980-b961-1743418f303f" />






  <role rolename="manager-gui"/>
  
  <role rolename="manager-script"/>
  
  <role rolename="manager-jmx"/>
 
  <role rolename="manager-status"/>
  
  <role rolename="admin-gui"/>
 
  <role rolename="admin-script"/>
 
  <user username="admin" password="admin" roles="manager-gui, manager-script, manager-jmx, manager-status, admin-gui, admin-script"/>




Restart Tomcat to apply the changes.

4. Create a Jenkins Job to Build and Deploy the Application:

Next, you need to create a Jenkins job that will build your web application (e.g., a WAR file) and deploy it to Tomcat.

From the Jenkins dashboard, click New Item.

Select Freestyle Project, give it a name, and click OK.

In the job configuration, go to the Build section and configure your build step, such as building a Maven project For Maven, you can use:

> mvn clean install

In the Post-build Actions section, add Deploy war/ear to a container.

In the WAR/EAR files field, provide the path to your WAR file (e.g., target/my-app.war).
In the Container field, choose the Tomcat server you configured earlier.
Set the Context Path (e.g., IfocusAWSDevOpsTraining), which is the URL path where the application will be accessible on Tomcat.
If you want Jenkins to deploy automatically after every successful build, check the option Deploy after every successful build.
Save the job.

5. Trigger the Build and Deployment:
Go to the Jenkins job you just created and click Build Now to trigger a build.
After the build completes, Jenkins should deploy the WAR file to your Tomcat server.

You can access your application by going to http://<tomcat_host>:<tomcat_port>/<context_path>

example::  http://localhost:8080/SRINFOTECHApplication/

POLL SCM:: * * * * * (every minute automatic build & deployment happend when new commits happend in github)

This setup will allow Jenkins to automatically build and deploy your Java web application to Tomcat with each new build


Polling SCM (Source Code Management) and webhooks are two common methods used for integrating continuous integration (CI) systems or automating tasks based on changes in repositories.

1. Polling SCM

Polling SCM is a method where a system (like Jenkins, GitLab CI, etc.) periodically checks the source code repository for changes. If it detects changes, it triggers the build process or some other automated task.

How it works:

A job is set up to check the SCM (like GitHub, GitLab, Bitbucket, etc.) at regular intervals (e.g., every minute or hour).

The CI server pulls the repository to see if there are any new commits since the last poll.

If changes are detected, it triggers the CI/CD pipeline to build, test, or deploy the application.

2. Webhooks

Webhooks provide a more efficient method for triggering actions based on changes in the repository. Rather than the CI system polling for changes, the source control platform sends an HTTP POST request (webhook) to the CI system when an event (like a commit or pull request) occurs.

![image](https://github.com/user-attachments/assets/59e3f392-4da9-4fe3-8238-d2bd2fee5fc3)



CI/CD::
==============

Github Project URL:::

https://github.com/srinfotech7358/onlinebookstore.git


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a91a97b0-9caa-400d-8f89-5d1b82bb9d6c" />


TomcatIntegarteWithJenkins::

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1bb75284-c2f7-4d89-8f86-b395efc5bc33" />


![image](https://github.com/user-attachments/assets/5fc161ca-106f-442c-9938-1ea4c840e919)

POLL SCM

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/53f4eb27-37ca-4019-8452-f4c8d1fbd582" />


Build Steps

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bf7e1b40-71cb-47ff-8bc9-75b02deba898" />


Post-build Actions


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d32fadf6-fda7-431c-bb3b-6ff0420b2beb" />


Deploy war/ear to a container

WAR/EAR files ----> target/*.war

Context path ---> SRinfotechonlinebookstore



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45afbce3-b983-4ac5-9ccf-6ea537f7accd" />


Tomcat 9.x Remote

![image](https://github.com/user-attachments/assets/de1c2aae-8c08-4f98-aead-a6829e01c24d)

Tomcat URL:: http://localhost:8080



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/80b00435-1fdc-4855-a039-d8a2a49484b2" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5238e642-33bd-4572-ad79-2ab0f83d7d3a" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4498301f-9f68-4e49-bac5-613c7fe75f50" />




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4d881060-16e9-4110-8140-e0d9ffe19577" />


