---
layout: post
title:      "Methods and Variable"
date:       2019-09-19 21:55:03 +0000
permalink:  methods_and_variable
---


A method in ruby is something that provides functionality to an object and there are a couple types of methods, each with different scopes. First there is the instance method, which can be called upon instances and second there is the class method wich can be called on the class itself. Then there are variables which hold a value that can change, depending on conditions or on information passed to the program. They have a few scopes to them such as local, instance, class, and global variables. 

With methods of different scoopes there are things to remember, because an instance method does not have the same scope as a class method it can not call an instance method on a class itself. Also vice versa a class method can not call a class method on a instance. 

The same basic rules follow with the variables and their four different scopes. First we have a the local variable, a local variable declared in a method or within a loop cannot be accessed outside of that loop or method and they must begin with an underscore ( _ ) or  a lower case letter ( a-z ). Second we have the instance variable, a variable who's value is local to a specific instance of an object and it is declared by a single at sign ( @ )in front of it. Third we have the class variable, a class variable can be used in all instances of a class and is declared with two at signs ( @@ ) in front of it. Lastly we have a global variable, which can be accessed from anywhere in the ruby program and must be declared with a dollar sign ( $ ).

Toguether these methods and variables can give a wide range in funcitonality to a class.


