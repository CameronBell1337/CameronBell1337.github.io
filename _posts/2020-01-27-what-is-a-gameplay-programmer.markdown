---
layout: post
title: <I>What is a 'Gameplay' programmer?</I>
date: 2020-01-27T13:30:00.000Z
author: Cameron Bell
categories:
  - Blog
  - Game-play Programming
  - Programming
  - Module
img: codeHeader.JPG
thumb: c_thumb.jpg
published: true
---



#### What is a game-play Programmer?
A <b>game-play programmer</b> are one team of many others within a Game Studio, they are responsible for the functionality of the game.
Game-play programmers implement the main gameplay within a game from things like the character movement and interaction, in-game entities that require logic.
They must work with scope in mind knowing how hard mechanics can be to design as everyone can have amazing ideas on what they want but in reality getting the
exact outcome while making sure its not too taxing on performance, look, feel and if it can even be possible. 

<img src="asge_01.png">

#### How do we use it?
```C++
int  static_int  = 2;
int* dynamic_int = new int(2);
```



#### How do we free it?
```C++
if ( dynamic_int )
{ 
  delete dynamic_int;
  dynamic_int = nullptr;
}
```

Dynamic memory is a complex and detailed area of C++ programming. There is still much to learn, but understanding why it exists and how it compares to static allocation can aid you in it's usage and understanding. Till next time.
