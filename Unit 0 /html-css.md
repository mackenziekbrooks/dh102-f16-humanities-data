# HTML + CSS

## How the web works
The internet is magic. Just kidding, it's really not. The internet is made up of computers connected to other computers. Even though you often connect to the internet wirelessly, the internet is still a very physical thing. The information you send and receive travels through wires and fiber-optic cables in the ground and under the ocean. These networked computers talk to each other using protocols. Every computer has an address, known as an IP (Internet Protocol) address, to help direct traffic. 

Another protocol that you use, even if you don't realize it, is the Hypertext Transfer Protocol, or HTTP. Your browser uses HTTP to render websites. When you type in ```http://www.wlu.edu``` your browser sends out a request to the computer that can serve up all the files at that particular address. The "server" returns the files and your browser renders them into a website. At its simplest, a website is just a folder full of text files and images. 

Here are a few videos that might help:
* [What is the Internet? ](https://www.youtube.com/watch?v=Dxcc6ycZ73M)
* [The Internet: Wires, Cables, and Wi-fi](https://www.youtube.com/watch?v=ZhEf7e4kopM)

## HTML
HTML, or Hypertext Markup Language, is one of the basic building blocks of the web. HTML is a set of tags that add structure to documents. 

When you write a document, you rely on style to indicate something about the text. You might put the title in a bigger font or break up paragraphs with tabs or new lines. Markup languages do this by adding tags around the content you wish to set apart. For example: ```<title>The Lord of the Rings</title>``` or ```<p>This is a whole paragraph.</p>``` Your human eyes and brain can infer things based on visual appear that computers need to be told explicitly. That's why we need semantic markup.

You can see the HTML for a basic website at the [W3 Schools HTML tutorial](http://www.w3schools.com/html/). 

In fact, you can see the HTML for any page on the web by right clicking anywhere on the page and selecting "view page source."

HTML documents are just plain text documents. You can write and read HTML in a text editor like Notepad++ or Sublime. The magic happens when you open an HTML document in the browser. 

## Activity 1

* Open your favorite text editor and using the W3 Schools as a guide, write your own HTML document.
* Save the file as ```index.html``` in your Box folder in a separate folder titled: ```activity_2016-09-13```.
*  To view your page in the browswer, open ```index.html``` in your browser, usually with the key commands ```Ctrl + o```
* You should include the basic set of tags: ```<html> <head> <title> <body>```
* Add five additional types of tags to the body of your HTML document, including a table.
* Add an additional HTML page and link the two pages.


## CSS 
Our next building block of the web is CSS, or Cascading Style Sheets. HTML structures your webpage, but you need something else to add the pretty colors and images. 

CSS has a different syntax than HTML. First you identify the HTML tag, then you declare the styles you wish to apply. ```title {color: red;}```

See some basic CSS at the [W3 Schools CSS tutorial](http://www.w3schools.com/css/default.asp). 

The beauty of CSS is that you can keep all your styles in one stylesheet which you link to all your HTML pages. 

## Activity 2

* Create a separate CSS document and save it as ```style.css``` in the same folder you created for Activity 1. 
* Link the ```style.css``` file to your HTML document. Consult the W3 Schools to figure out how to do this.
* Add a background color.
* Change the border on your table. 
* Add style to your links when you hover over them. 

## Activity 3
When you opened your HTML files in your browser, you were viewing your files locally. Only you could see them on your computer. Now it's time to upload them to your domain so other people can view them. 

* In CPanel, open up the File Manager.
* Navigate to the ```public_html``` folder. 
* Create a new folder titled ```activities``` or something similar. 
* Upload all your HTML and CSS files. 
* Navigate to your equivalent of ```www.yourdomain.com/activities```. What do you see?  

