# DevOps Questions & Exercises

:information_source: &nbsp;This repo contains questions and exercises on various technical topics, sometimes related to DevOps and SRE :)

:bar_chart: &nbsp;There are currently **1139** questions

:busts_in_silhouette: &nbsp;[Join](https://www.facebook.com/groups/538897960007080) our [Facebook group](https://www.facebook.com/groups/538897960007080) or follow us on [Twitter](https://twitter.com/devopsbit) for additional daily exercises, articles and more resources on DevOps

:warning: &nbsp;You can use these for preparing for an interview but most of the questions and exercises don't represent an actual interview. Please read [Q&A](common-qa.md) for more details

:thought_balloon: &nbsp;If you wonder "How to prepare for a DevOps interview?", you might want to read some of my suggestions [here](prepare_for_interview.md)

:pencil: &nbsp;You can add more questions and exercises by submitting pull requests :) You can read more about it [here](CONTRIBUTING.md)

:books: &nbsp;To learn more about DevOps and SRE, check the resources in [devops-resources](https://github.com/bregman-arie/devops-resources) repository

****

<!-- ALL-TOPICS-LIST:START -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<center>
<table>
  <tr>
    <td align="center"><a href="#devops"><img src="images/devops.png" width="70px;" height="75px;" alt="DevOps" /><br /><b>DevOps</b></a><br /><sub><a href="#devops-beginner">Beginner :baby:</a></sub><br><sub><a href="#devops-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#jenkins"><img src="images/jenkins.png" width="85px;" height="85px;" alt="Jenkins"/><br /><b>Jenkins</b></a><br /><sub><a href="#jenkins-beginner">Beginner :baby:</a></sub><br><sub><a href="#jenkins-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#git"><img src="images/git.png" width="80px;" height="75px;" alt="Git"/><br /><b>Git</b></a><br /><sub><a href="#git-beginner">Beginner :baby:</a></sub><br><sub><a href="#git-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#ansible"><img src="images/ansible.png" width="75px;" height="75px;" alt="Ansible"/><br /><b>Ansible</b></a><br /><sub><a href="#ansible-beginner">Beginner :baby:</a></sub><br><sub><a href="#ansible-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#Network"><img src="images/network.png" width="80x;" height="75px;" alt="Network"/><br /><b>Network</b></a><br /><sub><a href="#network-beginner">Beginner :baby:</a></sub><br><sub><a href="#network-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#linux"><img src="images/linux.png" width="75x;" height="75px;" alt="Linux"/><br /><b>Linux</b></a><br /><sub><a href="#linux-beginner">Beginner :baby:</a></sub><br><sub><a href="#linux-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#terraform"><img src="images/terraform.png" width="70px;" height="75px;" alt="Terraform"/><br /><b>Terraform</b></a><br /><sub><a href="#terraform-beginner">Beginner :baby:</a></sub><br><sub><a href="#terraform-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#docker"><img src="images/docker.png" width="70px;" height="75px;" alt="Docker"/><br /><b>Docker</b></a><br /><sub><a href="#docker-beginner">Beginner :baby:</a></sub><br><sub><a href="#docker-advanced">Advanced :star:</a></sub></td>
  </tr>
  <tr>
    <td align="center"><a href="#coding"><img src="images/coding.png" width="75px;" height="75px;" alt="coding"/><br /><b>Coding</b></a><br /><sub><a href="#coding-beginner">Beginner :baby:</a></sub><br><sub><a href="#coding-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#python"><img src="images/python.png" width="80px;" height="75px;" alt="Python"/><br /><b>Python</b></a><br /><sub><a href="#python-beginner">Beginner :baby:</a></sub><br><sub><a href="#python-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#go"><img src="images/Go.png" width="75px;" height="75px;" alt="go"/><br /><b>Go</b></a><br /><sub><a href="#go-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#shell-scripting"><img src="images/bash.png" width="70px;" height="75px;" alt="Bash"/><br /><b>Shell Scripting</b></a><br /><sub><a href="#shell-scripting-beginner">Beginner :baby:</a></sub><br><sub><a href="#shell-scripting-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#kubernetes"><img src="images/kubernetes.png" width="75px;" height="75px;" alt="kubernetes"/><br /><b>Kubernetes</b></a></td>
    <td align="center"><a href="#prometheus"><img src="images/prometheus.png" width="75px;" height="75px;" alt="Prometheus"/><br /><b>Prometheus</b></a><br /><sub><a href="#prometheus-beginner">Beginner :baby:</a></sub><br><sub><a href="#prometheus-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#mongo"><img src="images/mongo.png" width="75px;" height="75px;" alt="Mongo"/><br /><b>Mongo</b></a><br /><sub><a href="#mongo-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#sql"><img src="images/sql.png" width="75px;" height="75px;" alt="sql"/><br /><b>SQL</b></a><br /><sub><a href="#sql-beginner">Beginner :baby:</a></sub><br><sub><a href="#sql-advanced">Advanced :star:</a></sub></td>
  </tr>
  <tr>
    <td align="center"><a href="#cloud"><img src="images/cloud.png" width="110px;" height="75px;" alt="Cloud"/><br /><b>Cloud</b></a><br /><sub><a href="#cloud-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#aws"><img src="images/aws.jpg" width="75px;" height="75px;" alt="aws"/><br /><b>AWS</b></a><br /><sub><a href="#aws-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#azure"><img src="images/azure.png" width="75px;" height="75px;" alt="azure"/><br /><b>Azure</b></a><br /><sub><a href="#azure-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#gcp"><img src="images/googlecloud.png" width="80px;" height="75px;" alt="Google Cloud Platform"/><br /><b>Google Cloud Platform</b></a><br /><sub><a href="#gcp-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#openstack"><img src="images/openstack.png" width="75px;" height="75px;" alt="openstack"/><br /><b>OpenStack</b></a><br /><sub><a href="#openstack-beginner">Beginner :baby:</a></sub><br><sub><a href="#openstack-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#security"><img src="images/security.png" width="75px;" height="75px;" alt="security"/><br /><b>Security</b></a><br /><sub><a href="#security-beginner">Beginner :baby:</a></sub><br><sub><a href="#security-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#puppet"><img src="images/puppet.png" width="75px;" height="75px;" alt="puppet"/><br /><b>Puppet</b></a><br /><sub><a href="#puppet-beginner">Beginner :baby:</a></sub><br><sub><a href="#puppet-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#openshift"><img src="images/openshift.png" width="75px;" height="75px;" alt="OpenShift"/><br /><b>OpenShift</b></a><br /><sub><a href="#openshift-beginner">Beginner :baby:</a></sub><br><sub></td>
  </tr>
  <tr>
    <td align="center"><a href="#monitoring"><img src="images/monitoring.png" width="75px;" height="75px;" alt="Monitoring"/><br /><b>Monitoring</b></a><br /><sub><a href="#monitoring-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#elastic"><img src="images/elastic.png" width="110px;" height="75px;" alt="Elastic"/><br /><b>Elastic</b></a></td>
    <td align="center"><a href="#virtualization"><img src="images/virtualization.png" width="75px;" height="75px;" alt="Virtualization"/><br /><b>Virtualization</b></a><br /><sub><a href="#virtualization-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#dns"><img src="images/dns.png" width="75px;" height="75px;" alt="DNS"/><br /><b>DNS</b></a><br /><sub><a href="#dns-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#operating-system"><img src="images/os.png" width="75px;" height="75px;" alt="Operating System"/><br /><b>Operating System</b></a><br /><sub><a href="#operating-system-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#distributed"><img src="images/distributed.png" width="110px;" height="75px;" alt="Distributed"/><br /><b>Distributed</b></a></td>
    <td align="center"><a href="#general"><img src="images/general.png" width="110px;" height="75px;" alt="General"/><br /><b>General</b></a><br /><sub><a href="#general-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#HR"><img src="images/HR.png" width="110px;" height="75px;" alt="HR"/><br /><b>HR</b></a></td>
  </tr>
  <tr>
    <td align="center"><a href="#testing"><img src="images/testing.png" width="75px;" height="75px;" alt="Testing"/><br /><b>Testing</b></a></td>
    <td align="center"><a href="#databases"><img src="images/databases.png" width="75px;" height="75px;" alt="Databases"/><br /><b>Databases</b></a></td>
    <td align="center"><a href="#regex"><img src="images/regex.png" width="75ph;" height="75px;" alt="RegEx"/><br /><b>Regex</b></a><br /><sub><a href="#regex-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#design"><img src="images/design.png" width="110px;" height="75px;" alt="Design"/><br /><b>Design</b></a></td>
    <td align="center"><a href="#hardware"><img src="images/hardware.png" width="110px;" height="75px;" alt="Hardware"/><br /><b>Hardware</b></a></td>
    <td align="center"><a href="#big-data"><img src="images/big-data.png" width="110px;" height="75px;" alt="Big Data"/><br /><b>Big Data</b></a></td>
    <td align="center"><a href="#questions-you-ask"><img src="images/you.png" width="110px;" height="75px;" alt="you"/><br /><b>Questions you ask</b></a></td>
    <td align="center"><a href="#exercises"><img src="images/exercises.png" width="110px;" height="75px;" alt="Exercises"/><br /><b>Exercises</b></a></td>
  </tr>
  <tr>
    <td align="center"><a href="#certificates"><img src="images/certificates.png" width="75px;" height="75px;" alt="Certificates"/><br /><b>Certificates</b></a></td>
  </tr>
</table>
</center>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-TOPICS-LIST:END -->

## DevOps

<a name="devops-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is DevOps?</summary><br><b>

Amazon:

"DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market."

Microsoft:

"DevOps is the union of people, process, and products to enable continuous delivery of value to our end users. The contraction of “Dev” and “Ops” refers to replacing siloed Development and Operations to create multidisciplinary teams that now work together with shared and efficient practices and tools. Essential DevOps practices include agile planning, continuous integration, continuous delivery, and monitoring of applications."

Red Hat:

"DevOps describes approaches to speeding up the processes by which an idea (like a new software feature, a request for enhancement, or a bug fix) goes from development to deployment in a production environment where it can provide value to the user. These approaches require that development teams and operations teams communicate frequently and approach their work with empathy for their teammates. Scalability and flexible provisioning are also necessary. With DevOps, those that need power the most, get it—through self service and automation. Developers, usually coding in a standard development environment, work closely with IT operations to speed software builds, tests, and releases—without sacrificing reliability."

</b></details>

<details>
<summary>What are the benefits of DevOps? What it can help us to achieve?</summary><br><b>

You should mention some or all of the following:

  * Collaboration
  * Improved delivery
  * Security
  * Speed
  * Scale
  * Reliability

Make sure to elaborate :)
</b></details>

<details>
<summary>What are the anti-patterns of DevOps?</summary><br><b>

* Not allowing to push in production on Friday :)
* One specific person is in charge of different tasks. For example there is only one person who is allowed to merge the code of everyone else
* Treating production differently from development environment. For example, not implementing security in development environment
</b></details>

<details>
<summary>What is Continuous Integration?</summary><br><b>

A development practice where developers integrate code into a shared repository frequently. It can range from a couple of changes every day or a week to a couple of changes in one hour in larger scales.

Each piece of code (change/patch) is verified, to make the change is safe to merge. Today, it's a common practice to test the change using an automated build that makes sure the code can integrated. It can be one build which runs several tests in different levels (unit, functional, etc.) or several separate builds that all or some has to pass in order for the change to be merged into the repository.
</b></details>

<details>
<summary>What is Continuous Deployment?</summary><br><b>
</b></details>

<details>
<summary>What is Continuous Delivery?</summary><br><b>
</b></details>

<details>
<summary>What CI/CD best practices are you familiar with? Or what do you consider as CI/CD best practice?</summary><br><b>
</b></details>

<details>
<summary>What systems and/or tools are you using for the following?:

  * CI/CD
  * Provisioning infrastructure
  * Configuration Management
  * Monitoring & alerting
  * Logging
  * Code review
  * Code coverage
  * Tests</summary><br><b>
  * CI/CD - Jenkins, Circle CI, Travis
  * Provisioning infrastructure - Terraform, CloudFormation
  * Configuration Management - Ansible, Puppet, Chef
  * Monitoring & alerting - Prometheus, Nagios
  * Logging - Logstash, Graylog, Fluentd
  * Code review - Gerrit, Review Board
  * Code coverage - Cobertura, Clover, JaCoCo
  * Tests - Robot, Serenity, Gauge
</b></details>

<details>
<summary>What are you taking into consideration when choosing a tool/technology?</summary><br><b>

In your answer you can mention one or more of the following:
  * mature vs. cutting edge
  * community size
  * architecture aspects - agent vs. agentless, master vs. masterless, etc.
</b></details>

<details>
<summary>Explain mutable vs. immutable infrastructure</summary><br><b>

In mutable infrastructure paradigm, changes are applied on top of the existing infrastructure and over time
the infrastructure builds up a history of changes. Ansible, Puppet and Chef are examples of tools which
follow mutable infrastructure paradigm.

In immutable infrastructure paradigm, every change is actually a new infrastructure. So a change
to a server will result in a new server instead of updating it. Terraform is an example of technology
which follows the immutable infrastructure paradigm.
</b></details>

<details>
<summary>What ways are you familiar with to deliver a software? What are the advantages and disadvantages of each method?</summary><br><b>

  * Archive - collect all your app files into one archive (e.g. tar) and deliver it to the user.
  * Package - depends on the OS, you can use your OS package format (e.g. in RHEL/Fefodra it's RPM) to deliver your software with a way to install, uninstall and update it using the standard packager commands
  * Images - Either VM or container images where your package is included with everything it needs in order to run successfully.
</b></details>

<details>
<summary>What is caching? How does it works? Why is it important?</summary><br><b>
</b></details>

<details>
<summary>Explain stateless vs. stateful</summary><br><b>

Stateless applications don't store any data in the host which makes it ideal for horizontal scaling and microservices.
Stateful applications depend on the storage to save state and data, typically databases are stateful applications.
</b></details>

<details>
<summary>Describe the workflow of setting up some type of web server (Apache, IIS, Tomcat, ...)</summary><br><b>
</b></details>

<details>
<summary>How a web server works?</summary><br><b>
</b></details>

<details>
<summary>Explain "Open Source"</summary><br><b>
</b></details>

<details>
<summary>Describe me the architecture of service/app/project/... you designed and/or implemented</summary><br><b>
</b></details>

<details>
<summary>What types of tests are you familiar with?</summary><br><b>

Styling, unit, functional, API, integration, smoke, scenario, ...

You should be able to explain those that you mention.
</b></details>

<details>
<summary>You need to install periodically the same package on different operating systems (Ubuntu, RHEL, ...). How would you do it?</summary><br><b>

It can be as simple as one Ansible (or other CM tool) task that runs periodically with Cron. In more advanced cases, perhaps a CI system.
</b></details>

<details>
<summary>What is Reliability? How does it fit DevOps?</summary><br><b>

Reliability, when used in DevOps context, is the ability of a system to recover from infrastructure failure or disruption. Part of it is also being able to scale based on your organization or team demands.
</b></details>

<details>
<summary>Compare SRE to DevOps</summary><br><b>
</b></details>

<details>
<summary>What SRE team is responsible for?</summary><br><b>

One can argue whether it's per company definition or a global one but at least according to a large companies, like Google for example, the SRE team is responsible for availability, latency, performance, efficiency, change management, monitoring, emergency response, and capacity planning of their services
</b></details>

<details>
<summary>What is an error budget?</summary><br><b>
</b></details>

<details>
<summary>What are MTTF (mean time to failure) and MTTR (mean time to repair)? What these metrics help us to evaluate?</summary><br><b>
</b></details>

<details>
<summary>What is a post-mortem meeting?</summary><br><b>
</b></details>

<details>
<summary>What is "infrastructure as code"? What implementation of IAC are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>How do you manage build artifacts?</summary><br><b>
</b></details>

<details>
<summary>What Continuous Integration solution are you using/prefer and why?</summary><br><b>
</b></details>

<details>
<summary>What deployment strategies are you familiar with or have used?</summary><br><b>
</b></details>

<details>
<summary>You joined a team where everyone developing one project and the practice is to run tests locally on their workstation and push it to the repository if the tests passed. What is the problem with the process as it is now and how to improve it?</summary><br><b>
</b></details>

<details>
<summary>Explain test-driven development (TDD)</summary><br><b>
</b></details>

<details>
<summary>Explain agile software development</summary><br><b>
</b></details>

<details>
<summary>Is it right to say implementing or practicing DevOps leads to more secure software?</summary><br><b>
</b></details>

<a name="devops-advanced"></a>
#### :star: Advanced

<details>
<summary>Tell me how you perform plan capacity for your CI/CD resources (e.g. servers, storage, etc.)</summary><br><b>
</b></details>

<details>
<summary>How would you structure/implement CD for an application which depends on several other applications?</summary><br><b>
</b></details>

<details>
<summary>How do you measure your CI/CD quality? Are there any metrics or KPIs you are using for measuring the quality?</summary><br><b>
</b></details>

<details>
<summary>What is a configuration drift? What problems is it causing?</summary><br><b>

Configuration drift happens when in an environment of servers with the exact same configuration and software, a certain server
or servers are being applied with updates or configuration which other servers don't get and over time these servers become
slightly different than all others.

This situation might lead to bugs which hard to identify and reproduce.
</b></details>

<details>
<summary>How to deal with a configuration drift?</summary><br><b>
</b></details>

<details>
<summary>Do you have experience with testing cross-projects changes? (aka cross-dependency)</summary><br><b>

Note: cross-dependency is when you have two or more changes to separate projects and you would like to test them in mutual build instead of testing each change separately.
</b></details>

<details>
<summary>Have you contributed to an open source project? Tell me about this experience</summary><br><b>
</b></details>

<details>
<summary>Are you familiar with "The Cathedral and the Bazaar models"? Explain each of the models</summary><br><b>

* Cathedral - source code released when software is released
* Bazaar - source code is always available publicly (e.g. Linux Kernel)
</b></details>

## Jenkins

<a name="jenkins-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Jenkins? What have you used it for?</summary><br><b>

Jenkins is an open source automation tool written in Java with plugins built for Continuous Integration purpose. Jenkins is used to build and test your software projects continuously making it easier for developers to integrate changes to the project, and making it easier for users to obtain a fresh build. It also allows you to continuously deliver your software by integrating with a large number of testing and deployment technologies.

Jenkins integrates development life-cycle processes of all kinds, including build, document, test, package, stage, deploy, static analysis and much more.

</b></details>

<details>
<summary>What are the advantages of Jenkins over its competitors? Can you compare it to one of the following systems?

  * Travis
  * Bamboo
  * Teamcity
  * CircleCI</summary><br><b>
</b></details>

<details>
<summary>What are the limitations or disadvantages of Jenkins?</summary><br><b>
</b></details>

<details>
<summary>Explain the following:

  * Job
  * Build
  * Plugin
  * Slave
  * Executor</summary><br><b>
</b></details>

<details>
<summary>What plugins have you used in Jenkins?</summary><br><b>
</b></details>

<details>
<summary>Explain CI/CD and how you implemented it in Jenkins</summary><br><b>
</b></details>

<details>
<summary>What type of jobs are there? Which types have you used?</summary><br><b>
</b></details>

<details>
<summary>How did you report build results to users? What ways are you familiar with for reporting results?</summary><br><b>
</b></details>

<details>
<summary>You need to run unit tests every time a change submitted to a given project. Describe in details how your pipeline would look like and what will be executed in each stage</summary><br><b>
</b></details>

<details>
<summary>How to secure Jenkins?</summary><br><b>
</b></details>

<details>
<summary>Can you describe some of Jenkins best practices?</summary><br><b>
</b></details>

<details>
<summary>Describe how do you add new slaves to Jenkins</summary><br><b>

You can describe the UI way to add new slaves but better to explain how to do in a way that scales like a script or using dynamic source for slaves like one of the existing clouds.
</b></details>

<a name="jenkins-advanced"></a>
#### :star: Advanced

<details>
<summary>How to acquire multiple slaves for one specific build?</summary><br><b>
</b></details>

<details>
<summary>There are four teams in your organization. How to prioritize the builds of each team? So the jobs of team x will always run before team y for example</summary><br><b>
</b></details>

<details>
<summary>If you are managing a dozen of jobs, you can probably use the Jenkins UI. How do you manage the creation and deletion of hundreds of jobs every week/month?</summary><br><b>
</b></details>

<details>
<summary>What are some of Jenkins limitations?</summary><br><b>

  * Testing cross-dependencies (changes from multiple projects together)
  * Starting builds from any stage (although cloudbees implemented something called checkpoints)
</b></details>

<details>
<summary>How would you implement an option of a starting a build from a certain stage and not from the beginning?</summary><br><b>
</b></details>

#### Jenkins Dev

<details>
<summary>Do you have experience with developing a Jenkins plugin? Can you describe this experience?</summary><br><b>
</b></details>

<details>
<summary>Have you written Jenkins scripts? If yes, what for and how they work?</summary><br><b>
</b></details>

#### Jenkins Integration

<details>
<summary>How would you collect logs from Jenkins builds (not master) and display them to user via Kibana? Describe the process, components, etc.<br>
<img src="images/jenkins/jenkins-to-kibana.png" width="621x;" height="171px;"/>
</summary><br><b>
</b></details>

## Cloud 

<a name="cloud-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Cloud Computing? What is a Cloud Provider?</summary><br><b>
</b></details>

<details>
<summary>What are the advantages of cloud computing? Mention at least 3 advantages</summary><br><b>

* Pay as you go (or consumption-based payment) - you are paying only for what you are using. No upfront payments and payment stops when resources are no longer used.
* Scalable - resources are scaled down or up based on demand
</b></details>

<details>
<summary>What types of Cloud Computing services are there?</summary><br><b>

IAAS
PAAS
SAAS
</b></details>

<details>
<summary>Explain each of the following and give an example:

  * IAAS
  * PAAS
  * SAAS</summary><br><b>
</b></details>

<details>
<summary>What types of clouds (or cloud deployments) are there?</summary><br><b>

  * Public
  * Hybrid
  * Private
</b></details>

<details>
<summary>Explain each of the following Cloud Computing Deployments:

  * Public
  * Hybrid
  * Private</summary><br><b>

  * Hybrid - combination of public and private clouds
</b></details>

<details>
<summary>What are the differences between Cloud Providers and On-Premise solution?</summary><br><b>

In cloud providers, someone else owns and manages the hardware, hire the relevant infrastructure teams and pays for real-estate (for both hardware and people). You can focus on your business.

In On-Premise solution, it's quite the opposite. You need to take care of hardware, infrastructure teams and pay for everything which can be quite expensive. On the other hand it's tailored to your needs.
</b></details>

<details>
<summary>What is Serverless Computing?</summary><br><b>

The main idea behind serverless computing is that you don't need to manage the creation and configuration of server. All you need to focus on is splitting your app into multiple functions which will be triggered by some actions.

It's important to note that:

* Serverless Computing is still using servers. So saying there are no servers in serverless computing is completely wrong
* Serverless Computing allows you to have a different paying model. You basically pay only when your functions are running and not when the VM or containers are running as in other payment models
</b></details>

## AWS

<a name="aws-beginner"></a>
#### :baby: Beginner

#### Global Infrastructure

<details>
<summary>Explain the following

  * Availability zone
  * Region
  * Edge location</summary><br><b>
AWS regions are data centers hosted across different geographical locations worldwide, each region is completely independent of one another.<br>

Within each region, there are multiple isolated locations known as Availability Zones. Multiple availability zones ensure high availability in case one of them goes down.<br>

Edge locations are basically content delivery network which caches data and insures lower latency and faster delivery to the users in any location. They are located in major cities in the world.
</b></details>

#### AWS IAM

<details>
<summary>What is IAM? What are some of its features?</summary><br><b>

Full explanation is [here](https://aws.amazon.com/iam)
In short: it's used for managing users, groups, access policies & roles
</b></details>

<details>
<summary>True or False? IAM configuration is defined globally and not per region</summary><br><b>

True
</b></details>

<details>
<summary>Given an example of IAM best practices?</summary><br><b>

* Set up MFA
* Delete root account access keys
* Create IAM users instead of using root for daily management
</b></details>

<details>
<summary>What are Roles?</summary><br><b>

A way for allowing a service of AWS to use another service of AWS. You assign roles to AWS resources.
For example, you can make use of a role which allows EC2 service to acesses s3 buckets (read and write).
</b></details>

<details>
<summary>What are Policies?</summary><br><b>

Policies documents used to give permissions as to what a user, group or role are able to do. Their format is JSON.
</b></details>

<details>
<summary>A user is unable to access an s3 bucket. What might be the problem?</summary><br><b>

There can be several reasons for that. One of them is lack of policy. To solve that, the admin has to attach the user with a policy what allows him to access the s3 bucket.
</b></details>

<details>
<summary>What should you use to:

  * Grant access between two services/resources?
  * Grant user access to resources/services?</summary><br><b>

  * Role
  * Policy
</b></details>

<details>
<summary>What permissions does a new user have?</summary><br><b>

Only a login access.
</b></details>

#### AWS Compute

<details>
<summary>What is EC2?</summary><br><b>

"a web service that provides secure, resizable compute capacity in the cloud".
Read more [here](https://aws.amazon.com/ec2)
</b></details>

<details>
<summary>What is AMI?</summary><br><b>

Amazon Machine Images is "An Amazon Machine Image (AMI) provides the information required to launch an instance".
Read more [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html)
</b></details>

<details>
<summary>What are the different source for AMIs?</summary><br><b>

* Personal AMIs - AMIs you create
* AWS Marketplace for AMIs - Paid AMIs usually with bundled with licensed software
* Community AMIs - Free
</b></details>

<details>
<summary>What is instance type?</summary><br><b>

"the instance type that you specify determines the hardware of the host computer used for your instance"
Read more about instance types [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
</b></details>

<details>
<summary>True or False? The following are instance types available for a user in AWS:

  * Compute optimizied
  * Network optimizied
  * Web optimized</summary><br><b>

False. From the above list only compute optimized is available.
</b></details>

<details>
<summary>What is EBS?</summary><br><b>

"provides block level storage volumes for use with EC2 instances. EBS volumes behave like raw, unformatted block devices."
More on EBS [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
</b></details>

<details>
<summary>What EC2 pricing models are there?</summary><br><b>

On Demand - pay a fixed rate by the hour/second with no commitment. You can provision and terminate it at any given time.
Reserved - you get capacity reservation, basically purchase an instance for a fixed time of period. The longer, the cheaper.
Spot - Enables you to bid whatever price you want for instances or pay the spot price.
Dedicated Hosts - physical EC2 server dedicated for your use.
</b></details>

<details>
<summary>What are Security Groups?</summary><br><b>

"A security group acts as a virtual firewall that controls the traffic for one or more instances"
More on this subject [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html)
</b></details>

<details>
<summary>How to migrate an instance to another availability zone?</summary><br><b>
</b></details>

#### AWS Serverless Compute

<details>
<summary>Explain what is AWS Lambda</summary><br><b>

AWS definition: "AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume."

Read more on it [here](https://aws.amazon.com/lambda)
</b></details>

<details>
<summary>True or False? In AWS Lambda, you are charged as long as a function exists, regardless of whether it's running or not</summary><br><b>

False. Charges are being made when the code is executed.
</b></details>

<details>
<summary>Which of the following set of languages Lambda supports?

  * R, Swift, Rust, Kotlin
  * Python, Ruby, Go 
  * Python, Ruby, PHP</summary><br><b>

  * Python, Ruby, Go 
</b></details>

#### AWS Storage
 
<details>
<summary>Explain what is AWS S3?</summary><br><b>

S3 stands for 3 S, Simple Storage Service.
S3 is a object storage service which is fast, scalable and durable. S3 enables customers to upload, download or store any file or object that is up to 5 TB in size.

More on S3 [here](https://aws.amazon.com/s3)
</b></details>

<details>
<summary>What is a bucket?</summary><br><b>

An S3 bucket is a resource which is similar to folders in a file system and allows storing objects, which consist of data.
</b></details>

<details>
<summary>True or False? A bucket name must be globally unique</summary><br><b>

True
</b></details>

<details>
<summary>Explain folders and objects in regards to buckets</summary><br><b>

* Folder - any sub folder in an s3 bucket
* Object - The files which are stored in a bucket
</b></details>

<details>
<summary>Explain the following:

  * Object Lifecycles
  * Object Sharing
  * Object Versioning</summary><br><b>

  * Object Lifecycles - Transfer objects between storage classes based on defined rules of time periods
  * Object Sharing - Share objects via a URL link
  * Object Versioning - Manage multiple versions of an object
</b></details>

<details>
<summary>Explain Object Durability and Object Availability</summary><br><b>

Object Durability: The percent over a one-year time period that a file will not be lost
Object Availability: The percent over a one-year time period that a file will be accessible
</b></details>

<details>
<summary>What is a storage class? What storage classes are there?</summary><br><b>

Each object has a storage class assigned to, affecting its availability and durability. This also has effect on costs.
Storage classes offered today:
  * Standard:
    * Used for general, all-purpose storage (mostly storage that needs to be accessed frequently)
    * The most expensive storage class
    * 11x9% durability
    * 2x9% availability
    * Default storage class

  * Standard-IA (Infrequent Access)
    * Long lived, infrequently accessed data but must be available the moment it's being accessed
    * 11x9% durability
    * 99.90% availability

  * One Zone-IA (Infrequent Access):
    * Long-lived, infrequently accessed, non-critical data
    * Less expensive than Standard and Standard-IA storage classes
    * 2x9% durability
    * 99.50% availability
 
  * Intelligent-Tiering:
    * Long-lived data with changing or unknown access patterns. Basically, In this class the data automatically moves to the class most suitable for you based on usage patterns
    * Price depends on the used class
    * 11x9% durability
    * 99.90% availability

  * Glacier: Archive data with retrieval time ranging from minutes to hours
  * Glacier Deep Archive: Archive data that rarely, if ever, needs to be accessed with retrieval times in hours
  * Both Glacier and Glacier Deep Archive are:
    * The most cheap storage classes
    * have 9x9% durability

More on storage classes [here](https://aws.amazon.com/s3/storage-classes)

</b></details>

<details>
<summary>A customer would like to move data which is rarely accessed from standard storage class to the most cheapest class there is. Which storage class should be used?

  * One Zone-IA
  * Glacier Deep Archive
  * Intelligent-Tiering</summary><br><b>

Glacier Deep Archive
</b></details>

<details>
<summary>Explain what is Storage Gateway</summary><br><b>

"AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage".
More on Storage Gateway [here](https://aws.amazon.com/storagegateway)
</b></details>

<details>
<summary>Explain the following Storage Gateway deployments types

  * File Gateway
  * Volume Gateway
  * Tape Gateway</summary><br><b>

Explained in detail [here](https://aws.amazon.com/storagegateway/faqs)
</b></details>

<details>
<summary>What is the difference between stored volumes and cached volumes?</summary><br><b>

Stored Volumes - Data is located at customer's data center and periodically backed up to AWS
Cached Volumes - Data is stored in AWS cloud and cached at customer's data center for quick access
</b></details>

<details>
<summary>Explain data consistency</summary><br><b>
</b></details>

<details>
<summary>Can you host dynamic websites on S3? What about static websites?</summary><br><b>
</b></details>

<details>
<summary>What security measures have you taken in context of S3?</summary><br><b>
</b></details>

<details>
<summary>What storage options are there for EC2 Instances?</summary><br><b>
</b></details>

#### AWS CloudFormation

<details>
<summary>Explain what is CloudFormation</summary><br><b>
</b></details>

#### AWS CloudFront

<details>
<summary>Explain what is CloudFront</summary><br><b>

AWS definition: "Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment."

More on CloudFront [here](https://aws.amazon.com/cloudfront)
</b></details>

<details>
<summary>Explain the following

  * Origin
  * Edge location
  * Distribution</summary><br><b>
</b></details>

<details>
<summary>What delivery methods available for the user with CDN?</summary><br><b>
</b></details>

<details>
<summary>True or False?. Objects are cached for the life of TTL</summary><br><b>

True
</b></details>

<details>
<summary>What is AWS Snowball?</summary><br><b>

A transport solution which was designed for transferring large amounts of data (petabyte-scale) into and out the AWS cloud.
</b></details>

##### AWS ELB

<details>
<summary>What is ELB (Elastic Load Balancing)?</summary><br><b>

AWS definition: "Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions."

More on ELB [here](https://aws.amazon.com/elasticloadbalancing)
</b></details>

<details>
<summary>What is auto scaling?</summary><br><b>

AWS definition: "AWS Auto Scaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost"

Read more about auto scaling [here](https://aws.amazon.com/autoscaling)
</b></details>

<details>
<summary>True or False? Auto Scaling is about adding resources (such as instances) and not about removing resource</summary><br><b>

False. Auto scaling adjusts capacity and this can mean removing some resources based on usage and performances.
</b></details>

<details>
<summary>What types of load balancers are supported in EC2 and what are they used for?</summary><br><b>

  * Application LB - layer 7 traffic
  * Network LB - ultra-high performances or static IP address
  * Classic LB - low costs, good for test or dev environments
</b></details>

#### AWS Security 

<details>
<summary>What is the shared responsibility model? What AWS is responsible for and what the user is responsible for based on the shared responsibility model?</summary><br><b>

The shared responsibility model defines what the customer is responsible for and what AWS is responsible for.

More on the shared responsibility model [here](https://aws.amazon.com/compliance/shared-responsibility-model)
</b></details>

<details>
<summary>True or False? Based on the shared responsibility model, Amazon is responsible for physical CPUs and security groups on instances</summary><br><b>

False. It is responsible for Hardware in its sites but not for security groups which created and managed by the users.
</b></details>

<details>
<summary>What is the AWS compliance program?</summary><br><b>
</b></details>

<details>
<summary>Explain what each of the following services is used for

  * AWS Inspector
  * AWS Artifact
  * AWS GuardDuty
  * AWS Shield</summary><br><b>
</b></details>

<details>
<summary>What is AWS WAF? Give an example of how it can used and describe what resources or services you can use it with</summary><br><b>
</b></details>

<details>
<summary>What AWS VPN is used for?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between Site-to-Site VPN and Client VPN?</summary><br><b>
</b></details>

<details>
<summary>True or False? AWS Inspector can perform both network and host assessments</summary><br><b>

True
</b></details>

<details>
<summary>What is AWS Key Management Service (KMS)?</summary><br><b>

AWS definition: "KMS makes it easy for you to create and manage cryptographic keys and control their use across a wide range of AWS services and in your applications."
More on KMS [here](https://aws.amazon.com/kms)
</b></details>

<details>
<summary>What is AWS Acceptable Use Policy?</summary><br><b>

It describes prohibited uses of the web services offered by AWS.
More on AWS Acceptable Use Policy [here](https://aws.amazon.com/aup)
</b></details>

<details>
<summary>True or False? A user is not allowed to perform penetration testing on any of the AWS services</summary><br><b>

False. On some services, like EC2, CloudFront and RDS, penetration testing is allowed.
</b></details>

<details>
<summary>True or False? DDoS attack is an example of allowed penetration testing activity</summary><br><b>

False.
</b></details>

#### AWS Databases

<details>
<summary>What is AWS RDS?</summary><br><b>
</b></details>

<details>
<summary>What is AWS DynamoDB?</summary><br><b>
</b></details>

<details>
<summary>What is AWS Redshift and how is it different than RDS?</summary><br><b>
</b></details>

<details>
<summary>What do you if you suspect AWS Redshift performs slowly?</summary><br><b>

* You can confirm your suspicion by going to AWS Redshift console and see running queries graph. This should tell you if there are any long-running queries.
* If confirmed, you can query for running queries and cancel the irrelevant queries
* Check for connection leaks (query for running connections and include their IP)
* Check for table locks and kill irrelevant locking sessions
</b></details>

<details>
<summary>What is AWS ElastiCache? For what cases is it used?</summary><br><b>

Amazon Elasticache is a fully managed Redis or Memcached in-memory data store.                                                                       
It's great for use cases like two-tier web applications where the most frequently accesses data is stored in ElastiCache so response time is optimal.
</b></details>

<details>
<summary>What is Amazon Aurora</summary><br><b>

A MySQL & Postgresql based relational database. Also, the default database proposed for the user when using RDS for creating a database.
Great for use cases like two-tier web applications that has a MySQL or Postgresql database layer and you need automated backups for your application.
</b></details>

<details>
<summary>What "AWS Database Migration Service" is used for?</summary><br><b>
</b></details>

#### AWS Networking

<details>
<summary>What is VPC?</summary><br><b>

"A logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network that you define"
Read more about it [here](https://aws.amazon.com/vpc).
</b></details>

<details>
<summary>True or False? VPC spans multiple regions</summary><br><b>

False
</b></details>

<details>
<summary>True or False? Subnets belong to the same VPC, can be in different availability zones</summary><br><b>

True. Just to clarify, a single subnet resides entirely in one AZ.
</b></details>

<details>
<summary>What is an Internet Gateway?</summary><br><b>

"component that allows communication between instances in your VPC and the internet" (AWS docs).
Read more about it [here](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)
</b></details>

<details>
<summary>True or False? NACL allow or deny traffic on the subnet level</summary><br><b>

True
</b></details>

<details>
<summary>True or False? Multiple Internet Gateways can be attached to one VPC</summary><br><b>

False. Only one internet gateway can be attached to a single VPC.
</b></details>

<details>
<summary>What is an Elastic IP address?</summary><br><b>
</b></details>

<details>
<summary>True or False? Route Tables used to allow or deny traffic from the internet to AWS instances</summary><br><b>

False.
</b></details>

<details>
<summary>Explain Security Groups and Network ACLs</summary><br><b>

* NACL - security layer on the subnet level.
* Security Group - security layer on the instance level.

Read more about it [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html) and [here](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html)
</b></details>

<details>
<summary>What is AWS Direct Connect?</summary><br><b>

Allows you to connect your corporate network to AWS network.
</b></details>

#### Identify the service or tool

<details>
<summary>What would you use for easily creating similar AWS environments/resources for different customers?</summary><br><b>

CloudFormation
</b></details>

<details>
<summary>Using which service, can you add user sign-up, sign-in and access control to mobile and web apps?</summary><br><b>

Cognito
</b></details>

<details>
<summary>Which service would you use for building a website or web application?</summary><br><b>

Lightsail
</b></details>

<details>
<summary>Which tool would you use for choosing between Reserved instances or On-Demand instances?</summary><br><b>

Cost Explorer
</b></details>

<details>
<summary>What would you use to check how many unassociated Elastic IP address you have?</summary><br><b>

Trusted Advisor
</b></details>

<details>
<summary>What service allows you to transfer large amounts (Petabytes) of data in and out of the AWS cloud?</summary><br><b>

AWS Snowball
</b></details>

<details>
<summary>What provides a virtual network dedicated to your AWS account?</summary><br><b>

VPC
</b></details>

<details>
<summary>What you would use for having automated backups for an application that has MySQL database layer?</summary><br><b>

Amazon Aurora
</b></details>

<details>
<summary>What would you use to migrate on-premise Oracle database to AWS?</summary><br><b>

AWS Database Migration Service
</b></details>

<details>
<summary>What would you use to check why certain EC2 instances were terminated?</summary><br><b>

AWS CloudTrail
</b></details>

<details>
<summary>What would you use for SQL database?</summary><br><b>

AWS RDS
</b></details>

<details>
<summary>What would you use for NoSQL database?</summary><br><b>

AWS DynamoDB
</b></details>

<details>
<summary>What would you use for adding image and video analysis to your application?</summary><br><b>

AWS Rekognition
</b></details>

<details>
<summary>Which service is used for sending notifications?</summary><br><b>

SNS
</b></details>

<details>
<summary>What would you use for running SQL queries interactively on S3?</summary><br><b>

AWS Athena
</b></details>

<details>
<summary>Which service would you use for monitoring malicious activity and unauthorized behavior in regards to AWS accounts and workloads?</summary><br><b>

Amazon GuardDuty
</b></details>

<details>
<summary>Which service would you use for centrally manage billing, control access, compliance, and security across multiple AWS accounts?</summary><br><b>

AWS Organizations
</b></details>

<details>
<summary>Which service would you use for web application protection?</summary><br><b>

AWS WAF
</b></details>

#### AWS DNS

<details>
<summary>What is Route 53?</summary><br><b>

"Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service..."
Some of Route 53 features:
  * Register domain
  * DNS service - domain name translations
  * Health checks - verify your app is available

More on Route 53 [here](https://aws.amazon.com/route53)
</b></details>

#### AWS Monitoring & Logging

<details>
<summary>What is AWS CloudWatch?</summary><br><b>

AWS definition: "Amazon CloudWatch is a monitoring and observability service..."

More on CloudWatch [here](https://aws.amazon.com/cloudwatch)
</b></details>

<details>
<summary>What is AWS CloudTrail?</summary><br><b>

AWS definition: "AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account."

Read more on CloudTrail [here](https://aws.amazon.com/cloudtrail)
</b></details>

<details>
<summary>What is Simply Notification Service?</summary><br><b>

AWS definition: "a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications."

Read more about it [here](https://aws.amazon.com/sns)
</b></details>

<details>
<summary>Explain the following in regards to SNS:

  * Topics
  * Subscribers
  * Publishers</summary><br><b>

  * Topics - used for grouping multiple endpoints
  * Subscribers - the endpoints where topics send messages to 
  * Publishers - the provider of the message (event, person, ...)
</b></details>

#### AWS Billing & Support

<details>
<summary>What is AWS Organizations?</summary><br><b>

AWS definition: "AWS Organizations helps you centrally govern your environment as you grow and scale your workloads on AWS."
More on Organizations [here](https://aws.amazon.com/organizations)
</b></details>

<details>
<summary>What are Service Control Policies and to what service they belong?</summary><br><b>

AWS organizations service and the definition by Amazon: "SCPs offer central control over the maximum available permissions for all accounts in your organization, allowing you to ensure your accounts stay within your organization’s access control guidelines."

Learn more [here](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scp.html)
</b></details>

<details>
<summary>Explain AWS pricing model</summary><br><b>

It mainly works on "pay-as-you-go" meaning you pay only for what are using and when you are using it.
In s3 you pay for 1. How much data you are storing 2. Making requests (PUT, POST, ...)
In EC2 it's based on the purchasing option (on-demand, spot, ...), instance type, AMI type and the region used.

More on AWS pricing model [here](https://aws.amazon.com/pricing)
</b></details>

<details>
<summary>How one should estimate AWS costs when for example comparing to on-premise solutions?</summary><br><b>

* TCO calculator
* AWS simple calculator
* Cost Explorer
</b></details>

<details>
<summary>What basic support in AWS includes?</summary><br><b>

* 24x7 customer service
* Trusted Advisor
* AWS personal Health Dashoard
</b></details>

<details>
<summary>Which of the following are AWS accounts types (and are sorted by order)?

  * Basic, Developer, Business, Enterprise
  * Newbie, Intermediate, Pro, Enterprise
  * Developer, Basic, Business, Enterprise
  * Beginner, Pro, Intermediate Enterprise</summary><br><b>

  * Basic, Developer, Business, Enterprise
</b></details>

<details>
<summary>True or False? Region is a factor when it comes to EC2 costs/pricing</summary><br><b>

True. You pay differently based on the chosen region.
</b></details>

#### AWS Misc

<details>
<summary>What is AWS CloudSearch?</summary><br><b>
</b></details>

<details>
<summary>What is AWS Lightsail?</summary><br><b>

AWS definition: "Lightsail is an easy-to-use cloud platform that offers you everything needed to build an application or website, plus a cost-effective, monthly plan."
</b></details>

<details>
<summary>What is AWS Rekognition?</summary><br><b>

AWS definition: "Amazon Rekognition makes it easy to add image and video analysis to your applications using proven, highly scalable, deep learning technology that requires no machine learning expertise to use."

Learn more [here](https://aws.amazon.com/rekognition)
</b></details>

<details>
<summary>What is AWS Athena?</summary><br><b>

"Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL."

Learn more about AWS Athena [here](https://aws.amazon.com/athena)
</b></details>

<details>
<summary>What is AWS EMR?</summary><br><b>
</b></details>

<details>
<summary>What is AWS Quick Starts?</summary><br><b>

AWS definition: "Quick Starts are built by AWS solutions architects and partners to help you deploy popular technologies on AWS, based on AWS best practices for security and high availability."

Read more [here](https://aws.amazon.com/quickstart)
</b></details>

<details>
<summary>What is the Trusted Advisor?</summary><br><b>
</b></details>

<details>
<summary>What AWS services are serverless (or have the option to be serverless)?</summary><br><b>

AWS Lambda
AWS Athena
</b></details>

## Network

<a name="network-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Ethernet?</summary><br><b>

Ethernet simply refers to the most common type of Local Area Network (LAN) used today. A LAN—in contrast to a WAN (Wide Area Network), which spans a larger geographical area—is a connected network of computers in a small area, like your office, college campus, or even home.
</b></details>

<details>
<summary>What is TCP/IP?</summary><br><b>

A set of protocols that define how two or more devices can communicate with each other.
To learn more about TCP/IP, read [here](http://www.penguintutor.com/linux/basic-network-reference)
</b></details>

<details>
<summary>What is a MAC address? What is it used for?</summary><br><b>

A MAC address is a unique identification number or code used to identify individual devices on the network.

Packets that are sent on the ethernet are always coming from a MAC address and sent to a MAC address. If a network adapter is receiving a packet, it is comparing the packet’s destination MAC address to the adapter’s own MAC address.

</b></details>

<details>
<summary>When is this MAC address used?: ff:ff:ff:ff:ff:ff</summary><br><b>
</b></details>

<details>
<summary>What is an IP address?</summary><br><b>

An Internet Protocol address (IP address) is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication.An IP address serves two main functions: host or network interface identification and location addressing.


</b></details>

<details>
<summary>Explain subnet mask and given an example</summary><br><b>

A Subnet mask is a 32-bit number that masks an IP address, and divides the IP address into network address and host address. Subnet Mask is made by setting network bits to all "1"s and setting host bits to all "0"s. Within a given network, two host addresses are reserved for special purpose, and cannot be assigned to hosts. The "0" address is assigned a network address and "255" is assigned to a broadcast address, and they cannot be assigned to hosts.

**For Example**

```
| Address Class | No of Network Bits | No of Host Bits | Subnet mask     | CIDR notation |
| ------------- | ------------------ | --------------- | --------------- | ------------- |
| A             | 8                  | 24              | 255.0.0.0       | /8            |
| A             | 9                  | 23              | 255.128.0.0     | /9            |
| A             | 12                 | 20              | 255.240.0.0     | /12           |
| A             | 14                 | 18              | 255.252.0.0     | /14           |
| B             | 16                 | 16              | 255.255.0.0     | /16           |
| B             | 17                 | 15              | 255.255.128.0   | /17           |
| B             | 20                 | 12              | 255.255.240.0   | /20           |
| B             | 22                 | 10              | 255.255.252.0   | /22           |
| C             | 24                 | 8               | 255.255.255.0   | /24           |
| C             | 25                 | 7               | 255.255.255.128 | /25           |
| C             | 28                 | 4               | 255.255.255.240 | /28           |
| C             | 30                 | 2               | 255.255.255.252 | /30           |

```
</b></details>

<details>
<summary>What is a private IP address? What do we need it for?</summary><br><b>
</b></details>

<details>
<summary>Explain the OSI model. What layers there are? What each layer is responsible for?</summary><br><b>

- Application: user end (HTTP is here)
- Presentation: establishes context between application-layer entities (Encryption is here)
- Session: establishes, manages and terminates the connections
- Transport: transfers variable-length data sequences from a source to a destination host (TCP & UDP are here)
- Network: transfers datagrams from one network to another (IP is here)
- Data link: provides a link between two directly connected nodes (MAC is here)
- Physical: the electrical and physical spec the data connection (Bits are here)

You can read more about the OSI model in [penguintutor.com](http://www.penguintutor.com/linux/basic-network-reference)
</b></details>

<details>
<summary>For each of the following determine to which OSI layer it belongs:

  * Error correction
  * Packets routing
  * Cables and electrical signals
  * MAC address
  * IP address
  * Terminate connections
  * 3 way handshake</summary><br><b>

  * Error correction
  * Packets routing - Network
  * Cables and electrical signals - Physical
  * MAC address - Data link
  * IP address - Network
  * Terminate connections - Session
  * 3 way handshake - Transport
</b></details>

<details>
</b></details>

<details>
<summary>What delivery schemes are you familiar with?</summary><br><b>

Unitcast: One to one communication where there is one sender and one receiver.

Broadcast: Sending a message to everyone in the network. The address ff:ff:ff:ff:ff:ff is used for broadcasting.
           Two common protocols which use broadcast are ARP and DHCP.

Multicast: Sending a message to a group of subscribers. It can be one-to-many or many-to-many.
</b></details>

<details>
<summary>What is CSMA/CD? Is it used in modern ethernet networks?</summary><br><b>

CSMA/CD stands for Carrier Sense Multiple Access / Collision Detection.
Its primarily focus it to manage access to shared medium/bus where only one host can transmit at a given point of time.

CSMA/CD algorithm:

1. Before sending a frame, it checks whether another host already transmitting a frame.
2. If no one transmitting, it starts transmitting the frame.
3. If two hosts transmitted at the same time, we have a collision.
4. Both hosts stop sending the frame and they send to everyone a 'jam signal' notifying everyone that a collision occurred
5. They are waiting for a random time before sending again
6. Once each host waited for a random time, they try to send the frame again and so the
</b></details>

<details>
<summary>Describe the following network devices and the difference between them:

  * router
  * switch
  * hub</summary><br><b>
</b></details>

<details>
<summary>How does a router works?</summary><br><b>

A router is a physical or virtual appliance that passes information between two or more packet-switched computer networks. A router inspects a given data packet's destination Internet Protocol address (IP address), calculates the best way for it to reach its destination and then forwards it accordingly.


</b></details>

<details>
<summary>What is NAT?</summary><br><b>

 Network Address Translation (NAT) is a process in which one or more local IP address is translated into one or more Global IP address and vice versa in order to provide Internet access to the local hosts. 


</b></details>

<details>
<summary>What is a proxy? How does it works? What do we need it for?</summary><br><b>

A proxy server acts as a gateway between you and the internet. It’s an intermediary server separating end users from the websites they browse.

If you’re using a proxy server, internet traffic flows through the proxy server on its way to the address you requested. The request then comes back through that same proxy server (there are exceptions to this rule), and then the proxy server forwards the data received from the website to you.

roxy servers provide varying levels of functionality, security, and privacy depending on your use case, needs, or company policy.


</b></details>

<details>
<summary>What is TCP? How does it works? What is the 3 way handshake?</summary><br><b>

TCP 3-way handshake or three-way handshake is a process which is used in a TCP/IP network to make a connection between server and client.

A three-way handshake is primarily used to create a TCP socket connection. It works when:

- A client node sends a SYN data packet over an IP network to a server on the same or an external network. The objective of this packet is to ask/infer if the server is open for new connections.
- The target server must have open ports that can accept and initiate new connections. When the server receives the SYN packet from the client node, it responds and returns a confirmation receipt – the ACK packet or SYN/ACK packet.
- The client node receives the SYN/ACK from the server and responds with an ACK packet.
</b></details>

<details>
<summary>How does SSL handshake work?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between TCP and UDP?</summary><br><b>
	
TCP establishes a connection between the client and the server to guarantee the order of the packages, on the other hand, UDP does not establish a connection between client and server and doesn't handle package order. This makes UDP more lightweight than TCP and a perfect candidate for services like streaming.

[Penguintutor.com](http://www.penguintutor.com/linux/basic-network-reference) provides a good explanation.
</b></details>

<details>
<summary>What TCP/IP protocols are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Explain "default gateway"</summary><br><b>

A default gateway serves as an access point or IP router that a networked computer uses to send information to a computer in another network or the internet.
</b></details>

<details>
<summary>What is ARP? How does it works?</summary><br><b>

ARP stands for Address Resolution Protocol. When you try to ping an IP address on your local network, say 192.168.1.1, your system has to turn the IP address 192.168.1.1 into a MAC address. This involves using ARP to resolve the address, hence its name.

Systems keep an ARP look-up table where they store information about what IP addresses are associated with what MAC addresses. When trying to send a packet to an IP address, the system will first consult this table to see if it already knows the MAC address. If there is a value cached, ARP is not used.
</b></details>

<details>
<summary>What is TTL?</summary><br><b>
</b></details>

<details>
<summary>What is DHCP? How does it works?</summary><br><b>
</b></details>

<details>
<summary>What is SSL tunneling? How does it works?</summary><br><b>
</b></details>

<details>
<summary>What is a socket? Where can you see the list of sockets in your system?</summary><br><b>
</b></details>

<details>
<summary>What is IPv6? Why should we consider using it if we have IPv4?</summary><br><b>
</b></details>

<details>
<summary>What is VLAN?</summary><br><b>
</b></details>

<details>
<summary>What is MTU?</summary><br><b>
</b></details>

<details>
<summary>What happens if you send a packet that is bigger than the MTU?</summary><br><b>
</b></details>

<details>
<summary>True or False?. Ping is using UDP because it doesn't care about reliable connection</summary><br><b>
</b></details>

<details>
<summary>What is SDN?</summary><br><b>
</b></details>

<details>
<summary>What is ICMP? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>What is NAT? How does it works?</summary><br><b>
</b></details>

<details>
<summary>Which factors affect network performances</summary><br><b>
</b></details>

<details>
<summary>What the terms "Data Plane" and "Control Plane" refer?</summary><br><b>

The exact meaning is usually depends on the context but overall data plane refers to all the functions that forward packets and/or frames from one interface to another while control plane refers to all the functions that make use of routing protocols.

There is also "Management Plane" which refers to monitoring and management functions.
</b></details>

<a name="network-advanced"></a>
#### :star: Advanced

<details>
<summary>Explain Spanning Tree Protocol (STP)</summary><br><b>
</b></details>

<details>
<summary>What is link aggregation? Why is it used?</summary><br><b>
</b></details>

<details>
<summary>What is Asymmetric Routing? How do deal with it?</summary><br><b>
</b></details>

<details>
<summary>What overlay (tunnel) protocols are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What is GRE? How does it works?</summary><br><b>
</b></details>

<details>
<summary>What is VXLAN? How does it works?</summary><br><b>
</b></details>

<details>
<summary>What is SNAT?</summary><br><b>
</b></details>

<details>
<summary>Explain OSPF</summary><br><b>
</b></details>

<details>
<summary>Explain Spine & Leaf</summary><br><b>
</b></details>

<details>
<summary>What is Network Congestion? What can cause it?</summary><br><b>
</b></details>

<details>
<summary>What can you tell me about UDP packet format? What about TCP packet format? How is it different?</summary><br><b>
</b></details>

<details>
<summary>What is the exponential backoff algorithm? Where is it used?</summary><br><b>
</b></details>

<details>
<summary>Using Hamming code, what would be the code word for the following data word 100111010001101?</summary><br><b>

00110011110100011101
</b></details>

## Linux

<a name="linux-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is your experience with Linux?</summary><br><b>

An open question. Answer based on your real experience. You can highlight one or more of the following:

* Troubleshooting & Debugging
* Storage
* Networking
* Development
* Deployments
</b></details>

<details>
<summary>Explain what each of the following commands does and give an example on how to use it:

  * ls
  * rm 
  * rmdir (can you achieve the same result by using <code>rm</code>?)
  * grep
  * touch
  * whoami
  * man
  * nslookup or dig
  * pwd
  * df</summary><br><b>

  * ls - list files and directories. You can highlight common flags like -d, -a, -l, ...
  * rm - remove files and directories. You should mention -r for recursive removal
  * rmdir - remove directories but you should mention it's possible to use rm for that
  * grep - print lines that match patterns. Could be nice to mention -v, -r, -E flags
  * touch - update timestamps but common usage is to create files
  * whoami - current logged-in user
  * man - reference manuals
  * nslookup or dig - query nameservers
  * pwd - print working directory
  * df - provides info regarding file system disk space usage
</b></details>

<details>
<summary>What each of the following commands does?

  * cd ~
  * cd
  * cd ..
  * cd .
  * cd -</summary><br><b>
</b></details>

<details>
<summary>How to rename the name of a file or a directory?</summary><br><b>

mv command.
</b></details>

<details>
<summary>Explain each field in the output of `ls -l` command</summary><br><b>
</b></details>

<details>
<summary>What are hidden files/directories? How to list them?</summary><br><b>
</b></details>

<details>
<summary>Running the command <code>df</code> you get "command not found". What could be wrong and how to fix it?</summary><br><b>
</b>
<p><b>
Most likely the default/generated $PATH was somehow modified or overridden thus not containing <code>/bin/</code> where df would normally go.
This issue could also happen if bash_profile or any configuration file of your interpreter was wrongly modified, causing erratics behaviours.
You would solve this by fixing your $PATH variable:

As to fix it there are serveral options:

1. Manually adding what you need to your $PATH <code>PATH="$PATH":/user/bin:/..etc</code> 
2. You have your weird env variables backed up.
3. You would look for your distro default $PATH variable, copy paste using method #1

Note: There are many ways of getting errors like this: if bash_profile or any configuration file of your interpreter was wrongly modified; causing erratics behaviours,
permissions issues, bad compiled software (if you compiled it by yourself)... there is no answer that will be true 100% of the time.
</b>
</p>
</details>

<details>
<summary>How do you schedule tasks periodically?</summary><br><b>

You can use the commands <code>cron</code> and <code>at</code>.
With cron, tasks are scheduled using the following format:

<code>*/30 * * * * bash myscript.sh</code> Executes the script every 30 minutes.

<minute> <hour> <day of month> <month> <day of week> <command to execute>

The tasks are stored in a cron file, you can write in it using <code>crontab -e</code>

Alternatively if you are using a distro with systemd it's recommended to use systemd timers.

</b></details>

<details>
<summary>How to check which commands you executed in the past?</summary><br><b>

history command or .bash_history file
</b></details>

##### Permissions

<details>
<summary>How to change the permissions of a file?</summary><br><b>

Using the `chmod` command.

</b></details>

<details>
<summary>What does the following permissions mean?:

  * 777
  * 644
  * 750</summary><br><b>

<pre>
777 - You give the owner, group and other: Execute (1), Write (2) and Read (4); 4+2+1 = 7.
644 - Owner has Read (4), Write (2), 4+2 = 6; Group and Other have Read (4).
750 - Owner has x+r+w, Group has Read (4) and Execute (1); 4+1 = 5. Other have no permissions.
</pre>
</b></details>

<details>
<summary>What this command does? <code>chmod +x some_file</code></summary><br><b>
</b></details>

<details>
<summary>Explain what is setgid and setuid</summary><br><b>
</b></details>

<details>
<summary>What is the purpose of sticky bit?</summary><br><b>
</b></details>

<details>
<summary>What the following commands do?

  * chmod
  * chown
  * chgrp</summary><br><b>
</b></details>

<details>
<summary>You try to delete a file but it fails. Name at least three different reason as to why it could happen</summary><br><b>

* No more disk space
* No more indoes
* No permissions
</b></details>

<details>
<summary>What is systemd?</summary><br>
<b>
Systemd is a daemon (System 'd', d stands from daemon).

A daemon is a program that runs in the background without direct control of the user, although the user can at any time
talk to the daemon.

systemd has many features such as user processes control/tracking, snapshot support, inhibitor locks..


If we visualize the unix/linux system in layers, systemd would fall directly after the linux kernel.

Hardware -> Kernel -> <u>Daemons</u>, System Libraries, Server Display.
</b>
</details>

<details>
<summary>On a system which uses systemd, how would you display the logs?</summary><br><b>

<code>journalctl</code>
</b></details>

<details>
<summary>Describe how to make a certain process/app a service</summary><br><b>
</b></details>

##### Debugging (Beginner)

<details>
<summary>Where system logs are located?</summary><br><b>
</b></details>

<details>
<summary>How to follow file's content as it being appended without opening the file every time?</summary><br><b>

tail -f <file_name>
</b></details>

<details>
<summary>What are you using for troubleshooting and debugging <b>network</b> issues?</summary><br><b>

<code>dstat -t</code> is great for identifying network and disk issues.
<code>netstat -tnlaup</code> can be used to see which processes are running on which ports.
<code>lsof -i -P</code> can be used for the same purpose as netstat.
<code>ngrep -d any metafilter</code> for matching regex against payloads of packets.
<code>tcpdump</code> for capturing packets
<code>wireshark</code> same concept as tcpdump but with GUI (optional).
</b></details>

<details>
<summary>What are you using for troubleshooting and debugging <b>disk & file system</b> issues?</summary><br><b>

<code>dstat -t</code> is great for identifying network and disk issues.
<code>opensnoop</code> can be used to see which files are being opened on the system (in real time).
</b></details>

<details>
<summary>What are you using for troubleshooting and debugging <b>process</b> issues?</summary><br><b>

<code>strace</code> is great for understanding what your program does. It prints every system call your program executed.
</b></details>

<details>
<summary>What are you using for debugging CPU related issues?</summary><br><b>

<code>top</code> will show you how much CPU percentage each process consumes
<code>perf</code> is a great choice for sampling profiler and in general, figuring out what your CPU cycles are "wasted" on
<code>flamegraphs</code> is great for CPU consumption visualization (http://www.brendangregg.com/flamegraphs.html)
</b></details>

<details>
<summary>You get a call from someone claiming "my system is SLOW". What do you do?</summary><br><b>

* Check with `top` for anything unusual
* Run `dstat -t` to check if it's related to disk or network.
* Check if it's network related with `sar`
* Check I/O stats with `iostat`
</b></details>

<details>
<summary>Explain iostat output</summary><br><b>
</b></details>

<details>
<summary>How to debug binaries?</summary><br><b>
</b></details>

<details>
<summary>What kind of information one can find in /proc?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between CPU load and utilization?</summary><br><b>
</b></details>

<details>
<summary>How you measure time execution of a program?</summary><br><b>
</b></details>

#### Kernel

<details>
<summary>How do you find out which Kernel version your system is using?</summary><br><b>
</b></details>

<details>
<summary>What is a Linux kernel module and how do you load a new module?</summary><br><b>
</b></details>

<details>
<summary>Explain user space and kernel space</summary><br><b>
</b></details>

<details>
<summary>What is KVM?</summary><br><b>
</b></details>

<details>
<summary>What is SSH key? How is it used?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between SSH and SSL?</summary><br><b>
</b></details>

<details>
<summary>What is SSH port forwarding?</summary><br><b>
</b></details>

<details>
<summary>Explain redirection</summary><br><b>
</b></details>

#### Linux - Globbing, Wildcards

<details>
<summary>What is Globbing?</summary><br><b>
</b></details>

<details>
<summary>What are wildcards? Can you give an example of how to use them?</summary><br><b>
</b></details>

<details>
<summary>Explain what will <code>ls [XYZ]</code> match</summary><br><b>
</b></details>

<details>
<summary>Explain what will <code>ls [^XYZ]</code> match</summary><br><b>
</b></details>

<details>
<summary>Explain what will <code>ls [0-5]</code> match</summary><br><b>
</b></details>

<details>
<summary>What each of the following matches

  * ?
  * *</summary><br><b>

  * The ? matches any single character
  * The * matches zero or more characters
</b></details>

<details>
<summary>What do we grep for in each of the following commands?:

  * <code>grep '[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}' some_file</code>
  * <code>grep -E "error|failure" some_file</code>
  * <code>grep '[0-9]$' some_file</code>
</summary><br><b>

1. An IP address
2. The word "error" or "failure"
3. Lines which end with a number
</b></details>

<details>
<summary>Which line numbers will be printed when running `grep '\baaa\b'` on the following content:

aaa
bbb
ccc.aaa
aaaaaa</summary><br><b>

lines 1 and 3.
</b></details>

<details>
<summary>What is the difference single and double quotes?</summary><br><b>
</b></details>

<details>
<summary>What is escaping? What escape character is used for escaping?</summary><br><b>
</b></details>

<details>
<summary>Tell me everything you know about the Linux boot process</summary><br><b>

Another way to ask this: what happens from the moment you turned on the server until you get a prompt
</b></details>

<details>
<summary>What is an exit code? What exit codes are you familiar with?</summary><br><b>

An exit code (or return code) represents the code returned by a child process to its
parent process.

0 is an exit code which represents success while anything higher than 1 represents error.
Each number has different meaning, based on how the application was developed.

I consider this as a good blog post to read more about it: https://shapeshed.com/unix-exit-codes
</b></details>

##### Linux - Storage & Filesystem

<details>
<summary>What's an inode?</summary><br><b>

For each file (and directory) in Linux there is an inode, a data structure which stores meta data
related to the file like its size, owner, permissions, etc.
</b></details> 

<details>
<summary>Which of the following is not included in inode:

  * Link count
  * File size
  * File name
  * File timestamp</summary><br><b>
</b></details>

<details>
<summary>How to check which disks are currently mounted?</summary><br><b>
</b></details>

<details>
<summary>You run mount command but you get no output. How would you check what mounts you have on your system?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between a soft link and hard link?</summary><br><b>

Hard link is the same file, using the same inode.
Soft link is a shortcut to another file, using a different inode.
</b></details>

<details>
<summary>True or False? You can create an hard link for a directory</summary><br><b>

False
</b></details>

<details>
<summary>True or False? You can create a soft link between different filesystems</summary><br><b>

True
</b></details>

<details>
<summary>What happens when you delete the original file in case of soft link and hard link?</summary><br><b>
</b></details>

<details>
<summary>What is a swap partition? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>How to create a
  * new empty file 
  * a file with text (without using text editor)
  * a file with given size</summary><br><b>
</b></details>

<details>
<summary>You are trying to create a new file but you get "File system is full". You check with df for free space and you see you used only 20% of the space. What could be the problem?</summary><br><b>
</b></details>

<details>
<summary>How would you check what is the size of a certain directory?</summary><br><b>
</b></details>

<details>
<summary>What do you know about LVM?</summary><br><b>
</b></details>

<details>
<summary>Explain the following in regards to LVM:

  * PV
  * VG
  * LV</summary><br><b>
</b></details>

<details>
<summary>What is NFS? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>What RAID is used for? Can you explain the differences between RAID 0, 1, 5 and 10?</summary><br><b>
</b></details>

<details>
<summary>Describe the process of extending a filesystem disk space</summary><br><b>
</b></details>

<details>
<summary>What is lazy umount?</summary><br><b>
</b></details>

<details>
<summary>What is tmpfs?</summary><br><b>
</b></details>

<details>
<summary>Fix the following commands:

  * sed "s/1/2/g' /tmp/myFile
  * find . -iname \*.yaml -exec sed -i "s/1/2/g" {} ;
  
  </summary><br><b>
</b>
<code>sed 's/1/2/g' /tmp/myFile</code><br>
<code> find . -iname "*.yaml" -exec sed -i "s/1/2/g" {} \; </code>
</details>

<details>
<summary>Explain what is stored in each of the following paths and if there is anything unique about it:</summary><br><b>

  * /tmp
  * /var/log
  * /bin
  * /home
  * /usr/local
</b></details>

<details>
<summary>What is stored in each of the following logs?</summary><br><b>

  * /var/log/messages
  * /var/log/boot.log
</b></details>

<details>
<summary>True or False? both /tmp and /var/tmp cleared upon system boot</summary><br><b>

False. /tmp is cleared upon system boot while /var/tmp is cleared every a couple of days or not cleared at all (depends on distro).
</b></details>

#### Processes

<details>
<summary>How to run a process in the background and why to do that in the first place?</summary><br><b>

You can achieve that by specifying & at end of the command.
As to why, since some commands/processes can take a lot of time to finish
execution or run forever
</b></details>

<details>
<summary>How can you find how much memory a specific process consumes?</summary><br><b>
</b></details>

<details>
<summary>What signal is used by default when you run 'kill *process id*'?</summary><br><b>
<pre>
The default signal is SIGTERM (15). This signal kills
process gracefully which means it allows it to save current
state configuration.
</pre>
</b></details>

<details>
<summary>What signals are you familiar with?</summary><br><b>

SIGTERM - default signal for terminating a process
SIGHUP - common usage is for reloading configuration
SIGKILL - a signal which cannot caught or ignored

To view all available signals run `kill -l`
</b></details>

<details>
<summary>What <code>kill 0</code> does?</summary><br><b>
</b></details>

<details>
<summary>What <code>kill -0 <PID></code> does?</summary><br><b>
</b></details>

<details>
<summary>What is a trap?</summary><br><b>
</b></details>

<details>
<summary>What happens when you press ctrl + c?</summary><br><b>
</b></details>

<details>
<summary>What are daemons?</summary><br><b>
</b></details>

<details>
<summary>What are the possible states of a process in Linux?</summary><br><b>
<pre>
Running (R)
Uninterruptible Sleep (D) - The process is waiting for I/O
Interruptible Sleep (S)
Stopped (T)
Dead (x)
Zombie (z)
</pre>
</b></details>

<details>
<summary>How do you kill a process in D state?</summary><br><b>
</b></details>

<details>
<summary>What is a zombie process?</summary><br><b>

A process which has finished to run but has not exited.

One reason it happens is when a parent process is programmed incorrectly. Every parent process should execute wait() to get the exit code from the child process which finished to run. But when the parent isn't checking for the child exit code, the child process can still exists although it finished to run.
</b></details>

<details>
<summary>How to get rid of zombie processes?</summary><br><b>

You can't kill a zombie process the regular way with `kill -9` for example as it's already dead.

One way to kill zombie process is by sending SIGCHLD to the parent process telling it to terminate its child processes. This might not work if the parent process wasn't programmed properly. The invocation is `kill -s SIGCHLD [parent_pid]`

You can also try closing/terminating the parent process. This will make the zombie process a child of init (1) which does periodic cleanups and will at some point clean up the zombie process.
</b></details>

<details>
<summary>How to find all the

  * Processes executed/owned by a certain user
  * Process which are Java processes
  * Zombie Processes
</summary><br><b>

If you mention at any point ps command with arugments, be familiar with what these arguments does exactly.
</b></details>

<details>
<summary>What is the init process?</summary><br><b>
</b></details>

<details>
<summary>How to change the priority of a process? Why would you want to do that?</summary><br><b>
</b></details>

<details>
<summary>Can you explain how network process/connection is established and how it's terminated?></summary><br></b>
</b></details>

<details>
<summary>What are system calls? What system calls are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What <code>strace</code> does? What about <code>ltrace</code>?</summary><br><b>
</b></details>

<details>
<summary>Find all the files which end with '.yml' and replace the number 1 in 2 in each file</summary><br><b>

find /some_dir -iname \*.yml -print0 | xargs -0 -r sed -i "s/1/2/g"
</b></details>

<details>
<summary>How to check how much free memory a system has? How to check memory consumption by each process?</summary><br><b>

You can use the commands <code>top</code> and <code>free</code>
</b></details>

<details>
<summary>You run ls and you get "/lib/ld-linux-armhf.so.3 no such file or directory". What is the problem?</summary><br><b>

The ls executable is built for an incompatible architecture.
</b></details>

<details>
<summary>How would you split a 50 lines file into 2 files of 25 lines each?</summary><br><b>

You can use the <code>split</code> command this way: <code>split -l 25 some_file</code>
</b></details>

<details>
<summary>What is a file descriptor? What file descriptors are you familiar with?</summary><br><b>
Kerberos
File descriptor, also known as file handler, is a unique number which identifies an open file in the operating system.

In Linux (and Unix) the first three file descriptors are:
  * 0 - the default data stream for input
  * 1 - the default data stream for output
  * 2 - the default data stream for output related to errors

This is a great article on the topic: https://www.computerhope.com/jargon/f/file-descriptor.htm
</b></details>

<details>
<summary>What is NTP? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>Explain Kernel OOM</summary><br><b>
</b></details>

##### Linux Security

<details>
<summary>What is chroot? In what scenarios would you consider using it?</summary><br><b>
</b></details>

<details>
<summary>What is SELiunx?</summary><br><b>
</b></details>

<details>
<summary>What is Kerberos?</summary><br><b>
</b></details>

<details>
<summary>What is nftables?</summary><br><b>
</b></details>

<details>
<summary>What firewalld daemon is responsible for?</summary><br><b>
</b></details>

<details>
<summary>Do you have experience with hardening servers? Can you describe the process?</summary><br><b>
</b></details>

##### Linux - Networking

<details>
<summary>How to list all interfaces?</summary><br><b>
</b></details>

<details>
<summary>How to disable an interface?</summary><br><b>
</b></details>

<details>
<summary>What is a network namespace? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>How to check if a certain port is being used?</summary><br><b>

One of the following would work:

```
netstat -tnlp | grep <port_number>
lsof -i -n -P | grep <port_number>
```
</b></details>

<details>
<summary>How can you turn your Linux server into a router?</summary><br><b>
</b></details>

<details>
<summary>What is a virtual IP? In what situation would you use it?</summary><br><b>
</b></details>

<details>
<summary>True or False? The MAC address of an interface is assigned/set by the OS</summary><br><b>

False
</b></details>

<details>
<summary>Can you have more than one default gateway in a given system?</summary><br><b>

Technically, yes.
</b></details>

<details>
<summary>Which port is used in each of the following protocols?:

  * SSH
  * SMTP
  * HTTP
  * DNS
  * HTTPS</summary><br><b>

  * SSH - 22
  * SMTP - 35
  * HTTP - 80
  * DNS - 53
  * HTTPS - 443
</b></details>

<details>
<summary>What is telnet and why is it a bad idea to use it in production? (or at all)</summary><br><b>
</b></details>

<details>
<summary>What is the routing table? How do you view it?</summary><br><b>
</b></details>

<details>
<summary>How can you send an HTTP request from your shell?</summary><br><b>
<br>
Using nc is one way<br>
</b></details>

<details>
<summary>What are packet sniffers? Have you used one in the past? If yes, which packet sniffers have you used and for what purpose?</summary><br><b>
</b></details>

<details>
<summary>How to list active connections?</summary><br><b>
</b></details>

<details>
<summary>How to trigger neighbor discovery in IPv6?</summary><br><b>

One way would be `ping6 ff02::1`
</b></details>

##### Linux DNS

<details>
<summary>What the file <code>/etc/resolv.conf</code> is used for? What does it include?</summary><br><b>
</b></details>

<details>
<summary>What commands are you using for performing DNS queries (or troubleshoot DNS related issues)?</summary><br><b>

You can specify one or more of the following:

 * <code>dig</code>
 * <code>host</code>
 * <code>nslookup</code>
</b></details>

##### Packaging

<details>
<summary>Do you have experience with packaging? (as in building packages) Can you explain how does it works?</summary><br><b>
</b></details>

<details>
<summary>RPM: explain the spec format(what it should and can include)</summary><br><b>
</b></details>

<details>
<summary>How do you list the content of a package without actually installing it?</summary><br><b>
</b></details>

<details>
<summary>How to know to which package a file on the system belongs to? Is it a problem if it doesn't belongs to any package?</summary><br><b>
</b></details>

<details>
<summary>Where repositories are stored? (based on the distribution you are using)</summary><br><b>
</b></details>

<details>
<summary>What is an archive? How do you create one in Linux?</summary><br><b>
</b></details>

<details>
<summary>How to extract the content of an archive?</summary><br><b>
</b></details>

<details>
<summary>Why do we need package managers? Why not simply creating archives and publish them?</summary><br><b>

Package managers allow you to manage packages lifecycle as in installing, removing and update the packages.<br>
In addition, you can specify in a spec how a certain package will be installed - where to copy the files, which commands to run prior to the installation, post the installation, etc.
</b></details>

##### Applications and Services

<details>
<summary>What can you find in /etc/services?</summary><br><b>
</b></details>

<details>
<summary>How to make sure a Service starts automatically after a reboot or crash?</summary><br><b>

Depends on the init system.

Systemd: <code> systemctl enable [service_name] </code>
System V: <code> update-rc.d [service_name] </code> and add this line <code> id:5678:respawn:/bin/sh /path/to/app </code> to /etc/inittab
Upstart: add Upstart init script at /etc/init/service.conf
</b></details>

<details>
<summary>You run <code>ssh 127.0.0.1</code> but it fails with "connection refused". What could be the problem?</summary><br><b>

1. SSH server is not installed
2. SSH server is not running
</b></details>

<details>
<summary>How to print the shared libraries required by a certain program? What is it useful for?</summary><br><b>
</b></details>

<details>
<summary>What is CUPS?</summary><br><b>
</b></details>

<details>
<summary>What types of web servers are you familiar with?</summary><br><b>

Nginx, Apache httpd.
</b></details>

##### Users

<details>
<summary>How do you create users? Where user information is stored?</summary><br><b>
</b></details>

<details>
<summary>Which file stores information about groups?</summary><br><b>
</b></details>

<details>
<summary>How do you change/set the password of a user?</summary><br><b>
</b></details>

<details>
<summary>Which file stores users passwords? Is it visible for everyone?</summary><br><b>
</b></details>

<details>
<summary>Do you know how to create a new user without using adduser/useradd command?</summary><br><b>
</b></details>

<details>
<summary>What information is stored in /etc/passwd? explain each field</summary><br><b>
</b></details>

<details>
<summary>How to add a new user to the system without providing him the ability to log-in into the system?</summary><br><b>

`adduser user_name --shell=/bin/false --no-create-home`
You can also add a user and then edit /etc/passwd.
</b></details>

<details>
<summary>How to switch to another user? How to switch to root?</summary><br><b>

su command.
Use su - to switch to root
</b></details>

<details>
<summary>What is the UID the root user? What about a regular user?</summary><br><b>
</b></details>

<details>
<summary>What can you do if you lost/forogt the root password?</summary><br><b>

Re-install the OS IS NOT the right answer :)
</b></details>

<details>
<summary>What is sudo? How do you set it up?</summary><br><b>
</b></details>

<details>
<summary>What is /etc/skel?</summary><br><b>
</b></details>

<details>
<summary>How to see a list of who logged-in to the system?</summary><br><b>

Using the last command.
</b></details>

#### Linux - Hardware

<details>
<summary>Where can you find information on the processor?</summary><br><b>

/proc/cpuinfo
</b></details>

<details>
<summary>How can you print information on the BIOS, motherboard, processor and RAM?</summary><br><b>

dmidecoode
</b></details>

<details>
<summary>How can you print all the information on connected block devices in your system?</summary><br><b>

lsblk
</b></details>

#### Linux - Random

<details>
<summary>Give 5 commands which are two letters long</summary><br><b>

ls, wc, dd, df, du, ps, ip, cp, cd ...
</b></details>

<details>
<summary>What ways are there for creating a new empty file?</summary><br><b>

  * touch new_file
  * echo "" > new_file
</b></details>

<details>
<summary>How `cd -` works? How does it knows the previous location?</summary><br><b>

$OLDPWD
</b></details>

<details>
<summary>List three ways to print all the files in the current directory</summary><br><b>

* ls
* find .
* echo *
</b></details>

<details>
<summary>What is '|'? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>How to count the number of lines in a file? What about words?</summary><br><b>
</b></details>

<details>
<summary>You define x=2 in /etc/bashrc and x=6 ~/.bashrc you then login to the system. What would be the value of x?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between man and info?</summary><br><b>

A good answer can be found [here](https://askubuntu.com/questions/9325/what-is-the-difference-between-man-and-info-documentation)
</b></details>

<details>
<summary>Explain "environment variables". How do you list all environment variables?</summary><br><b>
</b></details>

<details>
<summary>How to create your own environment variables?</summary><br><b>

`X=2` for example. But this will persist to new shells. To have it in new shells as well, use `export X=2`
</b></details>

<details>
<summary>What a double dash (--) mean?</summary><br><b>

It's used in commands to mark the end of commands options. One common example is when used with git to discard local changes: `git checkout -- some_file`
</b></details>

#### Commands

<details>
<summary>What the <code>lsof</code> command does? Have you used it? What for?</summary><br><b>
</b></details>

<details>
<summary>What the <code>awk</code> command does? Have you used it? What for?</summary><br><b>
</b></details>

<details>
<summary>What commands you can use for searching files and/or directories?</summary><br><b>

  * find
  * locate
</b></details>

<details>
<summary>How can you check what is the path of a certain command?</summary><br><b>

  * whereis
  * which
</b></details>

<a name="linux-advanced"></a>
#### :star: Advanced

#### System Calls

<details>
<summary>Explain the fork() system call</summary><br><b>

fork() is used for creating a new process. It does so by cloning the calling process but the child process has its own PID and any memory locks, I/O operations and semaphores are not inherited.
</b></details>

<details>
<summary>Explain the exec() system call</summary><br><b>
</b></details>

<details>
<summary>What system call is used for listing files?</summary><br><b>
</b></details>

<details>
<summary>What system call is used for creating a new process?</summary><br><b>
</b></details>

<details>
<summary>What are the differences between exec() and fork()?</summary><br><b>
</b></details>

<details>
<summary>Why do we need the wait system call?</summary><br><b>

wait() is used by a parent process to wait for the child process to finish execution.
If wait is not used by a parent process then a child process might become a zombie process.
</b></details>

<details>
<summary>What execve() does?</summary><br><b>

Executes a program. The program is passed as a filename (or path) and must be a binary executable or a script.
</b></details>

<details>
<summary>What is the return value of malloc?</summary><br><b>
</b></details>

<details>
<summary>Explain the pipe() system call. What does it used for?</summary><br><b>

[Unix pipe implementation](https://toroid.org/unix-pipe-implementation)

"Pipes provide a unidirectional interprocess communication channel. A pipe has a read end and a write end. Data written to the write end of a pipe can be read from the read end of the pipe.
A pipe is created using pipe(2), which returns two file descriptors, one referring to the read end of the pipe, the other referring to the write end."
</b></details>

<details>
<summary>What happens when you execute <code>ls -l</code>?</summary><br><b>

* Shell reads the input using getline() which reads the input file stream and stores into a buffer as a string
* The buffer is broken down into tokens and stored in an array this way: {"ls", "-l", "NULL"}
* Shell checks if an expansion is required (in case of ls *.c)

* Once the program in memory, its execution starts. First by calling readdir()

Notes:

* getline() originates in GNU C library and used to read lines from input stream and stores those lines in the buffer
</b></details>

<details>
<summary>What happens when you execute <code>ls -l *.log</code>?</summary><br><b>
</b></details>

<details>
<summary>What readdir() system call does?</summary><br><b>


</b></details>

#### Linux Filesystem & Files

<details>
<summary>How to create a file of a certain size?</summary><br><b>

There are a couple of ways to do that:
  
  * dd if=/dev/urandom of=new_file.txt bs=2MB count=1
  * truncate -s 2M new_file.txt
  * fallocate -l 2097152 new_file.txt
</b></details>

<details>
<summary>Can you describe how processes are being created?</summary><br><b>
</b></details>

<details>
<summary>What does the following block do?:

```
open("/my/file") = 5
read(5, "file content")
```
</summary><br><b>

These system calls are reading the file <code>/my/file</code> and 5 is the file descriptor number.
</b></details>

<details>
<summary>Describe three different ways to remove a file (or its content)</summary><br><b>
</b></details>

<details>
<summary>What is the difference between a process and a thread?</summary><br><b>
</b></details>

<details>
<summary>You found there is a server with high CPU load but you didn't find a process with high CPU. How is that possible?</summary><br><b>
</b></details>

##### Linux Advanced - Networking

<details>
<summary>When you run <code>ip a</code> you see there is a device called 'lo'. What is it and why do we need it?</summary><br><b>
</b></details>

<details>
<summary>What the <code>traceroute</code> command does? How does it works?</summary><br><b>

Another common way to task this questions is "what part of the tcp header does traceroute modify?"
</b></details>

<details>
<summary>What is network bonding? What types are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>How to link two separate network namespaces so you can ping an interface on one namespace from the second one?</summary><br><b>
</b></details>

<details>
<summary>What are cgroups?</summary><br><b>
</b></details>

<details>
<summary>Explain Process Descriptor and Task Structure</summary><br><b>
</b></details>

<details>
<summary>What are the differences between threads and processes?</summary><br><b>
</b></details>

<details>
<summary>Explain Kernel Threads</summary><br><b>
</b></details>

<details>
<summary>What happens when socket system call is used?</summary><br><b>

This is a good article about the topic: https://ops.tips/blog/how-linux-creates-sockets
</b></details>

<details>
<summary>You executed a script and while still running, it got accidentally removed. Is it possible to restore the script while it's still running?</summary><br><b>
</b></details>

#### Memory

<details>
<summary>What is the difference between MemFree and MemAvailable in /proc/meminfo?</summary><br><b>

MemFree - The amount of unused physical RAM in your system
MemAvailable - The amount of available memory for new workloads (without pushing system to use swap) based on MemFree, Active(file), Inactive(file), and SReclaimable.
</b></details>

#### Distribution

<details>
<summary>What is a Linux distribution?</summary><br><b>
</b></details>

<details>
<summary>What Linux distributions are you familiar with? List at least four?</summary><br><b>
</b></details>

<details>
<summary>What are the components of a Linux distribution?</summary><br><b>

* Kernel
* Utilities
* Services
* Software/Packages Management
</b></details>

#### Linux Advanced - Misc

<details>
<summary>Wildcards are implemented on user or kernel space?</summary><br><b>
</b></details>

<details>
<summary>Why there are different sections in man? What is the difference between the sections?</summary><br><b>
</b></details>

## Operating System

<a name="operating-system-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is an operating system?</summary><br><b>

There are many ways to answer that. For those who look for simplicity, the book "Operating Systems: Three Easy Pieces" offers nice version:

"responsible for making it easy to run programs (even allowing you to seemingly run many at the same time), allowing programs to share memory, enabling programs to interact with devices, and other fun stuff like that"
</b></details>

<details>
<summary>What is POSIX?</summary><br><b>
</b></details>

#### Processes

<details>
<summary>Can you explain what is a process?</summary><br><b>

A process is a running program. A program is one or more instructions and the program (or process) is executed by the operating system.
</b></details>

<details>
<summary>If you had to design an API for processes in an operating system, what would this API look like?</summary><br><b>

It would support the following:

* Create - allow to create new processes 
* Delete - allow to remove/destroy processes
* State - allow to check the state of the process, whether it's running, stopped, waiting, etc.
* Stop - allow to stop a running process
</b></details>

<details>
<summary>How a process is created?</summary><br><b>

* The OS is reading program's code and any additional relevant data
* Program's bytes are loaded into the memory or more specifically, into the address space of the process.
* Memory is allocated for program's stack (aka run-time stack). The stack also initialized by the OS with data like argv, argc and parameters to main()
* Memory is allocated for program's heap which is required for data structures like linked lists and hash tables
* I/O initialization tasks like in Unix/Linux based systems where each process has 3 file descriptors (input, output and error)
* OS is running the program, strarting from main()

Note: The loading of the program's code into the memory done lazily which means the OS loads only partial relevant pieces required for the process to run and not the entire code.
</b></details>

<details>
<summary>True or False? The loading of the program into the memory is done eagerly (all at once)</summary><br><b>

False. It was true in the past but today's operating systems perform lazy loading which means only the relevant pieces required for the process to run are loaded first.
</b></details>

<details>
<summary>What are different states of a process?</summary><br><b>

* Running - it's executing instructions
* Ready - it's ready to run but for different reasons it's on hold
* Blocked - it's waiting for some operation to complete. For example I/O disk request
</b></details>

#### Concurrency

<details>
<summary>Explain what is Semaphore and what its role in operating systems</summary><br><b>
</b></details>

#### Memory

<details>
<summary>What is cache? What is buffer?</summary><br><b>

Buffer: Reserved place in RAM which is used to hold data for temporary purposes
Cache: Cache is usually used when processes reading and writing to the disk to make the process faster by making similar data used by different programs easily accessible.
</b></details>

## Virtualization

<a name="virtualization-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain what is Virtualization</summary><br><b>
</b></details>

<details>
<summary>What is "time sharing"?</summary><br><b>

Even when using a system with one physical CPU, it's possible to allow multiple users to work on it and run programs. This is possible with time sharing where computing resources are shared in a way it seems to the user the system has multiple CPUs but in fact it's simply one CPU shared by applying multiprogramming and multi-tasking.
</b></details>

<details>
<summary>What is "space sharing"?</summary><br><b>

Somewhat the opposite of time sharing. While in time sharing a resource is used for a while by one entity and then the same resource can be used by another resource, in space sharing the space is shared by multiple entities but in a way it's not being transfered between them.<br>
It's used by one entity until this entity decides to get rid of it. Take for example storage. In storage, a file is your until you decide to delete it.
</b></details>

## Ansible

<a name="ansible-beginner"></a>
#### :baby: Beginner

<details>
<summary>Describe each of the following components in Ansible, including the relationship between them:

  * Task
  * Module
  * Play
  * Playbook
  * Role</summary><br><b>

Task – a call to a specific Ansible module
Module – the actual unit of code executed by Ansible on your own host or a remote host. Modules are indexed by category (database, file, network, …) and also referred to as task plugins.

Play – One or more tasks executed on a given host(s)

Playbook – One or more plays. Each play can be executed on the same or different hosts

Role – Ansible roles allows you to group resources based on certain functionality/service such that they can be easily reused. In a role, you have directories for variables, defaults, files, templates, handlers, tasks, and metadata. You can then use the role by simply specifying it in your playbook.
</b></details>

<details>
<summary>How Ansible is different from other Automation tools?</summary><br><b>

Ansible is:

* Agentless
* Minimal run requirements (Python & SSH) and simple to use
* Default mode is "push" (it supports also pull)
* Focus on simpleness and ease-of-use
</b></details>

<details>
<summary>What kind of automation you wouldn't do with Ansible and why?</summary><br><b>

While it's possible to provision resources with Ansible it might not be the best choice for doing so as Ansible doesn't
save state by default. So a task that creates 5 instances for example, when executed again will create additional 5 instances (unless
additional check is implemented).
</b></details>

<details>
<summary>What is an inventory file and how do you define one?</summary><br><b>

An inventory file defines hosts and/or groups of hosts on which Ansible tasks executed upon.

An example of inventory file:

```
192.168.1.2
192.168.1.3
192.168.1.4

[web_servers]
190.40.2.20
190.40.2.21
190.40.2.22
```
</b></details>

<details>
<summary>What is a dynamic inventory file? When you would use one?</summary><br><br>

A dynamic inventory file tracks hosts from one or more sources like cloud providers and CMDB systems.

You should use one when using external sources and especially when the hosts in your environment are being automatically<br>
spun up and shut down, without you tracking every change in these sources.
</b></details>

<details>
<summary>How do you list all modules and how can you see details on a specific module?</summary><br><br>

1. Ansible online docs
2. `ansible-doc -l` for list of modules and `ansible [module_name]` for detailed information on a specific module
</b></details>

<details>
<summary>Write a task to create the directory ‘/tmp/new_directory’</summary><br><b>

```
- name: Create a new directory
  file:
    path: "/tmp/new_directory"
    state: directory
```
</b></details>

<details>
<summary>You want to run Ansible playbook only on specific minor version of your OS, how would you achieve that?</summary><br><b>
</b></details>

<details>
<summary>What the "become" directive used for in Ansible?</summary><br><b>
</b></details>

<details>
<summary>What are facts? How to see all the facts of a certain host?</summary><br><b>
</b></details>

<details>
<summary>What would be the result of the following play?</summary><br><b>

```
---
- name: Print information about my host
  hosts: localhost
  gather_facts: 'no'                                                                                                                                                                           
  tasks:
      - name: Print hostname
        debug:
            msg: "It's me, {{ ansible_hostname }}"
```

When given a written code, always inspect it thoroughly. If your answer is “this will fail” then you are right. We are using a fact (ansible_hostname), which is a gathered piece of information from the host we are running on. But in this case, we disabled facts gathering (gather_facts: no) so the variable would be undefined which will result in failure.
</b></details>

<details>
<summary>What would be the result of running the following task? How to fix it?

```
- hosts: localhost
  tasks:
      - name: Install zlib
        package:
          name: zlib
          state: present
```
</summary><br><b>
</b></details>

<details>
<summary>Which Ansible best practices are you familiar with?. Name at least three</summary><br><b>
</b></details>

<details>
<summary>Explain the directory layout of an Ansible role</summary><br><b>
</b></details>

<details>
<summary>What 'blocks' are used for in Ansible?</summary><br><b>
</b></details>

<details>
<summary>How do you handle errors in Ansible?</summary><br><b>
</b></details>

<details>
<summary>You would like to run a certain command if a task fails. How would you achieve that?</summary><br><b>
</b></details>

<details>
<summary>Write a playbook to install ‘zlib’ and ‘vim’ on all hosts if the file ‘/tmp/mario’ exists on the system.</summary><br><b>

```
---
- hosts: all
  vars:
      mario_file: /tmp/mario
      package_list:
          - 'zlib' 
          - 'vim'
  tasks:
      - name: Check for mario file
        stat:
            path: "{{ mario_file }}"
        register: mario_f

      - name: Install zlib and vim if mario file exists
        become: "yes"
        package:
            name: "{{ item }}"
            state: present
        with_items: "{{ package_list }}"
        when: mario_f.stat.exists
```
</b></details>

<details>
<summary>Write a single task that verifies all the files in files_list variable exist on the host</summary><br><b>

```
- name: Ensure all files exist
  assert:
    that:
      - item.stat.exists
  loop: "{{ files_list }}"
```
</b></details>

<details>
<summary>Write a playbook to deploy the file ‘/tmp/system_info’ on all hosts except for controllers group, with the following content</summary><br><b>

  ```
  I'm <HOSTNAME> and my operating system is <OS>
  ```

  Replace <HOSTNAME> and  <OS> with the actual data for the specific host you are running on

The playbook to deploy the system_info file

```
--- 
- name: Deploy /tmp/system_info file
  hosts: all:!controllers
  tasks: 
      - name: Deploy /tmp/system_info
        template:
            src: system_info.j2 
            dest: /tmp/system_info
```

The content of the system_info.j2 template

```
# {{ ansible_managed }}
I'm {{ ansible_hostname }} and my operating system is {{ ansible_distribution }
```
</b></details>

<details>
<summary>The variable 'whoami' defined in the following places:

  * role defaults -> whoami: mario
  * extra vars (variables you pass to Ansible CLI with -e) -> whoami: toad
  * host facts -> whoami: luigi
  * inventory variables (doesn’t matter which type) -> whoami: browser

According to variable precedence, which one will be used?</summary><br><b>

The right answer is ‘toad’.

Variable precedence is about how variables override each other when they set in different locations. If you didn’t experience it so far I’m sure at some point you will, which makes it a useful topic to be aware of.

In the context of our question, the order will be extra vars (always override any other variable) -> host facts -> inventory variables -> role defaults (the weakest).

A full list can be found at the link above. Also, note there is a significant difference between Ansible 1.x and 2.x.
</b></details>

<details>
<summary>For each of the following statements determine if it's true or false:

  * A module is a collection of tasks
  * It’s better to use shell or command instead of a specific module
  * Host facts override play variables
  * A role might include the following: vars, meta, and handlers
  * Dynamic inventory is generated by extracting information from external sources
  * It’s a best practice to use indention of 2 spaces instead of 4
  * ‘notify’ used to trigger handlers
  * This “hosts: all:!controllers” means ‘run only on controllers group hosts</summary><br><b>
</b></details>

<details>
<summary>What is ansible-pull? How is it different from how ansible-playbook works?</summary><br><b>
</b></details>

<details>
<summary>What is Ansible Vault?</summary><br><b>
</b></details>

<details>
<summary>Demonstrate each of the following with Ansible:

  * Conditionals
  * Loops
</summary><br><b>
</b></details>

<a name="ansible-advanced"></a>
#### :star: Advanced

<details>
<summary>What are filters? Do you have experience with writing filters?</summary><br><b>
</b></details>

<details>
<summary>Write a filter to capitalize a string</summary><br><b>

```
def cap(self, string):
    return string.capitalize()
```
</b></details>

<details>
<summary>You would like to run a task only if previous task changed anything. How would you achieve that?</summary><br><b>
</b></details>

<details>
<summary>What are callback plugins? What can you achieve by using callback plugins?</summary><br><b>
</b></details>

<details>
<summary>File '/tmp/exercise' includes the following content

```
Goku = 9001
Vegeta = 5200
Trunks = 6000
Gotenks = 32
```

With one task, switch the content to:

```
Goku = 9001
Vegeta = 250
Trunks = 40
Gotenks = 32
```
</summary><br><b>

```
- name: Change saiyans levels
  lineinfile:
    dest: /tmp/exercise
    regexp: "{{ item.regexp }}"
    line: "{{ item.line }}"
  with_items:
    - { regexp: '^Vegeta', line: 'Vegeta = 250' }
    - { regexp: '^Trunks', line: 'Trunks = 40' }
    ...
```
</b></details>

#### Ansible Testing

<details>
<summary>How do you test your Ansible based projects?</summary><br><b>
</b></details>

<details>
<summary>What is Molecule? How does it works?</summary><br><b>
</b></details>

<details>
<summary>You run Ansibe tests and you get "idempotence test failed". What does it mean? Why idempotence is important?</summary><br><b>
</b></details>

## Terraform

<a name="terraform-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain what Terraform is and how does it works</summary><br><b>

Read [here](https://www.terraform.io/intro/index.html#what-is-terraform-)
</b></details>

<details>
<summary>What benefits infrastructure-as-code has?</summary><br><b>

- fully automated process of provisioning, modifying and deleting your infrastructure
- version control for your infrastructure which allows you to quickly rollback to previous versions
- validate infrastructure quality and stability with automated tests and code reviews
- makes infrastructure tasks less repetitive
</b></details>

<details>
<summary>Why Terraform and not other technologies? (e.g. Ansible, Puppet, CloufFormation)</summary><br><b>

A common *wrong* answer is to say that Ansible and Puppet are configuration management tools
and Terraform is a provisioning tool. While technically true, it doesn't mean Ansible and Puppet can't
be used for provisioning infrastructure. Also, it doesn't explain why Terraform should be used over
CloudFormation if at all.

The benefits of Terraform over the other tools:

  * It follows the immutable infrastructure approach which has benefits like avoiding a configuration drift over time
  * Ansible and Puppet are more procedural (you mention what to execute in each step) and Terraform is declarative since you describe the overall desired state and not per resource or task. You can give the example of going from 1 to 2 servers in each tool. In Terraform you specify 2, in Ansible and puppet you have to only provision 1 additional server so you need to explicitly make sure you provision only another one server.
</b></details>

<details>
<summary>Explain what is "Terraform configuration"</summary><br><b>
A configuration is a root module along with a tree of child modules that are called as dependencies from the root module.
</b></details>

<details>
<summary>What is HCL?</summary><br><b>
HCL stands for Hashicorp Configuration Language. It is the language Hashicorp made to use as the configuration language for a number of its tools, including terraform.
</b></details>

<details>
<summary>Explain each of the following:

  * Provider
  * Resource 
  * Provisioner 
</summary><br><b>
  * Provider is any cloud based technology - github, aws, postgresql etc - which one can make an API call to with its unique terraform provider binary to provision available services and components.<br>  
  * Resources are the services and components you provision on these platforms.<br>
  * Provisioner in terraform's lingo specifically refers to configuration tools like ansible or salt-stack which are used in combination with terraform to orchestrate a system.
</b></details>

<details>
<summary>What <code>terraform.tfstate</code> file is used for?</summary><br><b> 

It keeps track of the IDs of created resources so that Terraform knows what it is managing.
</b></details>

<details>
<summary>Explain what the following commands do:

  * <code>terraform init</code> 
  * <code>terraform plan</code>	
  * <code>terraform validate</code> 
  * <code>terraform apply</code> 
</summary><br><b>

<code>terraform init</code> scans your code to figure which providers are you using and download them.
<code>terraform plan</code> will let you see what terraform is about to do before actually doing it.
<code>terraform validate</code> checks if configuration is syntactically valid and internally consistent within a directory.
<code>terraform apply</code> will provision the resources specified in the .tf files.
</b></details>

<details>
<summary>How to write down a variable which changes by an external source or during <code>terraform apply</code>?</summary><br><b>

You use it this way: <code>variable “my_var” {}</code>
</b></details>

<details>
<summary>Give an example of several Terraform best practices</summary><br><b>
</b></details>

<details>
<summary>Explain how implicit and explicit dependencies work in Terraform</summary><br><b>
</b></details>

<details>
<summary>What is <code>local-exec</code> and <code>remote-exec</code> in the context of provisioners?</summary><br><b>
</b></details>

<details>
<summary>What is a "tainted resource"?</summary><br><b>

It's a resource which was successfully created but failed during provisioning. Terraform will fail and mark this resource as "tainted".
</b></details>

<details>
<summary>What <code>terraform taint</code> does?</summary><br><b>
<code>terraform taint resource.id</code> manually marks the resource as tainted in the state file. So when you run <code>terraform apply</code> the next time, the resource will be destroyed and recreated.
</b></details>

<details>
<summary>What types of variables are supported in Terraform?</summary><br><b>

string
number
bool
list(<TYPE>)
set(<TYPE>)
map(<TYPE>)
object({<ATTR_NAME> = <TYPE>, ... })
tuple([<TYPE>, ...])
</b></details>

<details>
<summary>What is a data source? In what scenarios for example would need to use it?</summary><br><b>
Data sources lookup or compute values that can be used elsewhere in terraform configuration.

There are quite a few cases you might need to use them:
* you want to reference resources not managed through terraform
* you want to reference resources managed by a different terraform module
* you want to cleanly compute a value with typechecking, such as with <code>aws_iam_policy_document</code>
</b></details>

<details>
<summary>What are output variables and what <code>terraform output</code> does?</summary><br><b>
Output variables are named values that are sourced from the attributes of a module. They are stored in terraform state, and can be used by other modules through <code>remote_state</code>
</b></details>

<details>
<summary>Explain Modules</summary>
</b></details>

<details>
<summary>What is the Terraform Registry?</summary><br><b>
</b></details>

<details>
<summary>Explain <code>remote-exec</code> and <code>local-exec</code></summary><br><b>
</b></details>


<a name="terraform-advanced"></a>
#### :star: Advanced

<details>
<summary>Explain "Remote State". When would you use it and how?</summary><br><b>
  Terraform generates a `terraform.tfstate` json file that describes components/service provisioned on the specified provider. Remote  
  State stores this file in a remote storage media to enable collaboration amongst team.
</b></details>

<details>
<summary>Explain "State Locking"</summary><br><b>
  State locking is a mechanism that blocks an operations against a specific state file from multiple callers so as to avoid conflicting operations from different team members. Once the first caller's operation's lock is released the other team member may go ahead to   
  carryout his own operation. Nevertheless Terraform will first check the state file to see if the desired resource already exist and 
  if not it goes ahead to create it.
</b></details>

<details>
<summary>What is the "Random" provider? What is it used for</summary><br><b>
 The random provider aids in generating numeric or alphabetic characters to use as a prefix or suffix for a desired named identifier.
</b></details>

<details>
<summary>How do you test a terraform module?</summary><br><b>
  Many examples are acceptable, but the most common answer would likely to be using the tool <code>terratest</code>, and to test that a module can be initialized, can create resources, and can destroy those resources cleanly.
</b></details>

<details>
<summary>Aside from <code>.tfvars</code> files or CLI arguments, how can you inject dependencies from other modules?</summary><br><b>
  The built-in terraform way would be to use <code>remote-state</code> to lookup the outputs from other modules.
  It is also common in the community to use a tool called <code>terragrunt</code> to explicitly inject variables between modules.
</b></details>

## Docker

<a name="docker-beginner"></a>

#### :baby: beginner

<details>
<summary>What is Docker? What are you using it for?</summary><br><b>
Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.
</b></details>

<details>
<summary>How containers are different from VMs?</summary><br><b>

The primary difference between containers and VMs is that containers allow you to virtualize
multiple workloads on the operating system while in the case of VMs the hardware is being virtualized to
run multiple machines each with its own OS.

* Containers don't require an entire guest operating system as VMs
* It's usually takes a few seconds to set up a container as opposed to VMs which can take minutes or at least more time than containers as there is an entire OS to boot and initialize as opposed to container where you mainly lunch the app itself
* Docker is one of the technologies allowing you to manage containers - run multiple containers on a host, move containers between hosts, etc.
</b></details>

<details>
<summary>In which scenarios would you use containers and in which you would prefer to use VMs?</summary><br><b>

You should choose VMs when:
  * you need run an application which requires all the resources and functionalities of an OS
  * you need full isolation and security

You should choose containers when:
  * you need a lightweight solution
  * Running multiple versions or instances of a single application
</b></details>

<details>
<summary>Explain Docker architecture</summary><br><b>
</b></details>

<details>
<summary>Describe in detail what happens when you run `docker run hello-world`?</summary><br><b>

Docker CLI passes your request to Docker daemon.
Docker daemon downloads the image from Docker Hub
Docker daemon creates a new container by using the image it downloaded
Docker daemon redirects output from container to Docker CLI which redirects it to the standard output
</b></details>

<details>
<summary>How do you run a container?</summary><br><b>
	
docker run
</b></details>

<details>
<summary>What `docker commit` does?. When will you use it?</summary><br><b>
	
Create a new image from a container’s changes
</b></details>

<details>
<summary>How would you transfer data from one container into another?</summary><br><b>
</b></details>

<details>
<summary>What happens to data of the container when a container exists?</summary><br><b>
</b></details>

<details>
<summary>Explain what each of the following commands do:

  * docker run
  * docker rm
  * docker ps
  * docker pull
  * docker build
  * docker commit</summary><br><b>
</b></details>

<details>
<summary>How do you remove old, non running, containers?</summary><br><b>
	
1. To remove one or more Docker images use the docker container rm command followed by the ID of the containers you want to remove.
2. The docker system prune command will remove all stopped containers, all dangling images, and all unused networks
3. docker rm $(docker ps -a -q) - This command will delete all stopped containers. The command docker ps -a -q will return all existing container IDs and pass them to the rm command which will delete them. Any running containers will not be deleted.
</b></details>

##### Dockerfile

<details>
<summary>What is Dockerfile</summary><br><b>
	
Docker can build images automatically by reading the instructions from a Dockerfile. A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image.
</b></details>

<details>
<summary>What is the difference between ADD and COPY in Dockerfile?</summary><br><b>
	
COPY takes in a src and destination. It only lets you copy in a local file or directory from your host (the machine building the Docker image) into the Docker image itself.
ADD lets you do that too, but it also supports 2 other sources. First, you can use a URL instead of a local file / directory. Secondly, you can extract a tar file from the source directly into the destination.
Although ADD and COPY are functionally similar, generally speaking, COPY is preferred. That’s because it’s more transparent than ADD. COPY only supports the basic copying of local files into the container, while ADD has some features (like local-only tar extraction and remote URL support) that are not immediately obvious.
</b></details>

<details>
<summary>What is the difference between CMD and RUN in Dockerfile?</summary><br><b>
	
RUN lets you execute commands inside of your Docker image. These commands get executed once at build time and get written into your Docker image as a new layer.
CMD is the command the container executes by default when you launch the built image. A Dockerfile can only have one CMD.
You could say that CMD is a Docker run-time operation, meaning it’s not something that gets executed at build time. It happens when you run an image. A running image is called a container.
</b></details>

<details>
<summary>Do you perform any checks or testing related to your Dockerfile?</summary><br><b>

A common answer to this is to use [hadolint](https://github.com/hadolint/hadolint) project which is a linter based on Dockerfile best practices.
</b></details>

<details>
<summary>Explain what is Docker compose and what is it used for</summary><br><b>
	
Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.

For example, you can use it to set up ELK stack where the services are: elasticsearch, logstash and kibana. Each running in its own container.
</b></details>

<details>
<summary>Describe the process of using Docker Compose</summary><br><br>

* Define the services you would like to run together in a docker-compose.yml file
* Run `docker-compose up` to run the services
</b></details>

<details>
<summary>Explain Docker interlock</summary><br><b>
</b></details>

<details>
<summary>Where can you store Docker images?</summary><br><b>
</b></details>

<details>
<summary>What is Docker Hub?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between Docker Hub and Docker cloud?</summary><br><b>

Docker Hub is a native Docker registry service which allows you to run pull
and push commands to install and deploy Docker images from the Docker Hub.

Docker Cloud is built on top of the Docker Hub so Docker Cloud provides
you with more options/features compared to Docker Hub. One example is
Swarm management which means you can create new swarms in Docker Cloud.
</b></details>

<details>
<summary>What is Docker Repository?</summary><br><b>
</b></details>

<details>
<summary>Explain image layers</summary><br><b>
	
A Docker image is built up from a series of layers. Each layer represents an instruction in the image’s Dockerfile. Each layer except the very last one is read-only.
Each layer is only a set of differences from the layer before it. The layers are stacked on top of each other. When you create a new container, you add a new writable layer on top of the underlying layers. This layer is often called the “container layer”. All changes made to the running container, such as writing new files, modifying existing files, and deleting files, are written to this thin writable container layer. 
The major difference between a container and an image is the top writable layer. All writes to the container that add new or modify existing data are stored in this writable layer. When the container is deleted, the writable layer is also deleted. The underlying image remains unchanged.
Because each container has its own writable container layer, and all changes are stored in this container layer, multiple containers can share access to the same underlying image and yet have their own data state.
</b></details>

<a name="docker-advanced"></a>
#### :star: Advanced

<details>
<summary>What best practices are you familiar related to working with containers?</summary><br><b>
</b></details>

<details>
<summary>How do you manage persistent storage in Docker?</summary><br><b>
</b></details>

<details>
<summary>How can you connect from the inside of your container to the localhost of your host, where the container runs?</summary><br><b>
</b></details>

<details>
<summary>How do you copy files from Docker container to the host and vice versa?</summary><br><b>
</b></details>

## Kubernetes

<a name="kubernetes"></a>

<details>
<summary>What is Kubernetes? Why organizations are using it?</summary><br><b>

Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.

To understand what Kubernetes is good for, let's look at some examples:

* You would like to run a certain application in a container on multiple different locations. Sure, if it's 2-3 servers/locations, you can do it by yourself but it can be challenging to scale it up to additional multiple location.

* Performing updates and changes across hundreds of containers

* Handle cases where the current load requires to scale up (or down)
</b></details>

<details>
<summary>Describe the architecture of Kubernetes</summary><br><b>
</b></details>

<details>
<summary>What is a Kubernetes Cluster?</summary><br><b>

A cluster consists of a Master (which coordinates the cluster) and Nodes where the applications are running.
</b></details>

<details>
<summary>Describe in detail what the following command does <code>kubectl create deployment kubernetes-httpd --image=httpd</code></summary><br><b>
</b></details>

<details>
<summary>What the Master is responsible for?</summary><br><b>

The master coordinates all the workflows in the cluster:

* Scheduling applications
* Managing desired state
* Rolling out new updates
</b></details>

<details>
<summary>What is a Node?</summary><br><b>

A node is a virtual machine or a physical server that serves as a worker for running the applications.
It's recommended to have at least 3 nodes in Kubernetes production environment.
</b></details>

<details>
<summary>Explain what is Kubelet</summary><br><b>

Kubelet is an agent running on each node and responsible for node communication with the master.
</b></details>

<details>
<summary>What is Minikube?</summary><br><b>

Minikube is a lightweight Kubernetes implementation. It create a local virtual machine and deploys a simple (single node) cluster.
</b></details>

<details>
<summary>Explain what is a Kubernetes pod</summary><br><b>
</b></details>

<details>
<summary>True or False? A pod can manage multiple containers</summary><br><b>
</b></details>

<details>
<summary>How do you monitor your Kubernetes?</summary><br><b>
</b></details>

<details>
<summary>You suspect one of the pods is having issues, what do you do?</summary><br><b>

Start by inspecting the pods status. we can use the command `kubectl get pods` (--all-namespaces for pods in system namespace)<br>

If we see "Error" status, we can keep debugging by running the command `kubectl describe pod [name]`. In case we still don't see anything useful we can try stern for log tailing.<br>

In case we find out there was a temporary issue with the pod or the system, we can try restarting the pod with the following `kubectl scale deployment [name] --replicas=0`<br>

Setting the replicas to 0 will shut down the process. Now start it with `kubectl scale deployment [name] --replicas=1`
</b></details>

<details>
<summary>What the Kubernetes Scheduler does?</summary><br><b>
</b></details>

<details>
<summary>What happens to running pods if if you stop Kubelet on the worker nodes?</summary><br><b>
</b></details>

<details>
<summary>Describe how roll-back works</summary><br><b>
</b></details>

<details>
<summary>What is the control loop? How it works?</summary><br><b>

Explained [here](https://www.youtube.com/watch?v=i9V4oCa5f9I)
</b></details>

#### Kubernetes Operators

<details>
<summary>What is an Operator?</summary><br><b>

Explained [here](https://coreos.com/operators)

"An Operator is a method of packaging, deploying and managing a Kubernetes application"
</b></details>

<details>
<summary>What components the Operator consists of?</summary><br><b>

1. CRD (custom resource definition)
2. Controller - Custom control loop which runs against the CRD
</b></details>

<details>
<summary>What is the Operator Framework?</summary><br><b>

open source toolkit used to manage k8s native applications, called operators, in an automated and efficient way.
</b></details>

<details>
<summary>What components the Operator Framework consists of??</summary><br><b>

1. Operator SDK - allows developers to build operators
2. Operator Lifecycle Manager - helps to install, update and generally manage the lifecycle of all operators
3. Operator Metering - Enables usage reporting for operators that provide specialized services
</b></details>


<details>
<summary>Describe in detail what is the Operator Lifecycle Manager</summary><br><b>

It's part of the Operator Framework, used for managing the lifecycle of operators. It basically extends Kubernetes so a user can use a declarative way to manage operators (installation, upgrade, ...).
</b></details>

<details>
<summary>What openshift-operator-lifecycle-manager namespace includes?</summary><br><b>

It includes:

  * catalog-operator - Resolving and installing ClusterServiceVersions the resource they specify.
  * olm-operator - Deploys applications defined by ClusterServiceVersion resource
</b></details>

#### Kubernetes Commands

<details>
<summary>What is kubectl?</summary><br><b>
</b></details>

<details>
<summary>How do you:

  * Check the cluster status?
  * Check the status of the nodes?</summary><br><b>
</b></details>

<details>
<summary>What the following commands do?

  * kubectl get nodes
  * kubectl </summary><br><b>
</b></details>

<details>
<summary>What is kubconfig? What do you use it for?</summary><br><b>
</b></details>

#### Submariner

<details>
<summary>Explain what is Submariner and what is it used for</summary><br><b>

"Submariner enables direct networking between pods and services in different Kubernetes clusters, either on premise or in the cloud."

You can learn more [here](https://submariner-io.github.io)
</b></details>

<details>
<summary>What each of the following components does?:

  * Lighthouse
  * Broker
  * Gateway Engine
  * Route Agent</summary><br><b>
</b></details>

## Coding

<a name="coding-beginner"></a>
#### :baby: Beginner

<details>
<summary>What programming language do you prefer to use for DevOps related tasks? Why specifically this one?</summary><br><b>
</b></details>

<details>
<summary>Explain expressions and statements</summary><br><b>

An expression is anything that results in a value (even if the value is None). Basically, any sequence of literals so, you can say that a string, integer, list, ... are all expressions.

Statements are instructions executed by the interpreter like variable assignments, for loops and conditionals (if-else).
</b></details>

<details>
<summary>What is Object Oriented Programming? Why is it important?</summary><br><b>
</b></details>

<details>
<summary>Explain Composition</summary><br><b>
</b></details>

<details>
<summary>What is a compiler?</summary><br><b>
</b></details>

<details>
<summary>What is an interpreter?</summary><br><b>
</b></details>

<details>
<summary>Are you familiar with SOLID design principles?</summary><br><b>

SOLID design principles are about:

* Make it easier to extend the functionality of the system
* Make the code more readable and easier to maintain

SOLID is:

* Single Responsibility - A class should only have a single responsibility
* Open-Closed - An entity should be open for extension, but closed for modification. What this practically means is that you should extend functionality by adding a new code and not by modifying it. Your system should be separated into components so it can be easily extended without breaking everything.
* Liskov Substitution - Any derived class should be able to substitute the its parent without altering its corrections. Practically, every part of the code will get the expected result no matter which part is using it
* Interface segregation - A client should never depend on anything it doesn't uses 
* Dependency Inversion - High level modules should depend on abstractions, not low level modules
</b></details>

<details>
<summary>What are the four pillars of object oriented programming?</summary><br><b>
</b></details>

<details>
<summary>Explain recursion</summary><br><b>
</b></details>

<details>
<summary>Explain Inversion of Control</summary><br><b>
</b></details>

<details>
<summary>Explain Dependency Injection</summary><br><b>
</b></details>

<details>
<summary>Explain what are design patterns and describe three of them in detail</summary><br><b>
</b></details>

<details>
<summary>Explain big O notation</summary><br><b>
</b></details>

##### Common algorithms

<details>
<summary>Binary search:

  * How does it works?
  * Can you implement it? (in any language you prefer)
  * What is the average performance of the algorithm you wrote?</summary><br><b>

It's a search algorithm used with sorted arrays/lists to find a target value by dividing the array each iteration and comparing the middle value to the target value. If the middle value is smaller than target value, then the target value is searched in the right part of the divided array, else in the left side. This continues until the value is found (or the array divided max times) 

[python implementation](coding/python/binary_search.py)

The average performance of the above algorithm is O(log n). Best performance can be O(1) and worst O(log n).
</b></details>

##### Code Review

<details>
<summary>What are your code-review best practices?</summary><br><b>
</b></details>

<details>
<summary>Do you agree/disagree with each of the following statements and why?:

  * The commit message is not important. When reviewing a change/patch one should focus on the actual change
  * You shouldn't test your code before submitting it. This is what CI/CD exists for.</summary><br><b>
</b></details>

#### Strings

<details>
<summary>In any language you want, write a function to determine if a given string is a palindrome</summary><br><b>
</b></details>

<details>
<summary>In any language you want, write a function to determine if two strings are Anagrams </summary><br><b>
</b></details>

#### Integers

<details>
<summary>In any language you would like, print the numbers from 1 to a given integer. For example for input: 5, the output is: 12345</summary><br><b>
</b></details>

#### Time Complexity

<details>
<summary>Describe what would be the time complexity of the operations <code>access</code>, <code>search</code> <code>insert</code> and <code>remove</code> for the following data structures:</summary><br><b>

  * Stack
  * Queue
  * Linked List
  * Binary Search Tree
</b></details>

<details>
<summary>What is the complexity for the best, worst and average cases of each of the following algorithms?:

  * Quick sort
  * Merge sort
  * Bucket Sort
  * Radix Sort</summary><br><b>
</b></details>

#### Data Structures & Types

<details>
<summary>Implement Stack in any language you would like</summary><br><b>
</b></details>

<details>
<summary>Implement Hash table in any language you would like</summary><br><b>
</b></details>

<details>
<summary>What is Integer Overflow? How is it handled?</summary><br><b>
</b></details>

<a name="coding-advanced"></a>
#### :star: Advanced

<details>
<summary>Name 3 design patterns. Do you know how to implement (= provide an example) these design pattern in any language you'll choose?</summary><br><b>
</b></details>

<details>
<summary>Given an array/list of integers, find 3 integers which are adding up to 0 (in any language you would like)</summary><br><b>

```
def find_triplets_sum_to_zero(li):
    li = sorted(li)
    for i, val in enumerate(li):
        low, up = 0, len(li)-1
        while low < i < up:
            tmp = var + li[low] + li[up]
            if tmp > 0:
                up -= 1
            elif tmp < 0:
                low += 1
            else:
                yield li[low], val, li[up]
                low += 1
                up -= 1
```
</b></details>

## Python

<a name="python-beginner"></a>
#### :baby: Beginner

<details>
<summary>What are some characteristics of the Python programming language?</summary><br><b>

```
1. It is a high level general purpose programming language created in 1991 by Guido Van Rosum.
2. The language is interpreted, being the CPython (Written in C) the most used/maintained implementation.
3. It is strongly typed. The typing discipline is duck typing and gradual.
4. Python focuses on readability and makes use of whitespaces/identation instead of brackets { }
5. The python package manager is called PIP "pip installs packages", having more than 200.000 available packages.
6. Python comes with pip installed and a big standard library that offers the programmer many precooked solutions.
7. In python **Everything** is an object.

There are many other characteristics but these are the main ones that every python programmer should know.
```
</b></details>

<details>
<summary>What built-in types Python has?</summary><br><b>

    List
    Dictionary
    Set
    Numbers (int, float, ...)
    String
    Bool
    Tuple
    Frozenset
</b></details>

<details>
<summary>What is mutability? Which of the built-in types in Python are mutable? How can you show that a certain data type is mutable?</summary><br><b>

Mutability determines whether you can modify an object of specific type.

The mutable data types are:

    List
    Dictionary
    Set
    
The immutable data types are:

    Numbers (int, float, ...)
    String
    Bool
    Tuple
    Frozenset

You can usually use the function hash() to check an object mutability. If an object is hashable, it is immutable (although this does not always work as intended as user defined objects might be mutable and hashable).
</b></details>

<details>
<summary>What is the result of each of the following?

  * 1 > 2
  * 'b' > 'a'
  * 1 == 'one'
  * 2 > 'one'</summary><br><b>

  * False
  * True
  * False
  * TypeError
</b></details>

<details>
<summary>What is the result of of each of the following?

  * "abc"*3
  * "abc"*2.5
  * "abc"*2.0
  * "abc"*True
  * "abc"*False</summary><br><b>

  * abcabcabc
  * TypeError
  * TypeError
  * "abc"
  * ""
</b></details>

<details>
<summary>What is the result of `bool("")`? What about `bool(" ")`?</summary><br><b>
</b></details>

<details>
<summary>What is the result of running <code>[] is not []</code>? explain the result</summary><br><b>

It evaluates to True.<br>
The reason is that the two created empty list are different objects. `x is y` only evaluates to true when x and y are the same object.
</b></details>

<details>
<summary>Improve the following code:

```
char = input("Insert a character: ")
if char == "a" or char == "y" or  char == "o" or char == "e" or char =="u" or char == "i":
    print("It's a vowel!")
```
</summary><br><b>

```
if lower(input("Insert a character: ")[0]) in "aieou": # Takes care of multiple characters and small/Capital cases
    print("It's a vowel!")
```
OR
```
char = input("Insert a character: ") # For readablity
if lower(char[0]) in "aieou": # Takes care of multiple characters and separate cases
    print("It's a vowel!")
```
</b></details>

<details>
<summary>How to define a function with Python?</summary><br><b>
</b></details>

<details>
<summary>In Python, functions are first-class objects. What does it mean?</summary><br><b>

In general, first class objects in programming languages are objects which can be assigned to variable, used as a return value and can be used as arguments or parameters.<br>
In python you can treat functions this way. Let's say we have the following function

```
def my_function():
    return 5
```

You can then assign a function to a variables like this `x = my_function` or you can return functions as return values like this `return my_function`
</b></details>


<details>
<summary>Explain inheritance and how to use it in Python</summary><br><b>

```
By definition inheritance is the mechanism where an object acts as a base of another object, retaining all its
properties.

So if Class B inherits from Class A, every characteristics from class A will be also available in class B.
Class A would be the 'Base class' and B class would be the 'derived class'.

This comes handy when you have several classes that share the same functionalities.

The basic syntax is:

class Base: pass

class Derived(Base): pass

A more forged example:

class Animal:
    def __init__(self):
        print("and I'm alive!")

    def eat(self, food):
        print("ñom ñom ñom", food)

class Human(Animal):
    def __init__(self, name):
        print('My name is ', name)
        super().__init__()

    def write_poem(self):
        print('Foo bar bar foo foo bar!')

class Dog(Animal):
    def __init__(self, name):
        print('My name is', name)
        super().__init__()

    def bark(self):
        print('woof woof')


michael = Human('Michael')
michael.eat('Spam')
michael.write_poem()

bruno = Dog('Bruno')
bruno.eat('bone')
bruno.bark()

>>> My name is  Michael
>>> and I'm alive!
>>> ñom ñom ñom Spam
>>> Foo bar bar foo foo bar!
>>> My name is Bruno
>>> and I'm alive!
>>> ñom ñom ñom bone
>>> woof woof

Calling super() calls the Base method, thus, calling super().__init__() we called the Animal __init__.

There is a more advanced python feature called MetaClasses that aid the programmer to directly control class creation.
```
</b></details>

<details>
<summary>Explain and demonstrate class attributes & instance attributes</summary><br><b>

In the following block of code `x` is a class attribute while `self.y` is a instance attribute

```
class MyClass(object):
    x = 1

    def __init__(self, y):
        self.y = y
```
</b></details>

<details>
<summary>What is an error? What is an exception? What types of exceptions are you familiar with?</summary><br><b>

```
#  Note that you generally don't need to know the compiling process but knowing where everything comes from
#  and giving complete answers shows that you truly know what you are talking about.

Generally, every compiling process have a two steps.
    - Analysis
    - Code Generation.
    
    Analysis can be broken into:
        1. Lexical analysis   (Tokenizes source code)
        2. Syntactic analysis (Check whether the tokens are legal or not, tldr, if syntax is correct)
           
               for i in 'foo'
                          ^
             SyntaxError: invalid syntax
        
        We missed ':'
        
        
        3. Semantic analysis  (Contextual analysis, legal syntax can still trigger errors, did you try to divide by 0,
          hash a mutable object or use an undeclared function?)
          
                 1/0
                ZeroDivisionError: division by zero
        
    These three analysis steps are the responsible for error handlings.
    
    The second step would be responsible for errors, mostly syntax errors, the most common error.
    The third step would be responsible for Exceptions.
    
    As we have seen, Exceptions are semantic errors, there are many builtin Exceptions:
        
        ImportError
        ValueError
        KeyError
        FileNotFoundError
        IndentationError
        IndexError
        ...
    
    You can also have user defined Exceptions that have to inherit from the `Exception` class, directly or indirectly.

    Basic example:
        
    class DividedBy2Error(Exception):
        def __init__(self, message):
            self.message = message
    
    
    def division(dividend,divisor):
        if divisor == 2:
            raise DividedBy2Error('I dont want you to divide by 2!')
        return dividend / divisor
    
    division(100, 2)
    
    >>> __main__.DividedBy2Error: I dont want you to divide by 2!
```
</b></details>

<details>
<summary>Explain Exception Handling and how to use it in Python</summary><br><b>
	
**Exceptions:** Errors detected during execution are called Exceptions.

**Handling Exception:** When an error occurs, or exception as we call it, Python will normally stop and generate an error message.</br> 
Exceptions can be handled using `try` and `except` statement in python.

**Example:** Following example asks the user for input until a valid integer has been entered. </br>
If user enter a non-integer value it will raise exception and using except it will catch that exception and ask the user to enter valid integer again.


```py
while True:
    try:
        a = int(input("please enter an integer value: "))
        break
    except ValueError:
        print("Ops! Please enter a valid integer value.")

```

For more details about errors and exceptions follow this [https://docs.python.org/3/tutorial/errors.html](https://docs.python.org/3/tutorial/errors.html)

</b></details>

#### Python Built-in functions

<details>
<summary>Explain the following built-in functions (their purpose + use case example):

  * repr 
  * any
  * all</summary><br><b>
</b></details>

<details>
<summary>What is the difference between repr function and str?</summary><br><b>
</b></details>

<details>
<summary>What _ is used for in Python?</summary><br><b>

1. Translation lookup in i18n
2. Hold the result of the last executed expression or statement in the interactive interpreter.
3. As a general purpose "throwaway" variable name. For example: x, y, _ = get_data() (x and y are used but since we don't care about third variable, we "threw it away").
</b></details>

<details>
<summary>Explain what is GIL</summary><br><b>
</b></details>

<details>
<summary>What is Lambda? How is it used?</summary><br><b>

A <code>lambda</code> expression is an 'anonymous' function, the difference from a normal defined function using the keyword `def`` is the syntax and usage.

The syntax is:

```lambda[parameters]: [expresion]```

**Examples:**

* A lambda function add 10 with any argument passed.

```py
x = lambda a: a + 10
print(x(10))
```

* An addition function

```py
addition = lambda x, y: x + y
print(addition(10, 20))
```

* Squaring function

```py
square = lambda x : x ** 2
print(square(5))
```
Generally it is considered a bad practice under PEP 8 to assign a lambda expresion, they are meant to be used as parameters and inside of other defined functions.

</b></details>

#### Properties

<details>
<summary>Are there private variables in Python? How would you make an attribute of a class, private?</summary><br><b>
</b></details>

<details>
<summary>Explain the following:

* getter
* setter
* deleter</summary><br><b>
</b></details>

<details>
<summary>Explain what is @property</summary><br><b>
</b></details>

<details>
<summary>How do you swap values between two variables?</summary><br><b>

```
x, y = y, x
```
</b></details>

<details>
<summary>Explain the following object's magic variables:

  * __dict__ 
</summary><br><b>
</b></details>

<details>
<summary>Write a function to return the sum of one or more numbers. The user will decide how many numbers to use</summary><br><b>

First you ask the user for the amount of numbers that will be use. Use a while loop that runs until amount_of_numbers becomes 0 through subtracting amount_of_numbers by one each loop. In the while loop you want ask the user for a number which will be added a variable each time the loop runs.

```
def return_sum():
	amount_of_numbers = int(input("How many numbers? "))
	total_sum = 0
	while amount_of_numbers != 0:
		num = int(input("Input a number. "))
		total_sum += num
		amount_of_numbers -= 1
	return total_sum

```
</b></details>

<details>
<summary>Print the average of [2, 5, 6]. It should be rounded to 3 decimal places</summary><br><b>

```
li = [2, 5, 6]
print("{0:.3f}".format(sum(li)/len(li)))
```
</b></details>

#### Python Lists

<details>
<summary>How to add the items of [1, 2, 3] to the list [4, 5, 6]?</summary><br><b>
x = [4, 5, 6]
x.extend([1, 2, 3])
</b></details>

<details>
<summary>How to remove the first 3 items from a list?</summary><br><b>

`my_list[0:3] = []`
</b></details>

<details>
<summary>How do you get the maximum and minimum values from a list? How to get the last item from a list?</summary><br><b>

```
Maximum: max(some_list)
Minimum: min(some_list)
Last item: some_list[-1]
```
</b></details>

<details>
<summary>How to get the top/biggest 3 items from a list?</summary><br><b>

```
sorted(some_list, reverse=True)[:3]
```

Or

```
some_list.sort(reverse=True)
some_list[:3]
```
</b></details>

<details>
<summary>How to sort list by the length of items?</summary><br><b>

```
sorted_li = sorted(li, key=len)
```

Or without creating a new list:

```
li.sort(key=len)
```
</b></details>

<details>
<summary>Do you know what is the difference between list.sort() and sorted(list)?</summary><br><b>

* sorted(list) will return a new list (original list doesn't change)
* list.sort() will return None but the list is change in-place

* sorted() works on any iterable (Dictionaries, Strings, ...)
* list.sort() is faster than sorted(list) in case of Lists
</b></details>

<details>
<summary>Convert every string to an integer: <code>[['1', '2', '3'], ['4', '5', '6']]</code></summary><br><b>

```
nested_li = [['1', '2', '3'], ['4', '5', '6']]
[[int(x) for x in li] for li in nested_li]
```
</b></details>

<details>
<summary>How to merge two sorted lists into one sorted list?</summary><br><b>

```
sorted(li1 + li2) 
```

Another way:

```
i, j = 0
merged_li = []

while i < len(li1) and j < len(li2):
    if li1[i] < li2[j]:
        merged_li.append(li1[i])
        i += 1
    else:
        merged_li.append(li2[j])
        j += 1

merged_li = merged_li + merged_li[i:] + merged_li[j:] 
```
</b></details>

<details>
<summary>How to check if all the elements in a given lists are unique? so [1, 2, 3] is unique but [1, 1, 2, 3] is not unique because 1 exists twice</summary><br><b>
</b>

There are many ways of solving this problem:<br>
<code># Note: :list and -> bool are just python typings, they are not needed for the correct execution of the algorithm. </code>

Taking advantage of sets and len:

```
def is_unique(l:list) -> bool:
    return len(set(l)) == len(l)
```

This one is can be seen used in other programming languages.

```
def is_unique2(l:list) -> bool:
    seen = []

    for i in l:
        if i in seen:
            return False
        seen.append(i)
    return True
```

Here we just count and make sure every element is just repeated once.

```
def is_unique3(l:list) -> bool:
    for i in l:
        if l.count(i) > 1:
            return False
    return True
```

This one might look more convulated but hey, one liners.

```
def is_unique4(l:list) -> bool:
    return all(map(lambda x: l.count(x) < 2, l))
```
</details>

<details>
<summary>You have the following function

```
def my_func(li = []):
    li.append("hmm")  
    print(li)
```

If we call it 3 times, what would be the result each call?
</summary><br><b>

```
['hmm']
['hmm', 'hmm']
['hmm', 'hmm', 'hmm']
```
</b></details>

<details>
<summary>How to iterate over a list in reverse order?</summary><br><b>

Method 1
```
for i in reversed(li):
    ...
```

Method 2
```
n = len(li) - 1
while n > 0:
    ...
    n -= 1
```
</b></details>

<details>
<summary>Sort a list of lists by the second item of each nested list</summary><br><b>

```
li = [[1, 4], [2, 1], [3, 9], [4, 2], [4, 5]]

sorted(li, key=lambda l: l[1])
```

or

```
li.sort(key=lambda l: l[1)
```
</b></details>

<details>
<summary>Combine [1, 2, 3] and ['x', 'y', 'z'] so the result is [(1, 'x'), (2, 'y'), (3, 'z')]</summary><br><b>

```
nums = [1, 2, 3]
letters = ['x', 'y', 'z']

list(zip(nums, letters))
```
</b></details>

<details>
<summary>What is List Comprehension? Is it better than a typical loop? Why? Can you demonstrate how to use it?</summary><br><b>
</b></details>

#### Dictionaries

<details>
<summary>How to create a dictionary?</summary><br><b>

my_dict = dict(x=1, y=2)
OR
my_dict = {'x': 1, 'y': 2}
OR
my_dict = dict([('x', 1), ('y', 2)])
</b></details>

<details>
<summary>How to remove an item from a dictionary?</summary><br><b>

del my_dict['some_key']
you can also use `my_dict.pop('some_key')` which returns the value of the key.
</b></details>

<details>
<summary>How to sort a dictionary by values?</summary><br><b>

```
{k: v for k, v in sorted(x.items(), key=lambda item: item[1])}
```
</b></details>

<details>
<summary>How to sort a dictionary by keys?</summary><br><b>

```
dict(sorted(some_dictionary.items()))
```
</b></details>

<details>
<summary>How to merge two dictionaries?</summary><br><b>

```
some_dict1.update(some_dict2)
```
</b></details>

##### Common Algorithms Implementation

<details>
<summary>Can you implement "binary search" in Python?</summary><br><b>

[Solution](coding/python/binary_search.py)
</b></details>

#### Python Files

<details>
<summary>How to write to a file?</summary><br><b>

```
with open('file.txt', 'w') as file:
    file.write("My insightful comment")
```
</b></details>

<details>
<summary>How to print the 12th line of a file?</summary><br><b>
</b></details>

<details>
<summary>How to reverse a file?</summary><br><b>
</b></details>

<details>
<summary>Sum all the integers in a given file</summary><br><b>
</b></details>

<details>
<summary>Print a random line of a given file</summary><br><b>
</b></details>

<details>
<summary>Print every 3rd line of a given file</summary><br><b>
</b></details>

<details>
<summary>Print the number of lines in a given file</summary><br><b>
</b></details>

<details>
<summary>Print the number of of words in a given file</summary><br><b>
</b></details>

<details>
<summary>Can you write a function which will print all the file in a given directory? including sub-directories</summary><br><b>
</b></details>

#### Python OS

<details>
<summary>How to print current working directory?</summary><br><b>
</b></details>

<details>
<summary>Given the path <code>/dir1/dir2/file1</code> print the file name (file1)</summary><br><b>
</b></details>

<details>
<summary>Given the path <code>/dir1/dir2/file1</code> print the name of the directory where the file resides (dir2)</summary><br><b>
</b></details>

<details>
<summary>Given the path <code>/dir1/dir2/file1</code> print the path without the file name (/dir1/dir2)</summary><br><b>
</b></details>

<details>
<summary>How do you execute shell commands using Python?</summary><br><b>
</b></details>

#### Python Regex

<details>
<summary>How do you perform regular expressions related operations in Python? (match patterns, substitute strings, etc.)</summary><br><b>

Using the re module
</b></details>

<details>
<summary>How to substitute the string "green" with "blue"?</summary><br><b>
</b></details>

<details>
<summary>How to find all the IP addresses in a variable? How to find them in a file?</summary><br><b>
</b></details>

<details>
<summary>You have the following list: <code>[{'name': 'Mario', 'food': ['mushrooms', 'goombas']}, {'name': 'Luigi', 'food': ['mushrooms', 'turtles']}]</code>
  Extract all type of foods. Final output should be: {'mushrooms', 'goombas', 'turtles'}</summary><br><b>

```
brothers_menu =  \
[{'name': 'Mario', 'food': ['mushrooms', 'goombas']}, {'name': 'Luigi', 'food': ['mushrooms', 'turtles']}]

# "Classic" Way
def get_food(brothers_menu) -> set:
    temp = []

    for brother in brothers_menu:
        for food in brother['food']:
            temp.append(food)

    return set(temp)

# One liner way (Using list comprehension)
set([food for bro in x for food in bro['food']])
```
</b></details>

#### Python Strings

<details>
<summary>How to extract the unique characters from a string? for example given the input "itssssssameeeemarioooooo" the output will be "mrtisaoe"</summary><br><b>

```
x = "itssssssameeeemarioooooo"
y = ''.join(set(x))
```
</b></details>

<details>
<summary>Find all the permutations of a given string</summary><br><b>

```
def permute_string(string):

    if len(string) == 1:
        return [string]

    permutations = []
    for i in range(len(string)):
        swaps = permute_string(string[:i] + string[(i+1):])
        for swap in swaps:
            permutations.append(string[i] + swap)

    return permutations

print(permute_string("abc"))
```

Short way (but probably not acceptable in interviews):

```
from itertools import permutations

[''.join(p) for p in permutations("abc")]
```

Detailed answer can be found here: http://codingshell.com/python-all-string-permutations

</b></details>

<details>
<summary>How to check if a string contains a sub string?</summary><br><b>
</b></details>

<details>
<summary>Find the frequency of each character in string</summary><br><b>
</b></details>

<details>
<summary>Count the number of spaces in a string</summary><br><b>
</b></details>

<details>
<summary>Given a string, find the N most repeated words</summary><br><b>
</b></details>

<details>
<summary>Given the string (which represents a matrix) "1 2 3\n4 5 6\n7 8 9" create rows and colums variables (should contain integers, not strings)</summary><br><b>
</b></details>

<details>
<summary>What is the result of each of the following?

```
>> ', '.join(["One", "Two", "Three"])
>> " ".join("welladsadgadoneadsadga".split("adsadga")[:2])
>> "".join(["c", "t", "o", "a", "o", "q", "l"])[0::2]
```
</summary><br><b>

```
>>> 'One, Two, Three'
>>> 'well done'
>>> 'cool'
```
</b></details>

<details>
<summary>How to reverse a string? (e.g. pizza -> azzip)</summary><br><b>

The correct way is: 

```
my_string[::-1]
```

A more visual way is:<br>
<i>Careful: this is very slow</i>

```
def reverse_string(string):
    temp = ""
    for char in string:
        temp =  char + temp
    return temp
```
</b></details>

<details>
<summary>What is the output of the following code: <code>"".join(["a", "h", "m", "a", "h", "a", "n", "q", "r", "l", "o", "i", "f", "o", "o"])[2::3]</code></summary><br><b>

mario
</b></details>

<details>
<summary>Explain data serialization and how do you perform it with Python</summary><br><b>
</b></details>

<details>
<summary>How do you handle argument parsing in Python?</summary><br><b>
</b></details>

<details>
<summary>What is an iterator?</summary><br><b>
</b></details>

<details>
<summary>What is a generator? Why using generators?</summary><br><b>
</b></details>

<details>
<summary>What is <code>yeild</code>? When would you use it?</summary><br><b>
</b></details>

<details>
<summary>Explain the following types of methods and how to use them:

  * Static method
  * Class method
  * instance method</summary><br><b>
</b></details>

<details>
<summary>How to reverse a list?</summary><br><b>
</b></details>

<details>
<summary>How to combine list of strings into one string with spaces between the strings</summary><br><b>
</b></details>

<details>
<summary>You have the following list of nested lists: <code>[['Mario', 90], ['Geralt', 82], ['Gordon', 88]]</code> How to sort the list by the numbers in the nested lists?</code></summary><br><b>

One way is:

the_list.sort(key=lambda x: x[1])
</b></details>

<details>
<summary>Explain the following:

  * zip()
  * map()
  * filter()</summary><br><b>
</b></details>

#### Python - Slicing

For the following slicing exercises, assume you have the following list: `my_list = [8, 2, 1, 10, 5, 4, 3, 9]`

<details>
<summary>What is the result of `my_list[0:4]`?</summary><br><b>
</b></details>

<details>
<summary>What is the result of `my_list[5:6]`?</summary><br><b>
</b></details>

<details>
<summary>What is the result of `my_list[5:5]`?</summary><br><b>
</b></details>

<details>
<summary>What is the result of `my_list[::-1]`?</summary><br><b>
</b></details>

<details>
<summary>What is the result of `my_list[::3]`?</summary><br><b>
</b></details>

<details>
<summary>What is the result of `my_list[2:]`?</summary><br><b>
</b></details>

<details>
<summary>What is the result of `my_list[:3]`?</summary><br><b>
</b></details>

#### Python Debugging

<details>
<summary>How do you debug Python code?</summary><br><b>

pdb :D
</b></details>

<details>
<summary>How to check how much time it took to execute a certain script or block of code?</summary><br><b>
</b></details>

<details>
<summary>What empty <code>return</code> returns?</summary><br><b>
</b>

Short answer is: It returns a None object.

We could go a bit deeper and explain the difference between 

```
def a ():
    return
    
>>> None
```

And

```
def a ():
    pass
    
>>> None
```
Or we could be asked this as a following question, since they both give the same result.

We could use the dis module to see what's going on:

```
  2           0 LOAD_CONST               0 (<code object a at 0x0000029C4D3C2DB0, file "<dis>", line 2>)
              2 LOAD_CONST               1 ('a')
              4 MAKE_FUNCTION            0
              6 STORE_NAME               0 (a)

  5           8 LOAD_CONST               2 (<code object b at 0x0000029C4D3C2ED0, file "<dis>", line 5>)
             10 LOAD_CONST               3 ('b')
             12 MAKE_FUNCTION            0
             14 STORE_NAME               1 (b)
             16 LOAD_CONST               4 (None)
             18 RETURN_VALUE

Disassembly of <code object a at 0x0000029C4D3C2DB0, file "<dis>", line 2>:
  3           0 LOAD_CONST               0 (None)
              2 RETURN_VALUE

Disassembly of <code object b at 0x0000029C4D3C2ED0, file "<dis>", line 5>:
  6           0 LOAD_CONST               0 (None)
              2 RETURN_VALUE
```

An empty <code> return</code> is exactly the same as <code>return None</code> and functions without any explicit return
will always return None regardless of the operations, therefore 


```
def sum(a, b):
    global c
    c = a + b
    
>>> None
```
</b></details>

<details>
<summary>How to improve the following block of code?

```
li = []
for i in range(1, 10):
    li.append(i)
```
</summary><br><b>

```
[for i in in range(1, 10)]
```
</b></details>

<details>
<summary>Given the following function

```
def is_int(num):
    if isinstance(num, int):
        print('Yes')
    else:
        print('No')
```
What would be the result of is_int(2) and is_int(False)?
</summary><br><b>
</b></details>

##### Data Structures & Types

<details>
<summary>Implement Stack in Python</summary><br><b>
</b></details>

<details>
<summary>Implement Hash table in Python</summary><br><b>
</b></details>

##### Python Testing

<details>
<summary>What is your experience with writing tests in Python?</summary><br><b>
</b></details>

<details>
<summary>What is PEP8? Give an example of 3 style guidelines</summary><br><b>

PEP8 is a list of coding conventions and style guidelines for Python

5 style guidelines:

    1. Limit all lines to a maximum of 79 characters.
    2. Surround top-level function and class definitions with two blank lines.
    3. Use commas when making a tuple of one element
    4. Use spaces (and not tabs) for indentation
    5. Use 4 spaces per indentation level
</b></details>

<details>
<summary>How would you check if two strings are equal? What about booleans?</summary><br><b>
</b></details>

<details>
<summary>How to test if an exception was raised?</summary><br><b>
</b></details>

<details>
<summary>What <code>assert</code> does in Python?</summary><br><b>
</b></details>

<details>
<summary>Explain mocks</summary><br><b>
</b></details>

<details>
<summary>How do you measure execution time of small code snippets?</summary><br><b>
</b></details>

<details>
<summary>Why one shouldn't use <code>assert</code> in non-test/production code?</summary><br><b>
</b></details>

#### Flask

<details>
<summary>You wrote you have experience with Django/Flask. Can you describe what is Django/Flask and how you have used it? Why Flask and not Djano? (or vice versa)</summary><br><b>
</b></details>

<details>
<summary>What is a route?</summary><br><b>
</b></details>

<details>
<summary>How do you manage DB integration?</summary><br><b>
</b></details>

#### zip

<details>
<summary>Given <code>x = [1, 2, 3]</code>, what is the result of list(zip(x))?</summary><br><b>

```
[(1,), (2,), (3,)]
```
</b></details>

<details>
<summary>What is the result of each of the following:

```
list(zip(range(5), range(50), range(50)))
list(zip(range(5), range(50), range(-2)))
```
</summary><br><b>

```
[(0, 0, 0), (1, 1, 1), (2, 2, 2), (3, 3, 3), (4, 4, 4)]
[]
```
</b></details>

#### Misc


<details>
<summary>Implement simple calculator for two numbers</summary><br><b>

```
def add(num1, num2):
    return num1 + num2
        
        
def sub(num1, num2):
    return num1 - num2


def mul(num1, num2):
    return num1*num2


def div(num1, num2):
    return num1 / num2

operators = { 
    '+': add,
    '-': sub,
    '*': mul,
    '/': div 
}

if __name__ == '__main__':
    operator = str(input("Operator: "))
    num1 = int(input("1st number: "))
    num2 = int(input("2nd number: "))
    print(operators[operator](num1, num2))
```
</b></details>


<a name="python-advanced"></a>
#### :star: Advanced

<details>
<summary>What data types are you familiar with that are not Python built-in types but still provided by modules which are part of the standard library?</summary><br><b>

This is a good reference https://docs.python.org/3/library/datatypes.html
</b></details>

<details>
<summary>Explain what is a decorator</summary><br><b>
</b>
<b>In python, everything is an object, even functions themselves. Therefore you could pass functions as arguments
for another function eg;

```
def wee(word):
    return word

def oh(f):
    return f + "Ohh"
    
>>> oh(wee("Wee"))
<<< Wee Ohh
```

This allows us to control the before execution of any given function and if we added another function as wrapper,
(a function receiving another function that receives a function as parameter) we could also control the after execution.

Sometimes we want to control the before-after execution of many functions and it would get tedious to write

<code> f = function(function_1())</code>
<code> f = function(function_1(function_2(*args)))</code>

every time, that's what decorators do, they introduce syntax to write all of this on the go, using the keyword '@'.
</b>
</details>

<details>
<summary>Can you show how to write and use decorators?</summary><br><b>

<code>
These two decorators (ntimes and timer) are usually used to display decorators functionalities, you can find them in lots of
tutorials/reviews. I first saw these examples two years ago in pyData 2017. https://www.youtube.com/watch?v=7lmCu8wz8ro&t=3731s</code>

```
Simple decorator:

def deco(f):
    print(f"Hi I am the {f.__name__}() function!")
    return f

@deco
def hello_world():
    return "Hi, I'm in!"

a = hello_world()
print(a)

>>> Hi I am the hello_world() function!
    Hi, I'm in!
```

This is the simplest decorator version, it basically saves us from writting <code>a = deco(hello_world())</code>.
But at this point we can only control the before execution, let's take on the after:

```
def deco(f):
    def wrapper(*args, **kwargs):
        print("Rick Sanchez!")
        func = f(*args, **kwargs)
        print("I'm in!")
        return func
    return wrapper

@deco
def f(word):
    print(word)

a = f("************")
>>> Rick Sanchez!
    ************
    I'm in!
```

deco receives a function -> f
wrapper receives the arguments -> *args, **kwargs

wrapper returns the function plus the arguments -> f(*args, **kwargs)
deco returns wrapper.

As you can see we conveniently do things before and after the execution of a given function.

For example, we could write a decorator that calculates the execution time of a function.

```
import time
def deco(f):
    def wrapper(*args, **kwargs):
        before = time.time()
        func = f(*args, **kwargs)
        after = time.time()
        print(after-before)
        return func
    return wrapper

@deco
def f():
    time.sleep(2)
    print("************")

a = f()
>>> 2.0008859634399414
```

Or create a decorator that executes a function n times.

```
def n_times(n):
    def wrapper(f):
        def inner(*args, **kwargs):
            for _ in range(n):
                func = f(*args, **kwargs)
            return func
        return inner
    return wrapper

@n_times(4)
def f():
    print("************")

a = f()

>>>************
   ************
   ************
   ************
```

</b></details>

<details>
<summary>Write a decorator that calculates the execution time of a function</summary><br><b>
</b></details>

<details>
<summary>Write a script which will determine if a given host is accessible on a given port</summary><br><b>
</b></details>

<details>
<summary>Are you familiar with Dataclasses? Can you explain what are they used for?</summary><br><b>
</b></details>

<details>
<summary>You wrote a class to represent a car. How would you compare two cars instances if two cars are equal if they have the same model and color?</summary><br><b>
</b></details>

<details>
<summary>Explain Context Manager</summary><br><b>
</b></details>

<details>
<summary>Tell me everything you know about concurrency in Python</summary><br><b>
</b></details>

<details>
<summary>Explain the Buffer Protocol</summary><br><b>
</b></details>

<details>
<summary>Explain Descriptors</summary><br><b>
</b></details>

<details>
<summary>Do you have experience with web scraping? Can you describe what have you used and for what?</summary><br><b>
</b></details>

<details>
<summary>Can you implement Linked List in Python?</summary><br><b>
</b></details>

<details>
<summary>Can you implement Linux's <code>tail</code> command in Python? Bonus: implement <code>head</code> as well</summary><br><b>
</b></details>

<details>
<summary>You have created a web page where a user can upload a document. But the function which reads the uploaded files, runs for a long time, based on the document size and user has to wait for the read operation to complete before he/she can continue using the web site. How can you overcome this?</summary><br><b>
</b></details>

<details>
<summary>How yield works exactly?</summary><br><b>
</b></details>

##### Python Geeks :)

<details>
<summary>Tell me something about Python that you think most people don't know</summary><br><b>
</b></details>

## Monitoring

<a name="monitoring-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain monitoring. What is it? What its goal?</summary><br><b>
</b></details>

<details>
<summary>What is wrong with the old approach of watching for a specific value and trigger an email/phone alert while value is exceeded?</summary><br><b>

This approach require from a human to always check why the value exceeded and how to handle it while today, it is more effective to notify people only when they need to take an actual action.
If the issue doesn't require any human intervention, then the problem can be fixed by some processes running in the relevant environment.
</b></details>

<details>
<summary>What types of monitoring outputs are you familiar with and/or used in the past?</summary><br><b>

Alerts<br>
Tickets<br>
Logging<br>
</b></details>

<details>
<summary>What is the different between infrastructure monitoring and application monitoring? (methods, tools, ...)</summary><br><b>
</b></details>

## Prometheus

<a name="prometheus-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Prometheus? What are some of Prometheus's main features?</summary><br><b>
</b></details>

<details>
<summary>Describe Prometheus architecture and components</summary><br><b>
</b></details>

<details>
<summary>Have you set up Prometheus? How did you do it? Describe the process</summary><br><b>
</b></details>

<details>
<summary>Can you compare Prometheus to other solutions like InfluxDB for example?</summary><br><b>
</b></details>

<details>
<summary>What is an Alert?</summary><br><b>
</b></details>

<details>
<summary>Describe the following Prometheus components:

  * Prometheus server
  * Push Gateway
  * Alert Manager</summary><br><b>

Prometheus server responsible for scraping the storing the data<br>
Push gateway is used for short-lived jobs<br>
Alert manager is responsible for alerts ;)
</b></details>

<details>
<summary>What is an Instance? What is a Job?</summary><br><b>
</b></details>

<details>
<summary>What core metrics types Prometheus supports?</summary><br><b>
</b></details>

<details>
<summary>What is an exporter? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>Which Prometheus best practices are you familiar with?. Name at least three</summary><br><b>
</b></details>

<details>
<summary>How to get total requests in a given period of time?</summary><br><b>
</b></details>

<details>
<summary>What HA in Prometheus means?</summary><br><b>
</b></details>

<a name="prometheus-advanced"></a>
#### :star: Advanced

<details>
<summary>How do you join two metrics?</summary><br><b>
</b></details>

<details>
<summary>How to write a query that returns the value of a label?</summary><br><b>
</b></details>

<details>
<summary>How do you convert cpu_user_seconds to cpu usage in percentage?</summary><br><b>
</b></details>

## Git

<a name="git-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is the difference between <code>git pull</code> and <code>git fetch</code>?</summary><br><b>

Shortly, git pull = git fetch + git merge

When you run git pull, it gets all the changes from the remote or central
repository and attaches it to your corresponding branch in your local repository.

git fetch gets all the changes from the remote repository, stores the changes in
a separate branch in your local repository
</b></details>

<details>
<summary>Explain the following: <code>git directory</code>, <code>working directory</code> and <code>staging area</code></summary><br><b>

The Git directory is where Git stores the meta data and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

The working directory is a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

The staging area is a simple file, generally contained in your Git directory, that stores information about what will go into your next commit. It’s sometimes referred to as the index, but it’s becoming standard to refer to it as the staging area.

This answer taken from [git-scm.com](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics#_the_three_states)
</b></details>

<details>
<summary>How to resolve git merge conflicts?</summary><br><b>

<p>
First, you open the files which are in conflict and identify what are the conflicts.
Next, based on what is accepted in your company or team, you either discuss with your
colleagues on the conflicts or resolve them by yourself
After resolving the conflicts, you add the files with `git add <file_name>`
Finally, you run `git rebase --continue`
</p>
</b></details>

<details>
<summary>What is the difference between <code>git reset</code> and <code>git revert</code>?</summary><br><b>

<p>

`git revert` creates a new commit which undoes the changes from last commit.

`git reset` depends on the usage, can modify the index or change the commit which the branch head
is currently pointing at.
</p>
</b></details>

<details>
<summary>You would like to move forth commit to the top. How would you achieve that?</summary><br><b>

Using <code>git rebase></code> command
</b></details>

<details>
<summary>In what situations are you using <code>git rebase</code>?</summary><br><b>
</b></details>

<details>
<summary>What merge strategies are you familiar with?</summary><br><b>

Mentioning two or three should be enough and it's probably good to mention that 'recursive' is the default one.

recursive
resolve
ours
theirs

This page explains it the best: https://git-scm.com/docs/merge-strategies
</b></details>

<details>
<summary>How can you see which changes have done before committing them?</summary><br><b>

<code>git diff</code>
</b></details>

<details>
<summary>How do you revert a specific file to previous commit?</summary><br><b>

```
git checkout HEAD~1 -- /path/of/the/file
```
</b></details>

<details>
<summary>What is the <code>.git</code> directory? What can you find there?</summary><br><b>
	The <code>.git</code> folder contains all the information that is necessary for your project in version control and all the information about commits, remote repository address, etc. All of them are present in this folder. It also contains a log that stores your commit history so that you can roll back to history.


This info copied from [https://stackoverflow.com/questions/29217859/what-is-the-git-folder](https://stackoverflow.com/questions/29217859/what-is-the-git-folder)
</b></details>

<details>
<summary>What are some Git anti-patterns? Things that you shouldn't do</summary><br><b>

  * Not waiting too long between commits
  * Not removing the .git directory :)
</b></details>

<details>
<summary>How do you remove a remote branch?</summary><br><b>

You delete a remote branch with this syntax:

git push origin :[branch_name]
</b></details>

<details>
<summary>Are you familiar with gitattributes? When would you use it?</summary><br><b>

gitattributes allow you to define attributes per pathname or path pattern.<br>

You can use it for example to control endlines in files. In Windows and Unix based systems, you have different characters for new lines (\r\n and \n accordingly). So using gitattributes we can align it for both Windows and Unix with `* text=auto` in .gitattributes for anyone working with git. This is way, if you use the Git project in Windows you'll get \r\n and if you are using Unix or Linux, you'll get \n.
</b></details>

<details>
<summary>How do you discard local file changes? (before commit)</summary><br><b>

`git checkout -- <file_name>`
</b></details>

<details>
<summary>How do you discard local commits?</summary><br><b>

`git reset HEAD~1` for removing last commit
If you would like to also discard the changes you `git reset --hard``
</b></details>

<details>
<summary>True or False? To remove a file from git but not from the filesystem, one should use <code>git rm </code></summary><br><b>

False. If you would like to keep a file on your filesystem, use `git reset <file_name>`
</b></details>

<a name="git-advanced"></a>
#### :star: Advanced

<details>
<summary>Explain Git octopus merge</summary><br><b>

Probably good to mention that it's:

  * It's good for cases of merging more than one branch (and also the default of such use cases)
  * It's primarily meant for bundling topic branches together 

This is a great article about Octopus merge: http://www.freblogg.com/2016/12/git-octopus-merge.html
</b></details>

## Go

<a name="go-beginner"></a>
#### :baby: Beginner

<details>
<summary>What are some characteristics of the Go programming language?</summary><br><b>

  * Strong and static typing - the type of the variables can't be changed over time and they have to be defined at compile time
  * Simplicity 
  * Fast compile times
  * Built-in concurrency
  * Garbage collected
  * Platform independent
  * Compile to standalone binary - anything you need to run your app will be compiled into one binary. Very useful for version management in run-time. 

Go also has good community.
</b></details>

<details>
<summary>What is the difference between <code>var x int = 2</code> and <code>x := 2</code>?</summary><br><b>

The result is the same, a variable with the value 2.

With <code>var x int = 2</code> we are setting the variable type to integer while with <code>x := 2</code> we are letting Go figure out by itself the type.
</b></details>

<details>
<summary>True or False? In Go we can redeclare variables and once declared we must use it.</summary>

False. We can't redeclare variables but yes, we must used declared variables.
</b></details>

<details>
<summary>What libraries of Go have you used?</summary><br><b>

This should be answered based on your usage but some examples are:

  * fmt - formatted I/O
</b></details>

<details>
<summary>What is the problem with the following block of code? How to fix it?

```
func main() {
    var x float32 = 13.5
    var y int
    y = x
}
```
</summary><br><b>
</b></details>

<details>
<summary>The following block of code tries to convert the integer 101 to a string but instead we get "e". Why is that? How to fix it?

```
package main

import "fmt"

func main() {
    var x int = 101
    var y string
    y = string(x)
    fmt.Println(y)
}
```
</summary><br><b>

It looks what unicode value is set at 101 and uses it for converting the integer to a string.
If you want to get "101" you should use the package "strconv" and replace <code>y = string(x)</code> with <code>y = strconv.Itoa(x)</code>
</b></details>

<details>
<summary>What is wrong with the following code?:

```
package main

func main() {
    var x = 2
    var y = 3
    const someConst = x + y
}
```
</summary><br><b>

Constants in Go can only be declared using constant expressions.
But `x`, `y` and their sum is variable.
<br>
<code>const initializer x + y is not a constant</code>
</b></details>

<details>
<summary>What will be the output of the following block of code?:

```
package main

import "fmt"

const (
	x = iota
	y = iota
)
const z = iota

func main() {
	fmt.Printf("%v\n", x)
	fmt.Printf("%v\n", y)
	fmt.Printf("%v\n", z)
}
```
</summary><br><b>

Go's iota identifier is used in const declarations to simplify definitions of incrementing numbers. Because it can be used in expressions, it provides a generality beyond that of simple enumerations.
<br>
`x` and `y` in the first iota group, `z` in the second.
<br>
[Iota page in Go Wiki](https://github.com/golang/go/wiki/Iota)
</b></details>

<details>
<summary>What _ is used for in Go?</summary><br><b>
	
It avoids having to declare all the variables for the returns values.
It is called the [blank identifier](https://golang.org/doc/effective_go.html#blank).
<br>
[answer in SO](https://stackoverflow.com/questions/27764421/what-is-underscore-comma-in-a-go-declaration#answer-27764432)
</b></details>

<details>
<summary>What will be the output of the following block of code?:

```
package main

import "fmt"

const (
	_ = iota + 3
	x
)

func main() {
	fmt.Printf("%v\n", x)
}
```
</summary><br><b>

Since the first iota is declared with the value `3` (` + 3`), the next one has the value `4`
</b></details>

<details>
<summary>What will be the output of the following block of code?:

```
package main
 
import (
	"fmt"
	"sync"
	"time"
)
 
func main() {
	var wg sync.WaitGroup
	
	wg.Add(1)
	go func() {
		time.Sleep(time.Second * 2)
		fmt.Println("1")
		wg.Done()
	}()

	go func() {
		fmt.Println("2")
	}()

	wg.Wait()
	fmt.Println("3")
}
```
</summary><br><b>

Output: 2 1 3

[Aritcle about sync/waitgroup](https://tutorialedge.net/golang/go-waitgroup-tutorial/)

[Golang package sync](https://golang.org/pkg/sync/)
</b></details>

<details>
<summary>What will be the output of the following block of code?:

```
package main

import (
	"fmt"
)

func mod1(a []int) {
	for i := range a {
		a[i] = 5
	}
	
	fmt.Println("1:", a)
}

func mod2(a []int) {
	a = append(a, 125) // !
	
	for i := range a {
		a[i] = 5
	}
	
	fmt.Println("2:", a)
}

func main() {
	sl := []int{1, 2, 3, 4}
	mod1(s1)
	fmt.Println("1:", s1)

	s2 := []int{1, 2, 3, 4}
	mod2(s2)
	fmt.Println("2:", s2)
}
```
</summary><br><b>

Output: <code><br>
1 [5 5 5 5]<br>
1 [5 5 5 5]<br>
2 [5 5 5 5 5]<br>
2 [1 2 3 4]<br>
</code>

In `mod1` a is link, and when we're using `a[i]`, we're changing `s1` value to. 
But in `mod2`, `append` creats new slice, and we're changing only `a` value, not `s2`.

[Aritcle about arrays](https://golangbot.com/arrays-and-slices/),
[Blog post about `append`](https://blog.golang.org/slices)
</b></details>

<details>
<summary>What will be the output of the following block of code?:

```
package main

import (
	"container/heap"
	"fmt"
)

// An IntHeap is a min-heap of ints.
type IntHeap []int

func (h IntHeap) Len() int           { return len(h) }
func (h IntHeap) Less(i, j int) bool { return h[i] < h[j] }
func (h IntHeap) Swap(i, j int)      { h[i], h[j] = h[j], h[i] }

func (h *IntHeap) Push(x interface{}) {
	// Push and Pop use pointer receivers because they modify the slice's length,
	// not just its contents.
	*h = append(*h, x.(int))
}

func (h *IntHeap) Pop() interface{} {
	old := *h
	n := len(old)
	x := old[n-1]
	*h = old[0 : n-1]
	return x
}

func main() {
	h := &IntHeap{4, 8, 3, 6}
	heap.Init(h)
	heap.Push(h, 7)
  
  fmt.Println((*h)[0])
}
```
</summary><br><b>

Output: 3

[Golang container/heap package](https://golang.org/pkg/container/heap/)
</b></details>
## Mongo

<a name="mongo-beginner"></a>
#### :baby: Beginner

<details>
<summary>What are the advantages of MongoDB? Or in other words, why choosing MongoDB and not other implementation of NoSQL?</summary><br><b>

MongoDB advantages are as followings:
- Schemaless
- Easy to scale-out
- No complex joins
- Structure of a single object is clear

</b></details>

<details>
<summary>What is the difference between SQL and NoSQL?</summary><br><b>

The main difference is that SQL databases are structured (data is stored in the form of
tables with rows and columns - like an excel spreadsheet table) while NoSQL is 
unstructured, and the data storage can vary depending on how the NoSQL DB is set up, such
as key-value pair, document-oriented, etc.
</b></details>

<details>
<summary>In what scenarios would you prefer to use NoSQL/Mongo over SQL?</summary><br><b>

  * Heterogeneous data which changes often
  * Data consistency and integrity is not top priority
  * Best if the database needs to scale rapidly
</b></details>

<details>
<summary>What is a document? What is a collection?</summary><br><b>
</b></details>

<details>
<summary>What is an aggregator?</summary><br><b>
</b></details>

<details>
<summary>What is better? Embedded documents or referenced?</summary><br><b>
</b></details>

<details>
<summary>Have you performed data retrieval optimizations in Mongo? If not, can you think about ways to optimize a slow data retrieval?</summary><br><b>
</b></details>

##### Queries

<details>
<summary>Explain this query: <code>db.books.find({"name": /abc/})</code></summary><br><b>
</b></details>

<details>
<summary>Explain this query: <code>db.books.find().sort({x:1})</code></summary><br><b>
</b></details>

## OpenShift

<a name="openshift-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is OpenShift? What experience do you have with OpenShift?</summary><br><b>
</b></details>

<details>
<summary>Can you explain the difference between OpenShift and Kubernetes?</summary><br><b>
</b></details>

<details>
<summary>Define Pods and explain what are stateful pods</summary><br><b>
</b></details>

<details>
<summary>What types of build strategies are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Explain what are labels and what they are used for</summary><br><b>
</b></details>

<details>
<summary>Explain what are annotations and how they are different from labels</summary><br><b>
</b></details>

<details>
<summary>Explain what is Downward API</summary><br><b>
</b></details>

## Shell Scripting

<a name="shell-scripting-beginner"></a>
#### :baby: Beginner

<details>
<summary>Tell me about your experience with shell scripting</summary><br><b>

</b></details>

<details>
<summary>What this line in scripts mean?: <code>#!/bin/bash</code></summary><br><b>


`#!/bin/bash` is She-bang 

/bin/bash is the most common shell used as default shell for user login of the linux system. The shell’s name is an acronym for Bourne-again shell. Bash can execute the vast majority of scripts and thus is widely used because it has more features, is well developed and better syntax.

</b></details>

<details>
<summary>What do you tend to include in every script you write?</summary><br><b>

Few example:

  * Comments on how to run it and/or what it does
  * Adding "set -e" since I want the script to exit if a certain command failed 

You can have an entirely different answer. It's based only on your experience.
</b></details>

<details>
<summary>True or False?: when a certain command/line fails, the script, by default, will exit and will no keep running</summary><br><b>

Depends on the language and settings used.
When a script written in Bash fails to run a certain command it will keep running and will execute all other commands mentioned after the command which failed.
Most of the time we would actually want the opposite to happen. In order to make Bash exist when a specific command fails, use 'set -e' in your script.
</b></details>

<details>
<summary>Today we have tools and technologies like Ansible. Why would someone still use shell scripting?</summary><br><b>

  * Speed
  * The module we need doesn't exist
  * We are delivering the scripts to customers who don't have access to the public network and don't necessarily have Ansible installed on their systems.
</b></details>

<details>
<summary>Explain what would be the result of each command:

  * <code>echo $0</code>
  * <code>echo $?</code>
  * <code>echo $$</code>
  * <code>echo $@</code>
  * <code>echo $#</code></summary><br><b>
</b></details>

<details>
<summary>How do you debug shell scripts?</summary><br><b>

Answer depends on the language you are using for writing your scripts. If Bash is used for example then:

  * Adding -x to the script I'm running in Bash
  * Old good way of adding echo statements

If Python, then using pdb is very useful.
</b></details>

<details>
<summary>How do you get input from the user in shell scripts?</summary><br><b>

Using the keyword <code>read</code> so for example <code>read x</code> will wait for user input and will store it in the variable x.
</b></details>

<details>
<summary>Explain conditionals and how do you use them</summary><br><b>
</b></details>

#### Shell Scripting - Loops

<details>
<summary>What is a loop? What types of loops are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Demonstrate how to use loops</summary><br><b>
</b></details>

<details>
<summary>Explain <code>continue</code> and <code>break</code>. When do you use them if at all?</summary><br><b>
</b></details>


<details>
<summary>Running the following bash script, we don't get 2 as a result, why?

```
x = 2
echo $x
```
</summary><br><b>

Should be `x=2`
</b></details>

<details>
<summary>How to store the output of a command in a variable?</summary><br><b>
</b></details>

<details>
<summary>How do you check variable length?</summary><br><b>
</b></details>

##### Practical

<details>
<summary>Write a script which will list the differences between two directories</summary><br><b>
</b></details>

<details>
<summary>Write a script to determine whether a host is up or down</summary><br><b>

**EXAMPLE ONE**
```
#!/bin/bash
SERVERIP=<IP Address>
NOTIFYEMAIL=test@example.com

ping -c 3 $SERVERIP > /dev/null 2>&1
if [ $? -ne 0 ]
then
   # Use mailer here:
   mailx -s "Server $SERVERIP is down" -t "$NOTIFYEMAIL" < /dev/null 
fi
```

</b></details>

<details>
<summary>Write a script to remove all the empty files in a given directory (also nested directories)</summary><br><b>

**EXAMPLE ONE**
```
#! /bin/bash
for x in *
do
    if [ -s $x ]
    then
        continue
    else
        rm -rf $x
    fi
done
```

</b></details>

<a name="shell-scripting-advanced"></a>
#### Advanced

<details>
<summary>Explain the following code:

<code>:(){ :|:& };:</code>

</summary><br><b>
</b></details>

<details>
<summary>Can you give an example to some Bash best practices?</summary><br><b>
</b></details>

<details>
<summary>What is the ternary operator? How do you use it in bash?</summary><br><b>

A short way of using if/else. An example:

[[ $a = 1 ]] && b="yes, equal" || b="nope"
</b></details>

<details>
<summary>What does the following code do and when would you use it?
	
<code>diff <(ls /tmp) <(ls /var/tmp)</code>

</summary><br>
It is called 'process substitution'. It provides a way to pass the output of a command to another command when using a pipe <code>|</code> is not possible. It can be used when a command does not support <code>STDIN</code> or you need the output of multiple commands. 
https://superuser.com/a/1060002/167769
</details>


## SQL

<a name="sql-beginner"></a>
#### :baby: Beginner

<details>
<summary>What does SQL stand for?</summary><br><b>

Structured Query Language

</b></details>

<details>
<summary>How is SQL Different from NoSQL</summary><br><b>

The main difference is that SQL databases are structured (data is stored in the form of
tables with rows and columns - like an excel spreadsheet table) while NoSQL is 
unstructured, and the data storage can vary depending on how the NoSQL DB is set up, such
as key-value pair, document-oriented, etc.
</b></details>

<details>
<summary>What does it mean when a database is ACID compliant?</summary><br>

ACID stands for Atomicity, Consistency, Isolation, Durability. In order to be ACID compliant, the database much meet each of the four criteria

**Atomicity** - When a change occurs to the database, it should either succeed or fail as a whole. 

For example, if you were to update a table, the update should completely execute. If it only partially executes, the 
update is considered failed as a whole, and will not go through - the DB will revert back to it's original
state before the update occurred. It should also be mentioned that Atomicity ensures that each 
transaction is completed as it's own stand alone "unit" - if any part fails, the whole statement fails.

**Consistency** - any change made to the database should bring it from one valid state into the next.

For example, if you make a change to the DB, it shouldn't corrupt it. Consistency is upheld by checks and constraints that
are pre-defined in the DB. For example, if you tried to change a value from a string to an int when the column
should be of datatype string, a consistent DB would not allow this transaction to go through, and the action would
not be executed

**Isolation** - this ensures that a database will never be seen "mid-update" - as multiple transactions are running at
the same time, it should still leave the DB in the same state as if the transactions were being run sequentially.

For example, let's say that 20 other people were making changes to the database at the same time. At the
time you executed your query, 15 of the 20 changes had gone through, but 5 were still in progress. You should
only see the 15 changes that had completed - you wouldn't see the database mid-update as the change goes through.

**Durability** - Once a change is committed, it will remain committed regardless of what happens
(power failure, system crash, etc.). This means that all completed transactions 
must be recorded in non-volatile memory. 

Note that SQL is by nature ACID compliant. Certain NoSQL DB's can be ACID compliant depending on 
how they operate, but as a general rule of thumb, NoSQL DB's are not considered ACID compliant
</details>

<details>
<summary>When is it best to use SQL? NoSQL?</summary><br><b>

SQL - Best used when data integrity is crucial. SQL is typically implemented with many
businesses and areas within the finance field due to it's ACID compliance.

NoSQL - Great if you need to scale things quickly. NoSQL was designed with web applications 
in mind, so it works great if you need to quickly spread the same information around to 
multiple servers

Additionally, since NoSQL does not adhere to the strict table with columns and rows structure
that Relational Databases require, you can store different data types together.
</b></details>

<details>
<summary>What is a Cartesian Product?</summary><br>

A Cartesian product is when all rows from the first table are joined to all rows in the second
table. This can be done implicitly by not defining a key to join, or explicitly by 
calling a CROSS JOIN on two tables, such as below:

Select * from customers **CROSS JOIN** orders;

Note that a Cartesian product can also be a bad thing - when performing a join
on two tables in which both do not have unique keys, this could cause the returned information
to be incorrect. 
</details>

##### SQL Specific Questions

For these questions, we will be using the Customers and Orders tables shown below:

**Customers**

Customer_ID | Customer_Name | Items_in_cart | Cash_spent_to_Date
------------ | ------------- | ------------- | -------------
100204 | John Smith | 0 | 20.00
100205 | Jane Smith | 3 | 40.00
100206 | Bobby Frank | 1 | 100.20

**ORDERS**

Customer_ID | Order_ID | Item | Price | Date_sold
------------ | ------------- | ------------- | ------------- | -------------
100206 | A123 | Rubber Ducky | 2.20 | 2019-09-18
100206 | A123 | Bubble Bath | 8.00 | 2019-09-18
100206 | Q987 | 80-Pack TP | 90.00 | 2019-09-20
100205 | Z001 | Cat Food - Tuna Fish | 10.00 | 2019-08-05
100205 | Z001 | Cat Food - Chicken | 10.00 | 2019-08-05
100205 | Z001 | Cat Food - Beef | 10.00 | 2019-08-05
100205 | Z001 | Cat Food - Kitty quesadilla | 10.00 | 2019-08-05
100204 | X202 | Coffee | 20.00 | 2019-04-29

<details>
<summary>How would I select all fields from this table?</summary><br><b>

Select * <br>
From Customers;
</b></details>

<details>
<summary>How many items are in John's cart?</summary><br><b>

Select Items_in_cart <br>
From Customers <br>
Where Customer_Name = "John Smith";
</b></details>

<details>
<summary>What is the sum of all the cash spent across all customers?</summary><br><b>

Select SUM(Cash_spent_to_Date) as SUM_CASH <br>
From Customers;
</b></details>

<details>
<summary>How many people have items in their cart?</summary><br><b>

Select count(1) as Number_of_People_w_items <br>
From Customers <br>
where Items_in_cart > 0;
</b></details>

<details>
<summary>How would you join the customer table to the order table?</summary><br><b>

You would join them on the unique key. In this case, the unique key is Customer_ID in
both the Customers table and Orders table
</b></details>

<details>
<summary>How would you show which customer ordered which items?</summary><br><b>

Select c.Customer_Name, o.Item <br>
From Customers c <br>
Left Join Orders o <br>
  On c.Customer_ID = o.Customer_ID;

</b></details>

<a name="sql-advanced"></a>
#### Advanced

<details>
<summary>Using a with statement, how would you show who ordered cat food, and the total amount of money spent?</summary><br><b>

with cat_food as ( <br>
Select Customer_ID, SUM(Price) as TOTAL_PRICE <br>
From Orders <br>
Where Item like "%Cat Food%" <br>
Group by Customer_ID <br>
) <br>
Select Customer_name, TOTAL_PRICE <br>
From Customers c <br>
Inner JOIN cat_food f <br>
  ON c.Customer_ID = f.Customer_ID <br>
where c.Customer_ID in (Select Customer_ID from cat_food);

Although this was a simple statement, the "with" clause really shines when 
a complex query needs to be run on a table before joining to another. With statements are nice, 
because you create a pseudo temp when running your query, instead of creating a whole new table.

The Sum of all the purchases of cat food weren't readily available, so we used a with statement to create
the pseudo table to retrieve the sum of the prices spent by each customer, then join the table normally.
</b></details>

## Azure

<a name="azure-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain Azure's architecture</summary><br><b>
</b></details>

<details>
<summary>Explain availability sets and availability zones</summary><br><b>

An availability set is a logical grouping of VMs that allows Azure to understand how your application is built to provide redundancy and availability. It is recommended that two or more VMs are created within an availability set to provide for a highly available application and to meet the 99.95% Azure SLA.
</b></details>

<details>
<summary>What is Azure Policy?</summary><br><b>
</b></details>

<details>
<summary>What is the Azure Resource Manager? Can you describe the format for ARM templates?</summary><br><b>
</b></details>

<details>
<summary>Explain Azure managed disks</summary><br><b>
</b></details>

#### Network

<details>
<summary>What's an Azure region?</summary><br><b>
</b></details>

<details>
<summary>What is the N-tier architecture?</summary><br><b>
</b></details>

#### Storage

<details>
<summary>What storage options Azure supports?</summary><br><b>
</b></details>

#### Security

<details>
<summary>What is the Azure Security Center? What are some of its features?</summary><br><b>

It's a monitoring service that provides threat protection across all of the services in Azure.
More specifically, it:

* Provides security recommendations based on your usage
* Monitors security settings and continuously all the services
* Analyzes and identifies potential inbound attacks
* Detects and blocks malware using machine learning
</b></details>

<details>
<summary>What is Azure Active Directory?</summary><br><b>

Azure AD is a cloud-based identity service. You can use it as a standalone service or integrate it with existing Active Directory service you already running.
</b></details>

<details>
<summary>What is Azure Advanced Threat Protection?</summary><br><b>
</b></details>

<details>
<summary>What components are part of Azure ATP?</summary><br><b>
</b></details>

<details>
<summary>Where logs are stored in Azure Monitor?</summary><br><b>
</b></details>

<details>
<summary>Explain Azure Site Recovery</summary><br><b>
</b></details>

<details>
<summary>Explain what the advisor does</summary><br><b>
</b></details>

<details>
<summary>Explain VNet peering</summary><br><b>
</b></details>

<details>
<summary>Which protocols are available for configuring health probe</summary><br><b>
</b></details>

<details>
<summary>Explain Azure Active</summary><br><b>
</b></details>

<details>
<summary>What is a subscription? What types of subscriptions are there?</summary><br><b>
</b></details>

<details>
<summary>Explain what is a blob storage service</summary><br><b>
</b></details>

## GCP

<a name="gcp-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain GCP's architecture</summary><br><b>
</b></details>

<details>
<summary>What are the main components and services of GCP?</summary><br><b>
</b></details>

<details>
<summary>What GCP management tools are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Tell me what do you know about GCP networking</summary><br><b>
</b></details>

<details>
<summary>Explain Cloud Functions</summary><br><b>
</b></details>

<details>
<summary>What is Cloud Datastore?</summary><br><b>
</b></details>

<details>
<summary>What network tags are used for?</summary><br><b>
</b></details>

<details>
<summary>What are flow logs? Where are they enabled?</summary><br><b>
</b></details>

<details>
<summary>How do you list buckets?</summary><br><b>
</b></details>

<details>
<summary>What Compute metadata key allows you to run code at startup?</summary><br><b>

startap-script
</b></details>

<details>
<summary>What the following commands does? `gcloud deployment-manager deployments create`</summary><br><b>
</b></details>

## OpenStack

<a name="openstack-beginner"></a>
#### :baby: Beginner

<details>
<summary>Tell me about your experience with OpenStack. What do you think are the advantages and disadvantages of OpenStack?</summary><br><b>
</b></details>

<details>
<summary>What components/projects of OpenStack are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Can you tell me what each of the following services/projects is responsible for?:

  * Nova
  * Neutron
  * Cinder
  * Glance
  * Keystone</summary><br><b>

  * Nova - Manage virtual instances
  * Cinder - Block Storage
  * Keystone - Authentication service across the cloud
</b></details>

<details>
<summary>Identify the service/project used for each of the following:

  * Copy or snapshot instances
  * GUI for viewing and modifying resources
  * Block Storage
  * Manage virtual instances
</summary><br><b>

  * Glance - Images Service. Also used for copying or snapshot instances
  * Horizon - GUI for viewing and modifying resources
  * Cinder - Block Storage
  * Nova - Manage virtual instances
</b></details>

<details>
<summary>What is a tenant/project?</summary><br><b>
</b></details>

<details>
<summary>Determine true or false:

  * OpenStack is free to use
  * The service responsible for networking is Glance
  * The purpose of tenant/project is to share resources between different projects and users of OpenStack</summary><br><b>
</b></details>

<details>
<summary>Describe in detail how you bring up an instance with a floating IP</summary><br><b>
</b></details>

<details>
<summary>You get a call from a customer saying: "I can ping my instance but can't connect (ssh) it". What might be the problem?</summary><br><b>
</b></details>

<details>
<summary>What types of networks OpenStack supports?</summary><br><b>
</b></details>

<details>
<summary>How do you debug OpenStack storage issues? (tools, logs, ...)</summary><br><b>
</b></details>

<details>
<summary>How do you debug OpenStack compute issues? (tools, logs, ...)</summary><br><b>
</b></details>

#### OpenStack Deployment & TripleO

<details>
<summary>Have you deployed OpenStack in the past? If yes, can you describe how you did it?</summary><br><b>
</b></details>

<details>
<summary>Are you familiar with TripleO? How is it different from Devstack or Packstack?</summary><br><b>

You can read about TripleO right [here](https://docs.openstack.org/tripleo-docs/latest)
</b></details>

#### OpenStack Compute

<details>
<summary>Can you describe Nova in detail?</summary><br><b>

  * Used to provision and manage virtual instances
  * It supports Multi-Tenancy in different levels - logging, end-user control, auditing, etc.
  * Highly scalable
  * Authentication can be done using internal system or LDAP
  * Supports multiple types of block storage
  * Tries to be hardware and hypervisor agnostice
</b></details>

<details>
<summary>What do you know about Nova architecture and components?</summary><br><b>

  * nova-api - the server which serves metadata and compute APIs
  * the different Nova components communicate by using a queue (Rabbitmq usually) and a database
  * a request for creating an instance is inspected by nova-scheduler which determines where the instance will be created and running
  * nova-compute is the component responsible for communicating with the hypervisor for creating the instance and manage its lifecycle
</b></details>

#### OpenStack Networking (Neutron)

<details>
<summary>Explain Neutron in detail</summary><br><b>

  * One of the core component of OpenStack and a standalone project
  * Neutron focused on delivering networking as a service
  * With Neutron, users can set up networks in the cloud and configure and manage a variety of network services
  * Neutron interacts with:
      * Keystone - authorize API calls
      * Nova - nova communicates with neutron to plug NICs into a network
      * Horizon - supports networking entities in the dashboard and also provides topology view which includes networking details
</b></details>

<details>
<summary>Explain each of the following components:

  * neutron-dhcp-agent
  * neutron-l3-agent
  * neutron-metering-agent
  * neutron-*-agtent
  * neutron-server</summary><br><b>
 

  * neutron-l3-agent - L3/NAT forwarding (provides external network access for VMs for example)
  * neutron-dhcp-agent - DHCP services
  * neutron-metering-agent - L3 traffic metering
  * neutron-*-agtent - manages local vSwitch configuration on each compute (based on chosen plugin)
  * neutron-server - exposes networking API and passes requests to other plugins if required
</b></details>

<details>
<summary>Explain these network types:

  * Management Network
  * Guest Network
  * API Network
  * External Network</summary><br><b>

  * Management Network - used for internal communication between OpenStack components. Any IP address in this network is accessible only within the datacetner
  * Guest Network - used for communication between instances/VMs
  * API Network - used for services API communication. Any IP address in this network is publicly accessible
  * External Network - used for public communication. Any IP address in this network is accessible by anyone on the internet
</b></details>

<details>
<summary>What is a provider network?</summary><br><b>
</b></details>

<details>
<summary>What components and services exist for L2 and L3?</summary><br><b>
</b></details>

<details>
<summary>What is the ML2 plug-in? Explain its architecture</summary><br><b>
</b></details>

<details>
<summary>What is the L2 agent? How does it works and what is it responsible for?</summary><br><b>
</b></details>

<details>
<summary>What is the L3 agent? How does it works and what is it responsible for?</summary><br><b>
</b></details>

<details>
<summary>Explain what the Metadata agent is responsible for</summary><br><b>
</b></details>

<details>
<summary>What networking entities Neutron supports?</summary><br><b>
</b></details>

<details>
<summary>How do you debug OpenStack networking issues? (tools, logs, ...)</summary><br><b>
</b></details>

#### OpenStack - Glance

<details>
<summary>Explain Glance in detail</summary><br><b>

  * Glance is the OpenStack image service
  * It handles requests related to instances disks and images
  * Glance also used for creating snapshots for quick instances backups
  * Users can use Glance to create new images or upload existing ones
</b></details>

<details>
<summary>Describe Glance architecture</summary><br><b>

  * glance-api - responsible for handling image API calls such as retrieval and storage. It consists of two APIs: 1. registry-api - responsible for internal requests 2. user API - can be accessed publicly
  * glance-registry - responsible for handling image metadata requests (e.g. size, type, etc). This component is private which means it's not available publicly
  * metadata definition service - API for custom metadata
  * database - for storing images metadata
  * image repository - for storing images. This can be a filesystem, swift object storage, HTTP, etc.
</b></details>

#### OpenStack - Swift

<details>
<summary>Explain Swift in detail</summary><br><b>

  * Swift is Object Store service and is an highly available, distributed and consistent store designed for storing a lot of data
  * Swift is distributing data across multiple servers while writing it to multiple disks
  * One can choose to add additional servers to scale the cluster. All while swift maintaining integrity of the information and data replications.
</b></details>

<details>
<summary>Can users store by default an object of 100GB in size?</summary><br><b>

Not by default. Object Storage API limits the maximum to 5GB per object but it can be adjusted.
</b></details>

<details>
<summary>Explain the following in regards to Swift:

  * Container
  * Account
  * Object </summary><br><b>

  * Container - Defines a namespace for objects.
  * Account - Defines a namespace for containers
  * Object - Data content (e.g. image, document, ...)
</b></details>

<details>
<summary>True or False? there can be two objects with the same name in the same container but not in two different containers</summary><br><b>

False. Two objects can have the same name if they are in different containers.
</b></details>

#### OpenStack - Swift

<details>
<summary>Explain Cinder in detail</summary><br><b>

  * Cinder is OpenStack Block Storage service
  * It basically provides used with storage resources they can consume with other services such as Nova
  * One of the most used implementations of storage supported by Cinder is LVM
  * From user perspective this is transparent which means the user doesn't know where, behind the scenes, the storage is located or what type of storage is used
</b></details>

<details>
<summary>Describe Cinder's components</summary><br><b>

  * cinder-api - receives API requests
  * cinder-volume - manages attached block devices
  * cinder-scheduler - responsible for storing volumes
</b></details>

#### OpenStack - Keystone

<details>
<summary>Can you describe the following concepts in regards to Keystone?

  * Role
  * Tenant/Project
  * Service
  * Endpoint
  * Token</summary><br><b>

  * Role - A list of rights and privileges determining what a user or a project can perform
  * Tenant/Project - Logical representation of a group of resources isolated from other groups of resources. It can be an account, organization, ...
  * Service - An endpoint which the user can use for accessing different resources
  * Endpoint - a network address which can be used to access a certain OpenStack service
  * Token - Used for access resources while describing which resources can be accessed by using a scope
</b></details>

<details>
<summary>What are the properties of a service? In other words, how a service is identified?</summary><br><b>

Using:
  * Name
  * ID number
  * Type
  * Description
</b></details>

<details>
<summary>Explain the following:
  * PublicURL
  * InternalURL
  * AdminURL</summary><br><b>

  * PublicURL - Publicly accessible through public internet
  * InternalURL - Used for communication between services 
  * AdminURL - Used for administrative management
</b></details>

<details>
<summary>What is a service catalog?</summary><br><b>

A list of services and their endpoints
</b></details>

<a name="openstack-advanced"></a>
#### :baby: Advanced

#### OpenStack Advanced - Services

<details>
<summary>Describe each of the following services

  * Swift
  * Sahara
  * Ironic
  * Trove
  * Aodh 
  * Ceilometer</summary><br><b>

  * Swift - highly available, distributed, eventually consistent object/blob store
  * Sahara - Manage Hadoop Clusters
  * Ironic - Bare Metal Provisioning
  * Trove - Database as a service that runs on OpenStack
  * Aodh - Alarms Service
  * Ceilometer - Track and monitor usage
</b></details>

<details>
<summary>Identify the service/project used for each of the following:

  * Database as a service which runs on OpenStack
  * Bare Metal Provisioning
  * Track and monitor usage
  * Alarms Service
  * Manage Hadoop Clusters
  * highly available, distributed, eventually consistent object/blob store</summary><br><b>

  * Database as a service which runs on OpenStack - Trove
  * Bare Metal Provisioning - Ironic
  * Track and monitor usage - Ceilometer
  * Alarms Service - Aodh
  * Manage Hadoop Clusters
  * Manage Hadoop Clusters - Sahara
  * highly available, distributed, eventually consistent object/blob store - Swift
</b></details>

#### OpenStack Advanced - Keystone

<details>
<summary>Can you describe Keystone service in detail?</summary><br><b>

  * You can't have OpenStack deployed without Keystone
  * It Provides identity, policy and token services
    * The authentication provided is for both users and services
    * The authorization supported is token-based and user-based.
  * There is a policy defined based on RBAC stored in a JSON file and each line in that file defines the level of access to apply
</b></details>

<details>
<summary>Describe Keystone architecture</summary><br><b>

  * There is a service API and admin API through which Keystone gets requests
  * Keystone has four backends:
    * Token Backend - Temporary Tokens for users and services
    * Policy Backend - Rules management and authorization
    * Identity Backend - users and groups (either standalone DB, LDAP, ...)
    * Catalog Backend - Endpoints
  * It has pluggable environment where you can integrate with:
    * LDAP
    * KVS (Key Value Store)
    * SQL
    * PAM
    * Memcached
</b></details>

<details>
<summary>Describe the Keystone authentication process</summary><br><b>

  * Keystone gets a call/request and checks whether it's from an authorized user, using username, password and authURL
  * Once confirmed, Keystone provides a token.
  * A token contains a list of user's projects so there is no to authenticate every time and a token can submitted instead
</b></details>

#### OpenStack Advanced - Compute (Nova)

<details>
<summary>What each of the following does?:

  * nova-api
  * nova-compuate
  * nova-conductor
  * nova-cert
  * nova-consoleauth
  * nova-scheduler</summary><br><b>

  * nova-api - responsible for managing requests/calls
  * nova-compute - responsible for managing instance lifecycle
  * nova-conductor - Mediates between nova-compute and the database so nova-compute doesn't access it directly
</b></details>

<details>
<summary>What types of Nova proxies are you familiar with?</summary><br><b>

  * Nova-novncproxy - Access through VNC connections
  * Nova-spicehtml5proxy - Access through SPICE 
  * Nova-xvpvncproxy - Access through a VNC connection
</b></details>

#### OpenStack Advanced - Networking (Neutron)

<details>
<summary>Explain BGP dynamic routing</summary><br><b>
</b></details>

<details>
<summary>What is the role of network namespaces in OpenStack?</summary><br><b>
</b></details>

#### OpenStack Advanced - Horizon

<details>
<summary>Can you describe Horizon in detail?</summary><br><b>

  * Django-based project focusing on providing an OpenStack dashboard and the ability to create additional customized dashboards
  * You can use it to access the different OpenStack services resources - instances, images, networks, ...
    * By accessing the dashboard, users can use it to list, create, remove and modify the different resources
  * It's also highly customizable and you can modify or add to it based on your needs
</b></details>

<details>
<summary>What can you tell about Horizon architecture?</summary><br><b>

  * API is backward compatible
  * There are three type of dashboards: user, system and settings
  * It provides core support for all OpenStack core projects such as Neutron, Nova, etc. (out of the box, no need to install extra packages or plugins)
  * Anyone can extend the dashboards and add new components
  * Horizon provides templates and core classes from which one can build its own dashboard
</b></details>

## Security

<a name="security-beginner"></a>
#### :baby: Beginner

<details>
<summary>Can you describe the DevSecOps core principals? (or what is DevSecOps)</summary><br><b>
</b></details>

<details>
<summary>What DevOps security best practices are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What security techniques are you familiar with? (or what security techniques you used in the past?)</summary><br><b>
</b></details>

<details>
<summary>Explain Authentication and Authorization</summary><br><b>

Authentication is the process of identifying whether a service or a person is who they claim to be.
Authorization is the process of identifying what level of access the service or the person have (after authentication was done)
</b></details>

<details>
<summary>How do you manage passwords in different tools and platforms?</summary><br><b>
</b></details>

<details>
<summary>Explain what is Single Sign-On</summary><br><b>

SSO (Single Sign-on), is a method of access control that enables a user to log in once and gain access to the resources of multiple software systems without being prompted to log in again.


</b></details>

<details>
<summary>Explain MFA (Multi-Factor Authentication)</summary><br><b>

Multi-Factor Authentication (Also known as 2FA). Allows the user to present two pieces of evidence, credentials, when logging into an account.

- The credentials fall into any of these three categories: something you know (like a password or PIN), something you have (like a smart card), or something you are (like your fingerprint).  Credentials must come from two different categories to enhance security.

</b></details>

<details>
<summary>Explain RBAC (Role-based Access Control)</summary><br><b>

Access control based on user roles (i.e., a collection of access authorizations a user receives based on an explicit or implicit assumption of a given role). Role permissions may be inherited through a role hierarchy and typically reflect the permissions needed to perform defined functions within an organization. A given role may apply to a single individual or to several individuals.

- RBAC mapped to job function, assumes that a person will take on different roles, overtime, within an organization and different responsibilities in relation to IT systems.

</b></details>

<details>
<summary>Explain Symmetric encryption</summary><br><b>

A symmetric encryption is any technique where the same key is used to both encrypt and decrypt the data. 

</b></details>

<details>
<summary>Explain Asymmetric encryption</summary><br><b>

A asymmetric encryption is any technique where the there is two different keys that are used for encryption and decryption, these keys are known as public key and private key.

</b></details>


<details>
<summary>Explain the following:

  * Vulnerability
  * Exploits
  * Risk
  * Threat</summary><br><b>
</b></details>

<details>
<summary>What is XSS?</summary><br><b>

Cross Site Scripting (XSS) is an type of a attack when the attacker inserts browser executable code within a HTTP response. Now the injected attack is not stored in the web application, it will only affact the users who open the maliciously crafted link or third-party web page. A successful attack allows the attacker to access any cookies, session tokens, or other sensitive information retained by the browser and used with that site 

You can test by detecting user-defined variables and how to input them. This includes hidden or non-obvious inputs such as HTTP parameters, POST data, hidden form field values, and predefined radio or selection values. You then analyze each found vector to see if their are potential vulnerabilities, then when found you craft input data with each input vector. Then you test the crafted input and see if it works.
	
</b></details>

<details>
<summary>What is an SQL injection? How to manage it?</summary><br><b>

SQL injection is an attack consists of inserts either a partial or full SQL query through data input from the browser to the web application. When a successful SQL injection happens it will allow the attacker to read sensitive information stored on the database for the web application. 

You can test by using a stored procedure, so the application must be sanitize the user input to get rid of the tisk of code injection. If not then the user could enter bad SQL, that will then be executed within the procedure

</b></details>

<details>
<summary>What is Certification Authority?</summary><br><b>
</b></details>

<details>
<summary>How do you identify and manage vulnerabilities?</summary><br><b>
</b></details>

<details>
<summary>Explain "Privilege Restriction"</summary><br><b>
</b></details>

<details>
<summary>How HTTPS is different from HTTP?</summary><br><b>
</b></details>

<details>
<summary>What types of firewalls are there?</summary><br><b>
</b></details>

<details>
<summary>What is DDoS attack? How do you deal with it?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between asynchronous and synchronous encryption?</summary><br><b>
</b></details>

<details>
<summary>Explain Man-in-the-middle attack</summary><br><b>
</b></details>

<details>
<summary>Explain CVE and CVSS</summary><br><b>
</b></details>

<details>
<summary>What is ARP Poisoning?</summary><br><b>
</b></details>

<details>
<summary>Describe how do you secure public repositories</summary><br><b>
</b></details>

<details>
<summary>How do cookies work?</summary><br><b>
</b></details>

<details>
<summary>What is DNS Spoofing? How to prevent it?</summary><br><b>

DNS spoofing occurs when a particular DNS server’s records of “spoofed” or altered maliciously to redirect traffic to the attacker. This redirection of traffic allows the attacker to spread malware, steal data, etc.

**Prevention**
- Use encrypted data transfer protocols - Using end-to-end encryption vian SSL/TLS will help decrease the chance that a website / its visitors are compromised by DNS spoofing. 
- Use DNSSEC - DNSSEC, or Domain Name System Security Extensions, uses digitally signed DNS records to help determine data authenticity.
- Implement DNS spoofing detection mechanisms - it’s important to implement DNS spoofing detection software. Products such as XArp help product against ARP cache poisoning by inspecting the data that comes through before transmitting it.

</b></details>

<details>
<summary>What can you tell me about Stuxnet?</summary><br><b>

Stuxnet is a computer worm that was originally aimed at Iran’s nuclear facilities and has since mutated and spread to other industrial and energy-producing facilities. The original Stuxnet malware attack targeted the programmable logic controllers (PLCs) used to automate machine processes. It generated a flurry of media attention after it was discovered in 2010 because it was the first known virus to be capable of crippling hardware and because it appeared to have been created by the U.S. National Security Agency, the CIA, and Israeli intelligence.


</b></details>

<details>
<summary>What can you tell me about Spectre?</summary><br><b>

Spectre is an attack method which allows a hacker to “read over the shoulder” of a program it does not have access to. Using code, the hacker forces the program to pull up its encryption key allowing full access to the program

</b></details>

<details>
<summary>Explain OAuth</summary><br><b>
</b></details>

<details>
<summary>Explain "Format String Vulnerability"</summary><br><b>
</b></details>


<details>
<summary>Explain DMZ</summary><br><b>
</b></details>

<details>
<summary>Explain TLS</summary><br><b>
</b></details>

<details>
<summary>What is CSRF? How to handle CSRF?</summary><br><b>

Cross-Site Request Forgery (CSRF) is an attack that makes the end user to initate a unwanted action on the web application in which the user has a authenticated session, the attacker may user an email and force the end user to click on the link and that then execute malicious actions. When an CSRF attack is successful it will compromise the end user data 

You can use OWASP ZAP to analyze a "request", and if it appears that there no protection against cross-site request forgery when the Security Level is set to 0 (the value of csrf-token is SecurityIsDisabled.) One can use data from this request to prepare a CSRF attack by using OWASP ZAP
	
</b></details>

<details>
<summary>Explain HTTP Header Injection vulnerability</summary><br><b>

HTTP Header Injection vulnerabilities occur when user input is insecurely included within server responses headers. If an attacker can inject newline characters into the header, then they can inject new HTTP headers and also, by injecting an empty line, break out of the headers into the message body and write arbitrary content into the application's response.

</b></details>

<details>
<summary>What security sources are you using to keep updated on latest news?</summary><br><b>
</b></details>

<details>
<summary>What TCP and UDP vulnerabilities are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Do using VLANs contribute to network security?</summary><br><b>
</b></details>

<details>
<summary>What are some examples of security architecture requirements?</summary><br><b>
</b></details>

<details>
<summary>What is air-gapped network (or air-gapped environment)? What its advantages and disadvantages?</summary><br><b>
</b></details>

<details>
<summary>Explain what is Buffer Overflow</summary><br><b>

A buffer overflow (or buffer overrun) occurs when the volume of data exceeds the storage capacity of the memory buffer. As a result, the program attempting to write the data to the buffer overwrites adjacent memory locations.
</b></details>

##### Containers

<details>
<summary>What security measures are you taking when dealing with containers?</summary><br><b>
</b></details>

<details>
<summary>Explain what is Docker Bench</summary><br><b>
</b></details>

<a name="security-advanced"></a>
#### :baby: Advanced

<details>
<summary>Explain MAC flooding attack</summary><br><b>

MAC address flooding attack (CAM table flooding attack) is a type of network attack where an attacker connected to a switch port floods the switch interface with very large number of Ethernet frames with different fake source MAC address.

</b></details>

<details>
<summary>What is port flooding?</summary><br><b>
</b></details>

<details>
<summary>What is "Diffie-Hellman key exchange" and how does it work?</summary><br><b>
</b></details>

<details>
<summary>Explain "Forward Secrecy"</summary><br><b>
</b></details>

<details>
<summary>What is Cache Poisoned Denial of Service?</summary><br><b>

CPDoS or Cache Poisoned Denial of Service. It poisons the CDN cache. By manipulating certain header requests, the attacker forces the origin server to return a Bad Request error which is stored in the CDN’s cache. Thus, every request that comes after the attack will get an error page. 

</b></details>

## Puppet

<a name="puppet-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Puppet? How does it works?</summary><br><b>
</b></details>

<details>
<summary>Explain Puppet architecture</summary><br><b>
</b></details>

<details>
<summary>Can you compare Puppet to other configuration management tools? Why did you chose to use Puppet?</summary><br><b>
</b></details>

<details>
<summary>Explain the following:

  * Module
  * Manifest
  * Node</summary><br><b>
</b></details>

<details>
<summary>Explain Facter</summary><br><b>
</b></details>

<details>
<summary>What is MCollective?</summary><br><b>
</b></details>

<a name="puppet-advanced"></a>
#### :baby: Advanced

<details>
<summary>Do you have experience with writing modules? Which module have you created and for what?</summary><br><b>
</b></details>

<details>
<summary>Explain what is Hiera</summary><br><b>
</b></details>

## Elastic

<details>
<summary>What is the Elastic Stack?</summary><br><b>

The Elastic Stack consists of:

  * Elasticsearch
  * Kibana
  * Logstash
  * Beats
  * Elastic Hadoop
  * APM Server

Elasticserach, Logstash and Kibana are also known as the ELK stack.
</b></details>

<details>
<summary>Explain what is Elasticsearch</summary><br><b>

From the official [docs](https://www.elastic.co/guide/en/elasticsearch/reference/current/documents-indices.html):

"Elasticsearch is a distributed document store. Instead of storing information as rows of columnar data, Elasticsearch stores complex data structures that have been serialized as JSON documents"
</b></details>

<details>
<summary>What is Logstash?</summary><br><b>
</b></details>

<details>
<summary>Explain what beats are</summary><br><b>

Beats are lightweight data shippers. These data shippers installed on the client where the data resides.
Examples of beats: Filebeat, Metricbeat, Auditbeat. There are much more.<br>
</b></details>

<details>
<summary>What is Kibana?</summary><br><b>

From the official docs:

"Kibana is an open source analytics and visualization platform designed to work with Elasticsearch. You use Kibana to search, view, and interact with data stored in Elasticsearch indices. You can easily perform advanced data analysis and visualize your data in a variety of charts, tables, and maps."
</b></details>

<details>
<summary>Describe what happens from the moment an app logged some information until it's displayed to the user in a dashboard when the Elastic stack is used</summary><br><b>  

The process may vary based on the chosen architecture and the processing you may want to apply to the logs. One possible workflow is:

1. The data logged by the application is picked by filebeat and sent to logstash
2. Logstash process the log based on the defined filters. Once done, the output is sent to Elasticsearch
2. Elasticsearch stores the document it got and the document is indexed for quick future access
4. The user creates visualizations in Kibana which based on the indexed data
5. The user creates a dashboard which composed out of the visualization created in the previous step
</b></details>

##### Elasticsearch

<details>
<summary>What is a data node?</summary><br><b>

This is where data is stored and also where different processing takes place (e.g. when you search for a data).
</b></details>

<details>
<summary>What is a master node?</summary><br><b>

Par of a master node responsibilites:
  * Track the status of all the nodes in the cluster
  * Verify replicas are working and the data is available from every data node.
  * No hot nodes (no data node that works much harder than other nodes)

While there can be multiple master nodes in reality only of them is the elected master node.
</b></details>

<details>
<summary>What is an ingest node?</summary><br><b>

A node which responsible for parsing the data. In case you don't use logstash then this node can recieve data from beats and parse it, similarly to how it can be parsed in Logstash.
</b></details>

<details>
<summary>What is Coordinating node?</summary><br><b>

A Coordinating node responsible for routing requests out and in to the cluser (data nodes).
</b></details>

<details>
<summary>How data is stored in elasticsearch?</summary><br><b>

* Data is stored in an index
* The index is spread across the cluster using shards
</b></details>

<details>
<summary>What is an Index?</summary><br><b>

Index in Elastic is in most cases compared to a whole database from the SQL/NoSQL world.<br>
You can choose to have one index to hold all the data of your app or have multiple indices where each index holds different type of your app (e.g. index for each service your app is running).

The official docs also offer a great explanation (in general, it's really good documentation, as every project should have):

"An index can be thought of as an optimized collection of documents and each document is a collection of fields, which are the key-value pairs that contain your data"
</b></details>

<details>
<summary>Explain Shards</summary><br><b>

An index is split into shards and documents are hashed to a particular shard. Each shard may be on a different node in a cluster and each one of the shards is a self contained index.<br>
This allows Elasticsearch to scale to an entire cluster of servers.
</b></details>

<details>
<summary>What is an Inverted Index?</summary><br><b>

From the official docs:

"An inverted index lists every unique word that appears in any document and identifies all of the documents each word occurs in."
</b></details>

<details>
<summary>What is a Document?</summary><br><b>

Continuing with the comparison to SQL/NoSQL a Document in Elastic is a row in table in the case of SQL or a document in a collection in the case of NoSQL.
As in NoSQL a Document is a JSON object which holds data on a unit in your app. What is this unit depends on the your app. If your app related to book then each document describes a book. If you are app is about shirts then each document is a shirt.
</b></details>

<details>
<summary>You check the health of your elasticsearch cluster and it's red. What does it mean? What can cause the status to be yellow instead of green?</summary><br><b>

Red means some data is unavailable.
Yellow can be caused by running single node cluster instead of multi-node.
</b></details>

<details>
<summary>True or False? Elasticsearch indexes all data in every field and each indexed field has the same data structure for unified and quick query ability</summary><br><b>

False.
From the official docs:

"Each indexed field has a dedicated, optimized data structure. For example, text fields are stored in inverted indices, and numeric and geo fields are stored in BKD trees."
</b></details>

<details>
<summary>What reserved fields a document has?</summary><br><b>

  * _index
  * _id
  * _type
</b></details>

<details>
<summary>Explain Mapping</summary><br><b>
</b></details>

<details>
<summary>What are the advantages of defining your own mapping? (or: when would you use your own mapping?)</summary><br><b>

* You can optimize fields for partial matching
* You can define custom formats of known fields (e.g. date)
* You can perform language-specific analysis
</b></details>

<details>
<summary>Explain Replicas</summary><br><b>

In a network/cloud environment where failures can be expected any time, it is very useful and highly recommended to have a failover mechanism in case a shard/node somehow goes offline or disappears for whatever reason.
To this end, Elasticsearch allows you to make one or more copies of your index’s shards into what are called replica shards, or replicas for short.
</b></details>

<details>
<summary>Can you explain Term Frequency & Document Frequency?</summary><br><b>

Term Frequency is how often a term appears in a given document and Document Frequency is how often a term appears in all documents. They both are used for determining the relevance of a term by calculating Term Frequency / Document Frequency.
</b></details>

<details>
<summary>You check "Current Phase" under "Index lifecycle management" and you see it's set to "hot". What does it mean?</summary><br><b>

"The index is actively being written to".
More about the phases [here](https://www.elastic.co/guide/en/elasticsearch/reference/7.6/ilm-policy-definition.html)
</b></details>

<details>
<summary>What this command does? <code>curl -X PUT "localhost:9200/customer/_doc/1?pretty" -H 'Content-Type: application/json' -d'{ "name": "John Doe" }'</code></summary><br><b>

It creates customer index if it doesn't exists and adds a new document with the field name which is set to "John Dow". Also, if it's the first document it will get the ID 1.
</b></details>

<details>
<summary>What will happen if you run the previous command twice? What about running it 100 times?</code></summary><br><b>

1. If name value was different then it would update "name" to the new value
2. In any case, it bumps version field by one
</b></details>

<details>
<summary>What is the Bulk API? What would you use it for?</code></summary><br><b>

Bulk API is used when you need to index multiple documents. For high number of documents it would be significantly faster to use rather than individual requests since there are less network roundtrips.
</b></details>

##### Query DSL

<details>
<summary>Explain Elasticsearch query syntax (Booleans, Fields, Ranges)</summary><br><b>
</b></details>

<details>
<summary>Explain what is Relevance Score</summary><br><b>
</b></details>

<details>
<summary>Explain Query Context and Filter Context</summary><br><b>

From the official docs:

"In the query context, a query clause answers the question “How well does this document match this query clause?” Besides deciding whether or not the document matches, the query clause also calculates a relevance score in the _score meta-field."

"In a filter context, a query clause answers the question “Does this document match this query clause?” The answer is a simple Yes or No — no scores are calculated. Filter context is mostly used for filtering structured data"
</b></details>

##### Logstash

<details>
<summary>What are Logstash plugins? What plugins types are there?</summary><br><b>

  * Input Plugins - how to collect data from different sources
  * Filter Plugins - processing data
  * Output Plugins - push data to different outputs/services/platforms
</b></details>

<details>
<summary>What is grok?</summary><br><b>

A logstash plugin which modifies information in one format and immerse it in another.
</b></details>

<details>
<summary>How grok works?</summary><br><b>
</b></details>

<details>
<summary>What grok patterns are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What is `_grokparsefailure?`</summary><br><b>
</b></details>

<details>
<summary>How do you test or debug grok patterns?</summary><br><b>
</b></details>

<details>
<summary>What are Logstash Codecs? What codecs are there?</summary><br><b>
</b></details>

##### Kibana

<details>
<summary>What can you find under "Discover" in Kibana?</summary><br><b>

The raw data as it is stored in the index. You can search and filter it.
</b></details>

<details>
<summary>You see in Kibana, after clicking on Discover, "561 hits". What does it mean?</summary><br><b>

Total number of documents matching the search results. If not query used then simply the total number of documents.
</b></details>

<details>
<summary>What can you find under "Visualize"?</summary><br><b>

"Visualize" is where you can create visual representations for your data (pie charts, graphs, ...)
</b></details>

<details>
<summary>What visualization types are supported/included in Kibana?</summary><br><b>
</b></details>

<details>
<summary>What visualization type would you use for statistical outliers</summary><br><b>
</b></details>

<details>
<summary>Describe in detail how do you create a dashboard in Kibana</summary><br><b>
</b></details>

#### Beats

<details>
<summary>What is Filebeat?</summary><br><b>
</b></details>

<details>
<summary>If one is using ELK, is it a must to also use filebeat? In what scenarios it's useful to use filebeat?</summary><br><b>
</b></details>

<details>
<summary>What are filebeat modules?</summary><br><b>
</b></details>

<details>
<summary>Describe how would an architecture of production environment with large amounts of data would be different from a small-scale environment</summary><br><b>

There are several possible answers for this question. One of them is as follows:

A small-scale architecture of elastic will consist of the elastic stack as it is. This means we will have beats, logstash, elastcsearch and kibana.<br>
A production environment with large amounts of data can include some kind of buffering component (e.g. Reddis or RabbitMQ) and also security component such as Nginx.
</b></details>

#### Elastic Stack

<details>
<summary>How do you secure an Elastic Stack?</summary><br><b>

You can generate certificates with the provided elastic utils and change configuration to enable security using certificates model.
</b></details>

## DNS

<a name="dns-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is DNS? What is it used for?</summary><br><b>

DNS (Domain Name Systems) is a protocol used for converting domain names into IP addresses.<br>
As you know computer networking is done with IP addresses (layer 3 of the OSI model) but for as humans it's hard to remember IP addresses, it's much easier to remember names. This why we need something such as DNS to convert any domain name we type into an IP address. You can think on DNS as a huge phonebook or database where each corresponding name has an IP.
</b></details>

<details>
<summary>How DNS works?</summary><br><b>

In general the process is as follows:

  * The user types an address in the web browser (some_site.com)
  * The operating system gets a request from the browser to translate the address the user entered
  * A query created to check a local entry of the address exists in the system. In case it doesn't, the request is forwarded to the DNS resolver
  * The Resolver is a server, usually configured by your ISP when you connect to the internet, that responsible for resolving your query by contacting other DNS servers
  * The Resolver contacts the root nameserver (aka as .)
  * The root nameserver responds with the address of the relevant Top Level Domain DNS server (if your address ends with org then the org TLD)
  * The Resolver then contacts the TLD DNS and TLD DNS responds with the IP address that matches the address the user typed in the browser
  * The Resolver passes this information to the browser
  * The user is happy :D
</b></details>

<details>
<summary>Explain the resolution sequence of: www.site.com</summary><br><b>

It's resolved in this order:

1) .
2) .com
3) site.com
4) www.site.com
</b></details>

<details>
<summary>What types of DNS records are there?</summary><br><b>

  * A
  * PTR
  * MX
  * AAAA
</b></details>

<details>
<summary>What is a A record?</summary><br><b>

A (Address) Maps a host name to an IP address. When a computer has multiple adapter cards and IP addresses, it should have multiple address records.
</b></details>

<details>
<summary>What is a AAAA record?</summary><br><b>
	
An AAAA Record performs the same function as an A Record, but for an IPv6 Address.
</b></details>

<details>
<summary>What is a PTR record?</summary><br><b>

While an A record points a domain name to an IP address, a PTR record does the opposite and resolves the IP address to a domain name.
</b></details>

<details>
<summary>What is a MX record?</summary><br><b>
MX (Mail Exchange) Specifies a mail exchange server for the domain, which allows mail to be delivered to the correct mail servers in the domain.
</b></details>

<details>
<summary>Is DNS using TCP or UDP?</summary><br><b>
DNS uses UDP port 53 for resolving queries either regular or reverse. DNS uses TCP for zone transfer. 
</b></details>

<details>
<summary>What is Round Robin DNS?</summary><br><b>
</b></details>

<details>
<summary>What is DNS Record TTL? Why do we need it?</summary><br><b>
</b></details>

<details>
<summary>What is a zone? What types of zones are there?</summary><br><b>
</b></details>

## Distributed

<details>
<summary>Explain Distributed Computing (or Distributed System)</summary><br><b>

According to Martin Kleppmann:

"Many processes running on many machines...only message-passing via an unreliable network with variable delays, and the system may suffer from partial failures, unreliable clocks, and process pauses."

Another definition: "Systems that are physically separated, but logically connected"
</b></details>

<details>
<summary>What can cause a system to fail?</summary><br><b>

* Network
* CPU
* Memory
* Disk
</b></details>

<details>
<summary>Do you know what is "CAP theorem"? (aka as Brewer's theorem)</summary><br><b>

According to the CAP theorem, it's not possible for a distributed data store to provide more than two of the following at the same time:

* Availability: Every request receives a response (it doesn't has to be the most recent data)
* Consistency: Every request receives a response with the latest/most recent data
* Partition tolerance: Even if some the data is lost/dropped, the system keeps running 
</b></details>

<details>
<summary>What are the problems with the following design? How to improve it?<br>
<img src="images/distributed/distributed_design_standby.png" width="500x;" height="350px;"/>
</summary><br><b>
1. The transition can take time. In other words, noticeable downtime.
2. Standby server is a waste of resources - if first application server is running then the standby does nothing
</b></details>

<details>
<summary>What are the problems with the following design? How to improve it?<br>
<img src="images/distributed/distributed_design_lb.png" width="700x;" height="350px;"/>
</summary><br><b>
Issues:
If load balancer dies , we lose the ability to communicate with the application.

Ways to improve:
* Add another load balancer
* Use DNS A record for both load balancers
* Use message queue
</b></details>

<details>
<summary>What is "Shared-Nothing" architecture?</summary><br><b>

It's an architecture in which data is and retrieved from a single, non-shared, source usually exclusively connected to one node as opposed to architectures where the request can get to one of many nodes and the data will be retrieved from one shared location (storage, memory, ...).
</b></details>

<details>
<summary>Explain the Sidecar Pattern (Or sidecar proxy)</summary><br><b>
</b></details>

## General

<details>
<summary>What is a server?</summary><br><b>

A computer which serves data from itself to the client.
</b></details>

<details>
<summary>Define or Explain what is an API</summary><br><b>

I like this definition from [here](https://blog.christianposta.com/microservices/api-gateways-are-going-through-an-identity-crisis):

"An explicitly and purposefully defined interface designed to be invoked over a network that enables software developers to get programmatic access to data and functionality within an organization in a controlled and comfortable way."
</b></details>

<details>
<summary>What is latency?</summary><br><b>
</b></details>

<details>
<summary>What is bandwidth?</summary><br><b>
</b></details>

<details>
<summary>What is throughput?</summary><br><b>
</b></details>

<details>
<summary>When performing a search query, what is more important, latency or throughput? And how to assure that what managing global infrastructure?</summary><br><b>

Latency. To have a good latency, a search query should be forwarded to the closest datacenter.
</b></details>

<details>
<summary>When uploading a video, what is more important, latency or throughput? And how to assure that?</summary><br><b>

Throughput. To have a good throughput, the upload stream should be routed to an underutilized link.
</b></details>

<details>
<summary>What other considerations (except latency and throughput) are there when forwarding requests?</summary><br><b>

* Keep caches updated (which means the request could be forwarded not to the closest datacenter)
</b></details>

#### Jira

<details>
<summary>Explain/Demonstrate the following types in Jira:

  * Epic
  * Story
  * Task</summary><br><b>
</b></details>

<details>
<summary>What is a project in Jira?</summary><br><b>
</b></details>

#### Kafka

<details>
<summary>What is Kafka?</summary><br><b>
</b></details>

<details>
<summary>In Kafka, how to automatically balance brokers leadership of partitions in a cluster?

  * Enable auto leader election and reduce the imbalance
percentage ratio
  * Manually rebalance by using kafkat
  * Configure group.initial.rebalance.delay.ms to 3000
  * All of the above
</summary><br><b>
</b></details>

#### Cassandra

<details>
<summary>When running a cassandra cluster, how often do you need to run nodetool repair in order to keep the cluster consistent?

  * Within the columnFamily GC-grace Once a week
  * Less than the compacted partition minimum bytes
  * Depended on the compaction strategy
</summary><br><b>
</b></details>

#### HTTP

<details>
<summary>What is HTTP?</summary><br><b>
</b></details>

<details>
<summary>Describe HTTP request lifecycle</summary><br><b>

* Resolve host by request to DNS resolver
* Client SYN
* Server SYN+ACK
* Client SYN
* HTTP request
* HTTP response
</b></details>

<details>
<summary>True or False? HTTP is stateful</summary><br><b>

False. Server doesn't maintain state for incoming request.
</b></details>

<details>
<summary>How HTTP request looks like?</summary><br><b>

It consits of:

 * Request line - request type
 * Headers - content info like length, enconding, etc.
 * Body (not always included)
</b></details>

<details>
<summary>What HTTP method types are there?</summary><br><b>

* GET
* POST
* HEAD
* PUT
* DELETE
* CONNECT
* OPTIONS
* TRACE
</b></details>

<details>
<summary>What HTTP response codes are there?</summary><br><b>

* 1xx - informational
* 2xx - Success
* 3xx - Redirect
* 4xx - Error, client fault
* 5xx - Error, server fault
</b></details>

<details>
<summary>What is HTTPS?</summary><br><b>
</b></details>

<details>
<summary>Explain HTTP Cookies</summary><br><b>

HTTP is stateless. To share state, we can use Cookies.

TODO: explain what is actually a Cookie
</b></details>

<details>
<summary>What is HTTP Pipelining?</summary><br><b> 
</b></details>

<details>
<summary>What is a proxy?</summary><br><b> 
</b></details>

<details>
<summary>What is a reverse proxy?</summary><br><b> 
</b></details>

<details>
<summary>What is CDN?</summary><br><b> 
</b></details>

<details>
<summary>When you publish a project, you usually publish it with a license. What types of licenses are you familiar with and which one do you prefer to use?</summary><br><b>
</b></details>

#### Load Balancers

<details>
<summary>What is a load balancer?</summary><br><b> 
</b></details>

<details>
<summary>What load balancer algorithms are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What is an Application Load Balancer?</summary><br><b>
</b></details>

<details>
<summary>What is DNS load balancing? What its advantages? When would you use it?</summary><br><b>
</b></details>

<details>
<summary>What are sticky sessions?</summary><br><b>

Recommended read:
  * [Red Hat Article](https://access.redhat.com/solutions/900933)
</b></details>

<details>
<summary>What are the cons and pros of sticky sessions?</summary><br><b>

Cons:
  * Can cause uneven load on instance (since requests routed to the same instances)
Pros:
  * Ensures in-proc sessions are not lost when a new request is created
</b></details>

#### Licenses

<details>
<summary>Are you familiar with "Creative Commons"? What do you know about it?</summary><br><b>
</b></details>

<details>
<summary>Explain the differences between copyleft and permissive licenses</summary><br><b>

In Copyleft, any derivative work must use the same licensing while in permissive licensing there are no such condition. GPL-3 is an example of copyleft license while BSD is an example of permissive license.
</b></details>

#### Random

<details>
<summary>How a search engine works?</summary><br><b>
</b></details>

<details>
<summary>What is faster than RAM?</summary><br><b>
</b></details>

<details>
<summary>What is a memory leak?</summary><br><b>
</b></details>

<details>
<summary>What is your favorite protocol?</summary><br><b>

SSH
HTTP
DHCP
DNS
...
</b></details>

<details>
<summary>What is Cache API?</summary><br><b>
</b></details>

<details>
<summary>What is the C10K problem? Is it relevant today?</summary><br><b>

https://idiallo.com/blog/c10k-2016
</b></details>

## HR

These are not DevOps related questions as you probably noticed, but since they are part of the DevOps interview process I've decided it might be good to keep them

<details>
<summary>Tell us little bit about yourself</summary><br><b>
</b></details>

<details>
<summary>Tell me about your last big project/task you worked on</summary><br><b>
</b></details>

<details>
<summary>What was most challenging part in the project you worked on?</summary><br><b>
</b></details>

<details>
<summary>Why do you want to work here?</summary><br><b>
</b></details>

<details>
<summary>How did you hear about us?</summary><br><b>

Tell them how did you hear about them :D
Relax, there is no wrong or right answer here...I think.
</b></details>

<details>
<summary>How would you describe a good leadership? What makes a good boss for you?</summary><br><b>
</b></details>

<details>
<summary>Tell me about a time where you didn't agree on an implementation</summary><br><b>
</b></details>

<details>
<summary>How do you deal with a situation where key stakeholders are not around and a big decision needs to be made? </summary><br><b>
</b></details>

<details>
<summary>Where do you see yourself in 5 years?</summary><br><b>

Some ideas (some of them bad and should not be used):

* Senior DevOps
* Manager
* Retirement
* Your manager
</b></details>

<details>
<summary>Give an example of a time when you were able to change the view of a team about a particular tool/project/technology</summary><br><b>
</b></details>

<details>
<summary>Have you ever caused a service outage? (or broke a working project, tool, ...?)</summary><br><b>

If you worked in this area for more than 5 years it's hard to imagine the answer would be no. It also doesn't have to be big service outage. Maybe you merged some code that broke a project or its tests. Simply focus on what you learned from such experience.
</b></details>

<details>
<summary>Rank the following in order 1 to 5, where 1 is most important: salaray, benefits, career, team/people, work life balance</summary><br><b>

You know best your order just have a good thought if you really want to put salary in top or bottom....
</b></details>

<details>
<summary>You have three important tasks scheduled for today. One is for your boss, second for a colleague who is also a friend, third is for a customer. All tasks are equally important. What do you do first?</summary><br><b>
</b></details>

<details>
<summary>You have a colleague you don‘t get along with. Tell us some strategies how you create a good work relationship with them anyway.</summary><br><b>

Bad answer: I don't.
Better answer: Every person has strengths and weaknesses. This is true also for colleagues I don't have good work relationship with and this is what helps me to create good work relationship with them. If I am able to highlight or recognize their strengths I'm able to focus mainly on that when communicating with them.
</b></details>

<details>
<summary>What do you love about your work?</summary><br><b>

You know the best, but some ideas if you find it hard to express yourself:

* Diversity
* Complexity
* Challenging
* Communication with several different teams
</b></details>

<details>
<summary>What are your responsibilities in your current position?</summary><br><b>

You know the best :)
</b></details>

<details>
<summary>Why should we hire you for the role?</summary><br><b>

You can use and elaborate on one or all of the following:

* Passion
* Motivation 
* Autodidact
* Creativity (be able to support it with some actual examples)
</b></details>

#### Team Lead

<details>
<summary>How would you improve productivity in your team?</summary><br><b>
</b></details>

## Questions you CAN ask

<a name="questions-you-ask"></a>

A list of questions you as a candidate can ask the interviewer during or after the interview.
These are only a suggestion, use them carefully. Not every interviewer will be able to answer these (or happy to) which should be perhaps a red flag warning for your regarding working in such place but that's really up to you.

<details>
<summary>What do you like about working here?</summary><br><b>
</b></details>

<details>
<summary>How does the company promote personal growth?</summary><br><b>
</b></details>

<details>
<summary>What is the current level of technical debt you are dealing with?</summary><br><b>

Be careful when asking this question - all companies, regardless of size, have some level of tech debt. 
Phrase the question in the light that all companies have the deal with this, but you want to see the current
pain points they are dealing with <br>

This is a great way to figure how managers deal with unplanned work, and how good they are at 
setting expectations with projects.
</b></details>

<details>
<summary>Why I should NOT join you? (or 'what you don't like about working here?')</summary><br><b>
</b></details>

<details>
<summary>What was your favorite project you've worked on?</summary><br><b>

This can give you insights in some of the cool projects a company is working on, and if 
you would enjoy working on projects like these. This is also a good way to see if
the managers are allowing employees to learn and grow with projects outside of the
normal work you'd do.
</b></details>

<details>
<summary>If you could change one thing about your day to day, what would it be?</summary><br><b>

Similar to the tech debt question, this helps you identify any pain points with the company.
Additionally, it can be a great way to show how you'd be an asset to the team.<br>

For Example, if they mention they have problem X, and you've solved that in the past,
you can show how you'd be able to mitigate that problem.
</b></details>

<details>
<summary>Let's say that we agree and you hire me to this position, after X months, what do you expect that I have achieved?</summary><br><b>

Not only this will tell you what is expected from you, it will also provide big hint on the type of work you are going to do in the first months of your job.
</b></details>

## Testing

<details>
<summary>Explain white-box testing</summary><br><b>
</b></details>

<details>
<summary>Explain black-box testing</summary><br><b>
</b></details>

<details>
<summary>What are unit tests?</summary><br><b>
</b></details>

<details>
<summary>What types of tests would you run to test a web application?</summary><br><b>
</b></details>

<details>
<summary>Explain test harness?</summary><br><b>
</b></details>

<details>
<summary>What is A/B testing?</summary><br><b>
</b></details>

<details>
<summary>What is network simulation and how do you perform it?</summary><br><b>
</b></details>

<details>
<summary>What types of performances tests are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Explain the following types of tests:

  * Load Testing
  * Stress Testing
  * Capacity Testing
  * Volume Testing
  * Endurance Testing
</summary><br><b>
</b></details>

## Databases

<details>
<summary>What is a connection pool?</summary><br><b>

Connection Pool is a cache of database connections and the reason it's used is to avoid an overhead of establishing a connection for every query done to a database.
</b></details>

<details>
<summary>What is a connection leak?</summary><br><b>

A connection leak is a situation where database connection isn't closed after being created and is no longer needed.
</b></details>

<details>
<summary>What is Table Lock?</summary><br><b>
</b></details>

<details>
<summary>Your database performs slowly than usual. More specifically, your queries are taking a lot of time. What would you do?</summary><br><b>

* Query for running queries and cancel the irrelevant queries
* Check for connection leaks (query for running connections and include their IP)
* Check for table locks and kill irrelevant locking sessions
</b></details>

<details>
<summary>What is a Data Warehouse?</summary><br><b>

"A data warehouse is a subject-oriented, integrated, time-variant and non-volatile collection of data in support of organisation's decision-making process"
</b></details>

<details>
<summary>What is a data lake?</summary><br><b>

A single data source (at least usually) which is stored in a raw format.
</b></details>

<details>
<summary>What is OLTP (Online transaction processing)?</summary><br><b>
</b></details>

<details>
<summary>What is OLAP (Online Analytical Processing)?</summary><br><b>
</b></details>

## Regex

Given a text file, perform the following exercises

#### Extract

<details>
<summary>Extract all the numbers</summary><br><b>
</b></details>

<details>
<summary>Extract the first word of each line</summary><br><b>

Bonus: extract the last word of each line
</b></details>

<details>
<summary>Extract all the IP addresses</summary><br><b>
</b></details>

<details>
<summary>Extract dates in the format of yyyy-mm-dd or yyyy-dd-mm</summary><br><b>
</b></details>

<details>
<summary>Extract email addresses</summary><br><b>
</b></details>

#### Replace

<details>
<summary>Replace tabs with four spaces</summary><br><b>
</b></details>

<details>
<summary>Replace 'red' with 'green'</summary><br><b>
</b></details>

## Design

#### Architecture

<details>
<summary>Explain what is "Single point of failure" and give an example</summary><br><b>
</b></details>

<details>
<summary>Explain "3-Tier Architecture" (including pros and cons)</summary><br><b>
</b></details>

<details>
<summary>What are the drawbacks of monolithic architecture?</summary><br><b>

* Not suitable for frequent code changes and the ability to deploy new features
* Not designed for today's infrastructure (like public clouds)
* Scaling a team to work monolithic architecture is more challenging
</b></details>

<details>
<summary>What are the advantages of microoservices architecture over a monolithic architecture?</summary><br><b>

* Each of the services individually fail without escalating into an application-wide outage.
* Each service can be developed and maintained by a separate team and this team can choose its own tools and coding language
</b></details>

<details>
<summary>What's a service mesh?</summary><br><b>

[This article](https://www.redhat.com/en/topics/microservices/what-is-a-service-mesh) provides a great explanation.
</b></details>

#### Scalability

<details>
<summary>Explain Scalability</summary><br><b>

The ability easily grow in size and capacity based on demand and usage.
</b></details>

<details>
<summary>Explain Elasticity</summary><br><b>

The ability to grow but also to reduce based on what is required
</b></details>

<details>
<summary>Explain Fault Tolerance and High Availability</summary><br><b>

Fault Tolerance - The ability to self-heal and return to normal capacity. Also the ability to withstand a failure and remain functional.

High Availability - Being able to access a resource (in some use cases, using different platforms)
</b></details>

<details>
<summary>Explain Vertical Scaling</summary><br><b>

Vertical Scaling is the process of adding resources to increase power of existing servers. For example, adding more CPUs, adding more RAM, etc.
</b></details>

<details>
<summary>Explain Horizontal Scaling</summary><br><b>

Horizontal Scaling is the process of adding more resources that will be able handle requests as one unit
</b></details>

<details>
<summary>How would you update each of the services in the following drawing without having app (foo.com) downtime?<br>
<img src="images/design/cdn-no-downtime.png" width="300x;" height="400px;"/>
</summary><br><b>
</b></details>

<details>
<summary>What is the problem with the following architecture and how would you fix it?<br>
<img src="images/design/producers_consumers_issue.png" width="400x;" height="300px;"/>
</summary><br><b>

The load on the producers or consumers may be high which will then cause them to hang or crash.<br>
Instead of working in "push mode", the consumers can pull tasks only when they are ready to handle them. It can be fixed by using a streaming platform like Kafka, Kinesis, etc. This platform will make sure to handle the high load/traffic and pass tasks/messages to consumers only when the ready to get them.

<img src="images/design/producers_consumers_fix.png" width="300x;" height="200px;"/>
</b></details>

<details>
<summary>Users report that there is huge spike in process time when adding little bit more data to process as an input. What might be the problem?<br>
<img src="images/design/input-process-output.png" width="300x;" height="200px;"/>
</summary><br><b>
</b></details>

<details>
<summary>How would you scale the architecture from the previous question to hundreds of users?</summary><br><b>
</b></details>

#### Migrations

<details>
<summary>How you prepare for a migration? (or plan a migration)</summary><br><b>

You can mention:

roll-back & roll-forward
cut over 
dress rehearsals 
DNS redirection
</b></details>

<details>
<summary>Explain "Branch by Abstraction" technique</summary><br><b>
</b></details>

## Hardware

<details>
<summary>What is a CPU?</summary><br><b>
</b></details>

<details>
<summary>What is RAM?</summary><br><b>
</b></details>

<details>
<summary>What is an embedded system?</summary><br><b>
</b></details>

<details>
<summary>Can you give an example of an embedded system?</summary><br><b>

Raspberry Pi
</b></details>

<details>
<summary>What types of storage are there?</summary><br><b>
</b></details>

## Big Data

<details>
<summary>Explain what is exactly Big Data</summary><br><b>

As defined by Doug Laney:

* Volume: Extremely large volumes of data
* Velocity: Real time, batch, streams of data
* Variety: Various forms of data, structured, semi-structured and unstructured
* Veracity or Variability: Inconsistent, sometimes inaccurate, varying data
</b></details>

<details>
<summary>Explain the different formats of data</summary><br><b>

* Structured - data that has defined format and length (e.g. numbers, words)
* Semi-structured - Doesn't conform to a specific format but is self-describing (e.g. XML, SWIFT)
* Unstructured - does not follow a specific format (e.g. images, test messages)
</b></details>

<details>
<summary>What is a Data Warehouse?</summary><br><b>

[Wikipedia's explanation on Data Warehouse](https://en.wikipedia.org/wiki/Data_warehouse)
[Amazon's explanation on Data Warehouse](https://aws.amazon.com/data-warehouse)
</b></details>

<details>
<summary>What is Data Lake?</summary><br><b>

[Data Lake - Wikipedia](https://en.wikipedia.org/wiki/Data_lake)
</b></details>

#### Apache Hadoop

<details>
<summary>Explain what is Hadoop</summary><br><b>

[Apache Hadoop - Wikipedia](https://en.wikipedia.org/wiki/Apache_Hadoop)
</b></details>

<details>
<summary>Explain Hadoop YARN</summary><br><b>

Responsible for managing the compute resources in clusters and scheduling users' applications
</b></details>

<details>
<summary>Explain Hadoop MapReduce</summary><br><b>

A programming model for large-scale data processing
</b></details>

<details>
<summary>Explain Hadoop Distributed File Systems (HDFS)</summary><br><b>

* Distributed file system providing high aggregate bandwidth across the cluster.
* For a user it looks like a regular file system structure but behind the scenes it's distributed across multiple machines in a cluster
* Typical file size is TB and it can scale and supports millions of files
* It's fault tolerant which means it provides automatic recovery from faults
* It's best suited for running long batch operations rather than live analysis
</b></details>

<details>
<summary>What do you know about HDFS architecture?</summary><br><b>

[HDFS Architecture](http://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html)

* Master-slave architecture
* Namenode - master, Datanodes - slaves
* Files split into blocks
* Blocks stored on datanodes
* Namenode controls all metadata
</b></details>

## Certificates

If you are looking for a way to prepare for a certain exam this is the section for you. Here you'll find a list of certificates, each references to a separate file with focused questions that will help you to prepare to the exam. Good luck :)

#### AWS

* [Cloud Practitioner](certificates/cloud-practitioner.md) (Latest update: 2020)

## Exercises

Exercises are all about:

  * Setting up environments
  * Writing scripts
  * Designing and/or developing infrastructure apps
  * Fixing existing applications

Below you can find several exercises

#### Containers
* [Writing a Dockerfile and running a container](exercises/write_dockerfile_run_container.md)

#### Jenkins

* [Jenkins: writing scripts](exercises/jenkins_scripts.md)
* [Jenkins: writing pipelines](exercises/jenkins_pipelines.md)

#### CI

* [CI for open source project](exercises/ci_for_open_source_project.md)

#### Mixed

* [Flask, Containers and CI](exercises/flask_container_ci/README.md)
* [Flask, Containers and CI 2](exercises/flask_container_ci2/README.md)

#### Misc

* [Elasticsearch & Kibana on AWS](exercises/elk_kibana_aws.md)
* [ELK & Filebeat](exercises/eflk.md)
* [Ansible, Minikube and Docker](exercises/ansible_minikube_docker.md)
* [Cloud Slack bot](exercises/cloud_slack_bot.md)

## Credits

Thanks to all of our amazing [contributors](https://github.com/bregman-arie/devops-exercises/graphs/contributors) who make it easy for everyone to learn new things :)

Logos credits can be found [here](credits.md)

## License

[![License: CC BY-NC-ND 3.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%203.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/3.0/)
