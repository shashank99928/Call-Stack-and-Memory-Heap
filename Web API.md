
# Web API:
 ####  Inbuilt  API used to perform asynchronous operations. which use DOM,fetch(), setTimeout() to perform such operation. 
 #### Browser Provides us with Fetch and setTimeout through `window` 

 #### Whenever we run any code which has asynchronous nature its operation get passed from call stack to WEB API then to Callback Queue from there Eventloop continuously checks  for Call stack to get empty then it pushes the asynchronous operation back to Call Stack for Execution.

###  [Try it out](http://latentflip.com/loupe/?code=ZnVuY3Rpb24gcHJpbnRIZWxsbygpIHsNCiAgICBjb25zb2xlLmxvZygnSGVsbG8gZnJvbSBiYXonKTsNCn0NCg0KZnVuY3Rpb24gYmF6KCkgew0KICAgIHNldFRpbWVvdXQocHJpbnRIZWxsbywgMzAwMCk7DQp9DQoNCmZ1bmN0aW9uIGJhcigpIHsNCiAgICBiYXooKTsNCn0NCg0KZnVuY3Rpb24gZm9vKCkgew0KICAgIGJhcigpOw0KfQ0KDQpmb28oKTs%3D!!!PGJ1dHRvbj5DbGljayBtZSE8L2J1dHRvbj4%3D)
`const number= 420.69`  




## 2.Fetch

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


## 3.setTimeoutw

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
