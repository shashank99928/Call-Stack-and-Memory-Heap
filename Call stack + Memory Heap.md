
# Call stack + Memory Heap

## 1.Memory Heap

### Allocated memory for number stored in Memory heap.
`const number= 420.69`  

 ####  Allocated memory for objects and values which is stored in Memory heap.
`const robot={ 
 first:"Terminator"
 last:"Robot"
}
`


## 2.Call stack (LIFO)

 ####  Set of functions/opeations which uses Memory heap to perfrom operations
 ####  Stores only functions which are pushed into it.

` function multi(num){
return num*2;
} `

`function sum(){
const num = 5+9
return multi(num)
}
sum() `
 ####  Follows last in first out order to execute particular stack and stacking of this opeations is called stack frameing


## 3.StackOverflow 

 ####  This happens when maximum call stack size exceeds (eg:Recursion).


## 4.Garbage Collection

 ####  Javascript has automatic garbage colletion . It removes unused memory from Memory Heap which prevents memory leaks
 
  
## 5.Memory Leak

### Memory Leak Causes

 #### a. Infinte loop
 `let arr=[];
for(i=5;i>1;i++){
arr.push(i-1)
}`
 
 #### b. Global Variable
 
 #### c. setInterval (infinite call)
 
 
 ## 6.Single Threaded

 #### One thing at a time (synchronous) .It has only once call stack that's why it is called Single Thread. 
