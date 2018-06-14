# Lab06 Interfaces
This exercise implements the concepts of Interfaces using a zoo as the running theme.

---
## Concepts Implemented
Interfaces are like abstract classes in that they have behaviours that classes can implement.  
They allow classes to behave a certain way instead of having a class inherit these behaviours 
based on a hierarchical class inheritance.

---

## Interfaces Used
The interfaces used in this exercise is ISwim and IFly.
ISwim is applied to the abstract Fish class while
IFry is applied to the abstract Bird class.

---

## Dependencies
This exercise runs on .NET Core 2.1, which can be downloaded [here](https://www.microsoft.com/net/download/macos).

---
## Build
After installing the [.NET Core 2.1 SDK](https://www.microsoft.com/net/download/macos), clone this repo onto your machine. From a terminal interface, go to where this was cloned and type the following commands:

```
cd Lab05_Build_A_Zoo_
dotnet restore
dotnet run
```

---
## How to Use the Program
The console will log messages that will demonstrate that concrete classes have inherited from their base classes.

---

## Screenshots
Diagram of zoo hierarchy

![Hierarchy Diagram](/zoo.png)

Console Output:

![Console Output]()