# Lab 3
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- team member 1
- team member 2

## Lab Question Answers

Answer for Question 1: 

Question 1: Why are RESTful APIs scalable?

RESTful APIs can be scaled without much difficulty because there is a separation between the client and the server. The main reason behind saying a rest application is scalable is, Its built upon a HTTP protocol. Because HTTP is stateless. Stateless means it wont share anything between other request. So any request can go to any Server in a load balanced cluster. There is nothing forcing this user request go to this server. We can overcome this by using token. Because of this statelessness, REST APIs are very easy to scale.

Question 2: According to the definition of “resources” provided in the AWS article above,
What are the resources the mail server is providing to clients?

The resources the mail server is providing to clients are all indox and sentbox mail information. 


Question 3: What is one common REST Method not used in our mail server? How could
we extend our mail server to use this method?
One common REST method not used in the mail server is the "PUT" method. The mail server can be extended by using "PUT" to update the capabilities. PUT can also be used to create a resource in the case where the resource ID is chosen by the client instead of by the server. In other words, if the PUT is to a URI that contains the value of a non-existent resource ID.

Question 4: Why are API keys used for many RESTful APIs? What purpose do they
serve? Make sure to cite any online resources you use to answer this question!

By identifying the calling project, you can use API keys to associate usage information with that project. API keys allow the Extensible Service Proxy (ESP) to reject calls from projects that haven't been granted access or enabled in the API. Revealing your identiy to the server and allows for you get certain information. 

