# EJS Partials
## Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

## for examples : 
### <!-- views/partials/navbar.ejs -->
 ###   <div class="header clearfix">
###    <nav>
###            <ul class="nav nav-pills pull-right">
###                <li role="presentation"><a href="/">Home</a></li>
###            </ul>
 ###           <h3 class="text-muted">Node.js Blog</h3>
 ###       </nav>
 ###   </div>


 ## for example : 
 ## footer.ejs :
### <!-- views/partials/footer.ejs -->
 ###   <footer class="footer">
 ###       <p>© 90210 Lawyer Stuff.</p>
###    </footer>


## Now that we have our partials defined, we can use them in our home.ejs and post.ejs templates! In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters.


## to include partial file : 
### Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.

## example on includes partial files  : 
### <!-- views/post.ejs -->
 ###   <!DOCTYPE html>
###    <html>
 ###   <head>
 ###       <meta charset="utf-8">
  ###      <title>POST_TITLE | Node.js Blog</title>
 ###       <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
  ###      <style>
  ###          body {
  ###              padding-top: 20px;
   ###             padding-bottom: 20px;
   ###         }
   ###     </style>
 ###   </head>
 ###   <body>
  ###      <div class="container">
  ###          <%- include('partials/navbar') %>
  ###          <div>
 ###               <h2>POST_TITLE</h2>
  ###              <p>by <a href="#">POST_AUTHOR</a></p>
  ###              <p>POST_CONTENT</p>
  ###              <hr>
  ###          </div>
  ###          <%- include('partials/footer') %>
  ###      </div>
  ###  </body>
  ###  </html>





## As you can see creating and including partials is very straightforward with EJS. I’ve intentionally left in some placeholders such as LIST_OF_POSTS, POST_TITLE, POST_AUTHOR, and POST_CONTENT