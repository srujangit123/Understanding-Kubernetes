---
layout: "post"
title: "Microservices intro"

---

## Evolution

Before few years, things were built in monolithic architecture which means the whole application is a single thing, To build the app, it would take hours, and also companies were doing releases less frequently.
<br>
Also it was very hard for new developers to understand the complete application. Companies couldn't hire engineers to work on a particular piece of the application. To work on a certain part of the application, developers had to know the complete application, how it works, know all the technologies used in the entire application. 
Years after people started breaking the whole application into smaller pieces, Each piece is called microservice. So build time reduced from hours to seconds. And then wrap them into containers and deploy in seconds.
<br>
Microservices is speeding up the development of softwares. In monolithic architecture, a single tiny bug can affect the whole application unlike microservices architecture. Team working on a microservice can do multiple release in a day and they don't have to wait for other services. So each microservice is independent of other microservices. 
<br>
To test, monitor these services, we use scripts, kubernetes etc.

## Microservices

* Modular
* Easy to deploy
* Scale independently.
This architecture is used mostly when there is rapid deployments, continuous delivery. But can also be used even for a simple web application.
