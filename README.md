# Purpose 
Computational Aide to Finding the Perfect Fit.
This Repo will Illustrate the usage and functions of the ContainerAideR suite of products with descriptions of the Architecture, Tutorials and references to the API calls.

## ContainerAideR - Overview  
Enables efficient space planning by providing a customizable optimization engine the utilizes machine learning.  Commercially developed to efficiently load ISO shipping containers for international freight transportation, ContainerAideR can pack anything.  The infrastructure is delivered as a High Availability, Fault Tolerant, Auto-Scalable cloud resource to be used on-demand as needed and can be accessed in 3 main forms:

1. Event-driven web application

2. Automated Batch file transfers

3. AideR API - Gateway for microservices

### Web Application
Even from the beginning, we wanted the ability for other developers to become involved as a built-in feature to the platform. Our Big Data Analytic platform has many methods and vectors for data ingress / egress.  We want users to have fun with it, so we are drawn to use a new tech stack.  

Event-Driven Architecture - 
![alt text][event]

In order to work well, it needs to be fast!  Web Application servers and client components need to maintain [harmony](https://strongloop.com/strongblog/node-js-is-faster-than-java/) (asynchronous non-blocking), so we focused on server-side programming using [Node.js](https://nodejs.org/en/) a JavaScript runtime built on Chrome's V8 JavaScript engine. MongoDB is a natural choice as a database technology as it also employs JavaScript and JSON.  

### Batch Transactions
Our database layer also provides direct integration into the Analytic platform. The mongoimport tool imports content from an Extended JSON, CSV, or TSV export created by mongoexport, or potentially, another third-party export tool.  This allows you to work with your data in a human-readable Extended JSON or CSV format. This is useful for simple ingestion to or from a third-party system, and when you want to backup or export a small subset of your data.

### AideR API
We want to enable you to quickly create dynamic end-to-end REST APIs using the open-source [LoopBack Framework](http://loopback.io). By adding partners with expert knowledge of API development, [StrongLoop](https://strongloop.com/node-js/api-platform/) provides a strong platform for tools to handle enterprise level development of the Entire API Development Lifecycle.



[event]: https://github.com/ContainerAideR/Overview/blob/master/img/event_loop.jpg?raw=true "event"
