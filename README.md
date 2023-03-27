[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# Tech-interview-questions

Note: A documentation of technical engineering questions curated by experienced Engineers who have conducted many interviews.

For any fixes, updates or new additions, please make a pull-request (PR). Thank you!

## Contributing

- To contribute, please read our [Contributing Guidelines](CONTRIBUTING.md). For any fixes, updates or new additions, please make a pull-request (PR). Thank you!

## Charity 

- Since this is a community-based project and it is run by the community - we (the creators) do not gain any personal nor financial gain other than helping the community. Instead, any financial gain would be better suited to a charity. So we wanted to take it upon us to help those in need. We, as a community, have chosen a certified charity to donate to. Here is the link to donate to:
    - 


## Topics overview

- [X] [DevOps](#devops)
- [X] [System Design](#system-design)
- [X] [Backend & Frontend](#backend--frontend)
- [X] [Data](#data)
- [X] [Cyber Security & InfoSecurity](#cyber-security--info-security)
- [X]  [Interpersonal skills]()


## DevOps

### :small_blue_diamond: Linux

- What is Linux and difference between UNIX and Linux?
- What is the Linux kernel?
- 
- What are inodes in Linux?
- Explain the Linux boot process
- What is a zombie process?
- Difference between soft links and hardlinks?
- What are namespaces and c-groups?
- What are symbolic links?
- What are the different types of permissions in Linux?
- What is swap space?

Commands:
- What does chmod +x FILENAME do?
- Which command will show you free/used memory?
- Which command will show me the current directory I am in?
- How can I terminate an on going process?
- Write the command that will display all .yaml files including permissions of each file? ()
- How can I found the status of a process?
- 


Advanced:

- Does free memory exist on Linux?
- How can I check if a server is down?
- What is inside /proc?
- A process on the system can no longer log files, what can I do?
- What is LILO?
- I

### :small_blue_diamond: Networking

- What is HTTP? How is HTTPS different?
- TCP vs UDP
- What is DNS and how does it work?
- What is TLS?

Advanced:

- When I type google.com into the browser, what actually happens? (go into as much detail as you can)
- I can't reach a website, how can I troubleshoot? (use deep Linux + networking knowledge )
- Can you break down the OSI model and what does it signify?
- How does mTLS work and compare it to TLS? 

### :small_blue_diamond: Git

- What is Git?
- Difference between Git and SVN?
- What is the basic Git workflow?
- Difference between git pull and Git fetch
- What is git cherry-pick?
- What is the HEAD in Git ?
- When do I use Git stash?
- What does git reset do?

Advanced:
- I need to update my local repos, what commands do I use ?
- I need to rollback to a previous commit and I don't need my recent changes, what do I use ?
- How can I amend an older commit?
- What is the command to check the difference between two commits ?

### :small_blue_diamond: AWS

-----General--------
- What is AWS? 
- What are two services of AWS where you could store secrets? 

-----Networking-----
- What is a VPC?
- How do Subnets work?
- What network object do you need to allow a server ingress from the internet?
- What are the different type of load balancers in AWS?


- Name some managed runtimes for Lambda
- 
- 

### :small_blue_diamond: Azure

- What is Azure?
- What are ARM templates in Azure?
- What is Azure CDN?
- How is Azure App Service different from Azure Functions?
- How to define an Environment Variable on Azure using Azure CLI?
- How would you choose between Azure Blob Storage vs. Azure File Service?
- What is difference between Keys and Secrets in Azure Key Vault?
- What’s the difference between Azure SQL Database and Azure SQL Managed Instance?
- When should we use Azure Table Storage over Azure SQL?
- Explain what is the difference between Block Blobs, Append Blobs and Page Blobs in Azure?

Advanced:

- What to use: many small Azure Storage Blob containers vs one really large container with tons of blobs?
- 


### :small_blue_diamond: Terraform

- What is Terraform state
- 



Advanced:
- I have 3 people in my team who want to work on the same AWS Infrastructure on Terraform as well as same state. What can I do to ensure there are no clashes?
- In a pipeline, where would you store the Terraform state?


### :small_blue_diamond: Docker & K8s


Container (Docker):
- What is a container and what are its fundamentals?
- What are c-groups and namespaces in Linux?
- What is Docker and how does it work?
- When do I use Docker Compose vs Docker Swarm and K8s?
- What is a Dockerfile used for? 
- Can you explain the basic components of a Dockerfile?
- How is a container different from a virtual machine?

Container Orchestration (Kubernetes = K8s):

- What is Kubernetes?
- What problems does Kubernetes solve? 
- What is the difference between Docker and K8s?
- What is a Pod and what does it do?
- How can containers within a pod communicate with each other?
- What is a K8s cluster ?
- What are deployments?
- What are stateful sets?
- How do you restrict pod-to-pod communication in a cluster?
- How can I rollback a deployment?
- What are namespaces? 
- What is the role of the kube-apiserver?


Advanced:

- Can you mention some good practices to follow when creating containers?
- Can you explain a simple K8s cluster architecture and the components within it?
- What happens when a master node fails? 
- What happens when a worker node fails?
- What is an Ingress controller?
- How can one build a highly availabe (HA) cluster in K8s?
- What is the role of ETCD in K8s?

### :small_blue_diamond: Ansible

- What is Ansible? 
- How does Ansible work?
- What is Ansible Galaxy?
- What are Ansible handlers?
- What is Ansible Vault?
- What aer Ansible collections?
- How do you get a list of Ansible predefined variables?
- How is Ansible playbook different from ad-hoc commands?
- What is the recommended for securing secret information used within Ansible playbooks?
- What templating language is directly supported within Ansible for creating dynamic playbooks?
- What protocol does Ansible use for communicating with client systems?
- What is an inventory file?


Advanced:

- Can you name some Ansible best practices? 
- How do you handle errors in Ansible?
- How do you test your Ansible roles and tasks?
- What is Molecule and how does it works?

### :small_blue_diamond: CI/CD

- 

### :small_blue_diamond: DevOps methodology, practices,  & Agile

- What is meant by continuous integratons?
- What are the advantages of DevOps?
- Can you describe some branching strategies you have used?
- What is the blue/green deployment pattern?


## System Design

### :small_blue_diamond: CDN & Caching

- What is a CDN and why would I use one?
- What are CDN edge servers?
- How does CDN caching work?
- What is Cache invalidation? 
- What are some cache invalidation methods?
- What is a microservice architecture and when would I consider using one?
- 

- What is the CAP Theorem?
- Explain the difference between horizontal scaling and vertical scaling?
- Difference between forward proxy and reverse proxy?
- What is Load Balancing and how does it work? How does it relate to reverse proxies?
- Name me some common load balancers
- 

### :small_blue_diamond: Databases

- What is a database?
- What is DBMS (Database Management System)?
- What is the schema referred to in a Database?
- What are different types of databases?
- Advantages & Disadvantages of using relational databases?
- Advantages & Disadvantages of using NoSQL relational databases?
- What is a key-value database? What are some examples of this?
- What are graph databases? Name some examples?
- What is database replication?
- What is master-slave replication? And what is master-master replication?
- What is Synchronous vs Asynchronous replication?
- What are indexes in databases?



Advanced:

- What are message queues? And what are message brokers?
- How does the publish-subscribe model work?
- Can you explain how an event-driven architecture works?
- What is an API Gateway? How is this different from load balancers?
- Explain why CDN (in)availability may be a problem for using WebSockets? 

## BackEnd & FrontEnd


### :small_blue_diamond: Golang

- What is Go?
- Why was the Go langauge created?
- What is a pointer?
- What is the difference between the = and := operator?
- What are goroutines?
- Does Go have exceptions?


Advanced:
- Implement a function that reverses a slice of integers?
- What are generics and how do they work?


### :small_blue_diamond: Python

- 

### :small_blue_diamond: Java

- 

### :small_blue_diamond: JavaScript (TS,nodeJS...)






## Data


### Data Fundamentals


### SQL


### ETL, Pipelines


## Cyber Security & Info Security

- 


## License

This project is licensed under the Apache License. See the [LICENSE](LICENSE) file for more details.