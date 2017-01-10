# pswritfuncjsramda_nt

##2. Getting Started
###5 JavaScript as a Functional Programming Language

functions as data
```
var name = "ke";
var f = function sayHello(name){
	return name
}

console.log(f.name); //sayHello
console.log(f.call(null,name)); //ke
```
functions as arguments
```
var say = function(){}
setTimeout(say,1000)
```

##4. Composing for a More Readable Code
###2 Filtering Data with Ramda
```
const number= [12,3];
const isEven = x=>x%2===0;
R.filter(isEven,numbers);
```
###3 A First Composition
```
function hasPoster(movie){
  return R.not(R.isNil(movie.poster_path));
}
```
using R.compose
```

```
