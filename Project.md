# ISDM Group 2 Project - Call Management Centre(CMC) System

## Defining the Problem - Design Thinking Methodologies
### Empathy Maps
- We used Empathy Maps as part of our Design Thinking Process in order to explore and understand how our stakeholders may think and feel towards a new system. This allowed us to understand what boundaries and factors we will have to consider on a personal level when designing the CMC system.
- **Relationship Manager**
<p align="center">
  <img src="Empathy Map_RM.png" width="60%">
</p>

- **In-bount Customer**
<p align="center">
  <img src="Empathy Map_IB Customer.png" width="60%">
</p>

- **Out-Bound Customer**
<p align="center">
  <img src="Empathy Map_OB Customer.png" width="60%">
</p>

### POV Statements 
- We used POV statements to capture and better understand what it is that each stakeholder needed to gain from the system and what problem the system would solve for them respectively.

**In-bound Customers**
- As an inbound customer I want a comprehensive call exchange system which is fast so that i can make informed decisions and have quicker service. 

**Relationship Manager(MR)**
- As a relationship manager I want a call management system that is quick, effective and efficient so I can sell as many products as fast as possible. 

**Out-bount Customer**
- As a potentially interested buyer, I want incoming calls about products to be quick and effective. I don’t want to be stuck on the phone for long periods of time for a product I’m not interested in.

### HMW Statements 
**In-bound Customers**
- How might we improve customers' experiences when calling the system?
- How might we improve call efficiency to decrease the time customers spend on a call?

**Out-bound Customers**
- How might we call the customer at the right moment when they have time to talk?
- How might we make the customer feel like they are not being annoyed?

**Relationship Managers**
- How might we make every call as effective as possible?
- How might we increase the likelihood of generating sales during each call?

### Implementation of Agile Methodology; Scrum
During the completion of the project, the team needed to create and model a solution quickly so implementing an Agile methodology was crucial. Our team used the Scrum technique in order to organise ourselves and create deliverables in an iterative manner. Scrum allowed us to be flexible and adjust for any work that hadn't been completed and plan out the how and when sections of the work would be completed.

-**Product Backlog** Identified the requirements of each group member such as what particular work they contribute to the project

-**Prioritizing Backlog** The team log any issue and ordered them based on priority , the team idetified the most precedented issues and worked on them first, consequently we worked on the less precedented issues at a latter stage. 
- **Scrum Meetings:** Every 2-4 days, the group would gather and participate in Scrum meetings over MS Teams in order to go over the work that we had completed so far and any issues we were having. We would also review each other's work and provide feedback on eachothers work.
- **Sprints:** The team worked in Sprints, creating and working on a new section of the project each week. 
- **Sprint Retrospective Meetings:** At the end of each week, we would do a final review of the work that had been completed over the week and anything that hadn't been finished would need to be pushed into the next week's Sprint. We would also discuss a plan and assign work to each group member to be completed in the following weeks' sprint.
- **Sprint Backlog:** We used GitHub to plan out our backlog. This allowed us to understand and track what tasks still needed to be models and process the ones that had been completed. 

**Reflection during Ideation**
While investigating and understanding the system, there were several key features that we felt were missing in order for the system to function.
- One of the first assumptions we made about the system is that In-bound customers and Out-bound customers would have needed to already have provided some information to the company in order to be matched with the best fit Relationship Manager(RM). For Out-Bound customers, the system gets the users information from a database. We assumed that this meant the customer had already purchased a product in the past or had given an expression of interest including personal information in some regard. For In-Bound customers, we assumed that customers would need to provide some information if it is their first time calling in order to be given a Loyalty Score and be matched with the  appropriate RM.
- For this system, assuming that we may need variety Relationship Manager to follow the customer's files. For the inbound call, we assumed that the customers call to the server on the working time of RM beside that if the customers call after or before the working time, we need to give a solution for them to contact later. Also with the outbound call, if the customers are being busy at that time so the RM may need to contact them later. All of this is leading to best customer's experiences. 

## Workproduct, Models and Descriptions 
### Class Diagram
- The Class Diagram aims to model all the classes present within the system and how they will interact with other classes. It also models what functions/actions the classes can perform as well as what data they hold. The Out-Bound Call Organiser Class acts as an associative class, connecting the many RM's to the Outbound customers. The In-Bound Call Routing and Distributing Class also manages incoming calls from customers and links the RM's to Inbound customers as an associative class.
<p align="center">
  <img src="Class Diagram.png" width="60%">
</p>

### Use Case Diagram

- The Use Case Diagram is the primary form of system requirement for a new software program. A use case diagram is usually simple and does not show the detail of the use cases. It summarizes some of the relationship between Customer, Relationship managers and systems. 

<p align="center">
  <img src="Inbound call.png" width="60%">
</p>

<p align="center">
  <img src="Outbound call (1).png" width="60%">
</p>

### Collaboration Diagram 

- The Collaboration Diagram is utilised to show to how objects interact to achieve the behaviour of a particular use case. Collaboration diagram defines and clarifies the roles of the objects that performs a particular flow of events of a use case. 

<p align="center">
   <img src="Collaboration Diagram.png" width="60%">
  </p>

### Activity Diagram

- The Activity Diagram is a digram which shows step by step activities done by each actor for achieving something. Each steps and choices are shown in activity diagram, it has a start point and an end point. Activity diagram shows the steps of commencing inbound calls and outbound calls.

<p align="center">
  <img src="Inbound Activity Diagram.png" width="60%">
</p>

<p align="center">
  <img src="Outbound Activity Diagram.png" width="60%">
</p>

## Advantages of Implementing new System
Implementing the new system will provide many different benefits for the company:
- The new system taylors the service provided to each customer, allowing for a more satisfying and quicker customer experience.
- Relationship Managers are able to make sales at an increased rate as customers are better understood and are provided with options they are more likely to take rather than the Relationship Manager sifting through every option.
- The profit of the company will increase as the sales are increased
- The Company will be able to judge what holiday packages are popular based upon how many customers are recommended the holiday packages.
- The effectiveness of specific Relationship Manages will be tracked based on their number of recommended customers.
- Company will be able to have a good relationship with existing customers.
- Company will have a better reputation as the service given to every customer is very effective, hence customers will regard the company as a great company.
- Wait times will be shorter as customer and relationship manager interactions has been shortened, allowing for more customers to be served during busier times.
- The system will be able to track valuable and favourable customers through their loyalty score.

## Company Effects from Failures of the system
The new system could fail in many different ways leading to detrimental effects on the company.
- **Development Failure:** The system may fail during development due to lack of funds, poor management or unable to complete the system  before the deadline.This would result in a waste of company expenses and time. Depending on the significance of the failure, the company may be able to restart development or start from scratch. Nevertheless, this would result in even more money and time being needed to complete the project which the company may not have.
- **Security Failure:** The system may encounter a security failure after the implementation of the system. This would result in the leak in the sensitive information of company employees and customers. This could not only result in legal action being taken against the company but also be heavily damaging to the companies reputation. This is perhaps the largest failure the company could face as it could result in the failure of the company as a whole.
- **Functionality Failure:** The system may be implemented with faulty or incorrect functionality. Faulty functionality could lead the system to mismatching Relationship Managers with customers, faulty potential buyer lists being created and given to Relationship managers if the incorrect behaviour of any of the functionality. Depending on the importance of the functionality and the severity of the fault in its functionality, this could result in a mild nuisance to users of complete redundancy of the system.
- **Acceptance Failure:** Many of the pre-existing customers may dislike the new system. Customers may have become accustomed to the old system and perfected the way that it operated. This may result in the loss of valuable and loyal customers. If the level of customers is significant enough, this could adversily effect the profitability or reputation of the company.

## GitHub Repository
Below is a link to the GitHub repository to view the groups progress and contributions:
https://github.com/liamlindsay9/ISDM-Group-3
