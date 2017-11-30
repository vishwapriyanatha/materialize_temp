# materialize_temp

## NPM install

install npm materialize to your project folder
* `npm install materialize-css`

## Bower install

install Bower materialize to your project folder
* `bower install materialize`

  MyWebsite/<br />
  |--css/<br />
  |  |--materialize.css<br />
  |<br />
  |--fonts/<br />
  |  |--roboto/<br />
  |<br />
  |--js/<br />
  |  |--materialize.js<br />
  |<br />
  |--index.html<br />

  Compiled and minified CSS
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.100.2/css/materialize.min.css">

  Compiled and minified JavaScript
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.100.2/js/materialize.min.js"></script>

  Next you just have to make sure you link the files properly in your webpage. Generally it is wise to import javascript files at the end of the body to reduce page load time. Follow the example below on how to import Materialize into your webpage.

  One last thing to note is that you have to import jQuery before importing materialize.js!

    &lt;!DOCTYPE html&gt; <br />
  &lt;html&gt;<br />
    &lt;head&gt;<br />
      Import Google Icon Font<br />
      &lt;link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet"&gt;<br />
      Import materialize.css<br />
      &lt;link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/&gt;<br />

     Let browser know website is optimized for mobile<br />
      &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"/&gt;<br />
    &lt;/head&gt;<br />

    &lt;body&gt;<br />
      Import jQuery before materialize.js<br />
      &lt;script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"&gt;&lt;/script&gt;<br />
      &lt;script type="text/javascript" src="js/materialize.min.js"&gt;&lt;/script&gt;<br />
    &lt;/body&gt;<br />
  &lt;/html&gt;