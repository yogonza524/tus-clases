# Encapsulation
It describes the idea of bundling data and methods that work on that data within one unit, e.g., a class in Java.

This concept is also often used to hide the internal representation, or state, of an object from the outside. This is called information hiding. The general idea of this mechanism is simple. If you have an attribute that is not visible from the outside of an object, and bundle it with methods that provide read or write access to it, then you can hide specific information and control access to the internal state of the object.

## Access Modifiers
Java supports four access modifiers that you can use to define the visibility of classes, methods, and attributes. Each of them specifies a different level of accessibility, and you can only use one modifier per class, method or attribute. As a rule of thumb, you should always use the most restrictive modifier that still allows you to implement your business logic.

These modifiers are, starting from the most to the least restrictive one:

- private
- protected
- public
- no modifier

![](https://stackify.com/wp-content/uploads/2017/11/word-image-20.png)