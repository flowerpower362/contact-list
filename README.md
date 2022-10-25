# contact-list

contact list challenge in Boise Codeworks Training

My Contact List (Challenge)

Source Code:
In this course you are going to have several challenges to attempt on your own, then we’ll walk through the solution in the subsequent video. Take this time to challenge yourself to solidfy your learning. Do not simply watch the videos without pausing and trying the challenge.
This Code Challenge style of learning is designed to help you practice your syntax and prove to yourself that you are retaining information between videos and challenges.

Goals
In this app you will build a contact list management tool. This app will allow users to add and remove contacts from their list and mark some contacts as Emergency Contacts.

The Setup
The basic design and layout for this app has been mocked out and the names of the JavaScript functions have all been created. As the developer you will need to work accross HTML, CSS and JavaScript to complete the requirements. In the code you will see several comments intended to be used as help and guidelines on what needs to be accomplished. Once you have achieved the requirements of the app use GitHub to host the page live.

Requirements:
//Visualization-
The add contact form can be shown or hidden when necessary [CSS property hidden ]

Contacts marked as Emergency Contact must be easily distiguished [put check box input on the contacts form and add a red star icon next to the contact on the list (icon info from font awesome)

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/fontawesome.min.css" integrity="sha384-z4tVnCr80ZcL0iufVdGQSUzNvJsKjEtqYZjiQrrYKlpGow+btDHDfQWkFjoaz/Zr" crossorigin="anonymous">

<i class="fa-solid fa-star"></i>

]

A custom Google Font must be added --> [font-family: Source Serif Pro]

Contacts are visible when the page reloads--> [not sure ]

//Functionality-
Add Contact form clears when submitted [JS file function hidden vs. not hidden upon change in status]

Add Contact form submission does not reload the page--> [not sure ]

Contacts are stored in local storage. --> [not sure...have to go back and rewatch balloon pop local storage tutorial ]

Contacts can be deleted --> [not sure ]

//Step by Step Guide-

1. Add The extra input fields for phone and emergency-contact to the add
   Contact Form
   -use type checkbox for Emergency Contact [DONE]
   -Don’t forget the name Attribute [DONE]

2. Handle the form submission
   -Prevent the page from reloading when submitting the form [ ]
   -Pull the form data to get a new contact and give that contact an id
   -Add the new contact to the contacts list
   -Reset the form
   -Save the contacts list
   -Draw the contacts list

3. Handle Page Refresh
   -Load the contacts list
   -Draw the contacts list

4. Show and Hide Form on button clicks

codeworksacademy/contact-list
Language
CSS
Last updated
7 months ago
