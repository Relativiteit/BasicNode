# BasicNode
Basic nodejs api no framework 

# Structure 
- server.js setups the server on PORT and has the routes.
- controller/productControllers.js controlls what a route is doing, status, headers, interact with the data 
get data from the model to send back 
- data/product.json basic data source with a few objects 
- utils.js has utitlity functions such as reading in the data or getting the postData. 

## Lessons learned 

- Routing everything by hand and having to make model functions to acess everybit of data is tedius and prone to errors.
- First time using mvc like designpattern for nodejs backend.
- possible to load in data with require eventhough it is not the preffered method such as fs.

## Cons vanillajs
- Annoying to rewrite same lines of code (could have been put into smaller methods but still).
- Expanding routing is tedious. 
# whats next? 
- Build a api with express() and trace back to this repo what is build in.
- Find out what could be a problem in express instead of vanilla js. 




