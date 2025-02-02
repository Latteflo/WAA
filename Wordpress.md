# Vulnerabble Wordpress

* IP : 10.12.1.60
* PORT: 31338
* URL  : http://10.12.1.60:31338/

----

## What is Wordpress  
WordPress is a free, open-source content management system (CMS). This software written in PHP is based on a MySQL database and is distributed by the WordPress.org foundation. The functionalities of WordPress allow it to create and manage different types of websites: showcase site, online sales site, application site, blog, portfolio, institutional site, teaching site...

It is distributed under the terms of the GNU GPL version 2 license. The software is also used as the basis for the WordPress.com3 multi-site service, which supports several million sites4.

43% of the Web is powered by WordPress. More bloggers, small businesses and Fortune 500 companies use WordPress than all other options combined.

## Site Management and Administration
WordPress is a content management system designed to be installed locally on one's personal computer, on an office computer or on an intranet. Through its own web server or shared hosting, it is possible to access and modify the content of the website at any time24.

Installation and updates of WordPress are quick and easy.

The website can be managed and administered by several users, each of whom can create a profile by entering several pieces of information. It is possible to restrict the possibility of creating and modifying content for a user by managing his access rights 25 :

- administrator: has access to all the features of the WordPress administration, this profile is created automatically during the installation of WordPress;
- editor: can publish and manage his own pages as well as those of other users;
- author: can only publish and manage their own posts;
- contributor: can write and manage his own articles, but cannot publish them;
- subscriber: can only manage their profile and information.

## WPScan
WPScan is a free software that helps you identify security issues on your WordPress site. It does several things like:

Check if the site is using the vulnerable WP version
Check if a theme and plugin are up to date or known to be vulnerable
Check timthumbs
Check configuration backup, database exports
Brute force attack
and much more...

There are several ways to use WPScan.

- By installing on Linux servers
- Using Docker
- Using a pre-installed Linux distribution like Kali Linux, BackBox, Pentoo, BlackArch, etc.
- Online version

### Install

The beauty of using Kali Linux is that you don't have to install anything. WPScan is pre-installed.

Let's find out how to run the scanner.

Login to Kali Linux with root and terminal open
Run the scan using wpscan command
````
wpscan --url https://mysite.com
````


### Additionnal ressources
- https://www.cyberpratibha.com/blog/wpscan-kali-linux-tutorial/
- https://www.youtube.com/watch?v=aiVBMxaa2BM&ab_channel=TECHYRICK 
- https://www.it-connect.fr/comment-auditer-un-site-wordpress-avec-wpscan/ (French)

### Extension

There is also a WPScan extension for Chrome. It is called WPScan Extension. It is a browser extension that allows you to scan a WordPress site for vulnerabilities. It is available on the Chrome Web Store.
 [WPScan](https://wordpress.org/plugins/wpvulnerability/)

