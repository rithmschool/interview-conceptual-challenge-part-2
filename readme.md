# Interview Conceptual Warmup Part 2

## Instructions

* Fork and clone this repository
* Place your answers inside of this file (you can keep these answers to a sentence or two)
* Submit a pull request to submit the assignment

## Questions

1.  What is HTTP? HTTP is hypertext tsomething protocol, it is the language in which information is transmitted through the web. It's an address for the browser to assimilate into language that dns servers can understand and send to other servers.
2.  What is the difference between GET and POST?
    A get request is idempotent, meaning it does not change. a get request will return data that is not to be changed, only read essentially. A post is when anything needs to be changed or created, basically when something is being modified like a password, email or a post.
3.  What is REST?
    Rest is a convention for naming url end points, so that the industry can have a standard to fall back on and people can share a common archetype for back ends.
4.  What is DNS?
    DNS is a type of server, they are essentially computers that are extremely interconnected with other servers, who communicate packages to one another, receiving and sending data, usually in the form of website data.
5.  What is AJAX?
    AJAX is a way for javascript to be transcribed into JSON, then sent to a server to make requests for data.
6.  What is the Same Origin Policy?
    Idk
7.  What is CORS?
    Idk
8.  What is responsive design?
    Responsive design probably refers to design or user interface that will dynamically render things in response to user input, in the context of a web app, when you drag the screen size to be smaller and smaller, the elements on the page may change in accordance to the viewport width and height, hence it being "responsive."
9.  What does "use strict" do in JavaScript?
    It has something to do with the keyword this but I forget specifically what it does.
10. What are data- attributes good for?
    Data attributes are good for carrying information about the data, that describes the data, but not necessarily is a part of the data group itself. Like for example if you were transmitting data about pizzas, you might have crust, toppings, sauce. But a data attribute might say, "food", "italian." It has information about the data which is useful, but is irrelevant within the scope of the data itself. I may have totally misunderstood this question though, I'm not positive what the context of this question is...

11. Describe the differences between cookies, sessionStorage and localStorage
    Cookies are a way for your browser to save information that has already previously been rendered before. For example when you go into facebook, it may store all of your friends posts, images, and news feed items so that next time when you load the page, it doesn't have to go retrieve all that information from a server, it can simply render them from the cookies. Session storage is a type of storage, basically an object to store key value pairs, but it refreshes and clears anytime the session is ended, ie the browser is closed. Local storage will persist through these sessions, but only on your machine and until you clear it.

12. What is an HTTP header? List some examples of headers you've used.
    An HTTP header is basically an object that contains information about what the data being transmitted is. We've used authorization headers in the past.
13. What is Cross Site Scripting or XSS?
    XSS is when a web page secretly renders a form, then redirects you to another site. The form/input is still in the background but it's invisible and the information you type into the other site will also unknowingly go into their form as they catch and steal information.
14. What is SQL Injection?
    SQL injection is when you hack an input to close the input string and the computer processes the rest of your message as legitimate SQL run by the server. you can use this to steal private data or drop a database.
15. What is Cross Site Request Forgery or CSRF?
    CSRF is when you forge a valid token on another website, since usually all the website is checking for is a valid token.
16. What is Long polling?
    I'm not sure.
17. What would happen if you inserted a sorted list into a binary search tree? How can you avoid this problem?
    If you inserted a sorted list into a node of a BST for the value, it would probably break any algorithms that depend on extracting the value from the node... You could avoid this by not inserting sorted lists into a binary search tree? I'm really not sure what this question is asking..?

18. What are the advantages and disadvantages of using a linked list over an array?
    Linked list are much faster than an array for adding and removing from the front, however they are more cumbersome to manage when you need elements at a specific index. In an array you can just grab the element at whatever index, but in a linked list, indices dont exist so you need to loop through the list until you find the piece that you're looking for.
19. What interests you about web development?
    Web development does not interest me as much as technology development and technology as a whole does. We have an opportunity to build tools and spaces that people can use, and you can communicate with a potentially vast number of people to share knowledge, experience, or feelings. Web development is a vast medium through which you can communicate, which is what inspiress me.
20. Tell me about your background.
    I'm a photographer and visual artist with a science background. I spent a year working odd jobs after college then traveled for half a year to try to decide what I wanted to do with my life. Along the way I realized I had a passion for creating things and experiences, so through the medium of photography I began to explore visual aesthetics.. After about a year of following photography I felt like I was ready for it to be a major part of my life and decided to try to make that my career. Quickly soon I realized that the reality of being a full time photographer entailed everything that I disliked about photography. I found myself changing everything about my own work to fit what was popular and needed at the time and I realized if I wanted to truly make art a part of my life and a high priority, that I'd need to put it on the backburner and pursue other career interests first. About that time I had been toying with the idea of learning to code, and as I looked further and further into it I realized it was perfect for me. I had done web design for a company in the past and I found myself actually really enjoying the entire process. After I realized that it was a career I could see myself doing for the long haul I decided to jump for San Francisco and landed on a bootcamp to help me get started. I saw it as a way to be able to use my science/logical thinking background and my design skills to create usable products that people could interact with. I've never wanted to be in a place that I felt was stagnant and it seems that in the tech industry, things are always growing whether for better or for worse. I've always loved the idea of being rewarded for quality of product, rather than seniority or other factors that seem to mold other industries. So then I decided to go through with it, and it became a matter of finding the right place to learn and grow, upon which I happily stumbled across Rithm School.
