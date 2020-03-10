# Project Description
Homestead is a tool which facilitates access to community services for the homeless. 
It is also intended to inspire holistic self care, and self advocacy among those of 
the target population. Homestead is a resource with impact.  It promotes community  
unity as givers of assistance can connect directly with those in need.

Our application will contain mappable resources and the types of assistance offered by the agencies. 
Individuals will be able to search for an agency or browse through a list of agencies. 
An agency will be able to update their availability for supplies or beds and update any contact information.
 
---

# Intended Users
* Homeless individuals and families
* Municipal Health and Human Services agencies


* ### [User Stories](user-stories.md)

---

# External Services/Sources
 
* Calendar
  [Google calendar](https://developers.google.com/calendar/v3/reference)
  
  The Google calendar will be able to share events from Homestead calendar to the users own google Calendar on their own device. The Calendar will still function without constant online service but events cannot be changed or added.
  
* Weather Reports
  [Google Weather API](https://developers.google.com/android/reference/com/google/android/gms/awareness/state/Weather)
  
  The Google weather will provide information to the users based on the location they have selected. The weather service will not work without access to external data since it cannot update with google on the current weather status.
  
* Google Authorization
  [Google Auth](https://developers.google.com/identity)

  The Google authorization will be optional to access the app's content and the app will be able to function without access to the Google sign in.
---

# Design Documentation

### [Entity Relationship Diagram](erd.md) 

### [Wireframe](wireframe.md)

---

# Entity Classes

### [Agency Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Agency.java) 

### [Individual Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Individual.java)

### [Service Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Service.java)

### [User Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/User.java)

---

# Flat interfaces

### [Flat Agency](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/view/FlatAgency.java)

### [Flat Individual](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/view/FlatIndividual.java)

### [Flat Service](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/view/FlatService.java)

### [Flat User](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/view/FlatUser.java)

---

# Repository Interfaces

### [Agency Repository](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/service/AgencyRepository.java)

### [Individual Repository](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/service/IndividualRepository.java)

### [Service Repository](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/service/ServiceRepository.java)

### [User Repository](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/service/UserRepository.java)

---

# REST Controllers

### [Agency Controller](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/controller/rest/AgencyController.java)

### [Individual Controller](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/controller/rest/IndividualController.java)

### [Service Controller](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/controller/rest/ServiceController.java)

### [User Controller](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/controller/rest/UserController.java)

---

# Team Management

## Team Roster

* [Archie Jaramillo](archie.md)
* [Asa Cade](asa.md)
* [Mariah Chavez-Graham](mariah.md)


### [Team Ground Rules](ground-rules.md)