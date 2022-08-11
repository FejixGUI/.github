# Fejix Project

> Work in progress :hourglass:

Fejix a GUI framework that is focused on doing things right.

It has the following values:
* **Being accessible to many programming languages.** Fejix values the ability to be *easily* built into a library with a *C interface*. By my choice, it is written in C99. However, C interface is not all. GUIs are very hierarchical, and their behavior is far too complex to be specified in C. Thus, Fejix uses Lua to specify GUI and a code generator that would do all the hard work for you.
* **Defining widgets in a semantically correct way.** The idea is the following: you specify what your widgets are, how they must look and behave, and you get an auto-generated implementation compatible with your favourite language. Few or even none of modern GUI frameworks allow you to truly control what your widgets are. What if you want to add a pink line to the standard push button? Fejix can do that without any tricks.
* **Minimalism but with abilities to extend.** Fejix tried to give you a sensible default set of functionality, but you can always extend it.

Note that the project is not complete. There is no working example that you look at.