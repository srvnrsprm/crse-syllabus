
# Table of Contents

1.  [Introduction to JavaScript](#org47a492a)
    1.  [Why Java? Why Script?](#org98f8a71)
    2.  [Important features of JavaScript](#org6d3b980)
2.  [Basic Language Constructs](#org6b68960)
    1.  [Values](#org97e9f37)
    2.  [Numbers](#org6a27da0)
    3.  [Strings](#org479a10d)
    4.  [Booleans](#org10a1d85)
    5.  [Objects](#org271d138)
    6.  [null](#orgc6829e7)
    7.  [undefined](#orgcba1beb)
    8.  [Typing](#org762cf24)
    9.  [Reserved Words](#org2ceb504)
    10. [Comments](#orgd36d4b7)
    11. [Operators](#org82a9111)
    12. [Statements](#orga66e8eb)
    13. [Expressions](#org49b2cc7)
    14. [Conditionals](#orgce1d55a)
    15. [Looping](#org583e9cf)
3.  [Objects](#org9f96540)
    1.  [Understanding Primitive Types](#org4b3f968)
    2.  [Composite Types](#org44418af)
    3.  [Object Internals ‐ Use of Hashtables](#orgc0fe678)
    4.  [Predefined objects](#org2d08b7d)
    5.  [Ways to create Objects](#orgb1a18d2)
    6.  [Ways to iterate Objects](#org36fd148)
    7.  [Pass by reference](#org72a600b)
4.  [Functions and Functional Programming](#org42e1787)
    1.  [Function syntax](#orgb5f87b4)
    2.  [Return values of functions](#orgb42f781)
    3.  [Anonymous Functions](#org7ce19fc)
    4.  [Inner Functions](#org3cdac58)
    5.  [Function Scope](#orgcf340e4)
    6.  [Globals and how to avoid them](#orgfeac6a6)
    7.  [Functions as Objects](#orge67cf36)
    8.  [call and apply](#org172214c)
5.  [Arrays](#orge3d083f)
    1.  [How JavaScript arrays are different](#orgd799e59)
    2.  [Multidimensional arrays](#org9545c09)
6.  [Prototypes and Prototypal Inheritance](#org4055ee1)
    1.  [Inheritance in JavaScript](#org410a413)
    2.  [Constructor functions](#org94e750f)
    3.  [The prototype link](#org0c56a78)
    4.  [The object Function](#org7e6710b)
    5.  [Difference from classical inheritance](#org315816e)
    6.  [The this keyword](#orgfce3e2e)
7.  [JavaScript Programming Paradigms](#org37a886e)
    1.  [Object oriented programming in JavaScript](#orgb5a945d)
    2.  [Functional programming in JavaScript](#org74e0bc8)
    3.  [Aspect oriented programming in JavaScript](#org1ed6cb4)
8.  [Document Object Model](#org26b7fe5)
    1.  [Introduction to DOM](#orgb9d740e)
    2.  [A little history of the web](#orgd54a2d8)
    3.  [Levels (or types) of DOM](#orgf2bcdd8)
    4.  [Nodes](#orgc74ff31)
    5.  [Elements](#orga5a630d)
    6.  [Attributes](#orga398d0f)
    7.  [Text](#org533271c)
    8.  [Comment](#orgfbae659)
9.  [JavaScript and DOM](#org61a1f3e)
    1.  [Parsing XML in JavaScript](#org283d2f2)
    2.  [Create elements](#orgdc49d31)
    3.  [Retrieve elements](#org7040d9f)
    4.  [Delete elements](#org232cfb8)
    5.  [Work with attributes](#orgad1a894)
    6.  [A few examples](#org7a24154)
10. [Event Handling in JavaScript](#org68cfb65)
    1.  [Adding event handlers](#org8ffd4c3)
    2.  [Asynchronous handling of events with callbacks](#org293a11a)
    3.  [Event bubbling](#org35984bd)
    4.  [Event capturing](#org95ac42a)
11. [JavaScript Libraries](#org8ebadcb)
    1.  [The need for libraries](#orgc0cd4c8)
    2.  [Handling cross-browser issues with JS libraries](#org5c40c2f)
    3.  [jQuery](#org58c303f)
    4.  [Node.js](#org071b74d)
12. [AJAX and XMLHttpRequest](#org148865b)
    1.  [The components - XMLHttp, JavaScript, XML (or JSON) and DOM](#org59dab99)
    2.  [Intelligent clients with AJAX](#orgca5e788)
    3.  [Examples of AJAX usage](#orgba2e594)
13. [Data Formats](#org3d50777)
    1.  [What are data formats?](#org073f439)
    2.  [Difference from data structures](#orgf4a90f6)
    3.  [Serialization and deserialization](#org0684ac9)
    4.  [Maps as generic data containers](#orgc5fc12b)


<a id="org47a492a"></a>

# Introduction to JavaScript


<a id="org98f8a71"></a>

## Why Java? Why Script?


<a id="org6d3b980"></a>

## Important features of JavaScript


<a id="org6b68960"></a>

# Basic Language Constructs


<a id="org97e9f37"></a>

## Values


<a id="org6a27da0"></a>

## Numbers


<a id="org479a10d"></a>

## Strings


<a id="org10a1d85"></a>

## Booleans


<a id="org271d138"></a>

## Objects


<a id="orgc6829e7"></a>

## null


<a id="orgcba1beb"></a>

## undefined


<a id="org762cf24"></a>

## Typing


<a id="org2ceb504"></a>

## Reserved Words


<a id="orgd36d4b7"></a>

## Comments


<a id="org82a9111"></a>

## Operators


<a id="orga66e8eb"></a>

## Statements


<a id="org49b2cc7"></a>

## Expressions


<a id="orgce1d55a"></a>

## Conditionals


<a id="org583e9cf"></a>

## Looping


<a id="org9f96540"></a>

# Objects


<a id="org4b3f968"></a>

## Understanding Primitive Types


<a id="org44418af"></a>

## Composite Types


<a id="orgc0fe678"></a>

## Object Internals ‐ Use of Hashtables


<a id="org2d08b7d"></a>

## Predefined objects


<a id="orgb1a18d2"></a>

## Ways to create Objects


<a id="org36fd148"></a>

## Ways to iterate Objects


<a id="org72a600b"></a>

## Pass by reference


<a id="org42e1787"></a>

# Functions and Functional Programming


<a id="orgb5f87b4"></a>

## Function syntax


<a id="orgb42f781"></a>

## Return values of functions


<a id="org7ce19fc"></a>

## Anonymous Functions


<a id="org3cdac58"></a>

## Inner Functions


<a id="orgcf340e4"></a>

## Function Scope


<a id="orgfeac6a6"></a>

## Globals and how to avoid them


<a id="orge67cf36"></a>

## Functions as Objects


<a id="org172214c"></a>

## call and apply


<a id="orge3d083f"></a>

# Arrays


<a id="orgd799e59"></a>

## How JavaScript arrays are different


<a id="org9545c09"></a>

## Multidimensional arrays


<a id="org4055ee1"></a>

# Prototypes and Prototypal Inheritance


<a id="org410a413"></a>

## Inheritance in JavaScript


<a id="org94e750f"></a>

## Constructor functions


<a id="org0c56a78"></a>

## The prototype link


<a id="org7e6710b"></a>

## The object Function


<a id="org315816e"></a>

## Difference from classical inheritance


<a id="orgfce3e2e"></a>

## The this keyword


<a id="org37a886e"></a>

# JavaScript Programming Paradigms


<a id="orgb5a945d"></a>

## Object oriented programming in JavaScript


<a id="org74e0bc8"></a>

## Functional programming in JavaScript


<a id="org1ed6cb4"></a>

## Aspect oriented programming in JavaScript


<a id="org26b7fe5"></a>

# Document Object Model


<a id="orgb9d740e"></a>

## Introduction to DOM


<a id="orgd54a2d8"></a>

## A little history of the web


<a id="orgf2bcdd8"></a>

## Levels (or types) of DOM


<a id="orgc74ff31"></a>

## Nodes


<a id="orga5a630d"></a>

## Elements


<a id="orga398d0f"></a>

## Attributes


<a id="org533271c"></a>

## Text


<a id="orgfbae659"></a>

## Comment


<a id="org61a1f3e"></a>

# JavaScript and DOM


<a id="org283d2f2"></a>

## Parsing XML in JavaScript


<a id="orgdc49d31"></a>

## Create elements


<a id="org7040d9f"></a>

## Retrieve elements


<a id="org232cfb8"></a>

## Delete elements


<a id="orgad1a894"></a>

## Work with attributes


<a id="org7a24154"></a>

## A few examples


<a id="org68cfb65"></a>

# Event Handling in JavaScript


<a id="org8ffd4c3"></a>

## Adding event handlers


<a id="org293a11a"></a>

## Asynchronous handling of events with callbacks


<a id="org35984bd"></a>

## Event bubbling


<a id="org95ac42a"></a>

## Event capturing


<a id="org8ebadcb"></a>

# JavaScript Libraries


<a id="orgc0cd4c8"></a>

## The need for libraries


<a id="org5c40c2f"></a>

## Handling cross-browser issues with JS libraries


<a id="org58c303f"></a>

## jQuery


<a id="org071b74d"></a>

## Node.js


<a id="org148865b"></a>

# AJAX and XMLHttpRequest


<a id="org59dab99"></a>

## The components - XMLHttp, JavaScript, XML (or JSON) and DOM


<a id="orgca5e788"></a>

## Intelligent clients with AJAX


<a id="orgba2e594"></a>

## Examples of AJAX usage


<a id="org3d50777"></a>

# Data Formats


<a id="org073f439"></a>

## What are data formats?


<a id="orgf4a90f6"></a>

## Difference from data structures


<a id="org0684ac9"></a>

## Serialization and deserialization


<a id="orgc5fc12b"></a>

## Maps as generic data containers

