#GitPractice

only for command line practice

##Create a repository
###1.Empty repo from scratch
first get to the location where you want put your project directory in.
then
> git clone repo_url

add some files then

>git add file1<br/>
>git add file2<br/>
>git add ...<br/>
>git commit -m "message aobt this commit"<br/>
>git push origin master<br/>

###2. From exsiting project

first get into the directory of your project, then

>git init<br/>
>git add file1<br/>
>git add file2<br/>
>git add ...<br/>
>git commit -m "message aobt this commit"<br/>

touch with remote repo in github

>git remote add origin git@github.com:your_repo_url

transfer files to remote repo

>git push -u origin master

##Update a repository

use

>git add -u

then commit the changes and finally push the changes

>git push -u origin master