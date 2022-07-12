0x01. Git
======================

-   By Egbe Marvelous M.


Resources
---------

**Read or watch**:

-   [Resources to learn Git](https://alx-intranet.hbtn.io/rltoken/EC5rb6yWBWllPB-T8rd0SQ "Resources to learn Git")
-   [About READMEs](https://alx-intranet.hbtn.io/rltoken/yM5FZakIhHB2TWO1PN2PZg "About READMEs")
-   [How to write a Git commit message](https://alx-intranet.hbtn.io/rltoken/SihXX88mKA9TFaIebKX3Rw "How to write a Git commit message")

**Resources for advanced tasks** (Read only after finishing the mandatory tasks):

-   [Learning branching](https://alx-intranet.hbtn.io/rltoken/hBgLCXoQaGTcOwr_kmCoEA "Learning branching")
-   [Effective pull requests and other good practices for teams using GitHub](https://alx-intranet.hbtn.io/rltoken/xhKV_qX3eXvyePzeNraEGw "Effective pull requests and other good practices for teams using GitHub")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/Rfy6VuvRfNAau31z1J_b-w "explain to anyone"), **without the help of Google**:

### General

-   What is source code management
-   What is Git
-   What is GitHub
-   What is the difference between Git and GitHub
-   How to create a repository
-   What is a README
-   How to write good READMEs
-   How to commit
-   How to write helpful commit messages
-   How to push code
-   How to pull updates
-   How to create a branch
-   How to merge branches
-   How to work as collaborators on a project
-   Which files should and which files should not appear in your repo

### Copyright - Plagiarism

-   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
-   You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
-   You are not allowed to publish any content of this project.
-   Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements
-------------

### General

-   A `README.md` file at the root of the `alx-pre_course` repo, containing a description of the repository
-   A `README.md` file, at the root of the folder of this project (i.e. `0x01-git`), describing what this project is about
-   **Do not use GitHub’s web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
-   Your answer files should only contain the command, and nothing else

More Info
---------

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main

```


Tasks
-----

### 0.Create and setup your Git and GitHub account

mandatory

**Step 0 - Create an account on GitHub [if you do not have one already]**

You will need a GitHub account for all your projects at ALX. If you do not already have a github.com account, you can create an account for free [here](https://alx-intranet.hbtn.io/rltoken/hQPhGkQBxYfTYTYDKtrZvw "here")

**Step 1 - Create a Personal Access Token on Github**

To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow [this tutorial](https://alx-intranet.hbtn.io/rltoken/1sEAC5BvAQ1G5VabbAl2iA "this tutorial") to create a token.

Once it’s created, you should have a token that looks like this:

[click here to view image](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/a449483cd76a72cef1b42df831e686c64faa1cf6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220712T135809Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a617ac848d43a42936a03b28f29d28689f3f77b7a9d4649b2584d86a67221178 "click here to view image")

**Step 2 - Update your profile on the Intranet**

Update your Intranet profile by adding your Github username [here](https://alx-intranet.hbtn.io/rltoken/vHKiFlBLIC7VCcAWGWF8FA "here")
If it’s not done **the Checker won’t be able to correct your work**

[click here to view image](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/6270480a0a982cd1846b877eda2ee405d2e8f575.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220712T135809Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=83bb02258a71174a45a89315f576e5cb700dd304dcd15caf7116693091e5c147 "click here to view image")

**Step 3 - Create your first repository**

Using the graphic interface on the [github website](https://alx-intranet.hbtn.io/rltoken/hQPhGkQBxYfTYTYDKtrZvw "github website"), create your first repository.

-   Name: `alx-pre_course`
-   Description: `I'm now a ALX Student, this is my first repository as a full-stack engineer`
-   Public repo
-   No `README`, `.gitignore`, or license

[click to view image](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/2340a2d0f7c74b5dd6f8fc2aa58f94d13ea2c775.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220712T135809Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=aacf735e64ababa07a8b3cf8d051b725be7b61ffde6c5f9bb488a902f8a6dabc "click to view image")

**Step 4 - Open the sandbox**

On the intranet, just under the task, click on the button [Get a sandbox](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/9db8eece71455dfddf4b7d8585c037c535f1d18d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220712T135809Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4d163fbd50e74fcbe4aaa9a14dd4956dbe7d500d08f9c4f356f3929776b26a4f "Get a sandbox") and `run` to start the machine.

Once the container is started, click on [Webtern](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/be9d1fbfb3d97e6924a4d2af7df9290ad7ae77df.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220712T135809Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=13d864ef5a2661aba0a52e903f52dd4331e5c86824004fdd49cb4aee435f8ae0 "Webtern") to open a shell where you can start work from.

**Step 5 - Clone your repository**

On the webterm of the sandbox, do the following:
-   Clone your repository

```
root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git                  
Cloning into 'alx-pre_course'...
warning: You appear to have cloned an empty repository.

```
**Replace {YOUR_PERSONAL_TOKEN} with your token from step 1**
**Replace {YOUR_USERNAME} with your username from step 0 and 1**

**Step 6 - Create the README.md and push the modifications**

-   Navigate to this new directory. [Tips](https://alx-intranet.hbtn.io/rltoken/_hv6gkuqwPeF_nefdPygcw "Tips")

```
root@896cf839cf9a:/# cd alx-pre_course/
root@896cf839cf9a:/alx-pre_course#
```
-   Create the file `README.md` with the content `My first readme`. [Tips](https://alx-intranet.hbtn.io/rltoken/0U_R5Z7fbzEFJ1hXKx4fdQ"Tips")
```
root@896cf839cf9a:/alx-pre_course# echo 'My first readme' > README.md                                                                 
root@896cf839cf9a:/alx-pre_course# cat README.md                                                                                      
My first readme
```
