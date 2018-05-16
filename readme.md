# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?
    HyperText Transfer Protocol. Used to send information over the web. All browser-based web usage is done via http/https.
2.  What is the difference between GET and POST?
    GET and POST are both http requests. GET makes a request for data from an endpoint/resource. GET is idempotent, meaning that a GET request to the same resource will not modify the resource or cause it to change in anyway. GET requests can send data in a query string, but this data is public. POST requests are send data to a resource/endpoint via a method body and contain a header with metadata about the request itself. POST requests are more secure.
3.  What is REST?
    A way of architecting/designing the web. For web development, we often employ routes in accordance with the REST convention (RESTful routing), which is a set of conventions dictating how routes/endpoints should be set up.
4.  What is DNS?
    Domain Name System(?). DNS is the system by which we can convert domain names to the actual IP addresses associated with those domain names.
5.  What is AJAX?
    Asynchronous Javascript and XML(?)
    Ajax is the process by which we can make http requests from a webpage using client-side javascript. The cs-js can then recieve the response and make changes to the web page without ever reloading the webpage itself. This allows us to modify our webpages without having to refresh the page or redirect to new pages. This allows for SPAs (single page applications) and better user experiences.
6.  What is the Same Origin Policy?
    Protection built into the web that prevents scripts from other domains from modifying/interacting with a web page's contents or client-side code. This helps prevent a website from malicious attacks from 3rd parties.
7.  What is CORS?
    Cross Origin Resource Sharing (?)
    Has to do with Same Origin Policy.
8.  What is responsive design?
    Procedure for modifying how css affects a webpage depending on a variety of environmental factors (screen size/windox size being the most common). Responsive design allows for differently styled pages on different devices/differently sized windows. This allows for a better user experience and prevents us from needing to make completely different websites to service different devices.
9.  What does "use strict" do in JavaScript?
    Prevents a number of javascript's bug-prone features.
    Prevents the var keyword from being bound to the global scope when it is declared inside of a function.

10. What are data- attributes good for?
    Allows us to store/associate data with a piece of html. This is often useful if we want to make a script that will interact with an html element but will need additional data associated with the element.
11. Describe the differences between cookies, sessionStorage and localStorage
    Cookies: stored in the client, sends data to the server each time a request is sent. Persists across visits to different websites.
    sessionStorage: stored in client, only lasts as long as session
    localStorage: stored in client
12. What is an HTTP header? List some examples of headers you've used.
    Metadata about http request.
    Specify whatever auth tokens we have.
    Specify the type of data we'd like in the response
    Do all types of http requests have/need headers?
13. What is Cross Site Scripting or XSS?
    Malicious attack in which a 3rd party script gains access/permissions to a webpage and runs malware. Can destroy data on site, send data from a website to a 3rd party, or some other malicious activity.
14. What is SQL Injection?
    Malcious attack in which a 3rd party gets malicious SQL code into a SQL database (often through an unsanitized front-end facing form or an unvalidated back-end endpoint).
15. What is Cross Site Request Forgery or CSRF?
    Malicious attack in which authorization is forged. Allows a malicious 3rd party access to parts of the website that are supposed to be confidential/protected.
16. What is Long polling?
    No idea.
17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?
    I don't understand the question. If you inserted properly (in element at a time) there would be no problem?

18. What are the advantages and disadvantages of using a linked list over an array?
    Advantage: O(1) modification to front of data structure (vs O(n) for array).
    Disadvantage: O(n) lookup for element, even if you know where it is in the data structure (vs O(1) for array)

19. What interests you about web development?

In order of escalating melodrama:

Stable field (relatively) with strong opportunities for advancement.
Having the capacity to build/create.
Constant opportunity to expand/grow my skill set.
Having access to priveleged information/competency about a vital contemporary technology/skill set.
Being in an industry on the edge of human advancement/progress.

20. Tell me about your background.
    Communication degree from UC Davis 2015 (I normally say Psych since the two are closely related and no one knows what 'Communication' is.) Retail jobs since graduation.
