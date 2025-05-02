# Jenkins
Jenkins is an open-source automation server used primarily for continuous integration (CI) and continuous delivery (CD) of software projects. It helps developers automate the process of building, testing, and deploying code, making software development faster, more reliable, and more consistent.

![Alt-text](https://github.com/herrry107/Jenkins/blob/main/images/jenkins.png)

- Jenkins is an open source project written in Java that runs on windows, mac and other unix like operation systems. It is free community supported and might be your first choice tool for CI.
- Jenkins automate the entire software development life cycle.
- Jenkins was origninally developed by sun micro system in 2004 under the name hudson.
- The project was later named jenkins when oracle bought microsystem.
- It can run on any major platform without any compatibility issues.
- Whenever developers write codes, we integrate all that code of all developers at that point of time and we build, test and Deliver/Deploy to the client. This process is called CI/CD.
- Because of CI, Nows bugs will be reported fast and get rectified fast so the entire software development happens fast.

# Workflow of Jenkins
- We can attach git, maven, selenium and artifactory plugins to Jenkins.
- Once developer puts code in github, Jenkins pulls that code and send to maven for build.
- Once build is done, jenkins pull that code and send to selenium for testing.
- Once testing is done, then jenkins will pull that code and send to artifactory as per requirement and so on.
- We can also deploy with jenkins.

# Advantages of Jenkins
- It has lots of plugin available.
- You can write your own plugin.
- You can use community plugin.
- Jenkins is not just a tool. It is a framework, you can do whatever, you want all you need is plugin.
- We can attach slaves(nodes) to Jenkins master. It instruct others(slaves) to do job. If slaves are not available, Jenkins itself does the job.
- Jenkins also behave as crone server replacement. means can do scheduled task.
- It can create labels.

# Read All Jenkins Docs by these sequence
[1) Insallation Step](https://github.com/herrry107/Jenkins/tree/main/installation-step)

[2) Plugin](https://github.com/herrry107/Jenkins/tree/main/plugin)
  
[3) Project Create](https://github.com/herrry107/Jenkins/tree/main/project-create)

[4) User Mangement](https://github.com/herrry107/Jenkins/tree/main/User-Management)

[5) Master-Slave] (https://github.com/herrry107/Jenkins/tree/main/Master-Slave)
