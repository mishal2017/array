# array

var names = new Array(5);
names [0]= "juhj";
names [1]= "jmn";
names [2]= "bnhj";
names [3]= "jushj";
names [4]= "mklhj";
console.log(names.length);
// name. length for length of array


var names = ["juhj",
"jmn",
"bnhj",
 "jushj",
"mklhj"];

console.log(names);
names.push();// add new array
name.pop();// cut the last array
var names = ["anam", "namae"];
var country = ["Namibia", "Hatia"];
var add = names.concat(country);
console.log(add);// concating new variable


var num = [10,25,45,67,80];
var sum = 0;
for( var i = 0;i<5;i++){
console.log(num[i]);
sum = sum + num[i];
}
console.log(sum);//use of loop in array 

var num = [];
for(var i =0; i<5; i++){
num[i]= parseInt(prompt(" Enter your number"));
}

var sum = 0;
for( var i = 0;i<5;i++){
console.log(num[i]);
sum = sum + num[i];
}
console.log(sum);

// array methods
// shift method oppposite of pop which cut the valuse from first
var names = ["Ani", "Nia", "Mia", "Mila"];
names.shift();
console.log(names);
// unshift add element in first
var names = ["Ani", "Nia", "Mia", "Mila"];
names.unshift("Ania");
console.log(names);

// splice uses to add or remove elements
var names = ["Ani", "Nia", "Mia", "Mila"];
names.splice(2,1,"Miyai","Hali");
console.log(names);// here on the splice method 1st number is to add element and the 2nd number is cut the element from last after the new one

names.splice(1,2);
console.log(names);// here splice is used to remove the element

// slice method to delete element
var names = ["Ani", "Nia", "Mia", "Mila"];
var newArray = names.slice(2);
console.log(newArray);


//sort method
var names = ["Ani", "Nia", "Mia", "Mila"];
var newArray = names.sort();
console.log(newArray);
//reverse sort
var names = ["Ani", "Nia", "Mia", "Mila"];
var newArray = names.sort();
names.reverse();
console.log(newArray);

// sort method in number
var numbers = [78,23,34,56,32];
numbers.sort(function(a,b){
return a-b;
});
console.log(numbers);// here on the a and b parameter numbers from the array enter into the function and value of a is greater then b the it will sort accordingly that means small to large number or vice and versa. Here 23 will be the small number then 32..  
