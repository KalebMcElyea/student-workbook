What are the two common operations that we will set in the handler?

The get operation which gets the operation of the value of the key. And set is performed to a new key to the object.


What do you have to make sure you are doing with every Get to insure the value does not become undefined?

The get operator takes 2 parameters the object itself and the property. So you would use a custom overide called trap. Which is basically sets of "traps" that will go off whenever the property is being accessed. 


What are some of the benefits of the proxy object that we are using in our structure for applications?

I think a benefit is the custom logic that we've been seeing in our application. This way it'll keep us the developer on track to make sure we're implementing what we're suppose to and the person viewing the content see's what was intended. 

https://github.com/KalebMcElyea/latewinter2021-gregslist