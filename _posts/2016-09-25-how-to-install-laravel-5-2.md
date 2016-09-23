---
layout: post
title: How to install Laravel 5.2
---

**OBS:** This is still working, but i would recommend using v. 5.3 instead

# What are we gonna go through?
* Installation
* Setup (Enc key, db etc)


# Installation

To install Laravel you need to follow the guide in Laravels documentation.
i will try to elaborate the guide a bit with tips and tricks.

First of all you need to install composer, composer is a dependency manager, which you don’t need to learn about now, in shorts it’s a tool you are going to use trough the terminal to install the Laravel installer.
So first install Composer trough this link. So now when you have installed Composer we are ready to install the Laravel Installer. The Laravel installer is just a terminal tool which downloads the laravel application from their git repository. It just makes everything easier.

To install the Laravel installer put the following command in your terminal:
***composer global require “laravel/installer”***

When it is done, cd in to the directory you want to install Laravel(You don’t need MAMP, XAMP etc to use Laravel, so you can put the application anywhere).

And then run this in the terminal laravel new applicationname this will run some stuff, and show you a success message.

Congratulations you have now installed Laravel!
