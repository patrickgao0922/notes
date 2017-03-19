# Garbage Collector (GC) in Node.JS

[Understanding V8's Memory Handling](https://blog.risingstack.com/finding-a-memory-leak-in-node-js/)

## Terms

* resident set size: is the portion of memory occupied by a process that is held in the RAM, this contains:

  * the code itself
  * the stack
  * the heap

* stack: contains primitive types and references to objects
* heap: stores reference types, like objects, strings or closures
* shallow size of an object: the size of memory that is held by the object itself
* retained size of an object: the size of the memory that is freed up once the object is deleted along with its' dependent objects

[A tour of V8: Garbage Collection](http://jayconrod.com/posts/55/a-tour-of-v8-garbage-collection)