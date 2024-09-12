# Portfolio

## Index Page

This is the first page that a user finds on the website.  The index.html has my picture and my overall career alignment. It also has a link to my LinkedIn profile and my other social media pages

## About Page

The about page has my interests, in depth description of my aspirations and my skills. The about.html file is made for the about page.

## Resume page

The resume page has my educational background and professional experience. it also contains a link to download the cv. This is found in the resume.html

## Projects page

The projects page has my projects. This is found in the services.html.

## Contact page

The contact page has a contact form that sends mails to my email address. The form uses fetch to make http request to a backend node server that I managed to make and host in order to send mails. Since Javascript is a client side language and the only mailing service opens the mail app in order to send the email, I had to make sure the user is not bothered to do so by using the node JS server for the task. The fetch request uses post method to send the form details as a body object to the server and then the server sends the mails to me. I had to host the server on render because the server will not be running on local host when hosted on github pages. 

Here is a link to the github code of the Node JS server: https://github.com/lesmadeit/contact_server.git