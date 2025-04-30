# Create Project

**Project1: Where we only pull git repository from github**

click on **"Dashboard -> New Item"**

![Dashboard -> New Item](https://github.com/herrry107/Jenkins/blob/main/images/project1/jenkins-newitem.png)

click on **"Dashboard -> New Item -> Freestyle Project"**

![Dashboard -> New Item -> Freestyle Project](https://github.com/herrry107/Jenkins/blob/main/images/project1/jenkins-newitem-free-style.png)

click on **"Dashboard -> New Item -> Freestyle Project -> git -> repository url"**

!["Dashboard -> New Item -> Freestyle Project -> git -> repository url"](https://github.com/herrry107/Jenkins/blob/main/images/project1/jenkins-newitem-free-style-git.png)


if we want to build periodically means run build after every time set (optionally)
click on **"Dashboard -> New Item -> Freestyle Project -> git -> repository url -> trigger -> Build Periodically"**

![Build Periodically](https://github.com/herrry107/Jenkins/blob/main/images/project1/jenkins-newitem-free-style-build-periodically.png)

if we want to build periodically but when any change in repository means run build after any changes not every decided time than we use **Source Code Polling**
click on **"Dashboard -> New Item -> Freestyle Project -> git -> repository url -> trigger -> Poll SCM"**

![Poll SCM](https://github.com/herrry107/Jenkins/blob/main/images/project1/jenkins-newitem-free-style-scm.png)

# Run Project 

![Build Now](https://github.com/herrry107/Jenkins/blob/main/images/project1/jenkins-newitem-run.png)

# Run Completed

![Build Completed](https://github.com/herrry107/Jenkins/blob/main/images/project1/jenkins-newitem-run-complete.png)
