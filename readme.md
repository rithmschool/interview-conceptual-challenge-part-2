# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?

* hyper text trasnfer protocol--evrerything sent over the internet must be text
* set of rules for communication btwn client/server or server/server
* https is secure http

2.  What is the difference between GET and POST?

* GET appears in the query string as key/value pairs; use POST for passwords!
* POST sends data in the body
* GET is idempotent--if data is sent to server and response may be different, use POST

3.  What is REST?

* convention governing how routes should be named
* pattern for archityping we applications

4.  What is DNS?

* Domain Name System--connection between

5.  What is AJAX?

* tool to send request methods and retrieve responses
* asyncrhonous javascript and XML
* making requests to a back end without refreshing the page

6.  What is the Same Origin Policy?

* incredibly restricts how a document or script will interact with another document or script
* browser based
* ports, domains, protocol--these cannot differ (cannot use AJAX with twitter for example)

7.  What is CORS?

* Cross origin resource sharing--permitting sharing information across domains
* enabled using headers -> accesed control -> use cors
* _study this_

8.  What is responsive design?

* web/app design that adjusts to screen size, orientation, and/or with window resizing
* approch to building web pages--three principles:
  * flexible layout: some way of adjusting layout based on screen size, etc.
    * %, rem, em, vh, vw
  * media queries: the rules specified that govern css depeding on width/height
  * flexible images: scaling image size appropriately for the device/connection
    * `<picture>` tag in html, replacing img
* (responsive design, 'mobile first', when building applications/sites)

9.  What does "use strict" do in JavaScript?

* turns off cheat codes... enables strict mode which disallows the following code:
* cannot use undeclared variables without var/let/const
* not setting properties on primitives
* cannot name parameters all the same names

10. What are data- attributes good for?

* stores custom data in an HTML attribute: `<p data-some-type="some value"></p>`
* data attributes have no real meaning (vs a class for js/css or id to be unique)
* provides additional informatin but don't hold much semantic value, no pre-defined meaning

11. Describe the differences between cookies, sessionStorage and localStorage

* cookies store information in the browser to allow for faster load times on regularly visited pages reruiring the same information; sessionStorage stores information in the browser for a specified period of time (token); localStorage stores information in the browser until deleted
* cookies is 4KB, accessible across all domains
* localStorage is 5MB, domain specific
* sessionStorage is tab specific

12. What is an HTTP header? List some examples of headers you've used.

* an optional part of a method request (`Authorization: Bearer <Token>`; caching, CORS)
* lists meta-data about the request or response

13. What is Cross Site Scripting or XSS?

* inserting malicious script into a page--E.g., form takes input value and places it on webpage, a script would be added to the page
* thwarted by escaping HTML--treat script tags and children as strings

14. What is SQL Injection?

* attempting to write SQL commands, usually in a form input, to access a site's database
* ORMs help thwart SQL injection--limit don't use string concatenation
* commonly done by adding another SQL command following form input (`1; DROP TABLE users`)

15. What is Cross Site Request Forgery or CSRF?

* creating a form on one website with an action linking to another site, using the user's information from the form for reasons other than intended
* submitting a form in not necessary, can be triggered on page load
* on the server side, ensure that a form contains a CSRF/authenticity token generated each time form is created

16. What is Long polling?

* making a request to a server after a certain amount of times (every 100 ms, check the server for chat messages)
* ineffecient--wasting HTTP requests when no new info is available
* WS (web-sockets) Protocol--web is stateless and client server handshake, but they keep shaking hands so info is auto passed back and forth near real-time (used for chat; socket.io is a popular web library)
* Web RTC (reat time communication)--client to client connections (video chat) to be as seemless as possible

17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?

* the tree would be weighted to one side; use the middle as the root, inserting everything on its right in order and everything to its left in reverse order (assuming sorted in order not reverse order)

18. What are the advantages and disadvantages of using a linked list over an array?

* linked list is time constant when shifting, unshifting, popping, and pushing, but has no constant look-up by index
* stacks or queues can add order

19. What interests you about web development?

* It is possible to be on the forefront of solving big problems affecting large populations with the newest techologies; data collection and its growing leverage potential, further automization/AI/machine learning and its introduction to daily life, and streamlining the user exerperience of these things are fascinating, relevent, and unstoppable. I want to be a part of the teams ethically piecing together this evolving puzzle.

20. Tell me about your background.

* I graduated UC Irvine with a BA in Film & Media Studies and Minor in Digital Arts, and have successfully completed a four month full stack engineering accelerator at Rithm. Most recently I was contracted to a team at Groupmuse to delvelop their first iOS application. I bring with me a wide variety of work epxperience--DreamWorks Animation, fitness and nutrition personal trainer, EMT and firefighter intern--illustrating my ability to adapt and succeed in new and stressful situations tackling challenging and potentially unforseen problems. I have excellent written and oral communication skills, able to bridge the divide between interpersonaly work relations and technical conversation, and I have a passion for software development. I have been studying and working near 12 hours most days for four months building my skills in _insert relevant language/framework_ and before this worked and interned 70+ hours per week on an abulance and fire engine. I can promise a strong and consistent work ethic, a passion for learning, implementing, and improving, and a team-player who values honesty, support, and progress. At Jesuit High School Sacramento, I was taught to be a "Man for Others", an ideal by which I continue to challenge myself to live personally and professionally.
