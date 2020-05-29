# ISDM Group 2 Project - Call Management Centre(CMC) System

## Defining the Problem - Design Thinking Methodologies
### Empathy Maps
- We used Empathy Maps as part of our Design Thinking Process on order to explore and understand how our stakeholders may think feel towards a new system. This allowed us to understand what boundries and factors we will have to consider on a personal level when designing the CMC system.
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
- How might we improve customers experiences when calling the system?
- How might we improve call efficiency to decrease the time customers spend on a call.

**Out-bound Customers**
- How might we call the customer at the right moment when they have time to talk.
- How might we make the customer feel like they are not being annoyed.
### Implementation of Agile Methodology; Scrum
During the completion of the project, the team needed to create and model a solution quickly so implementing an Agile methodology was cruical. Our team used the Scrum technique in order to organise ourselves and create deliverables in an interative manner. Scrum allowed us to be flexible and adjust for any work that hadn't been completed and plan out the how and when sections of the work would be completed.
- **Scrum Meetings:** Every 2-4 days, the group would gather and participate in Scrum meetings over MS Teams in order to go over the work that we had completed so far and any issues we were having. We would also review eachother work and provide feedback on eachothers work.
- **Sprints:** The team worked in Sprints, creating and working on a new section of the project each week. 
- **Sprint Retrospective Meetings:** At the end of each week, we would do a final review of the work that had been completed over the week and anything that hadnt been finished would need to be pushed into the next weeks Sprint. We would also discuss a plan and assign work to each group member to be completed in the following weeks' sprint.
- **Sprint Backlog:** We used GitHub to plan out our backlog. This allowed us to understand and track what tasks still needed to be models and process the ones that had been completed. 

**Reflection during Ideation**
While investigating and understanding the system, there were several key features that we felt were missing in order for the system to function.
- One of the first assumptions we made about the system is that In-bound customers and Out-bound customers would have needed to already have provided some information to the company in order to be matched with the best fit Relationship Manager(RM). For Out-Bound customers, the system gets the users information from a database. We assumed that this mean the customer had already purchased a product in the past or had given an expession of interest including personal information in some regard. For In-Bound customers, we assumed that customers would need to provide some information if it is their first time calling in order to be given a Loyalty Score and be matched with the approapriate RM.
- For this system, assuming that we may need variety Relationship Manager to follow the customer's files. For the inbound call, we assumed that the customers call to the server on the working time of RM beside that if the customers call after or before the working time, we need to give a solution for them to contact later. Also with the outbound call, if the customers are being busy at that time so the RM may need to contact them later. All of this is leading to best customer's experiences. 

## Workproduct, Models and Descriptions 
### Class Diagram
- The Class Diagram aims to model all the classes present within the system and how they will interact with other classes. It also models what functions/action the classes can perform aswell as what data they hold. The Out-Bound Call Organiser Class acts as an associative class, connecting the many RM's to the Outbound customers. The In-Bound Call Routing and Distributing Class also manages incoming calls from customers and linking the RM's to Inbound customers as an associative class.
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
