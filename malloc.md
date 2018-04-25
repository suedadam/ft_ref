# Malloc
<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1600/1*cr5mPS7Mw2hRC8UwboXE-Q.png">
</p>

This project was intended to be an intro to heap memory allocation and recode it all; however, it quickly took a different turn. I was inspired by our CTO to rewrite it in a way that is more efficient than every implementation out there. I made a Malloc that did all operations in a constant O(1). 

Medium Article about the implementation:

(Link coming soon)

[PDF](pdf/ft_malloc.en.pdf)
---

# Objectives
|Name|TL;DR
|:-:|:-:|
|Understand Heap memory|This project was an intro to recreating Malloc to manage the heap memory space.|
|Make a Malloc to rule them all|I took it upon myself to make a Malloc faster than them all, one that can perform in constant O(1).|
|Thread safety|To make this project work with DYLD (to allow preloading/hijacking) basic threadsafety was required, this meant understanding how threads really work behind the scenes to prevent slowdowns.|

# Skills
|Skill|How it was used
|:-:|:-:|
|Data structures|While brainstoriming how to make my implementation O(1) I had to make a hybrid data structure which used arrays and Meatdata to allow scalability with little overhead.|
|Multithreading|To make all operations have little cost in the processing pipeline we had to push processing outside of the pipeline with multithreading.|
