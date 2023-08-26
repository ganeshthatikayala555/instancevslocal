# instancevslocal
this will contain to see how local variables and instance variables work....in memories
the stack is used for storing local(exist for short time).Local variables will have scope within the func in which they are declared,
so when a block like for loop is executing,it creates a stack frame for that method
and executes that method and stack frame gets released from stack,,and whenever the method called again
,a new stack is created for execution
--lifo model of stacks helps quicker access of localvariables and function calls which are stored in stackframes
--And heap allows dyanamic creation of objects,,we dont know how many objects will be created at compile time,,number of objects created will depend 
on useer interaction at run time,,and they will exist for life long(as long as pgm exists)..
So,instance and objects are stored in heap 
stackis datasructure and heap is space
--each instance of will have seperate space in heap to store its set of instance variables
---In this exampl the main method creates a stack frame,which is constant and for somemethod a new method gets pushed into stack every time itis 
called,and gets popped out after excution,,and a new stackframe created when it is called next time 


