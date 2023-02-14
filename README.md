# **Object-Oriented Programming**
Object-Oriented Programming is a way of approaching, designing and developing software, so that the components of the software and the interactions between them resembles real-life objects and their interactions rather than functions and logic. 

An object can be defined as a data field that has unique attributes and behavior. 

## **Object**
An object is an abstract data type with the addition of polymorphism and inheritance.Rather than structure programs as code and data, an object-oriented system integrates the two using the concept of an "object". An object has state (data) and behavior (code). Objects can correspond to things found in the real world.
### Example 
An online shopping system will have objects such as shopping cart, customer, product. The shopping system will support behaviors such as place order, make payment, and offer discount.

## **Class**
While modeling real-life objects with object oriented programming, we ensure to bundle related information together to clearly separate information of different objects.

Bundling of related properties and actions together is called Encapsulation.

Classes can be used to bundle related properties and actions.

![](https://res.cloudinary.com/due4dmz2b/image/fetch/dpr_auto,w_auto,f_auto,q_auto/https://bss-backend-media-static.s3.ap-south-1.amazonaws.com/prod/media/profile_pic/card-notes-attachment/31ede6f6-e467-4797-80b7-11f46b89fa3a.png)

In Python, a special method __init__ is used to assign values to properties.

```class Mobile:
    def __init__(self, model, camera):
        self.model = model
        self.camera = camera
    def make_call(self, number):
        print("calling..")
```

In the above example, model and camera are the properties and **attributes** are which passed to the __init__ method and make_call is **method**.

## Points to remember
* Everything is an object
* Developer manipulates objects that uses message passing.
* Every object is an instance of a class.
* The class contains the attribute and behavior associated with an object.

## Pillars of OOPs

The major concepts that we have discussed above are known as pillars of OOPs. There are four pillars on which OOP rests.

* Abstraction
* Encapsulation
* Inheritance
* Polymorphism

## **Abstraction**

Abstraction is the process of hiding the internal details of an application from the outer world. Abstraction is used to describe things in simple terms. It’s used to create a boundary between the application and the client programs.

### Abstraction in OOPS

Objects are the building blocks of Object-Oriented Programming. An object contains some properties and methods. We can hide them from the outer world through access modifiers. We can provide access only for required functions and properties to the other programs. This is the general procedure to implement abstraction in OOPS.

### There are two types of abstraction

* Data Abstraction
* Process Abstraction

## **Encapsulation**

Encapsulation is a mechanism that allows us to bind data and functions of a class into an entity. It protects data and functions from outside interference and misuse. Therefore, it also provides security. A class is the best example of encapsulation.

## **Inheritance**

The concept allows us to inherit or acquire the properties of an existing class (parent class) into a newly created class (child class). It is known as inheritance. It provides code reusability.

![](https://static.javatpoint.com/core/images/what-is-object-oriented-programming5.png)

## **Polymorphism**

The word polymorphism is derived from the two words i.e. ploy and morphs. Poly means many and morphs means forms. Polymorphism is one of the core concepts of object-oriented programming (OOP) and describes situations in which something occurs in several different forms. 

In computer science, it describes the concept that you can access objects of different types through the same interface. Each type can provide its own independent implementation of this interface.

To know whether an object is polymorphic, you can perform a simple test. If the object successfully passes multiple is-a or instanceof tests, it’s polymorphic. It allows the developer to create clean, sensible, readable, and resilient code.

![](https://www.phptutorial.net/wp-content/uploads/2021/03/PHP-Polymorphism-Abstract-Class.svg)


## References 
* https://www.javatpoint.com/what-is-object-oriented-programming
* https://www.digitalocean.com/community/tutorials/what-is-abstraction-in-oops