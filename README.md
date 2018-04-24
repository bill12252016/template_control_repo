# template_control_repo

Overview:

This is the control repo used as a starter for using ElasticDev.  The control repo serves to:

1) Infrastrucre:
   - Create the Infrastructure for the project

2) Build - 
   - Instead of adding or creating a pipeline for each microservice, this repo creates all of them (tyically, 10-20 microservices for a project) in parallel.
   
3) Deploy
   - Create Deploy(s) configuration for the project, from a single dev environment to serveral development and testing environments.

Setup:

1) Look at the availble branches for each starter project. And checkout the branch that best fits you.

 - git branch -r

2) Add your ssh keys to access the build and deploy container here:

   elasticdev/access/ssh_keys

3) Modify elasticdev/elasticdev.yml accordingly with:

   - reference the correct build repos
   - specify the correct environmental variables need for the app
