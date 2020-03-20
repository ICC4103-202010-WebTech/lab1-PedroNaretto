Lab 1 - Pedro Naretto

1.-How is the list of news articles structured with HTML?

The list of articles are structured as a tree structure. This meens that the page start with one object and thiis object has many others objects in it, and this others objects have others objects. Every article in the list its a diferent object from the others, having his own class, id and others characteristics.

 2.-Briefly describe what you see in files with names starting with hn.js and news.css. How are these files different? What is their purpose?

In this two files you can see code to see how the web page is gonna behave. The files hn.js it is full of functions that are gonna tell de web page how it has to react to the interaction. the other file, news.css, it tells us how the web page is gonna be seeing. As an example, in the file hn.js the function $(id) returns us the asked document by using its id. On the other side, the file news.css tell us what type of letter is gonna be used, where its gonna be putted, the size, etc.

3.-How many requests has it taken for the browser to download the Hacker News main page? What are the HTTP request methods in each case? Check out the HTTP response headers and find out what kind of web server is used for this website.

For the browser, it has taken 7 requests to download the Hacker News main page, and all the requests methods where Get. The kind of server of web server is nginx.