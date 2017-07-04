## Synopsis

PAM is a new framework made from best parts of PHP, ANGULAR and MONGODB.  PAM is also designed to work without any database at all, and can easily also use mySQL or any other database you like.

We chose mongodb as a default because of its speed and flexibility.

PAM is a work in progress and still in  development. 

We are currently looking for contributors.

1. Asset Management
   Keep information such as servers and passwords for your apps, webservices, and websites in one place.
   
   1. Google Pagespeed
   2. SEO Tools
   3. Dashboards for sites and apps
   4. Social Network Management with facebook and twitter (as of now)
   5. create/delete users for all assets with one form regardless of platform
   
2. Project Management
   Keep track of bugs, feature requests, and incidents with agile project management software.
  
   1. Simple version of jira
   2. custom but simple agile solution
   3. Scrum boards
   4. Customizable Charts and Reporting
3. Code Deployment
   Custom solution with integration to Github/Bitbucket for simple code deployment

4. Team Communication
   Store all users and clients in PAM, with all of their contact info.  Integration with slack, or perhaps a custom solution with jabber.

5. Code Bank
   Integration with codepen so your entire team can reuse code. No more writing the same code more than once.

   1. Codepen Integration
   2. 

  
6. Time Tracking
   Keep track of time and automatically create invoices for your clients.
    
7. Invoicing
   1. Simple invoices as html & downloadble pdf
   2. Accept Bitcoin and Ethereum (ether)
   3. Accept Credit Cards 
   4. Export to Quickbooks

8. Document Management
   Integrate a custom document library built by Amir Meshkin for Wordpress.  Keeps track of all types of documents, and allows creation of PDF docs from html you create.
   
   1. Store documents
   2. Create and Edit documents
   3. Share with anyone 

Packing all of these features into one open source software package is our ultimate goal.
    
Every module will be kept fairly simple.  If there is a real need, then use jira.



## How it Works

PAM uses node modules, composer and bower.  Although bower is somewhat unneeded and may be removed.

Docker is also slated to be added to make installation easier.

## Screenshots


 ## Main Dashboard ##

![picture alt](http://www.brightlightpictures.com/assets/images/portfolio/thethaw_header.jpg "Title is optional")

## Motivation

I've built websites for a living for almost 20 years.  One thing I've noticed is that each agency lacks a centralized system for digital asset management.  

PAM is the place where you can store details about your apps and sites, and much more.  Tools and screens such as the SEO Dashboards, pagespeed dash and others are designed to help webmasters get their info in one place.

PAM will save hours with on-boarding, and help teams work together better.

## Installation

TODO: // add docker and quick install

GOOGLE DOCUMENT FOR DEVS

https://docs.google.com/document/d/10vl0BbHNAB6LBeIyedmFMdRGXTofGwQ3r_zojSzjVJo/edit?usp=sharing

## API Reference

//TODO: need awesome angular documentation system


## Contributors

Actively seeking out the best contributors!

## License

MIT


## TEMP INSTALL INSTRUCTIONS

Since PAM uses php, you will need to have a php server with the app folder as root.  

We're going to add docker soon to make this easier.

Open a terminal window to the root directory and type:

npm install

composer install

gulp

 