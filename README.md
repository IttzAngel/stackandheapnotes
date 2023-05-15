### What is the stack?
- The stack is where method invocations and local variables live
- The method on top of the stack is always the currently executing method
- If a method calls another method, the called method is placed on top of the stack
- Methods stays on the stack until the method reaches its curly brackets
- When calling a method, it will **ALWAYS** land on the top of a call stack

### What is the heap?
- The heap is where objects live
- **ALL** objects live on the garbage collectible heap
- Even if the local variable is a reference to an object, only the variable goes on the stack, and the object still goes on the heap
- No matter where the object reference variable is declared (inside a method vs an instance variable of a class) the object **ALWAYS** goes on the heap
- Instance variables live on the heap inside the object they belong to
- Even if using a reference variable in an object, only the orignal object will be on the heap, and another object will have to be created with the reference
