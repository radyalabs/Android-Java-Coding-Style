Android-Java-Coding-Style
==========================

Radya Labs Android Java Coding Style


## Introduction
This document is describe guidelines and recommendations when developing Android application. Our main goal is to define a consistent format and style for every source code produced by all Radya Labs developer.
 
##	Scope
This coding guideline only apply to Android project and Java project in general. 

##	Terminology and Definition
* PascalCase	:	Every first word begin with UpperCase. Ex: TextView
* CamelCase		:	First alhabet using lowercase and every first word begin with uppercase. Ex: myTextView
* AllUpperCase	: 	All alphabet using uppercase. Ex: SEAT_SIZE
* AllLowerCase	: 	All alphabet using lowercase. Ex: com.radya.controller


## Naming Convention

###Overview
* Project File 	: 	PascalCase
* Package		:	AllLowerCase
* ClassFile		:	PascalCase
* Class			:	PascalCase
* Struct		:	PascalCase
* Interface		:	PascalCase
* Enum			:	PascalCase
* Enum Attribute:	AllUpperCase
* Method		:	CamelCase
* Attribute		:	CamelCase
* Constant		:	AllUpperCase
* Static Attribute	:	AllUpperCase
* Parameter		:	camelCase


###General Guide

1.  Always use PascalCase and camelCase for name of entity
3.  Never declare variables using only case letter difference. Give meaningful name
5.  Avoid use numeric suffix in name or identifier
6.  Always use meaningful and specific name
7.  Variables and properties should describe an entity, not type or measurement
8.  Avoid Hungarian Notation!. For example : strName or iCount
9.  Avoid using abbreviation
10. Abbreviation only for common term and widely accepted
11. Never use Java keyword for identifier
12. Avoid use name that will be potentially conflict with Java SDK Class or Android Class
13. Avoid redundant prefix or suffix that does not explain more about an identifier. 

E.g : 

```java
public enum ColorsEnum { }
public class CVehicle { }
public struct RectangleStruct { }
```


14. Avoid use parent class name in a attribute

```java
Customer.name not Customer.customerName
```

15. Try to add "can","is","has" prefix to boolean variable
16. Add "Average,Count,Sum,Min,Max" in a certain variable that reflect aggregation

###Name and Syntax

**Project File**


**package**

Try use AllLowerCase and name that match project title. 

**Class**

Try use PascalCase. Use noun or noun phrase for class. Add suffix or part of parent class for child class

```java
	public class Customer { }
    private struct ApplicationSettings { }
```

**Interface**

Try use PascalCase.

```java
	public interface OnClickListener
    { }
```

**Method**

Try use CamelCase. 

```csharp
	public String getName(){ 
	}
```




