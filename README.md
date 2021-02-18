
# Call stack + Memory Heap

## 1.Memory Heap

### allocated memory for number stored in Memory heap.
`const number= 420.69`  

 ### allocated memory for objects and values which is stored in Memory heap.
`const robot={ 
 first:"Terminator"
 last:"Robot"
}
`


## 2.Call stack (LIFO)

### set of functions/opeations which uses Memory heap to perfrom operations
### stores only functions which are pushed into it.

` function multi(num){
return num*2;
} `

`function sum(){
const num = 5+9
return multi(num)
}
sum() `

### Follows last in first out order to execute particular stack and stacking of this opeations is called stack frameing

## 3.StackOverflow 
### This happens when maximum call stack size exceeds (eg:Recursion).

## 3.Garbage Collection
### Javascript has automatic garbage colletion . It removes unused memory from Memory Heap which prevents memory leaks
 
 
 


