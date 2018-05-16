# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?

hyper text transfer protocol: a set of rules for sending information over the internet

2.  What is the difference between GET and POST?

GET is idempotent, i.e, it doesn't change the server's state and gets back the same response every time. Any data is conveyed in the query string as a key-value pair ,e.g., ?movie=titanic

POST is not idempotent. It seeks to change the server's state. Data is conveyed in the body of the request.

3.  What is REST?

REST is a set of conventions for architecting web applications. A RESTful API would be organized around resources, with route names such as /users, /users/new, /users/<id>/edit

4.  What is DNS?

Domain Name Server. It takes the human readable URL and looks up the IP address.

5.  What is AJAX?

Asynchronous JavaScript And XML, now commonly in JSON format. It is a way of implementing single page applications by making API calls and rendering new elements, all without refreshing the page.

6.  What is the Same Origin Policy?

?

7.  What is CORS?

?

8.  What is responsive design?

Responsive design ensures webpages respond to resizing in a user-friendly way.

9.  What does "use strict" do in JavaScript?

Prevent variables from being unintentionally declared globally without the var/let/const keywords.

10. What are data- attributes good for?

?

11. Describe the differences between cookies, sessionStorage and localStorage

cookies store information across domains

sessionStorage stores information for a single domain for as long as the session lasts

localStorage stores information for a single domain that persists beyond a single session

12. What is an HTTP header? List some examples of headers you've used.

An http header stores information about an HTTP request, such as an Authorization header which contains a token from the server.

13. What is Cross Site Scripting or XSS?

?

14. What is SQL Injection?

?

15. What is Cross Site Request Forgery or CSRF?

CSRF is when a malicious user makes a request from a victim's browser. For example, if someone was logged into their bank's site and also went to a malicious site, the malicious user could trigger a request from the victim's browser (with its token in local storage, for instance) to the bank to transfer the victim's funds to the malicious user (if there weren't safeguards in place).

16. What is Long polling?

?

17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?

The tree would be extremely unbalanced. You avoid this by balancing the tree when inserting.

18. What are the advantages and disadvantages of using a linked list over an array?

Time complexity for shifting and unshifting is constant O(1) for a linked list but linear O(n) for an array.
Look up for an index is constant O(1) for an array but linear O(n) for a linked list.

19. What interests you about web development?

I enjoy problem-solving and learning, and I find technology interesting. I like to know how things work. Learning JavaScript and Python has been fun, solving challenges has been fun, making things that work has been satisfying.

20. Tell me about your background.

I majored in math because I liked the problem-solving challenge but didn't find a career that used it and ended up in retail by default. I intended to only stay until I figured out what I wanted to do instead but that took a while since my choices usually meant going back to school and I didn't want to incur a large amount of debt. Computer science is one of the majors I considered in college so when I read that there is a large demand for those skills and non-traditional ways to gain them, I started pursuing that path. I found I enjoyed it and was reasonably good at it.
