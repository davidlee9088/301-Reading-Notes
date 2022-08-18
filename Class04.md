1. What is a ‘Controlled Component’?
Data handled by React.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
We should we waiting for the response from the form into state when they submit because just incase the data has to be changed. Once the data has been sent that is when we can submit the form.
3. How do we target what the user is entering if we have an event handler on an input field? we target what the user is entering by using event.target method.


1. Why would we use a ternary operator?
We should be using tetrnary operator like we are using arrow functions. To make it simpler to code and shorter.

2. Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

let abc = (x === y) 'true' : 'false';
console.log(abc)