# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?
HTTP stands for HyperText Transfer Protocol. This is one of the standards that underline all communications on the Internet. It pertains to the format of sending and receiving messages.

2.  What is the difference between GET and POST?
These are both HTTP verbs (request forms), but GET request asks for information, does this more openly (information is sent through the query string), and in an idempotent way, POST is used when infromation needs to be sent (posted) to the server and does it in a slightly more secure way.

3.  What is REST?
REST is a standard to architect http endpoints. Using REST ensures that all developers can quickly get up to speed and work on the system and that developers can easily target the endpoints when developing connected apps.

4.  What is DNS?
DNS servers are servers that run the Internet's addressing system. DNS servers contain all the adresses of all the domains connected to the Internet and translate it from the human readable URL to the machine readable IP address.

5.  What is AJAX?
AJAX stands for Asynchronous Javascript and XML. Ajax is a way to make requests writing JS code using, for example, the jQuery library.

6.  What is the Same Origin Policy?
?

7.  What is CORS?
?

8.  What is responsive design?
Responsive design is a design phylosophy that enables webpages and web apps to render according to the environment (platform / resolution / etc.).

9.  What does "use strict" do in JavaScript?
I'm not certain, but I think strict influences how JS is interpreting the value of the this keyword and is treating variables. In strict mode the global this keyword will return undefined and I think it is impossible to drop variables from the function scope to the global scope (by not using var/let/const when defining it). 

10. What are data- attributes good for?
In requests the data attributes usually contain data pertaining to the request.

11. Describe the differences between cookies, sessionStorage and localStorage
These are all components of storing inforamtion about the communication between a client and the server. Because the web is 'stateless', servers and clients cannot identify eachother otherwise.
Cookies - they are a package sent by the server with authentication information that is stored by the client.
sessionStorage - can contain information duing the session on the server.
localStorage - a client side storage system in the web browser that can contain, for example, tokens.

12. What is an HTTP header? List some examples of headers you've used.
HTTP headers are part of http communications that usually contain additional information (like authentication) about the communication. I used headers to send user information and authentication token from the front-end to the server in a project.

13. What is Cross Site Scripting or XSS?
?

14. What is SQL Injection?
SQL injection is when an unauthorized party slips SQL commands into a communication that gives instructions to the data server. These can range from gaining access to information without authorization to damaging the database consistency or even making the database unusable (DROP tables/columns/DB).

15. What is Cross Site Request Forgery or CSRF?
Cross Site Request Forgery is a form of attack that enables the attacker to hijack data from another site that is also open in the web browser on the client and use the credentials to access information on the server without authorization.

16. What is Long polling?
?

17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?
Binary search trees don't take arrays, but primitives only, so the question is ambiguous.
But if you inserted a sorted list's elements one by one, you will end up with a very imbalanced tree as the first element will become the root and everything will go (depending on wheteher the list is sorted in ascending or descending order) either on the right or the left of the root.
If we know that the elements in the list are sorted, we can add the median of the list first and then recursively call medianInsert on the list on the left and on the right of the element until there are elements left.
If we don't know up front that the elements are in order, we can employ sophisticated balancing algorithms that move the elements of the tree around as more elements are added.

18. What are the advantages and disadvantages of using a linked list over an array?
An array is simpler, it also has a length property, it can be traversed in O(n) time and elements can be added and popped from the end in (1) time and space. But linked lists can have additional properties and elements can be added or removed from the front of the list in O(1) time and space, which would be an O(n) operation for an array. 

19. What interests you about web development?
I'm most interested in the unerlying systems and the business logic of how apps operate. I'm fascinated by how small changes and tweaks can have so huge impact on how systems and apps work.

20. Tell me about your background.
I studied law and economics at multiple universities. Thereafter I did a PhD in EU law and a postdoc in renewable energy law and policy. During this time I worked in Denmark and California.