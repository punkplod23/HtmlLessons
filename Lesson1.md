# Intro
- Our first step is open this <a href="https://trinket.io/library/trinkets/a9c2635601">link</a>
- We are now presented with the below html code, it may look daunting though its just simple HTML
- We call HTML/ CSS Pseudocode, because they can create complex things though are rather simple. 
```html
<html>
  <head>
      <title>My first Web page</title>
    	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css" type="text/css" media="screen">
      <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div class="col-xs-4">
          <h1>Col 1 Title</h1>
          <p>Style this</p>
        </div>
        <div class="col-xs-4">
          <h1>Col 1 Title</h1>
          <p>Style this</p>
        </div>
        <div class="col-xs-4">
          <h1>Col 1 Title</h1>
          <p>Style this</p>
        </div>
      </div>
    </div>
  </body>
</html>
```
- If you click the tab marked style.css you will see this
```css
.container {padding:20px 10px 20px 10px;}
h1 {}
p {}
```

# Break it down
<img src="http://78.media.tumblr.com/9bbfd5ea7b2acf5cb70c6776f844c654/tumblr_mi2utg3sgw1s559c9o1_500.gif" width="300" height="100" alt="funny" />

- HTML stands for hypertext markup language
- CSS stands for cascading style sheets

# Mark Up HTML
- Lets look at the HTML Code
```html
          <p>Style this</p>
   
```
- This is a p tag, tags are represented in <> to open and </> to close example the p above the content that is displayed is "Style this".
- Change the content of the p and the h1 in each div tag to something else, remember how we discussed tags above.
```html
   <div class="col-xs-4">
          <h1>Hammer Time</h1>
          <p>Du,du,du,dud dud du</p>
          <p>Can't Touch this</p>
        </div>
```
- Can you see the pattern with the tags can you see the class="col-xs-4" we will discuss this more in our next lesson.
- Lets add something new into each of the three divs lets add an a tag with an attribute href
```html
   <div class="col-xs-4">
          <h1>Col 1 Title</h1>
          <p>Style this</p>
          <a href="#nogo">Link 1</a>
        </div>
```
- Attributes in html are our best freind wait for the next lesson when we go into more details into this.
- Lets add an image copy this below into one of the divs
```html
<img src="http://78.media.tumblr.com/9bbfd5ea7b2acf5cb70c6776f844c654/tumblr_mi2utg3sgw1s559c9o1_500.gif" width="300" height="100" alt="funny" />
```
- Like this
```html
   <div class="col-xs-4">
          <h1>Hammer Time</h1>
          <p>Du,du,du,dud dud du</p>
          <p>Can't Touch this</p>
  
<img src="http://78.media.tumblr.com/9bbfd5ea7b2acf5cb70c6776f844c654/tumblr_mi2utg3sgw1s559c9o1_500.gif" width="300" height="100" alt="funny" />
        </div>
```

# CSS
- There are numerous ways to explain css lets aim for the simplist today alter this in you're style.css click the tab copy and paste below.
```css
.container {padding:20px 10px 20px 10px;}
h1 { color:red; font-size:34px;}
p { color:#0fcfcfc; font-size:20px;}
a {color:rgba(233,122,133,0.9); font-size:22px; }
```
- Remember how we discussed tags in html <p></p> <a></a> <h1></h1> etc.
- We can style these in css







