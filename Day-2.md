# Day 2 - Structure and Style
Today we are going to:
 - Learn about web browsers
 - Learn some more basic HTML
 - Learn basic css
 - Learn how to link files
 
## Terms for today
 - __Web Browser__ or __Browser__: Computer application used to view websites on the internet
 - __Website Server__ or __Server__ : A computer that is always on, waiting for web browsers to ask it for it's website.
 - __render__: The process of turning an HTML file into a website.
 - CSS: __C__ascading __S__tyle __S__heets or Styles are documents that tell a web browser what a website should look like.
 
## Part 1 - The web browser
__Firefox__, __Chrome__, __Safari__, __Internet Explorer__ and others are all computer applications that billions of people around the world use to browse the internet. The main job of a web browser is very simple; ask a website server for a website, and then display that website on your computer. Underneath all websites are 3 main technologies; HTML, CSS, and Javascript. When a web browser asks a website server for a website, the server sends back just a single HTML document. This single HTML document contains __references__ to all the other information that the web browser needs to properly display the website. These references are to things like __CSS__ files, __Javascript__ files, __images__, __MP3s__, __videos__ and a few other things. The web browser then retrieves these references by asking a server for these additional files and uses them to properly __render__ the webpage.

As an example, say we want to go to google.com. After we type in google.com and hit enter:
 - Our browser asks the server at google.com for it's website.
 - The server at google.com sends our browser a single html document.
 - Our browser checks this document looking for references to other files like CSS and Javascript.
 - The server sends our browser these additional files.
 - Our browser renders all the files into a website for us to use.
 
## Part 2 - Linking Files
Go to your neocities.com dashboard and edit your index.html file. Here is a convenient link:<br>
https://neocities.org/site_files/text_editor/index.html

You should see the HTML that we put there in Day 1. On the 3rd line of code we can see the opening tag for the __head__ element. The __head__ element is a special kind of element in HTML that doesn't get directly displayed on screen, but instead it contains information about our website and links to other files that our web browser needs to properly display our website. We are going to add a reference to a CSS file so that our web browser knows what our website should look like.

 - Put your cursor __inside__ the __head__ element, right below the __title__ element.
Like this:
~~~
<head>
  <title>My Website!</title>
  | <-- Your cursor goes here!
</head>
~~~

 - Now we are going to add a __link__ element that tells the web browser about a file it needs to display our website.
 - Type the following __link__ element where your cursor is:
~~~
<link rel="stylesheet" type="text/css" href="style.css">
~~~
This link element is interesting for a few reasons. __1st:__ it doesn't have a __closing tag__. There is no `</link>` tag anywhere. __2nd:__ it doesn't have any __content__ but it has __attributes__. In HTML, an __attribute__ is a piece of information __about__ an element. Just like the __head__ is a special section __about__ the website, the __attributes__ are information about individual __elements__. In this case, we are telling the web browser that this element is a __stylesheet__ (`rel="stylesheet"`), and it is specifically __CSS__ (`type="text/css"`) and then we specify the location of this file (`href="style.css"`).

 - Save your index.html file. ( control + s )
 
## Part 3 - Cascading Style Sheets
CSS files, or __C__ascading __S__tyle __S__heets or simply Styles, tell a web browser what a website should look like. They give websites their "look and feel". Let's check it out!

 - Go back to your dashboard and edit style.css -> https://neocities.org/site_files/text_editor/style.css
 - Select everything ( control + a )
 - And delete it ( backspace or delete )
