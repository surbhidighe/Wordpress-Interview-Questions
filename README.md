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
| * Can add plugins and themes  | * Can not add plugins and themes  |
| * Can make money by placing ads  | * Can not make money |
| * Need to look after backups and updates  | * We will not have to worry about updates or backups. WordPress.com will take care of that. |

### 6. How can you enable and disable debug mode in wordpress
##### Disable Debugging
* define( 'WP_DEBUG', false ); //in wp-config.php file

##### Enable Debugging
* define( 'WP_DEBUG', true ); //in wp-config.php file

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


******************************In progress******************************************


