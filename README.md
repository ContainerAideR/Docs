# Purpose 
Computational Aide to Finding the Perfect Fit.
This Repo will Illustrate the usage and functions of the ContainerAideR suite of products with descriptions of the Architecture, Tutorials and references to the API calls.

## ContainerAideR - Overview  
Enables efficient space planning by providing a customizable optimization engine the utilizes machine learning.  Commercially developed to efficiently load ISO shipping containers for international freight transportation, ContainerAideR can pack anything.  The infrastructure is delivered as a fault tolerant, highly available, scalable cloud resource to be used as needed and can be accessed in 3 main forms:

1. Event-driven web application

2. Automated Batch file transfers

3. AideR API - Gateway for microservices
 
No contracts required, use as needed.

### Web Application
Even from the beginning, we wanted the ability for other developers to become involved as a built-in feature to the platform. Our Big Data Analytic platform has many methods and vectors for data ingress / egress.  We want users to have fun with it, so we are drawn to use a new tech stack.  
In order to work well, it needs to be fast!  Web Application servers and client components need to maintain [harmony](https://strongloop.com/strongblog/node-js-is-faster-than-java/), so we focused on server-side programming using [Node.js](https://nodejs.org/en/)a JavaScript runtime built on Chrome's V8 JavaScript engine. MongoDB is a natural choice as a database technology as it also employs JavaScript and JSON.  Our database layer also provides direct integration into the Analytic platform. 
