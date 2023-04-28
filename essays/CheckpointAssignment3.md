---
layout: essay
type: essay
title: "Checkpoint Assignment #3"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: false
labels:
  
---

1) Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype <br>
View screencast <a href = "https://www.youtube.com/watch?v=3lxld3xFF04">here</a>.
<br>

2) Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product 
pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.<br>
The site's shopping cart will be a separate page. When we get values from quantity textboxes and load the shopping cart with the chosen values.
<br>

3) Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.<br>
We will use sessions to maintain the shopping cart. Quantities that a user chose will be loaded onto the session. We will store the product name, price, and quantity desired. The server will load the session by the session id, which users will get after logging in before being able to view their cart.
<br>

4) How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address? <br>
When a user is logged in, they will receive a login cookie. If the user doesn’t have one then they will not be able to access the invoice and/or shopping cart. Some security concerns we need to address is the fact that cookies can be manipulated.
<br>

5) Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)<br>
Upon a successful login, our personalized UI will have welcome message for the user similar to the cookies and sessions lab, or a message saying that this user is logged in like the previous assignment.
<br>

6) If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is 
doing what and when? <br>
I am working with a partner. I will be working on the main requirements of the assignment and the initial work while my partner will work on the IRs and the page formatting.
<br>

7) How are you approaching Assignment 3 differently than Assignment 2?<br>
I intend to ask for as much help as possible during this assignment, and use outisde sources and examples to help give me inspiration. I am also looking into it earlier than I have for the previous assignments.
