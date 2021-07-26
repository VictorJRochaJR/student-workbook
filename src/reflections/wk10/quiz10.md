# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Its used to arrange  all the classese and everything else within them

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
a class is a refernce type, while a struct is a value type

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
dynamic class

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
 that the param or the return will be a string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
 changing the methods class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
to allow to add other values or classes to it

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public
private
void
internal

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the things within it

```