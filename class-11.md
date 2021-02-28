# Working with volumes
## You can perform a volumes search by sending an HTTP GET request to the following URI:
### https://www.googleapis.com/books/v1/volumes?q=search+terms

## This request has a single required parameter:

## q - Search for volumes that contain this text string. 
## There are special keywords you can specify in the search terms to search in particular fields, such as:
## intitle: Returns results where the text following this keyword is found in the title.
## inauthor: Returns results where the text following this keyword is found in the author.
## inpublisher: Returns results where the text following this keyword is found in the publisher.
## subject: Returns results where the text following this keyword is listed in the category list of the volume.
## isbn: Returns results where the text following this keyword is the ISBN number.
## lccn: Returns results where the text following this keyword is the Library of Congress Control Number.
## oclc: Returns results where the text following this keyword is the Online Computer Library Center number.

## If the request succeeds, the server responds with a 200 OK HTTP status code and the volume results:

### 200 OK

### {
### "kind": "books#volumes",
### "items": [
###  {
 ###  "kind": "books#volume",
 ###  "id": "_ojXNuzgHRcC",
 ###  "etag": "OTD2tB19qn4",
 ###  "selfLink": "https://www.googleapis.com/books/v1/volumes/_ojXNuzgHRcC",
 ###  "volumeInfo": {
 ###   "title": "Flowers",
 ###   "authors": [
  ###   "Vijaya Khisty Bodach"
 ###   ],
###   ...
###  },
###  {
###   "kind": "books#volume",
 ###  "id": "RJxWIQOvoZUC",
 ###  "etag": "NsxMT6kCCVs",
 ###  "selfLink": "https://www.googleapis.com/books/v1/volumes/RJxWIQOvoZUC",
 ###  "volumeInfo": {
 ###   "title": "Flowers",
 ###   "authors": [
  ###   "Gail Saunders-Smith"
 ###   ],
  ###  ...
  ###},
 ### {
 ###  "kind": "books#volume",
 ###  "id": "zaRoX10_UsMC",
###   "etag": "pm1sLMgKfMA",
 ###  "selfLink": "https://www.googleapis.com/books/v1/volumes/zaRoX10_UsMC",
 ###  "volumeInfo": {
 ###   "title": "Flowers",
  ###  "authors": [
 ###    "Paul McEvoy"
###    ],
 ### },
 ### "totalItems": 3
### }


## You can use the filter parameter to restrict the returned results further by setting it the to one of the following values:

### partial - Returns results where at least parts of the text are previewable.
### full - Only returns results where all of the text is viewable.
### free-ebooks - Only returns results that are free Google eBooks.
### paid-ebooks - Only returns results that are Google eBooks with a price.
### ebooks - Only returns results that are Google eBooks, paid or free. Examples of non-eBooks would be publisher content that is available in limited preview and not for sale, or magazines.

# EJS
## EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.

## EJS benefits :
1. ### Use plain JavaScript
2. ### Simple syntax
3. ### Active development
4. ### Easy debugging
5. ### Speedy execution

## TO install EJS ($ npm install ejs)
