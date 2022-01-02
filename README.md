# Wordpress-Interview-Questions
Wordpress interview questions
## Table of Contents

| S.No  | Questions |
| ------------- | ------------- |
| 1  | [What is Wordpress](#1-what-is-wordpress)
| 2  | [When was wordpress released](#2-when-was-wordpress-released)  |
| 3  | [What are the features of wordpress](#3-what-are-the-features-of-wordpress)  |
| 4  | [What are the minimum requirements to run wordpress](#4-what-are-the-minimum-requirements-to-run-wordpress)  |
| 5  | [Difference between wordpress.com and wordpress.org](#5-difference-between-wordpresscom-and-wordpressorg)  |
| 6  | [How can you enable and disable debug mode in wordpress](#6-how-can-you-enable-and-disable-debug-mode-in-wordpress)  |
| 7  | [Where is Wordpress content stored](#7-where-is-wordpress-content-stored)  |
| 8  | [Difference between posts and pages](#8-difference-between-posts-and-pages)  |
| 9  | [Current version of wordpress](#9-current-version-of-wordpress)  |
| 10 | [What is wordpress loop](#10-what-is-wordpress-loop)  |
| 11 | [Do deactivated plugins slow down your wordPress website](#11-do-deactivated-plugins-slow-down-your-wordpress-website)  |
| 12 | [What do you mean by child theme](#12-what-do-you-mean-by-child-theme)  |
| 13 | [What is the purpose of single.php file](#13-what-is-the-purpose-of-singlephp-file)  |
| 14 | [What is excerpt](#14-what-is-excerpt)  |
| 15 | [What are the 2 important files to make a wordpress theme](#15-what-are-the-2-important-files-to-make-a-wordpress-theme)  |
| 16 | [What are the different user roles](#16-what-are-the-different-user-roles)  |
| 17 | [What is htaccess file and its purpose](#17-what-is-htaccess-file-and-its-purpose)  |
| 18 | [How many default tables are there in wordpress](#18-how-many-default-tables-are-there-in-wordpress)  |
| 19 | [Name some form plugins that can be used to create forms in wordpress](#19-name-some-form-plugins-that-can-be-used-to-create-forms-in-wordpress)  |
| 20 | [What is wordpress taxonomy](#20-what-is-wordpress-taxonomy)  |
| 21 | [From SEO point of view is wordpress helpful](#21-from-seo-point-of-view-is-wordpress-helpful)  |
| 22 | [What are the rules that one must follow while developing a plugin](#22-what-are-the-rules-that-one-must-follow-while-developing-a-plugin)  |
| 23 | [What is the prefix of WordPress tables by default](#23-what-is-the-prefix-of-wordpress-tables-by-default)  |
| 24 | [What is comment moderation](#24-what-is-comment-moderation)  |
| 25 | [What are the limitations of wordpress](#25-what-are-the-limitations-of-wordpress)  |
| 26 | [How can we take backup of a wordpress site](#26-how-can-we-take-backup-of-a-wordpress-site)  |
| 27 | [What might be the reasons when the Plugins menu is not visible](#27-what-might-be-the-reasons-when-the-plugins-menu-is-not-visible)|
| 28 | [What are the steps to develop a wordpress plugin](#28-what-are-the-steps-to-develop-a-wordpress-plugin)|
| 29 | [When should you not recommend wordPress to a client](#29-when-should-you-not-recommend-wordpress-to-a-client)|
| 30 | [What are meta tags](#30-what-are-meta-tags)|



### 1. What is Wordpress
* Wordpress is a free open-source CMS (Content Management System)
* It is written in PHP and licensed under GPL (General Public License)

### 2. When was wordpress released
* It was released on May 27, 2003 

### 3. What are the features of wordpress
* Easy theme system
* Multilingual Support
* Built-in comment system
* Extend a specific functionality using adding plugins
* Free and open source
* SEO (Search Engine Optimized)
* User and media management

### 4. What are the minimum requirements to run wordpress
* PHP version 7 or greater
* MySQL version 5.6 or greater OR MariaDB version 10.0 or greater
* The mod_rewrite Apache module
* HTTPS support(Recommended)

### 5. Difference between wordpress.com and wordpress.org

| Wordpress.org  |Wordpress.com |
| ------------- | ------------- |
| * We host our site  | * WordPress.com takes care of all of this | 
| * Open Source and 100% free  | * It has different pricing plans (Free plan has limited features)  |
| * Can add plugins and themes  | * Can not add plugins and themes  |
| * Can make money by placing ads  | * Can not make money |
| * Need to look after backups and updates  | * We will not have to worry about updates or backups. WordPress.com will take care of that. |

### 6. How can you enable and disable debug mode in wordpress
##### Disable Debugging
```
define( 'WP_DEBUG', false ); //in wp-config.php file
```

##### Enable Debugging
```
define( 'WP_DEBUG', true ); //in wp-config.php file
```

### 7. Where is Wordpress content stored
* WordPress contents are stored in MySQL database on the Server.

### 8. Difference between posts and pages
Both are content types in wordpress

* Posts - They are timely and listed in reverse chronological order (Latest/Newest posts at the top). They can have categories, tags and author
* Pages - They are timeless e.g contact us/about page and so on.

### 9. Current version of wordpress
* You need to tell the current version of wordpress available at that time

### 10. What is wordpress loop
* Wordpress use PHP code to display posts, this code is termed as loop

### 11. Do deactivated plugins slow down your wordPress website
* No, Wordpress only loads the activated plugins and ignores the deactivated one

### 12. What do you mean by child theme
* Child theme is an extension of parent theme
* If we want to modify/change the existing functionality of a theme, then we can use child theme 
* Child theme will preserve all the changes and customizations even after updating the theme

### 13. What is the purpose of single.php file
* single.php file display a single post/blog.

### 14. What is excerpt
* A WordPress excerpt is an optional summary or brief summary that you can attach to a post.

### 15. What are the 2 important files to make a wordpress theme
* Style.css and index.php

### 16. What are the different user roles
1. Administrator 2. Editor 3. Author 4. Contributor 5. Subscriber.

### 17. What is htaccess file and its purpose
* htaccess file is a basic configuration file used by the Apache web server
* It lets you create special rules that tell your web server how to function
* It can override many server configuration settings
* Can be used for authorization, cache control, website optimization, and URL rewriting.

### 18. How many default tables are there in wordpress
There are 12 default tables in WordPress database
* wp_options
* wp_users
* wp_usermeta
* wp_comments
* wp_commentmeta
* wp_terms
* wp_termmeta
* wp_posts
* wp_postmeta
* wp_links
* wp_term_relationships
* wp_term_taxonomy

### 19. Name some form plugins that can be used to create forms in wordpress
* WPForms
* Formidable Forms
* HubSpot for WordPress
* Contact Form 7
* Jetpack Form
* Ninja Forms

### 20. What is wordpress taxonomy
* Wordpress taxonomy is a groupting mechanism to group related posts together
* By default, wordpress has 4 taxonomies - Category, Tag, Link Categroy, Post Formats

### 21. From SEO point of view is wordpress helpful
* Wordpress has an inbuilt SEO engine and it is one of the main advantage of using wordpress
* We can also install an extra SEO plugin (Most popular seo plugin is - YOAST SEO)

### 22. What are the rules that one must follow while developing a plugin
1. Create a folder inside wp-content/plugins directory
2. Give a unique name to that folder. For e.g I want to create a cookie plugin so, I'll set "Cookie" as folder name
3. Create a sub-folder for PHP files, translations, and assets
4. Create the main plugin file, and fill up the header information
5. Create activation and de-activation function
6. Create an uninstall script
7. Create a readme.txt file
8. Use proper constants and functions to detect paths to a plugin file

### 23. What is the prefix of WordPress tables by default
```
wp_ is the prefix for WordPress
```

### 24. What is comment moderation
When a visitor/user comments on a post, the comment is not published directly until and unless it is approved by the admin to be posted. It is used to avoid comment spamming.

### 25. What are the limitations of wordpress
* Using a huge number of plugins can make the website heavy to load
* Frequent plugin and theme updates
* Data Security and Vulnerability
* One must have knowledge about PHP in order to write custom code
* Some plugins may conflict with each other

### 26. How can we take backup of a wordpress site
There ar 3 ways to take backup-
1. Using Plugin
```
There are various plugins that can be used to automate the backup of a wordpress site. Some of them are UpdraftPlus, BackupBuddy etc.
```
2. Through Hosting
```
Most web hosting companies offer free, automatic backups with their advanced hosting plans and charge a little extra for users on their basic plans. 
```
3. Manually
```
We can use backup scripts and can manually take backup from FTP or Cpanel
```
### 27. What might be the reasons when the Plugins menu is not visible
* Reason 1 - When the website is hosted on wordpress.com
* Reason 2 - When the user is logged in with a non-admin account 
* Reason 3 - When the WordPress website/blog is a part of a multi-site-network and the network admin has disabled the plugin menu
* Reason 4 - Plugins or Themes Conflict

### 28. What are the steps to develop a wordpress plugin
1. Create a new folder inside wp-content/plugins directory
2. Give a unique name to that folder e.g My-First-Plugin
3. Create a new php file inside My-First-Plugin folder
4. Add below header info inside the php file
```
<?php
/**
* Plugin Name: My First Plugin
* Plugin URI: https://www.yourwebsiteurl.com/
* Description: This is the first plugin I have created.
* Version: 1.0
* Author: Your Name Here
* Author URI: http://yourwebsiteurl.com/
**/
```
5. Create functions for activation and deactivation, create an uninstall script and readme.txt file.

### 29. When should you not recommend wordPress to a client?
1. If they are working on a non-CMS based project
2. If they want complex website
3. If the site requires a huge number of custom scripting solutions

### 30. What are meta tags
Meta-tags are descriptions and keywords that are used to display website or page information.

******************************In progress


