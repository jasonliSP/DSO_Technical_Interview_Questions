**Can you explain CI/CD?**

Generally look for them to say continuous integration/continuous deployment(or delivery). Look for them to explain this in their own words - should sound something along the lines of making incremental code changes and being able to frequently and reliably deliver application releases through automation.

*a. What are some common tools that are used in CI/CD*

CI/CD automation tools are super varied nowadays. I generally look for a couple of the more widely used tools:

1. Orchestration:\
Jenkins, github actions, gitlab, azure pipeline, aws codepipeline (codecommit, codebuild), etc

2. Artifact repository:\
Artifactory, Nexus, etc

3. Static Code analysis:\
SonarQube (or similar tool)

4. Compliance/security analysis:\
Whitesource (or similar tool)

5. Testing:\
Must be able to mention some sort of testing phase. If senior they should be able to mention the different types of testing. 

*b. Can you briefly go over what a CI/CID pipeline looks like*

They should at least be able to mention the process that looks somewhat like the below process:

Code push -> webhook -> kick off build process -> scans -> unit test -> deploy dev -> integration tests -> security tests -> deploy to higher environment -> integration -> security -> etc

*c. What is the most important part of CI/CD (open ended)*

Open ended, use your best judgement for this
