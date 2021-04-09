# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is designed for keeping one set of names separate from another.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A structure type is a value type and a class is a reference type. 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public 
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
It's declaring it's variable as a string. 
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It's preventing it from creatin another object. 
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It allows the method to be modified to return "Vrooooom"
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Internal, Protected.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed within the same class. 
```