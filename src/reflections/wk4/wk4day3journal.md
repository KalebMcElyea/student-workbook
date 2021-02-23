What are the three states of a Promise?

1. Pending: The starting state before the promise succeeds or fails. 
2. Resolved: A completed promise
3. Rejected: A failed promise



How do promises seek to resolve the issues of "callback hell"?

It seeks to resolve the issues by chaining callbacks with another callback. Hence when chaining callbacks with promise it makes the code clean easier to read.


What is the difference between .then() and .catch()?

.then(): This method is called after the promise is resolved. Then we can decide what to do with the resolved promise. 
.catch(): This method is called after the promise has failed. If the promise fails then it will go to the catch method and rely a different message on our console log. 





https://github.com/KalebMcElyea/latewinter2021-gregslist