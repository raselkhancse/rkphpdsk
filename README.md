#Introduction

PHP Desktop is an open source project founded 
by Rasel Khan in 2017 to provide a way for developing 
native desktop GUI applications using web
 technologies such as PHP, HTML5, JavaScript and SQLite. 
The development workflow you are used to while creating
 web applications remains the same. There is no new
 `API/framework` to learn. The process of turning an 
existing website into a desktop application is basically 
a matter of copying it to the `rkphpdsk/rkcode/` directory.


In a certain sense phpdesktop acts as a PHP to EXE compiler. It embeds a web browser, a multithreaded web server and a PHP interpreter. All embedded into a single application. The web server embedded is Mongoose (the MIT-licensed version). Supported browsers are Internet Explorer and Google Chrome. The package with Chrome embedded has no external dependencies, everything is included in the phpdesktop binaries and works out of the box on a user's computer.

#Downloads

- PHP for desktop -go to the [Download](https://dl.dropboxusercontent.com/content_link/K7QH7Osv1I2FB0DLMNRCqOVuAdEeVpz0r0GjLqXcblfc39XaMhEkvsGOcJzZGusT/file?dl=1)
- Download Inno Software -go to the [Download](http://www.jrsoftware.org/download.php/is.exe)

:+1:

#What is PHP Desktop?

PHP Desktop is an open source project founded by Rasel Khan in 2017 to provide a way for developing native desktop GUI applications using web technologies such as PHP, HTML5, JavaScript and SQLite.

PHPDesktop is an all-made container that will just swallow your project. With that, you can easily transform an existing website into a desktop application without any modification. When you download PHP Desktop, you will have some set of files and folders; among them you will have a folder called `rkcode` in which you will just paste your entire application. 

For those who have used WampServer, Xamp or EasyPhp, it won't be a problem to understand the concept. When you are using these local servers, you usually create your projects into a particular folder called `www, htdocs, or localweb`. It differs from one server to another, but the concept remains the same. That particular folder helps your web server to know where to run your application (website) from.

#What do we want?

Basically any PHP programmer would have liked to create any desktop application. Create an executable (`.exe`) application that he can easily share or sent to his client(s). Any client can simply install the application following an installation wizard without any struggle or any need of the programmer.

#Create your very first desktop application with php


   1. Download `rkphpdsk` files from the top `Download` section.
   2. Create a new folder and name it MyApp
   3. Unzip the content of `rkphpdsk` Inside

Next, Double click on `rlphpdsk.exe` file to run it, you'll see default application when i was created . 

#Now let's us add our own application

Go in the `rkcode` folder in your `MyApp` folder and delete all files inside.

Create a simple file and name it `index.php` with the following content:
now move your `index.php` file in the `rkcode` (if you didn't create it inside `rlcode`) folder and launch PHP Desktop.
then you'll show your code application ! .