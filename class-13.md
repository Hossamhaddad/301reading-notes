# Client/server architecture
##  the web uses a client/server architecture that can be summarized as follows. a client sends a request to a server, using the HTTP protocol. The server answers the request using the same protocol.


# FORM
## An HTML Form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.

# Form action attribute
## The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form.

# FORM method attribute
## We Have to types of methods : 
1. ### get
2. ### post

# The GET method
## The GET method is the method used by the browser to ask the server to send back a given resource ,
## Since the GET method has been used, you'll see the URL www.foo.com/?say=Hi&to=Mom appear in the browser address bar when you submit the form.


# The POST method
## The POST method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.


## Viewing HTTP requests:
1. ### Open the developer tools.
2. ### Select "Network"
3. ### Select "All"
4. ### Select "Headers"




