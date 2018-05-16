# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?

hyper text transfer protocol: a set of rules for sending information over the internet
rules that govern communication between client and server, or server and server
GET,POST,PATCH,DELETE

https? secure http

2.  What is the difference between GET and POST?

GET is idempotent, i.e, it doesn't change the server's state and gets back the same response every time. Any data is conveyed in the query string as a key-value pair ,e.g., ?movie=titanic

POST is not idempotent. It seeks to change the server's state. Data is conveyed in the body of the request.

3.  What is REST?

REST is a set of conventions for architecting web applications. A RESTful API would be organized around resources, with route names such as /users, /users/new, /users/<id>/edit

(web is stateless, using GET/POST etc, using http etc)

4.  What is DNS?

Domain Name System. It takes the human readable URL and looks up the IP address.
https://www.cloudflare.com/learning/dns/what-is-dns/

5.  What is AJAX?

Asynchronous JavaScript And XML, now commonly in JSON format. It is a way of implementing single page applications by making API calls and rendering new elements, all without refreshing the page.

(Asynchronous: request doesn't block code, JavaScript: doesn't exist in Python)

6.  What is the Same Origin Policy?

A web browser permits scripts contained in a first web page to access data in a second web page only if both web pages have the same origin. (Wikipedia)

7.  What is CORS?

Cross Origin Resource Sharing: a way around the Same Origin Policy using headers
https://www.maxcdn.com/one/visual-glossary/cors/

8.  What is responsive design?

Responsive design is an approach to building web pages
It ensures webpages respond to resizing in a user-friendly way.
3 principles:

1.  Responsive/Flexible Qayout: need some way of adjusting layout, eg, using different measurements rem, %
2.  Media Queries: rules that specify css for certain widths and heights
3.  Responsive/Flexible images: 500x500 not cool on mobile. <Picture> tag now allows for different images. (If you load an unnecessarily large image, it has latency issues ie takes a long time unnecessarily.) Like a large if statement that html handles for you and renders the correct image for the circumstance.

9)  What does "use strict" do in JavaScript?

Enables strict mode.
Enforces better JavaScript practices.
Not setting properties of primitives. (Can't, but won't raise an error without strict mode.)
Not using var let or const.
No duplicate names for your parameters.

The point of strict mode is to fail loudly instead of silently.

Prevent variables from being unintentionally declared globally without the var/let/const keywords.

10. What are data- attributes good for?

data-anything
Used in the Rithm app for things like analytics
Giving additional information to html elements that can be targeted with JavaScript.
If list of todos and have ids from database, don't want it be stored in an id attribute (for css, and becomes global variable on window in JS)

11. Describe the differences between cookies, sessionStorage and localStorage

cookies store information across domains, are much smaller (4KB). Track user info across domains.

sessionStorage stores information for a single domain for as long as the session lasts (5MB). Tab specific.

localStorage stores information for a single domain that persists beyond a single session. Domain specific.

cookies easier to encrypt. Can't really encrypt localStorage. (Servers normally set the cookie.)

12. What is an HTTP header? List some examples of headers you've used.

An http header stores information about an HTTP request, such as an Authorization header which contains a token from the server.
Cacheing: tell browser to remember something for a certain amount of time
Header for CORS
Content type: I want JSON

13. What is Cross Site Scripting or XSS?

Injecting malicious js on a page. Form that is trusting, takes user input and set it as html on a page with jQuery. Could make ajax requests or access cookies.

Solution: Escaping text. "Sanitize" it. Treat it as string, not html.

<script> </script>

14. What is SQL Injection?

If you use a variable and that variable is directly user input, they could escape and write another command.
1; DROP TABLE users;
ORMs prevent this. Some allow only 1 SQL query at a time. Others say no string concatenation when user input.

15. What is Cross Site Request Forgery or CSRF?

CSRF is when a malicious user makes a request from a victim's browser. For example, if someone was logged into their bank's site and also went to a malicious site, the malicious user could trigger a request from the victim's browser (with its token in local storage, for instance) to the bank to transfer the victim's funds to the malicious user (if there weren't safeguards in place).

Prevent: Server requires a token for a form. WTForms in Flask.

16. What is Long polling?

Make requests over and over again.
Long polling: make request to server after a certain amount of time. Ajax request every 100ms.
Chat app.
FB alerts pop up frequently.

Very inefficient. If no updates.
A better way it to not use http.
WS - web socket (client server handshake of trust, get data, then handshake is done. web socket is like a very awkward handshake that doesn't end. eg socket.io very popular tool. Don't have to do authorization stuff every time b/c handshake is still there. socket.io is really easy to use with great tutorials.)
WebRTC - video chat would need this. Closest to communication between client and client. Need the most real time as possible, eg, for video chat. Any latency is terrible.

17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?

The tree would be extremely unbalanced. You avoid this by balancing the tree when inserting.

Could start in the middle of the sorted array, go left, go right, then go left again etc.
Elie said this could lead to the interviewer asking you to write a function to check if a BST is balanced.

18. What are the advantages and disadvantages of using a linked list over an array?

Time complexity for shifting and unshifting is constant O(1) for a linked list but linear O(n) for an array.
Look up for an index is constant O(1) for an array but linear O(n) for a linked list.

19. What interests you about web development?

I enjoy problem-solving and learning, and I find technology interesting. I like to know how things work. Learning JavaScript and Python has been fun, solving challenges has been fun, making things that work has been satisfying.

20. Tell me about your background.

I majored in math because I liked the problem-solving challenge but didn't find a career that used it and ended up in retail by default. I intended to only stay until I figured out what I wanted to do instead but that took a while since my choices usually meant going back to school and I didn't want to incur a large amount of debt. Computer science is one of the majors I considered in college so when I read that there is a large demand for those skills and non-traditional ways to gain them, I started pursuing that path. I found I enjoyed it and was reasonably good at it.

21. What happens when you type google.com and press center

request made
DNS lookup to find on of google's IP addresses
server sends http response, text
browser looks at header to see if it's html,
browser parses text,
creates the DOM
any more script tags, make more requests
paint or draw the page

There's a github page with lot of "what happens when..."

TCP is the handshake, where packets being sent. Stick with high level. Don't fake it.
