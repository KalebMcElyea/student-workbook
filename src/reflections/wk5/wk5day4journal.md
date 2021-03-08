What is a virtual property?

A virtual property is a additional field for a given model. Virtual properties only exist logically.


When might you use a virtual property?

You would use it when you need to add two different properties. For exmaple in our reading they used the example of Peter Parker using virtual property to combine both the first (Peter) and last (Parker) names.
So in short I'd use the virtual property whenever I need to combine two properties together, like a full name.


How do you search by a virtual properties value?

If you use a get method you would do userSchema.virtual("fullname").get(funcion(){return the this.first " " + this.last;}) within your get method. Then console.log(user.fullname)



