This application was built following [this tutorial](https://medium.com/@erickwendel/node-v14-x-is-up-deep-diving-into-new-features-ace6dd89ac0b) wrote by [Erick Wendel](https://erickwendel.com.br/).

The project show how we can create a APM (Application Performance Monitor) using amazing concepts of Nodejs, some contents:
- Created an interceptor that changes the default behavior of http emit native module to add a custom header on all requests
- When we receive a post request we use streams to handle with data, using a Transform to handle with chunk, converting it and after using pipeline to return data to client
- Use the build in reports of Nodejs to save logs when some uncaught error occurs
- Created tests to each module, using the nodejs assert module