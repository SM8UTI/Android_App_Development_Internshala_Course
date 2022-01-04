## Day-4

> Date : 04/01/22

#### Module : ( World of Kotlin ) 
![error](https://cdn57.androidauthority.net/wp-content/uploads/2017/11/kotlin-and-android-840x472.jpg.webp)

## Classes of Kotlin ( `Constructors and Real Life Applications`)

#### Constructors : 
* A `constructor` is a special kind of member function that is used to initialise the state or properties of the newly created objects of a class.
* `Constructors` is written inside the class.
* ** Constructors ** are required to create objects of a class. Every class must always have a ** Constructors ** .

Types of Constructors : 
  1. `Primary Constructors`
  2. `Secondary Constructors`

|Primary Constructors|Secondary Constructors|
|--------------------|----------------------|
|A class have only one Primary Constructor|A class can have multiple Secondary Constructor|

#### Primary Constructor : 
* Example : 
```kotlin
class Dog(breed:String,age:Int){
  var breed:String
  var age:Int

  init{
    this.breed = breed
    this.age = age
  }
}
```
Dog(`breed:String,age:Int`)  : Constructor Variable

{
  `var breed:String, 
   var age:Int1`
}  : Member or Local Variable 


#### Problem : 

|Question Number|Question Name|Ans|
|---------------|-------------|---|
|01|Create class 'Clothes' with ‘material’, ‘colour’, and ‘price’ as properties in primary constructor and create its objects in the main function.|[q1.kt](https://github.com/SM8UTI/Android_App_Development_Internshala_Course/blob/main/Day-4/q1.kt)|
|02|Create a class named ‘Book’ with properties as ‘book name’, ‘genre’ and ‘publisher’ in the primary constructor and create its objects in the main function.|[q2.kt](https://github.com/SM8UTI/Android_App_Development_Internshala_Course/blob/main/Day-4/q2.kt)|
