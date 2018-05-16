# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?

* HTTP (hyper text transfer protocol) is set of rules that governs communication between client and servers.
* HTTPS is the same except with a level of security.

2.  What is the difference between GET and POST?

* GET sends a request to the server to retrieve information.
* POST sends a request to the server to display information.

* How form data is transmitted. GET is when you send information in a query string and it can be seen. POST is more secure when sending information. It sends it in the form of the body. Idempotent is not changing. GET is idempotent.

3.  What is REST?

* REST is a standard/pattern for architecting applications which has solid assumptions. It is common for APIs.

4.  What is DNS?

* Domain Name System - the idea of when some request comes in. Its the system that maps the plaintext to the IP address. It's the first part of some request.

5.  What is AJAX?

* Asynchronous JavaScript and XML - make request to some backend without refreshing the page. Can't make AJAX request in any other language except Python.

6.  What is the Same Origin Policy?

* Same Origin Policy will restrict how one page/document or a script when loaded from one place can interact with another page/document or script from another page. Browser based security mechanism. It's a restrictive policy. (i.e. Twitter API enforces Same Origin Policy. You cannot use AJAX with their API)

7.  What is CORS?

* CORS - cross origin resource sharing - determines whether to block or fulfill a request. With CORS, the idea is you can share resources across different domains. To enable CORS, you enable it on the server by using headers (i.e. headers control access origin).

8.  What is responsive design?

* Responsive design is an approach to building a webpage that makes use of three things:
  a. flexible layout (%, rems, viewport height(vh))
  b. media queries - rules you specify that governs what CSS you use on screen sizes
  c. flexible images - handle responsive or flexible images (i.e. html picture tag)

9.  What does "use strict" do in JavaScript?

* "use strict" enables strict mode, which enforces better JS practices. (i.e. strict mode will immediately throw an error when creating functions with the same parameters)

10. What are data- attributes good for?

* Data attributes is one you want to give your HTML elements to give it additional information. It doesn't have any semantic or pre-defined meaning. Maybe you want to add properties to your element.

11. Describe the differences between cookies, sessionStorage and localStorage

* Cookies - cookies are much smaller. can only store 4kb. accessible across any domain you visit.
* sessionStorage - tab specific.
* localStorage - domain specific. can store 5mb. great if you have data pertinent to that specific domain.

12. What is an HTTP header? List some examples of headers you've used.

* An HTTP header lists metadata about request or response. Examples, authorization with value of token or things like caching.

13. What is Cross Site Scripting or XSS?

* Cross Site Scripting is the idea of injecting malicious JS onto a page and trusted websites. Escape the script text by turning it into a string.

14. What is SQL Injection?

* SQL Injection is taking user input and directly modifying your SQL queries based on that user input. You can directly access someones database. Don't use string conctenation.

15. What is Cross Site Request Forgery or CSRF?

* CSRF is that when you're logged into a site when some cookie has been sent, someone can maliciously take that cookie, send it back to the server, and forge the request as you. To prevent CSRF attacks, on the server side, anytime a request has been submitted, the server will check for a CSRF or authenticity token.

16. What is Long polling?

* Long polling is the idea of making a request to a server after a certain amount of time. Making the request over and over again to update the page in real time. Long polling is inefficient. Better way to update in real time. Long pulling is what we used to do.

Two protocols we use now instead of Long Polling:

* WS(web sockets): awkward handshake, no one lets go. client trusts server, server trusts client. popular library (socket.io - used for chat messages). saves time bc you don't have to make another AJAX call.
* WebRTC (Web real time communication): communication between client and client. used for video chat.

17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?

* You would have an imbalanced tree. The tree would lean more to one side. It would look like a linked list. It depends on the problem. To avoid this, figure out which problem you are trying to solve, whether its dealing with a sorted list or dealing with a tree. If we are dealing with a sorted list, we can start from the median and build a tree from there.

* think as high level.

18. What are the advantages and disadvantages of using a linked list over an array?

* Advantages - you can point to the next node in the linked list.
* Disadvantages - you have to loop through each node in the linked list to get your value, whereas in an array you can locate it by index.

* Adding elements - arrays are great
* removing elements - lists are great
* lookup - lists aren't great at this, but arrays are.

* real world way using linkedlists - using stacks or queues.

19. What interests you about web development?

* I'm interested in web development because I enjoy building products that people will use. I enjoy seeing projects from start to finish.

20. Tell me about your background.

* My work experience is varied. I started my career in events and made my way to international education to tech to program management to edtech before starting work as a developer.

//////
Q: What happens when you go to google.com

* make get request
* go to dns server that will go to google.com
* server checks if the route is valid
* if yes, it will respond with text based response.
* text is parsed by browser and turns it to html. creates the dom
