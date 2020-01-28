---
layout: post
title: <I>What is a 'Gameplay' programmer?</I>
date: 2020-01-27T13:30:00.000Z
author: Cameron Bell
categories:
  - Blog
  - Game-play Programming
  - Programming
img: codeHeader.jpg
thumb: c_thumb.jpg
published: true
---



#### Why do we use it?
Because the stack is restrictive


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
