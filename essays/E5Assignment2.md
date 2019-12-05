---
layout: essay
type: essay
title: E5 - Reflecting on Assignment 2
date: 2019-12-4
labels:
  - Assignment2
  - File I/O
  - Programming
---

The assignment was about upgrading Assignment 1 by implementing a login and registration page into our websiteand validating the user registration information to allow the user to make a purchase. Features to be included would be security, to make sure the user logs in or registers before making a purchase, and personalization, so the user’s name would appear on the invoice. A way we implemented the login was by using the File I/O to create a json file to store the information and having the server use the file.
https://dport96.github.io/ITM352/morea/150.Assignment2/experience-Assignment2_retrospective.html

From this assignment, I learned that sometimes, the code is simpler than one might think. Additionally, it could just be a search away. The was I was able to find a lot of the validation code and the meaning behind it was simply by looking online, reading how it worked, and implementing it into the code. I also learned that if something does not work, it could possibly be because the order is off. When I was trying to do a params.get() for a few variables but it did not work, it was a matter of simply moving one of the statements to the bottom because it was the one with the res.redirect, therefore not allowing the other statements to execute.

I did not work with a partner, so therefore the amount I contributed was 100%. Instead, I got help from Prof. Port whenever I needed it. Quite frankly, I needed help with nearly most things. A couple primary ones were starting the validations for registration, figuring out how to keep the text in the textboxes upon reload, and working on the security for the webpage and making sure the user didn’t go to the invoice page without going through login first. Additionally, my login page did not work correctly and kept attempting to load, which was a matter of wrong order in the if-else statement. I also needed help with figuring out why I was unable to have labels appear for the registration validation.

This assignment was similar from the first assignment in needing validation, but since we learned about creating the if-else statements for validations, it was more straightforward figuring out the rules to create the validations. Additionally, for Assignment 2, I feel that I had to implement more code on the server compared to the web pages themselves to make them work. In comparison, Assignment 1 seemed to need more code on the webpages (product display page and invoice page) than Assignment 2 since that was the assignment when we were trying to figure out how to make the validations work on the product display page and the invoice to correctly calculate the total price.

I spend about 20% of my time trying to figure out how to do something, 30% of my time writing code, and 50% trying to test and debug. Some of the time I used to write what I thought the code might be, but most of my time was spent staring at it trying to figure out what was happening.

What worked well was setting up the registration error validations and figuring out the basic code on how to create the error labels. However, what didn’t work well with that one was trying to get the parameters for the errors to the registration page in order to make the errors actually appear. A similar problem happened in trying to personalize the invoice with a name and making it appear. I also had problems with the login page not loading correctly if there was an error, which was a problem I should have solved earlier because it did not allow me to check validations correctly.

If I could go back in time, I would be more careful in reading the error messages and correcting them. Through reading the error messages in the console, it made it easier to diagnose the problem and figure out what might be wrong. Initially, I was more frustrated that I didn’t know what was going on and why something didn’t work the way I wanted it to, but by reading the error messages more carefully, it eliminated some of those issues. I also should have addressed the problem with my login page not loading correctly earlier because if I did, I could have allowed myself to check my validations easier if it did load correctly.

Additionally, I would try to take more breaks in between my coding. I often found myself sitting in front of my computer for hours on end trying to figure out how to make something work. Although I got one or two things figured out (like the validations on one instance and having the name show up on the invoice on another), it was still done within a 4-8 hours sitting when I could have been doing other work instead of being stuck on other problems.
