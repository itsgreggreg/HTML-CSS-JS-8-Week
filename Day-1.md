# Day 1 - Setup
Today we are going to:
 - Setup an E-mail address
 - Setup a neocities account
 - Learn common shortcuts
 - Learn basic HTML
 - Create a set of usefull links on our website.

## Step 1 - Email
__Already have an email address? Skip this step.__<br>

 - Go to https://gmail.com
 - Click __[ Create an account ]__
 - Fill in all the details
   - Make your user name your name with this format `firstinitial.lastname`.
   - If that is already taken, try a different combination like `firstname.lastname` or `lastname.firstinitial`
   - You don't have to give a phone number or previous email if you don't want. But providing a phone number will help with password recovery.
 - Click __[ Next step ]__
 - Click __[ No thanks ]__
 - Done
 
## Step 2 - Neocities
__Already have a neocities account? Skip this step.__

 - Go to https://neocities.org
 - Fill in the __Sign up for free__ form
   - Make your username the same as your email address username
   - If that is allready taken try different combinations as suggested in the (Email)[#step-1---email] step
   - In the __tags__ section put __OperationSpark__
   - Make the __Password__ the same as your email address password
   - For __Email__ use the gmail address you just set up
 - Click __[ Create my account ]__
 - Click __[ Continue ]__ in the __Free Plan__ section
 - Click __[ Edit Site ]__
 - Done

## Step 3 - Common Keyboard Shortcuts
Keyboard Shortcuts generally involve holding one key down and tapping another key. Web developers use them all the time for convenience and to save time.

 - Go to your neocities dashboard: https://neocities.org/dashboard
   - You should already be there from the end of __Step 2__
- Open your website in a new tab
  - Near the top of the page is a red link to your website, it looks like __yoursite.neocities.org__
    - Click it
- Go back to your dashboard
- Hover your mouse over __index.html__ and click the __Edit__ button that appears.

### control + a = Select all
In side your index.html file is the standard place-holder html that neocities gives you so you can see how neocities works. We don't want it 'cos we're gonna do better! Here's how you get rid of it.

 - Click anywhere inside the editor.
 - Hold __control__ and tap a
 - Now all the text in the code editor should be highlighted.
 - Press the __delete__ or __backspace__ key on your keyboard to get rid of all of it.
 - Click __[ Save ]__ in the upper right corner.

### control + r = Refresh
 - Go to your webpage tab
 - Hold __control__ and tap __r__ on your keyboard
 - Your webpage should now be blank. Awesome!

### control + c = Copy
 - Open this lesson file in a new tab
 - Highligh the following HTML with your mouse
~~~
<!DOCTYPE html>
<html>
 <head>
   <title>My Website!</title>
 </head>
 <body>
    Hello!
 </body>
</html>
~~~
 - Hold __control__ and tap __c__
 - Now the HTML is in your computer's clipboard
   - The clipboard is just a way to store 1 piece of information at a time so that you can transfer it somewhere else quickly and easily.

### control + v = Paste
 - Go back to your neocities editor for the index.html file
 - Click anywhere in the editor
 - Hold __control__ and tap __v__

### control + s = Save
- Hold __control__ and tap __s__
- You should see a notice that __Your site has been saved__
- Go to your website tab and refresh!
  - It should now just say `Hello!`
- This is a very common combination of actions for a web programmer. Copy, Paste, Save, Refresh - We are going to be doing it all the time!
  
## Step 3 - Basic HTML
 - Go to your neocities editor for your index.html file. And take a look at what we have in there.
 
This is the minimum boilerplate that every HTML page needs. At the very top we see `<!DOCTYPE html>`. This is a very special piece of text and every html page must start with it. There are many versions of HTML and this piece of text tells the web browser what kind of html we want to use. Lucky for us, to use the most modern HTML version this is all we have to write.

Just below that we see the start of our actual __HTML__. HTML is made up of __elements__. Elements are made up of __tags__ and sometimes __content__ and other elements. Elements contain things, and tags define elements. The first tag we see is `<html>` and as you can guess, this tag starts the html element that contains all the rest of our html. The next tag we see is `<head>`. The head element contains all of our website's metadata. Metadata is information __about__ our website such as relavant keywords, the site's title, what our site should look like, and other things. Next we see the `<title>` element that sets our website's title. Just below that we see the head's __closing tag__ `</head>`. Most tags in html need to be closed like this. This is so the browser knows where that tag ends. Next we see the `<body>` tag. The body tag is where all the __content__ for our website goes. Text and images and structure go here.

### Let's write some html

When we say "go inside an element", what we mean is to place your cursor inbetween the opening and closing tags. Usually these tags are on seperate lines like the body element. So to go _inside_ the body element we want to place our cursor on a line between its opening ang closing tags like so:
~~~
<body>
  | <- your cursor here is inside the body element
</body>
~~~

We are going to create a list of useful links for ourselves so we don't forget them. Make sure your cursor is inside the body element like above and type out the following:

~~~~
<ul>
  <li><a href="https://github.com/itsgreggreg/stuff/">Class</a></li>
</ul>
~~~~

After you have that typed out save your file using the shortcut we learned before (control + s) and then go to your website page and refresh using the shortcut we learned above: (control + r).

__YEAH! DONE!__
