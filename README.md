# Simple plugin starter

A structured, object oriented foundation to help you quickly build and deliver plugins.

## Contents

Page builder add on boilerplate is structured as mentioned below:

* `plugin-starter.php` Your main plugin file and class, adds admin and public hooks and initiates admin and public classes
* `README.md` The file that you’re currently reading.
* `assets` Contains client side and admin side scripts and styles
  * `front.js` jQuery script enqueued on front end
  * `front.css` Stylesheet enqueued on front end
  * `admin.js` jQuery script enqueued on admin end
  * `admin.css` Stylesheet enqueued on admin end
* `inc` Contains server side scripts to include
  * `class-admin.php` Admin class Adds a sample tab and a sample field in both the panels Row settings panel and Content block panel
  * `class-public.php` Public class Adds sample styles to Row and Content block utilising sample input fields added by admin class

## Features

* All classes, methods and properties are documented so that you know what you need to be changed.
* All action and filter hooks, admin as well as public, are registered by the main class.
* Separate admin and public classes
* `inc` directory to add more classes or partial templates
* Front end jQuery script enqueued - `front.js`
* Front end stylesheet enqueued - `front.css`
* Admin end jQuery script enqueued - `admin.js`
* Admin end stylesheet enqueued - `admin.css`

## License

The WordPress Plugin Boilerplate is licensed under the GPL v2 or later.

> This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License, version 2, as published by the Free Software Foundation.

> This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

> You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA

## Just these two things to get started quickly

1. Change `my-plugin.php` and `class-my-plugin.php` to something like `your-awesome-addon.php` and `class-your-awesome-addon.php`
2. Do following search and replace through your entire project

Search For | Replace With
-----------|-------------
My_Plugin | My_Awesome_Plugin
My Plugin | My Awesome Plugin
my-plugin | my-awesome-plugin

##Documentation

For pootle page builder developer documentation visit http://pootlepress.com/