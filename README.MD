
# SOA

# what Is Service-Oriented Architecture ?
 ## A Look At the Nuts and Bolts of Service-Oriented Architecture
![SOA](https://miro.medium.com/max/1400/1*Xot9nbkQAGbGaYwi84Kh-w.png)

### What Is Service-Oriented Architecture   ?

##### Service-Oriented Architecture (SOA) is a style of software design where services are provided to the other components by application components, through a communication protocol over a network. Its principles are independent of vendors and other technologies. (In service oriented architecture), a number of services communicate with each other, in one of two ways: through passing data or through two or more services coordinating an activity. This is just one definition of Service-Oriented Architecture. [An article on Wikipedia goes into much more detail](https://en.wikipedia.org/wiki/Service-oriented_architecture#Event-driven_architectures).

## Why Service-Oriented Architecture Is Important
![SOA](https://miro.medium.com/max/1220/1*QpkU690MioKK7lHwLE0_Bg.png)

#### There are many [benefits to service-oriented architecture](https://www.bmc.com/blogs/service-oriented-architecture-overview/), especially in a web service based business. We’ll outline a  Use Service-Oriented Architecture to create reusable code: 
#### Not only does this cut down on time spent on the development process, but there’s no reason to reinvent the coding wheel every time you need to create a new service or process. Service-Oriented Architecture also allows for using multiple coding languages because everything runs through a central interface.

#### Use Service-Oriented Architecture to promote interaction: With Service-Oriented Architecture, a standard form of communication is put in place, allowing the various systems and platforms to function independent of each other. With this interaction, Service-Oriented Architecture is also able to work around firewalls, allowing “companies to share services that are vital to operations.”

#### Use Service-Oriented Architecture for scalability: It’s important to be able to scale a business to meet the needs of the client, however certain dependencies can get in the way of that scalability. Using Service-Oriented Architecture cuts back on the client-service interaction, which allows for greater scalability.

#### Use Service-Oriented Architecture to reduce costs: With Service-Oriented Architecture, it’s possible to reduce costs while still “maintaining a desired level of output.” Using Service-Oriented Architecture allows businesses to limit the amount of analysis required when developing custom solutions.







### Characteristics Of Service-Oriented Architecture


#### While the defining concepts of Service-Oriented Architecture vary from company to company, there are six key tenets that overarch the broad concept of Service-Oriented Architecture. These core values include:


- Business value

- Strategic goals

- Intrinsic inter-operability

- Shared services

- Flexibility

#### Evolutionary refinementEach of these core values can be seen on a continuum from older format distributed computing to Service-Oriented Architecture.

## Implementing Service-Oriented Architecture :


#### When it comes to implementing service-oriented architecture (SOA), there is a wide range of technologies that can be used, depending on what your end goal is and what you’re trying to accomplish.

#### Typically, Service-Oriented Architecture is implemented with web services, which makes the “functional building blocks accessible over standard internet protocols.”

#### An example of a web service standard is [SOAP](https://en.wikipedia.org/wiki/SOAP), which stands for Simple Object Access Protocol. In a nutshell, SOAP “is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks. Although SOAP wasn’t well-received at first, since 2003 it has gained more popularity and is becoming more widely used and accepted. Other options for implementing Service-Oriented Architecture include Jini, COBRA, or REST.

#### It’s important to note that architectures can “operate independently of specific technologies,” which means they can be implemented in a variety of ways, including messaging, such as ActiveMQ; Apache Thrift; and SORCER.

### There are two major roles within Service-oriented Architecture: 

### 1) Service provider:
 * The service provider is the maintainer of the s    ervice and the organization that makes available one or more services for others to use. To advertise services, the provider can publish them in a registry, together with a service contract that specifies the nature of the service, how to use it, the requirements for the service, and the fees charged

 ### 2)  Service consumer: 
 - The service consumer can locate the service metadata in the registry and develop the required client components to bind and use the service.

 ![Services provider & consumer](https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-245.png)

#### Services might aggregate information and data retrieved from other services or create workflows of services to satisfy the request of a given service consumer. This practice is known as service orchestration Another important interaction pattern is service choreography, which is the coordinated interaction of services without a single point of control. 
### Components of SOA: 
![Components of SOA ](https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-248.png)
### Guiding Principles of SOA: 

### 1)Standardized service contract: 
**Specified through one or more service description documents.**
### 2) Loose coupling:
**Services are designed as self-contained components, maintain relationships that minimize dependencies on other services.**
### 3) Abstraction: 
**A service is completely defined by service contracts and description documents. They hide their logic, which is encapsulated within their implementation.**
### 4) Reusability: 
**Designed as components, services can be reused more effectively, thus reducing development time and the associated costs.**
### 5) Autonomy: 
**Services have control over the logic they encapsulate and, from a service consumer point of view, there is no need to know about their implementation.**
### 6) Discoverability: 
**Services are defined by description documents that constitute supplemental metadata through which they can be effectively discovered. Service discovery provides an effective means for utilizing third-party resources.**
### 7) Composability:
**Using services as building blocks, sophisticated and complex operations can be implemented. Service orchestration and choreography provide a solid support for composing services and achieving business goals.**


### Advantages of SOA: 

### 1) Service reusability:
- In SOA, applications are made from existing services. Thus, services can be reused to make many applications.
### 2) Easy maintenance:
- As services are independent of each other they can be updated and modified easily without affecting other services.
### 3) Platform independent: 
- SOA allows making a complex application by combining services picked from different sources, independent of the platform.
### 4) Availability:
- SOA facilities are easily available to anyone on request.
### 5) Reliability: 
-  SOA applications are more reliable because it is easy to debug small services rather than huge codes
### 6) Scalability: 
- Services can run on different servers within an environment, this increases scalability
### Disadvantages of SOA: 


### 1)  High overhead:
- A validation of input parameters of services is done whenever services interact this decreases performance as it increases load and response time.
### 2) High investment: 
- A huge initial investment is required for SOA.
### 3) Complex service management: 
- When services interact they exchange messages to tasks. the number of messages may go in millions. It becomes a cumbersome task to handle a large number of messages.
### Practical applications of SOA: 
* SOA is used in many ways around us whether it is mentioned or not. 

* SOA infrastructure is used by many armies and air forces to deploy situational awareness systems.
* SOA is used to improve healthcare delivery.
* Nowadays many apps are games and they use inbuilt functions to run. For example, an app might need GPS so it uses the inbuilt GPS functions of the device. This is SOA in mobile solutions.
* SOA helps maintain museums a virtualized storage pool for their information and content.