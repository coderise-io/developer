---
title: 'Get started with codeRISE, Part 2: Projects and Services'
permalink: /get-started/quick-start-part-two/
excerpt: How to quickly get start with codeRISE - Projects and Services
last_modified_at: '2017-07-03 20:38:15 -0400'
published: true
---

A Project is like a folder or container which can contain many independently deployable, small, modular Services. How the services communicate with each other depends on your application’s requirements, but many developers use HTTP/REST with JSON. Here's a simple example: 

1.	Project A: Ecommerce Website
- 1.1.	 Service A1: Frontend (JSP/Html)
- 1.2.   Service A3: Framework (Java)
- 1.3.   Service A2: Database (Consul/Mongo DB)

2.	Project B: Mobile Apps
- 2.1.	Service B1: Android app  
- 2.2.	Service B2: iPhone app

### Create Project and Services 

1.	In the Dashboard, click 'Create Project +' button.
2.	Name your Project and provide Project description. Project name can only contain characters such as: a-z, A-Z, hyphens and underscores.
3.	Name your new Service. Service name can only contain characters such as: a-z, A-Z, hyphens and underscores.
4.  Select if it is a New Service or you will Select from repository then click Next 
- 4.1.	Choosing New Service will automatically select from the existing repository and its branch. 
- 4.1.1.	 Select a Stack. You can click on the script contents, edit and save them if required.
- 4.1.2.	 Click Create and Build.
- 
- 4.2.	Choosing Select from repository will let you select from the existing repository. 
- 4.2.1.	 Select from the existing Repository.
- 4.2.2.	 Select from the existing branch.
- 4.2.3.	 Select a Stack. You can click on the script contents, edit and save them if required.
- 4.2.4.	 Click Create and Build.

 
<figure>
  <img src="http://assets.coderise.io/images/gifs/service.gif" alt="codeRISE Projects and Services">
</figure>
