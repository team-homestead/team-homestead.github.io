#  Project Overview

## Team Roster
### Project Lead, and Back-End Developer
[J. Asa Cade](asa.md)

### Front-End Developer
[Mariah Chavez-Graham](mariah.md)

### Back-End Developer
[Archie Jaramillo](archie.md)



## Project Description
Homestead is a powerful tool that facilitates access to community services for the homeless. 
It promotes holistic self care, and self advocacy among those of the target population 
while creating a platform for service providers to present the care they offer.
In fostering this community unity, Homestead proves itself a resource with impact.

The application allows consumers to search for local agencies or browse through a list of local 
agencies and their respective services offered.  An agency is able to update its list of available 
supplies, upcoming events and bed capacity.  Consumers are able to review agency listings in 
real-time, and map the shortest distance to what they need.  With every service experience, 
consumers can favorite an agency or event.



## Intended Users
* Homeless individuals and families
* Municipal Health and Human Services agencies



## Summary of Current State of the Project
The application as it currently stands can navigate between pages, a list of all Agencies, display the Agency information, and add or remove favorites by clicking the heart icon then updating the favorites list. The information displayed for the Agency is only what has been manually put into the database.

The current bug that crashes the application is the Agency page which is intended to display a list of favorite Agencies. 

The future functionality will display categories of services on the Resources page and each category will list the Agencies that offer a specific service. Agencies will be allowed to add, edit, or remove their information shown and post updates of services available to the users. Any events should be able to share to the user's personal calendar, the Agency address should be linkable to the maps application, and the Agency phone number should pull up the phone functionality. There will be a Weather api to pull current, local weather forcasts. 


# Functional Documentation
## [User Stories](user-stories.md)

## [Wireframe](wireframe.md)

## [Basic User Instructions](basic-user-instructions.md)



# Technical Documentation
## [Entity Relationship Diagram](erd.md)
 

## Entity Classes

### [Agency Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Agency.java) 

### [Service Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Service.java)

### [User Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/User.java)


## Flat interfaces

### [Flat Agency](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/view/FlatAgency.java)

### [Flat Service](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/view/FlatService.java)

### [Flat User](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/view/FlatUser.java)


## Repository Interfaces

### [Agency Repository](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/service/AgencyRepository.java)

### [Service Repository](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/service/ServiceRepository.java)

### [User Repository](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/service/UserRepository.java)


## REST Controllers

### [Agency Controller](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/controller/rest/AgencyController.java)

### [Service Controller](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/controller/rest/ServiceController.java)

### [User Controller](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/controller/rest/UserController.java)



## DDL
[DDL](ddl.md)


## Javadocs Documentation
[Client Javadocs](https://team-homestead.github.io/client/api/overview-summary.html)
[Server Javadocs](https://team-homestead.github.io/server/api/) 


## Build Instructions



## Copyrights & Licenses
[Legal Notices](notice.md)


