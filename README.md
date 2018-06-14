# Lab05 Build A Zoo Introduction
Grouping animals found in a zoo are a way to visually introduce Object Oriented Programming (OOP) principles. This exercise employs the 4 OOP principles which include _Inheritance_, _Encapsulation_, _Abstraction_, and _Polymorphism_.

---
## Explanation of OOP in terms of base and derived classes
_Inheritance_

Inheritance is when a derived class receives qualities from a base class, these qualities get passed down the line.  Every class derived from a Plants class will have qualities like HasSeed or RequiresSun.  Inheritance further down the line will involve some or no change in these qualities like plants will always have a seed, but plants like some household indoor ones don't require sunlight.  This is where the other OOP principles come into play.

_Encapsulation_

Encapsulation involves hiding or protecting information within a class.  This prevents the user of a derived class from manipulating objects.  An example of this would be an Under21 class with a sealed property of bool HasAlcohol.  This prevents the Under21 class from drinking. 

_Abstraction_

Abstraction involves hiding all but the relevant data.  Derived class inherit Abstract qualities, but how they use them is up to interpretation.  An example of this is humans raise their offspring based on 'parenting styles', but 'parenting styles' differ between humans.

_Polymorphism_

Polymorphism also involves inheriting qualities from a base class, but presenting it in a different form.  An example would be a business class that inherits employees.  These employees do the same thing, they work for the business.  However, there are contracted employees and permament employees. 

---
## Concepts Implemented Within Context
_Inheritance_

Animals derived from the **NonLactating** abstract class indicates that they cannot lactate.  They inherit a Diet() and Sound() that will be changed because the animals are different from each other; they require different diets and they make different sounds.

_Encapsulation_

If this zoo diagram was split into Herbivores and Carnivores, a property of DietType can be set to vegetarian and then sealed so that all animals derived from this base class will only eat plants.

_Abstraction_

Animals derived from the **Lactating** abstract class will all inherit an abstract method called **Diet()**, which must be changed for concrete classes derived from **Lactating**.  This is because those derived animals require different diets, e.g Bears are carnivores while dogs are omnivores.

_Polymorphism_

Polymoprphism involves inheritance.  Derived animals inherit qualities from their base class.  

There are some qualities they must change and some qualities they can choose to change:  

An example of polymorphism is shown from the **Falcon** class, derived from **BirdsOfPrey**, derived from **NonLactating** class has to change their Sound().  The other class derived from **NonLactating**, down to the concrete level is **Sharks**, which makes a different sound then a **Falcon**.

---

## Program Specifications
This grouping of zoo animals involve the following with _specific_ examples found in the diagram:

different abstract classes: **Lactating**, **NonLactating**, **Mammal**, **Bird**, **Fish**, **Mammal2Leg**, **Mammal4Leg**, **BirdOfPrey**, **FishWithCartilage**

layers of inheritance example: **Dog** inherits qualities from **Mammal4Leg**, which inherits qualities from **Mammal**, which inherits qualities from **Lactating**

concrete animals: **Bear**, **Bat**, **Dog**, **Cat**, **Falcon**, **Sharks**

2 abstract methods that will also be overridden: **Diet()**, **Sound()**

2 abstract Properties that will also be overriden: **bool Nocturnal**, **bool WarmBlooded**

2 virtual methods: **Appearance()**, **DoesntLaysEggs**

2 virtual properties: **bool fur**, **bool Vertebbrae

---

## Diagram
![Build a Zoo](/zoo.png)
