# Intro
- Our first step is open this <a href="https://trinket.io/library/trinkets/a9c2635601" target="_blank">link</a>
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
  - HTML is for structure / Layout of the page
- CSS stands for cascading style sheets
  - CSS is for the styling of the page.

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
- Remember how we discussed tags in html ```html <p></p> <a></a> <h1></h1>``` etc.
- We can style these in css tab ```html <p>Content</p>``` = ```css p { color:#0fcfcfc; font-size:20px;}``` 
  - An unset css p Tag would be ```css p {}``` 
- Lets look at the code in the css Tag
  - font-size:20px; this sets the font size to 20px
  - CSS attributes are "name:setting;"
  - @Gaz why so many different ways of exrpessing color:
    - #0fcfcfc is hex
    - rgba(233,122,133,0.9) is rgba means (red,green,blue and alpha) alpha means transparency.
    - red is an expression of red,
    - Why not just use red, limited color combinations, why not just use hex then because hex does not support transparency.
    - @Gaz: Why is this so confusing, well once a man called Tim Berners Lee and a computer had an wonderful little baby, then humanity got hold of it
- Lets increase the font size of the H1 tag
```css 
h1 { color:red; font-size:62px;}
``` 
- Lets change the color of the p tag
```css 
p { color:#141414; font-size:20px;}
```       
- Have a look at a <a href="https://www.w3schools.com/colors/colors_picker.asp">color wheel</a> to replace more colors.
- Look at the image tag <img , see the src="" attribute replace like follows src="https://upload.wikimedia.org/wikipedia/commons/4/41/Rick_Astley_Dallas.jpg"
- Lets embed a youtube video.
  - Copy and paste this code unto one of the divs like this index.html tab
```html 
        <div class="col-xs-4">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
        </div>
``` 
- Have a play with what you have learn't more coming next week.

# Refferences
- <a href="https://www.w3schools.com/tags/default.asp" target="_blank">HTML Tags</a>
- <a href="https://www.w3schools.com/cssref/default.asp" target="_blank">CSS attributes</a>

# Next week
- css classes id
- imgs
- structure
- more bad jokes and grammer











