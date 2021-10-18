# Eventarz-EurekaServer

A part of my Master's dissertation - a simple web application for organizing events, consisting of 7 microservices:

- [Eventarz-Gateway](https://github.com/Atloas/Eventarz-Gateway) - contains full project description.
- [Eventarz-Application](https://github.com/Atloas/Eventarz-Application)
- [Eventarz-Users](https://github.com/Atloas/Eventarz-Users)
- [Eventarz-Groups](https://github.com/Atloas/Eventarz-Groups)
- [Eventarz-Events](https://github.com/Atloas/Eventarz-Events)
- [Eventarz-EurekaServer](https://github.com/Atloas/Eventarz-EurekaServer)
- [Eventarz-ZuulServer](https://github.com/Atloas/Eventarz-ZuulServer)

---

This microservice is a central server for Eureka service discovery, gathering data about connected Eureka clients and sending it back to them as a complete list of available service instances and their addresses.
The data is then used for load balancing.