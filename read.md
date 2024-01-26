### URL SHORTNER:-
# Description:- 
design a URL shortener service that takes in a valid URL and
return a shortened URL and redirecting the user to the previously provided URL

Also keep track of total visits/clicks on the URL 

# ROUTES:-
POST/URL - generate a new short URL and returns the shortened URL in the format example.com/random-id

GET/:id -redirects the user to the original URL

GET/URL/analytics/:id -return the click for the provided short id


## MONGODB MODEL:-
Mongoose model provides an interface for the database to create, query, update, delete records
->syntax  {modelname = mongoose.model('collection name', 'schemaname');}

## in $push why we used $ :-
In MongoDB update operations, the dollar sign ($) is used as an update operator.
$push: The update operator that specifies the type of update you want to perform.
 

### app.set("view engine", "ejs"); :
this is use to specify the view engine as ejs
