#Assignment 8

In this assignment, you'll start using Github Actions pipelines to conduct static code scanning as well as container image scanning. 

We'll be using a fork of a deliberately insecure webapp called PyGoat. PyGoat implements insecure code that maps to the OWASP Top 10 Web App Vulnerabilities. It is an open source project; I've forked it so as to better maintain dependencies for ease of use in this class. Some of the improvements I've made just to get the webapp functional may have broken some of the security vulnerabiliteis

In Part 1, you'll run the PyGoat web app locally via the container image. (If you wish, you can explore the web app's functionality and start pentesting it to discover the vulnerabilities, however that is not a requirement of the assignment.) You will then set up a GHA pipeline job to conduct a static code scan on the repository.
In Part 2, you'll scan the container image in the repository for vulnerabilities using Docker Scout actions.
In Part 3, you'll view the results of the Trivy and Docker Scout scans using Microsoft's SARIF reader extension in VSCode. You'll also start thinking about how to remediate the vulnerabilities in the code base.  

To submit the assignment, add a link to your PyGoat repository in D2L. It should include:
- A main.yml file that defines your GHA workflows
- Answers to Part 3 questions in the Assignment-8-Answers.md file.

Have fun!