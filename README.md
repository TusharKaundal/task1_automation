
# About the Project:

This Project is all about Integrating Docker+GitHub +Jenkins to provide Automation to testing and production environment.

## Solution:

* JOB 1 : If Developer push to master branch then Jenkins will fetch from master and deploy on master-docker environment.

* JOB 2 : If Developer push to dev branch then Jenkins will fetch from dev and deploy on dev-docker environment.
both dev-docker and master-docker environment are on different docker containers.

* JOB 3 : Manually the QA team will check (test) for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger job 2.

## For more about Project
[Click Here](https://medium.com/@kaundaltushar/integrating-docker-github-jenkins-to-provide-automation-to-testing-and-production-environment-2782ad89365a?source=friends_link&sk=20fec402608f31f38fc993b19e9723c0)
