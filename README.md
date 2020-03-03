# Project Description
Homestead is a tool which facilitates access to community services for the homeless. 
It is also intended to inspire holistic self care, and self advocacy among those of 
the target population. Homestead is a resource with impact.  It promotes community  
unity as givers of assistance can connect directly with those in need.
 


# Intended Users
* Homeless individuals and families
* Municipal Health and Human Services agencies
### [User Stories](user-stories.md)



# External Services/Sources

* Google Maps for Albuquerque
  [Municipal maps](https://www.cabq.gov/abq-data)
  [GPS locator](https://developers.google.com/maps/documentation/geolocation/intro)
  This service facilitates the core project feature of guiding homeless individuals to shelters
  with vacancies.  The app will function if this feature is not operable.
 
* Calendar
  [Google calendar](https://developers.google.com/calendar/v3/reference)
  This service facilitates the project bulletin board which informs individuals of upcoming
  community outreach events.  The app will function if this feature is not operable.
  
* Weather Reports
  [Google Weather API](https://developers.google.com/android/reference/com/google/android/gms/awareness/state/Weather)
  This service is crucial to the app feature displaying current weather conditions for the benefit of
  users.  The app will function if this service is not operable.
  
* Google Authorization
  [Google Auth](https://developers.google.com/identity)
  This service allows for the regimented access of the homeless and agency users.  It is intended
  to provide confidentiality of access.  App function hinges on operable authorization of access.  



# Design Documentation
### [Entity Relationship Diagram](erd.md) 

### [Agency Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Agency.java) 
### [Individual Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Individual.java)
### [Service Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/Service.java)
### [User Entity](https://github.com/team-homestead/server/blob/master/src/main/java/edu/cnm/deepdive/server/model/entity/User.java)


# Team Management
### [Team Ground Rules](ground-rules.md)