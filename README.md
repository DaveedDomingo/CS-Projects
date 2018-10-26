# CS-Projects
This repository will hold projects designed for Computer Science Students. 

## Table Of Contents
1. [Distributed Computing Projects](#distributed-computing-projects)
    * [RPC: The Bulletin Board Web Service](#rpc--the-bulletin-board-web-service)
    * [REST: A Restful Web Service](#rest--a-restful-web-service)
    * [Map-Reduce: Word Counting](#map-reduce--word-counting)
2. [Checking Out a Project](#checking-out-a-project)
3. [Project Maintenance](#project-maintenance)


## Distributed Computing Projects <a name="distributed-computing-projects"></a>
### RPC: The Bulletin Board Web Service <a name="rpc--the-bulletin-board-web-service"></a>
In this projects, Remote Procedure Calls using the modern framework of gRPC and Google Protocol Buffers.
### REST: A Restful Web Service <a name="rest--a-restful-web-service"></a> 
In this project, students will explore RESTful Design by implement a RESTful web service that also makes RESTful requests to external APIs.  
### Map-Reduce: Word Counting <a name="map-reduce--word-counting"></a>
In this projects, students will explore distributed computing programming by using the Map Reduce framework to implement their own word count. 


## Checking Out A Project <a name="checking-out-a-project"></a> 
Each project within this repository is on its own branch. Simply clone the project branch and
```
git clone -b <project directory> https://github.com/DaveedDomingo/CS-Projects.git <project directory>
```
For example cloning the Bullet Board Web Service Project can be done


## Project Maintenance <a name="project-maintenance"></a>
In order to add a project to respository:
1. Checkout the repository 
2. Create an orphan branch for the project ``` git checkout --orphan <branchname> ```
3. Ensure your working directory is clean ``` git rm --cached -r ```
4. Make a folder for your project and add project within the folder
5. Merge into master branch (Do not delete original branch)

In order to modify a project in this repository:
1. Checkout the project branch
2. Push changes to branch
3. Merge into master branch
