# Getting Started Instruction

## Before you start, Make sure you have 

* wamp server installed
* github account
* git installed

Login to your github

You need to fork the project. Put in the search bar "user:acct2day repo:wp-website-2015". Then click on the link to the repo. Click on 'Fork' inside the 'wp-website-2015' repo to fork it. Now you have the repo forked in your git account.

Run GIT Terminal

Navigate to the direcotry where you save your projects on your local machine

`~ $ cd /D/www/`

Make a directory for your project

`~/D/www $ mkdir wp-dev7-b`
`~/D/www $ cd wp-dev7-b`

Now initailize the repository

`~/D/www/wp-dev7-b $ git init`

Add this as the remote origin:

`~/D/www/wp-dev7-b (master) $ git remote add origin https://github.com/acct2day/wp-website-2015.git`

Pull from Github to local:

`~/D/www/wp-dev7-b (master) $ git pull origin master`

Now the files from git are copied to your local dir. You need to copy "local-config-sample.php" and rename your copy "local-config.php". Start your wamp server. Go to "http://localhost/phpmyadmin/" and create a database "wp-website-2015". Open "local-config.php" and update the database information.

local-config.php - is in .gitignore so it is not commited to github.

Open "http://localhost/wp-website-2015/" on your browser, you will be prompted to install wordpress on your local machine. If you are not redirected to the installation page, try this url "http://localhost/wp-website-2015/wp/wp-admin/install.php".

Now, to make any changes you need to create a branch and checkout the branch. You never edit on master. You only merge to master.



--------

This repository is meant to provide an example for *forking* a repository on GitHub.

Creating a *fork* is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit *Pull Requests* to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.

After forking this repository, you can make some changes to the project, and submit [a Pull Request](https://github.com/octocat/Spoon-Knife/pulls) as practice.

For some more information on how to fork a repository, [check out our guide, "Forking Projects""](http://guides.github.com/overviews/forking/). Thanks! :sparkling_heart:
