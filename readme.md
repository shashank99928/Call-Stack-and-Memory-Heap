
// call stack + Memory Heap

// Memory Heap

const number= 420.69  // allocated memory for number stored in Memory heap.

const robot={ // allocated memory for objects and values which is stored in Memory heap.
first:"Terminator"
last:"Robot"
}


//   call stack (LIFO)

set of functions/opeations which uses Memory heap to perfrom operations

function multi(num){
return num*2;
}

function sum(){
const num = 5+9
return multi(num)
}

sum()  // Follows last in first out order to execute particular stack and stacking of this opeations is called stack frameing


