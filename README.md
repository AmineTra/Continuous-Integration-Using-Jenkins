# Continuous-Integration-Using-Jenkins
Continuous Integration Using Jenkins, Nexus, Sonarqube &amp; Slack

![Architecture](https://github.com/AmineTra/Continuous-Integration-Using-Jenkins/assets/104666924/dff98a74-25a7-462d-a80e-e9ff563cc1d1)

The project's main goal was to create an automated pipeline that uses Jenkins, Nexus, SonarQube, and Slack. The pipeline takes input from every commit made by a developer and produces a well-tested artifact that can be deployed to servers for testing. If the artifact passes the testing phase, it is then promoted to production.

📍 I have created 3 EC2 instances for Jenkins, Nexus, and SonarQube with user-data scripts
📍 Created a GitHub repository and GitHub webhook for Jenkins to automatically trigger the build job whenever there is a code change
📍 Created Sonarqube webhook to send notifications to Jenkins once the quality gate reports are ready.
📍 Created Jenkinsfile for the pipeline, and configured Jenkins job to get this file from the project repository in #GitHub.
📍 Created hosted, group, and proxy repositories for Maven in Nexus Artifact Repository
📍 Configured Slack Integration with Jenkins for post-build notification after CI jobs.
