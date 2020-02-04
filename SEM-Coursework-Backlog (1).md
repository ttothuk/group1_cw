SEM Coursework Backlog

Team: Group 1.

David Ciocoiu 40323308  
Tibor Toth 40400971  
Mihail Benev 40342604  
Ani Georgieva 40402729

Product Owner: Ani

Scrum Master: David

Team members: Everyone

Product Backlog:

1.  Set up a development environment in IntelliJ

    -   Create a new project with Maven as a project type

    -   Enter name, group details and version

2.  Set up version control for the project

    -   Initialize Git as a version control in IntelliJ

    -   Add a .gitignore file and list the Java specific files and the files in
        .idea to be ignored

    -   Add a README file written in Markdown

3.  Set up GitHub

    -   Create a repository

    -   Give IntelliJ the location of the repository

    -   Pull the GitHub version to add the license file on our PC

    -   Complete the first commit to GitHub

4.  Testing with a simple app

    -   Create a Java app with some code

    -   Build the project and run it

5.  Set up Docker

    -   Install Docker and check if it works in the terminal

    -   Pull Nginx (lightweight web server) and run the Nginx image to start it
        as a container

    -   Open a port, mapping the machine’s port 8080 to the port 80 of the web
        server

    -   Test the container in the web browser

    -   Stop and remove the containers

    -   Install Docker in IntelliJ and connect to it

    -   Create a Dockerfile in IntelliJ and test it

    -   Commit and push to GitHub

6.  Import the project in IntelliJ

    -   Pull the project from GitHub

    -   Create a new project from the source code

7.  Set up Travis CI

    -   Log in with GitHub and activate Travis for the sem repository

    -   Add a Travis build file and push to GitHub

    -   Add a Travis Badge to the README file

    -   Push and check in we see the badge in GitHub

    -   Add a license and release badges

8.  Set up Travis to work with Docker

    -   Update the .travis.yml file to build the Docker image and run an
        instance of it, push

9.  Set up Gitflow Workflow

    -   Create a Develop branch and push it

10. Add a develop build status to GitHub

    -   Add a Travis develop build badge to the README file

11. Set up database support via MongoDB

    -   Start MongoDB server via Docker

    -   Create a Feature branch and push it to GitHub

    -   Add dependencies to the pom.xml file

    -   Update the Java file to test if we can reach MongoDB

    -   If everything works fine, push to GitHub

12. Link containers

    -   Create JAR for the project with the external libraries

    -   Add a network bridge in Docker

    -   Update the Java app, Dockerfile and the MongoDB instance

    -   Update the Travis build file, adding a few more docker commands

13. Merge Feature

    -   Merge the develop branch to the feature branch

    -   Switch back to develop branch and checkout

    -   Merge the feature branch in the current branch

14. Create a Release

    -   Create a release branch

    -   Update the version of the release in the pom.xml and the Dockerfile

    -   Rebuild project and package the project through Maven

    -   Build the docker image and run it

    -   Merge the release back to master

    -   Go to the GitHub page of the sem project and create a new release

    -   Merge the release back to develop

| **Done**                          | **In progress**                     | **To do**                 |
|-----------------------------------|-------------------------------------|---------------------------|
| Set up IntelliJ                   | MongoDB Research                    | Lab 3                     |
| Set up a Version Control - Git    | Reporting on population information | Lab 4                     |
| Set up GitHub                     |                                     | Lab 5                     |
| Set up Docker                     |                                     | Prepare for code review 2 |
| Set up Travis CI                  |                                     | Coding the app in Java    |
| Set up Travis to work with Docker |                                     |                           |
| Set up Gitflow workflow           |                                     |                           |
| Set up MongoDB                    |                                     |                           |
| Link Containers                   |                                     |                           |

-   Develop branch

-   Feature branch

-   Release Branch
