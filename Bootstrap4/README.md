# Getting Started with Bootstrap

## Objectives and Outcomes

Steps to set up web page to make use of Bootstrap classes and components. At the end of this exercise, the following will be able to be done:

Download Bootstrap using NPM and include it in the project,
(npm install)

Understand how to set up a web project to use Bootstrap, by installing bootstrap 4.0.0 and it's dependencies; jquerry and popper.js
(npm install bootstrap@4.0.0 --save)
(npm install jquery@3.3.1 popper.js@1.12.9 --save)

Include the Bootstrap CSS and JS classes into a web page,
Insert the following code in the <head> of the index.html file before the title:
<!-- Required meta tags always come first -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta http-equiv="x-ua-compatible" content="ie=edge">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">

At the bottom of the page, just before the end of the body tag, add the following code to include the JQuery library, popper.js library and Bootstrap's Javascript plugins. Bootstrap by default uses the JQuery Javascript library for its Javascript plugins. Hence the need to include JQuery library in the web page.
 <!-- jQuery first, then Popper.js, then Bootstrap JS. -->
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>

