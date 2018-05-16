# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?

Hyper Text Transfer Protocol, while the web commonly uses HTTPS, a more secure form of HTTP, HTTP is the protocol that is used accross the web for transfering data.

2.  What is the difference between GET and POST?

GET is idempontent meaning you can continuously make the same request and expect the same result. A caveat when using GET requests is to avoid using them with forms that require a password because the input from the form displays in the RL when the request is made.

POST is non-idempontent. When you make a POST a requests there are effectively 2 response cycles that occur, where the request is made to the server, then another request is made to a database. GET is a little faster, however, POST is more secure.

3.  What is REST?

REST is a convention used to organize resources or collections of data. This typically is in tandem with CRUD - Create, Read, Update, and Delete. The HTTPS actions used are GET for reading, POST for creating, PUT for updating and DELETE for deleting.

4.  What is DNS?

DNS stands for Domain Name System. Websites across the web are given an IP address that either follow IPv4 of IPv6. A domain name is mask over that IP address that allows it to be more human readable.

5.  What is AJAX?

AJAX stands for ansynchronous Javascript and XML. It is method for making requests to a server is quick manner to avoid slow updates.

6.  What is the Same Origin Policy?

It's a security approach that involves scripts that are executed with other scripts may need to have the same origin to excute together. An example would be going to the second page of site that requires the origin of the first page to be the same.


7.  What is CORS?

CORS stands for Cross Origin Resource Sharing. On high level it allows permitted access specific domains on a website.

8.  What is responsive design?

Responsive design is an approach in software development that allows apps to be used in multiple window sizes. Responsive may commonly be used so that a web render correctly on a mobile device

9.  What does "use strict" do in JavaScript?

"use strict" is a mode in Javascript that is supposed to help avoid simple mistakes. An example of something that would be inforced in "strict mode" is the ust of semicolons after each statement.

10. What are data- attributes good for?

**pulled from internet
Data-attributes are used for storing private data. An example would embedding custom data on all HTML elements.

11. Describe the differences between cookies, sessionStorage and localStorage



12. What is an HTTP header? List some examples of headers you've used.



13. What is Cross Site Scripting or XSS?



14. What is SQL Injection?



15. What is Cross Site Request Forgery or CSRF?



16. What is Long polling?



17. What would happen if you inserted a sorted list into a binary search tree?
How can you avoid this problem?



18. What are the advantages and disadvantages of using a linked list over an array?

Arrays have order, built in methods and can be created faster, but can be memory inefficient when it comes to insert data.

While linked lists don't have order, you do not have to create a whole new set when you are inserting like you would an array. Other data structures such as tries and binary trees are fundamentally built off linked lists.

19. What interests you about web development?

It's a field that will continue grow in the future. The development cycles can be a lot faster than other domains of engineering. I also think there are more opporutunities to innovate in this field than any other field.

20. Tell me about your background.

I launched my interest in engineering from building rockets that could go into space and beyond for NASA when I was in high school. That lead me to start tinkering with various things, one of which was a wireless charger that placed me in the semifinals for a science competition.

That lead me to pursue electrical engineer at Kettering Univerity in Flint, Michigan. During my time there I had the opportunity to explore the auto industry and work at Tesla Motors. At Tesla Motors I grew addicted to the workflow that went beyond the typical 9-5 job with opportunities to impact people around the world. I developed software for the Model X front door motors and Model 3 front door motors, and after seeing my code deployed across the world, I knew I wanted to do something software related in the future.

I tried have my own successful biotech startup with some other friends and received seed funding but could overcome the challenges of production. I came back to the Bay Area to continue try to follow my passion for software development. I found Holberton School, that then lead me to Rithm School and here I am trying to make it happen with the experience and energy I bring to the table.