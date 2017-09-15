# Single PHP Proxy

Single-file web proxy application with full features in PHP.

## Configuration:

Setup a PHP environment and put the SinglePHPProxy.php in the web folder and that's it. (The filename of the SinglePHPProxy.php can be changed as you wish)

## Features:

- Full proxy - Normal resources such as .js, .css and image files are downloaded to the server and the links in the webpage are fixed;

- Hrefs to resources in the same site are fixed; a loop searching function would be executed to ensure that the server could find the resources;

- Hrefs are fixed in webpage to keep new page proxied;

- Automatically clear temp files downloaded by server;

- Cookies supported; cookies are stored on server for permanent use; users can clear the cookies by executing the 'Clear all cookies' function;

- HTTPS supported;

- UTF-8 encoding supported;

## TODO list:

- Supporting POST method;

- Supporting local storage;

- AD blocking function;
