# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP?

    HTTP is a protocol (means of communication) between servers and browsers. HTTP is the underlying protocol used by the web and it defines how information is transmitted. It also specifies how servers and browsers should interact. In HTTP, we have requests that are issued by clients (and sometimes servers) to other servers. Those servers then issue a response back to the originator of the request.

    Hyper Text Transfer Protocol is the underlying protocol used by the World Wide Web. This protocol _defines_ how messages are formatted and transmitted and what actions web servers and browswers should respond to various commands.

    * HTTP is a stateless protocol because each command is executed independently, without any knowledge of the commands that came before it.
    * HTTP Status Codes are Error Messages

2.  What is the difference between GET and POST?

    GET - An _idempotent_(**An idempotent operation is one that will repeatedly produce the same result.**) operation that is designed for getting data from the server

    POST - A _non_ idempotent operation that can create data on the server or otherwise modify data.

3.  What is REST?

    (REpresentational State Transfer) is an architectural style, and an approach to communications that is often used in the development of Web services. The purpose of REST is to provide a framework for creating fast, scalable and reliable APIs.

4.  What is DNS?

    Short for Domain Name System, this is a system that takes human-readable URLs and converts them into IP addresses.

5.  What is AJAX?

    this stands for Asynchronous JavaScript and XML. It is a set of technologies that allows for building single page applications (applications that do not require full page refreshes to change data on the page).

6.  What is the Same Origin Policy?

    In computing, the same-origin policy is an important concept in the web application security model. Under the policy, a web browser permits scripts contained in a first web page to access data in a second web page, but only if both web pages have the same origin

    The same-origin policy restricts how a document or script loaded from one origin can interact with a resource from another origin. It is a critical security mechanism for isolating potentially malicious documents - MDN

7.  What is CORS?

    Cross-Origin Resource Sharing is a mechanism that uses additional HTTP headers to let a user agent gain permission to access selected resources from a server on a different origin (domain) than the site currently in use. A user agent makes a cross-origin HTTP request when it requests a resource from a different domain, protocol, or port than the one from which the current document originated

8.  What is responsive design?

    Responsive design is the idea that your webpage will resize when the screen size changes.

9.  What does "use strict" do in JavaScript?

    1.  Eliminates some JavaScript silent errors by changing them to throw errors.
    2.  Fixes mistakes that make it difficult for JavaScript engines to perform optimizations: strict mode code can sometimes be made to run faster than identical code that's not strict mode.
    3.  Prohibits some syntax likely to be defined in future versions of ECMAScript.

10. What are data- attributes good for?

    allow us to store extra information on standard, semantic HTML elements without other hacks such as non-standard attributes, extra properties on DOM

11. Describe the differences between cookies, sessionStorage and localStorage

    Cookies

    SessionStorage

    LocalStorage

12. What is an HTTP header? List some examples of headers you've used.

    allow the client and the server to pass additional information with the request or the response
    tokens

13. What is Cross Site Scripting or XSS?

    Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted web sites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user. Flaws that allow these attacks to succeed are quite widespread and occur anywhere a web application uses input from a user within the output it generates without validating or encoding it.

14. What is SQL Injection?

    SQL Injection (SQLi) refers to an injection attack wherein an attacker can execute malicious SQL statements (also commonly referred to as a malicious payload) that control a web application’s database server (also commonly referred to as a Relational Database Management System – RDBMS). Since an SQL Injection vulnerability could possibly affect any website or web application that makes use of an SQL-based database, the vulnerability is one of the oldest, most prevalent and most dangerous of web application vulnerabilities.

15. What is Cross Site Request Forgery or CSRF?

    CSRF is an attack that forces an end user to execute unwanted actions on a web application in which they're currently authenticated. CSRF attacks specifically target state-changing requests, not theft of data, since the attacker has no way to see the response to the forged request.

16. What is Long polling?

    Long polling basically involves making an HTTP request to a server and then holding the connection open to allow the server to respond at a later time

17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?

    It would be on oneside(right). Root should be the middle node to ensure it is balanced

18. What are the advantages and disadvantages of using a linked list over an array?

    Advantages:
    Finding Point of insetion and deletion is O(n)
    Performing Insertion/deletion is O(1)

    Disadvantages:

    Not ordered

19. What interests you about web development?
20. Tell me about your background.
