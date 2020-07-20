# DevOps-task1
Task Description :- 
Task 1

JOB#1
If Developer push to dev branch then Jenkins will fetch from dev and deploy on dev-docker environment.

JOB#2
If Developer push to master branch then Jenkins will fetch from master and deploy on master-docke environment.
both dev-docker and master-docker environment are on different docker containers.

JOB#3
Manually the QA team will check (test) for the website running in dev-docker env++ironment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger #job 2


Pre-requisites For This Project :- 

- Base OS in my case it is Windows 10 and On the Top of Windows 10 I am using Red Hat Enterprise Linux (RHEL 8 ) with the Help of Virtual Box
- In This RHEL we need Jenkins to installed and setup to be completedd so that we can use it in our ptoject. 


This is the code which is pushed by Developer From Git Bash to GitHub on 2 different branches i.e. master and dev branch now we ill use this in Jeknins to use them and merge branches to merge the code ..

Screen is inside the folder
