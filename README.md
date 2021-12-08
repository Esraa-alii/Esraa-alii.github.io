# usage of const and &amp; in c++
# const
The const keyword allows you to specify whether or not a variable is modifiable. 

You can use const to prevent modifications to variables and const pointers and const references prevent changing the data pointed to (or referenced).

***1-Constant Variables:***
The primary purpose of constness is to provide documentation and prevent programming mistakes. Const allows you to make it clear to yourself and others that something should not be changed.
![image](https://media.geeksforgeeks.org/wp-content/uploads/Untitled-drawing-30.jpg)

there is 2 ways to declare constant variable :

*data_type const Name = value;*

**or**

*const data_type Name = value;*


***2-Const Pointers:***
when you declare a const reference, you're only making the data referred to const. References, by their very nature, cannot change what they refer to.

there is 3 ways to declare constant pointer :

*const data_type* var_name;*

**or**

*data_type* const var_name;*

**or**

*const data_type* const var_name;*
![image](https://i.stack.imgur.com/Zt0G2.png//user-images.githubusercontent.com/91143454/145293183-ffae4b51-b337-476c-b9a1-248df13fb4c8.png)


 ***3-Const iterators: ***
 C++ requires that const functions return only const pointers and references. Since iterators can also be used to modify the underlying collection, when an STL collection is declared const, then any iterators used over the collection must be const iterators.


***4-Const Functions:***
Like member functions and member function arguments, the objects of a class can also be declared as const. An object declared as const cannot be modified and hence, can invoke only const member functions as these functions ensure not to modify the object.

Syntax:

*const Class_Name Object_name;*

•	When a function is declared as const, it can be called on any type of object, const object as well as non-const objects.

•	Whenever an object is declared as const, it needs to be initialized at the time of declaration. However, the object initialization while declaring is possible only with the help of constructors.

Syntax:

*Const return_type name(){
}*




# &
used in 2 ways :

***1-The logical AND operator (&&): ***
(&&) returns true if both operands are true and returns false otherwise.
![image](https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Logical-AND.png![image](https://user-images.githubusercontent.com/91143454/145296660-16fa475a-561a-4d52-a3ec-3b6050d9dcea.png)


***2-- Address Of operator: ***
a unary operator that returns the address of its opernad
![image](https://s3.studytonight.com/tutorials/uploads/pictures/1613545250-79873.png)








