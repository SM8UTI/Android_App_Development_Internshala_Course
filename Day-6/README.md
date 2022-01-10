## Day-5

> Date : 05/01/22

#### Module : ( World of Kotlin ) 
![error](https://cdn57.androidauthority.net/wp-content/uploads/2017/11/kotlin-and-android-840x472.jpg.webp)

## Inheritance and Interfaces

#### Visiblity Modifiers :  
* Accessibility of Variables , functions , classes , objects ,Constructor , Properties etc.

##### Types of  Visiblity Modifiers in Kotlin :
1. Public 
2. Private 
3. Protected
4. Internal


#### Public : 
* Anything that is declared public is accessiable everywhere in the project.

#### Private : 
* A top-level function or class that is declared private can be accessed only with in the file where it is declared.

* Any member function , Constructor or Property that is declared private is Visible only within the class where it is declared.

#### Protected : 
* Any Property or member function declared Protected is Visible or accessiable only with in the class and its subclasses where it has been declared .
* A function is not declared a Protected.

* Internal : 
*Anything declared Internal is accessiable only within the same module is a set of files compiled together.

* Maximum Visiblity Modifiers is  ` public -> Internal -> Protected -> Private  `

** * 

#### Interfaces : 
* Interfaces are similar to class but they don't have a state.so they don't have Constructors as well.
* Use `Interfaces` Keywoard 

`Note : function body is called deafult  implementation`

Syntax : 
```kotlin
interface InterfaceName{
  //Block Of Codes
}
```

```kotlin
class ClassName:InterfaceName{
  //Block Of Codes
}
```

** * 

###  Questions or Quiz :
1. Which of the following Properties of a programmiing language enebles reusabiiity ?
 ( a. Data Class b. objects c. Interfaces d. Inheritance ) 
`Ans : Inheritance `
2. Which Keywoard is used to allow reusabiiity of a class ? 
`Ans : Open `
3. Inheriting is to base classes what ________to Interfaces.
`Ans  :implementation`


`Note : A function which is only declared inside an interface i.e, it Doesn't have any deafult implementation needs to be overridden inside th class implementation that interface.`

** * 
Problems : 

|Problems Numbers | Problems Statement|Answer|
|-----------------|-------------------|------|
|01|Create a parent class Car and functions speedUp() and applyBrake(). Now create two different child classes inheriting class Car. Also, create objects for both of the child classes and use the functions that were created inside the parent class.|[q1.kt](https://github.com/SM8UTI/Android_App_Development_Internshala_Course/blob/main/Day-6/q1.kt)|
