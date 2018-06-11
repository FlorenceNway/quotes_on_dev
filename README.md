# Quotes on Dev Starter

A WordPress theme for the Quotes on Dev project, forked from Underscores.

## Installation


### 1. Download generic wordpress theme 

	Add to  `wp-content/themes` directory.


### 2. Install the dev dependencies

 	`npm install` **inside theme directory** to install the npm packages needed for Gulp, etc.


### 3. Developing

-Build using WordPress as CMS
-Using Rest API
-Contain a About page, an Archives page, and Submit a Quote page
-Contain a blog post index page and a single view for blog posts
-Contain a search results page and 404 page
-Fetch an initial random post on the front page
-Fetch additional random posts on the front page using the WP API
-Display one item per page for the blog index and author archives, five items per page for category an  tag archives, and ten items per page for search results
-Accept new quote submissions from the front-end of the site using WP API (for logged in users only), 	 and set those submissions to pending by default
-Show a message to unauthenticated users on the “Submit a Quote” page that informs them they must log in to submit a new quote
