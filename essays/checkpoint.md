---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - ITM353
  - Assignment 3
  - Checkpoint
---
Screencast link:https://www.youtube.com/watch?v=3lxld3xFF04

Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype
Shown in the screen cast

Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.

The sites shopping cart will be a separate page where the user can view and edit their product choices. We will get the values from the quantity textboxes and load them into the cart from the given values.

Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.

How we will use sessions to mange our shopping cart is that we will load the given quantities the user wants from the product pages and load them into their session. The type of data we will be storing is the product name, price, and quantity desired. The server can load the session by the session id where users have to login before viewing there cart. 

How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?

How we will avoid access to the application when the user is not logged in or registered is that we will see if the user has a login cookie. If the user doesn’t then we won’t give them access to the invoice. Some security concerns we need to address is manipulating the cookies and not just putting the values in the query string like we had in assignment 2.

Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)

How we will provide personalization in the UI is that we while have a welcome message for the user or a message saying that this user is logged in after they have done so.

If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?

I am working with a partner. How we will split up the work is that my partner will work on the main requirements of the assignments and the initial work while I will be working on the IRs and formatting the pages.

How are you approaching Assignment 3 differently than Assignment 2?

How I’m approaching assignment 3 differently than assignment 2 is that I am starting earlier and making sure to ask for help and making sure I understand the code along the way.
