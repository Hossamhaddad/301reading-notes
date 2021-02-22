# What Google Learned From Its Quest to Build the Perfect Team
## A worker today might start the morning by collaborating with a team of engineers, then send emails to colleagues marketing a new brand, then jump on a conference call planning an entirely different product line, while also juggling team meetings with accounting and the party-planning committee.
## Teammates should gathered to discuss homework assignments, compare spreadsheets and strategize for exams. 

### Software engineers are encouraged to work together, in part because studies show that groups tend to innovate faster, see mistakes more quickly and find better solutions to problems.


### After looking at over a hundred groups for more than a year, Project Aristotle researchers concluded that understanding and influencing group norms were the keys to improving Google’s teams.

## For Project Aristotle, research on psychological safety pointed to particular norms that are vital to success. There were other behaviors that seemed important as well — like making sure teams had clear goals and creating a culture of dependability

## Best team should : 
1. #### Listen to one another
2. #### show sensitivity to feelings 
3. #### care about other needs

## Project Aristotle is a reminder that when companies try to optimize everything, it’s sometimes easy to forget that success is often built on experiences — like emotional interactions and complicated conversations and discussions

# SuperAgent
## SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js.


# Request basics
## A request can be initiated by invoking the appropriate method on the request object, then calling .then()

# Setting header fields
## Setting header fields is simple, invoke .set() with a field name and value for example :
###  request
 ###  .get('/search')
###   .set('API-Key', 'foobar')
###   .set('Accept', 'application/json')
 ###  .then(callback);


 # GET requests
## The .query() method accepts objects, which when used with the GET method will form a query-string. The following will produce the path /search?query=Manny&range=1..5&order=desc . for example : 
request
  ###  .get('/search')
  ### .query({ query: 'Manny' })
  ###  .query({ range: '1..5' })
  ###  .query({ order: 'desc' })
  ###  .then(res => {
  ###  });

