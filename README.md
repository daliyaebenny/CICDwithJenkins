# CICD with Jenkins
 Continuous Integration using Jenkins 
 ### Jenkins    
 Jenkins is a platform for creating a Continuous Integration/Continuous Delivery (CI/CD) environment. The system offers many different tools, languages, and automation tasks to aid in pipeline creation when developing and deploying programs.    

Although Jenkins requires scripting some automation steps, the program provides a fast and robust way to systematize the software development lifecycle.     
In Jenkins, builds represent single execution of a job with the current configuration. A build creates software from different sources defined in the project procedure. Depending on the project, the build mechanisms include:

Gathering dependencies.
Compiling or transforming code.
Archiving materials.
Testing.
Deploying to different environments.
Therefore, a build is one run of a defined project with various steps.
 
 ## User Story
 Make a simple Java application and create a continuous integration env. ensure the action "Build now" process every 15 minutes if anything changes in code (Git Repo).   
 ## Acceptance Criteria    
- Git Repository
- A piece of code in Repo in Java.
- Configure Git on Jenkins (Git-bash must be installed)
- A Master or slave instance to run it.
- A Jenkins job that create builds every 15 seconds
