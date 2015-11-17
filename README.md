REST Service for Client Side Scaffolding of HTML, JS, CSS, Frameworks and jQuery plugins.


This service allows you to choose several options to add to your scaffold 
and creates a basic site directory with the files you've chosen to include.


The Basic directory package includes only the items listed below
in the following directory structure:


#Your new project
  - index.html
  - css
    -- style.css
  - js
    -- site.js

The Cadillac directory option includes everything listed below 
in the following directory structure:

#Your new project

  - index.html
	
  - css
	
	  -- style.css
  - js
	
	  -- site.js
		
  - assets
	
	  -- bootstrap
		
		  --- bootstrap.css
			
		  --- bootstrap.js
			
	  -- foundation
		
		  --- foundation.css
			
		  --- foundation.js
			
	  -- jquery-validation -> for complete information see http://jqueryvalidation.org/documentation/
			
		  --- demo
			
		  --- dist
			
		  --- lib
			
		  --- src
			
		  --- test
			
		  --- Gruntfile.js
			
		  --- README.md
			
		  --- package.json
		
	  -- jQuery.js
		
		
The index.html file will only contain the basics to get started.
The more assets you choose the more links will be included in the <head>.
The style.css file will only contain styles for a very basic navigation.

#Question: 
What is the difference between bootstrap and foundation?

#Answer: 
Bootstrap and Foundation are both front end web development frameworks
built around a responsive grid system.  Bootstrap includes a variety of
css themes and can save you loads of time if you don't need to design a 
site that looks completely unique and fresh.  Foundation has built-in form
validation from Abide, so you won't also need jQuery-validation.
Framework doesn't have as much css included which means adding your own flare
is a bit easier, Bootstrap has a reputation for looking like your site was
designed with Bootstrap and the css file is bigger.  However, if you want 
to get a site designed fast and you don't really care that people might
be able to tell you've designed it with Bootstrap then Bootstrap is
significantly faster to implement than Foundation.  Often designers use
Bootstrap themes to create quick mock up of a site.

