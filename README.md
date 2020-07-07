# Databases & API <!-- omit in toc -->
The concepts of Application Program Interfaces (APIs) and Databases are closely connected because it provides an *abstraction* for the developers to communicate with the backend - all using something called **end-points**. 

During this assignment, we will be focusing mainly on **RESTful APIs** that uses HTTP requests to carry out simple interactions with the data such as create/read/update/delete (CRUD) operations. This repository will contain notes for some of the key points, as well as screenshots of my work. <br>
<hr>

### Table Of Contents <!-- omit in toc -->
- [Model](#model)
- [Setup Azure Database](#setup-azure-database)
- [Coding Time](#coding-time)
<hr>

### Model
Before we start to program our database, it is important to design its structure because the cost of changing it in the future would be expensive. We refer to this structure as a **model**.

Our initial (and very simple) model will contain the following inputs -
- StudentID
- FirstName
- LastName
- EmailAddress

### Setup Azure Database
Here are basic steps for the process of creating SQL instances in Azure. The **resource group** is a collection of resources which are used for a particular application, and you need to create one for this particular application.

Thereafter you create a server which will contain your SQL database, and you can configure it according to your future-scaling needs. In real world cases, you need to restrict the access to your server from permitted IPs only - but simplicity's sake we can allow all ranging from 0.0.0.0 to 255.255.255.255. This can be done from the server settings.

### Coding Time