# Go Out Safe

This is the main repository of GoOutSafe application, self
project of *Advanced Software Engineering* course,
University of Pisa.
 
## Team info

- The *squad id* is **4**
- The *team leader* is Leonardo Calamita

#### Members

|Name and Surname  | Email                         |
|------------------|-------------------------------|
|Federico Silvestri|f.silvestri10@studenti.unipi.it|
|Leonardo Calamita |l.calamita@studenti.unipi.it   |
|Chiara Boni       |c.boni5@studenti.unipi.it      |
|Nunzio Lopardo    |n.lopardo@studenti.unipi.it    |
|Paolo Murgia      |p.murgia1@studenti.unipi.it    |

## Instructions

### Clone the repository

To clone the repository you have to specify the recursive parameter,
in this way:

`git clone --recursive git@github.com:federicosilvestri/gos-main.git`

All the submodules will be fetched from GitHub and they will be
placed inside the project root.

### Add a submodule

If you want to add a microservice (hence a submodule), you
have to run the command:

`git submodule add -b <branchName> <repoURL>`

### Pull the updates from all repositories

If a developer has pushed to <branchName> branch and you want
to pull the updates, you have to run the following command:

`git submodule update --remote`

#### Documentation

If you are not familiar with git submodules or you have some
doubts about it, you can check the git-scm documentation
[here](https://git-scm.com/book/en/v2/Git-Tools-Submodules). 

## Build and run

Application is built with docker-compose. To build the environment
you have to run

`docker-compose build`

To startup application you can issue the following command:

`docker-compose run`

#### Application Environment

The default application environment for this application is **production**. 


