This is Practice Question & Anwes


// //Question No = 1

// let countString = "ankitgill"
// let sum = 0;
//  for(let i = 0; i < countString.length; i++){
//     let char = countString.charAt(i).toLowerCase();
//     if(char >= "a" && char <= "z" && ! "aeiou".includes(char)){
//         sum++;
//     }
// }
// console.log("number of the count", sum);


// //Question No = 2


// function uppercse (){
//   let lower = "ankitgill";
//   let upper = lower.toUpperCase();
//   console.log(upper);
// } 
// uppercse();


// //Question No = 3

// function lowercase (){
//     let upper = "ANKITGILL";
//     let lower = upper.toLowerCase();
//     console.log(lower);
//   } 
// lowercase();


// //Question No = 4;

// function capitalize(){
// let  string  = "ankit";
//  console.log(string[0].toUpperCase()+
//  string.slice(1));
// }
// capitalize();

// //Qouestion No  = 5

// function leepYear(year){
//     if((0 == year % 4) && (0 != year % 100) || (0 == year % 400)){
//         console.log( year +   "    this is a leep year");
//     }else{
//         console.log( year +   "    this is a not leep year");
//     }
// }

const year = prompt('Enete your year');

// leepYear(year);


// //Question No = 6

// function largestNumber(a,b,c){
//     return Math.max(a,b,c);
// }

// const num1 = 12;
// const num2 = 23;
// const num3 = 45;

// const result = largestNumber(num1,num2,num3);

// console.log(result);


// //Question No = 7

// function  smallNumber(a,b,c){
//     return Math.min(a,b,c);
// }

// const number1 = 112;
// const number2 = 299;
// const number3 = 456;

// const slove = smallNumber(number1,number2,number3);

// console.log(slove);



//Question No = 8

// const sume1 = 16;
// const sume2 = 23; 
// console.log(sume1 , sume2); 


//Question No = 9

// function parameter(name){
//     return `Hello ${name}!`

// }
// const resultes = parameter(`ankitgill`);

// console.log(resultes);

//Question No = 10

// const carsName = ["thar","fouter","scroopuo"];
// console.log(carsName);

//Question No = 11

// function sum(a,b){
//     return a + b;
// }console.log(sum( 2 , 2 ));


//Question No = 12
// const person = {
//  myName : "Ankit",
//  age : 18,
//  study : "Atschool"
// }
// console.log(person);


// // Question No = 1


// for(let i = 0; i < 10; i++){
// console.log(i);
// }


// Question No = 2

// function multi(a,b){
//  return a * b;

// }console.log(multi(7,8));

// Question No = 3

// const myName = ("ankit");
// const lastName = ("gill");
// console.log(myName,lastName);

// Question No = 4

// function square(a,b,){
//    return Math.sqrt(a * a + b * b );
// }console.log(square(3,4))

// Question No = 5

// const fruitName = ["mango", "apple","banna"];
// console.log(fruitName);

// Question No = 6

// function leng(int){ 
// return int.length;
// }

// const str = "ankit"; 
// const lent = leng(str);

// console.log(`${lent}`)

// Question No 7

// const num = [1,23,3,4,5]
// let sume = Math.min(...num)
// console.log(sume);


// Question No 8

// function find(){
//     let sum = 1;
//  if(sum % 2 === 0){
//     return console.log("even");
//  }else{
//     console.log("odd");
//  }
// }
// find();

// Question No 9

// function join(s1,s2){
// return s1 + s2;
// } 
// const s1 = "ankit";
// const s2 = " gill";
// const result = join(s1,s2);
// console.log(result);

//Question No = 10;

// function last(arry){
// return arry[arry.length -1];
// }
// const arry = ["ankit","gill","payal","jatin","rahul"];
// const result = last(arry);
// console.log(result);

// Questioin No = 11;
// const arry = ["ankit","gill",7];
// console.log(arry);

//Question No = 12

// function revers(rev){
//   return rev.reverse();
// }
// const rev = ["ankit","jatin","payal"];
// const result = revers(rev);
// console.log(result);

//Question No = 13

// function upper(str){
//     return str.toUpperCase();
// }
// const str = ["ankit"];
// const solve = upper(...str);
// console.log(solve);


//Question No = 14

// function upper(str){
//     return str.toLowerCase();
// }
// const str = ["ANKIT"];
// const solve = upper(...str);
// console.log(solve);

//Question No = 15

// function type(vare){
//  return typeof vare;
// }
// const vare = false;
// const answer = type(vare);
// console.log(answer);

// Question No 16

// function getCheck(get){
//     return get.includes("");
// }
// const get = "ankit";
// const sum = getCheck(get);
// console.log(sum);

// Question No 17

// const color = ['red','blue','green','yellow'];
// console.log(color);



// Question No 1

// function first(str){
//   return  str.charAt(0);

// }
// const str = "ankit";
// const result = first(str);
// console.log(result);

//Question No 2
// const cars = ['thar','bmw','ode','bullet'];
// cars.shift();
// console.log(cars);

//Question No 3

// function empty(arr){
//     if(arr.length === 0){
//         console.log("this arry is empty");
//     }else{
//         console.log("this arry is not empty");
//     };
//     return arr.length;
// };
// const arr = [];
// const result = empty(arr);
// console.log(result);

//Question No 4;

// function element(str){
//    return str.join();
// };

// const str = ["ankit","gill","payal"];
// const result = element(str);
// console.log(result);

//Question No 5;

// function splet(word){
//     return word.split(" ");
// }
// const word = "I LOVE MY WIFE ";
// const result = splet(word);
// console.log(result);

// Question No 6;

// function  short(asin){
//     return asin.sort((a,b) => a - b);
// }
// const asin = [102,3949,847,9844,974,934];
// const result = short(asin);
// console.log(result);

//Question No 7;
// function white(space){
//     return space.trim();
// }
// const space = '  ankit  ';
// const result  = white(space);
// console.log(result);

//Question No 8;

// function shorts(dsin){
//     return dsin.sort((a,b) => a > b ? -1 : 1);
// }
// const dsin = [0,4,7,546,7,5,75,646];
// const result = shorts(dsin);
// console.log(result);

//Question No 9;

// function date(carnt){
//     return   new Date();
// }
// const carnt = "this is a current time";
// const result = date(carnt);
// console.log(result);

//Question No 10;

// const right = true;
// const result = typeof right
// console.log(result)

//Question No 11;

// function positive(num){
//    if(num > 0){
//         console.log("positvie");
//       }else if(num === 0){
//         console.log("the number is zero");
//       }
//       else{
//           console.log("nevegit");
//       }  
//        return num
//     }
// const num = -1;
// const result = positive(num);
// console.log(result);

//Question No 12;

// const friut = ['orange','mango','papa'];
// const result = friut.length;
// console.log(result);

//Question No 13;

// function first(arr,n){
//     return arr.slice(0 ,n);
// }
// const arr = ["thar",'scropyo','fourten','manstanh','beloro'];
// const n = 1;
// const result = first(arr,n);
// console.log(result);

//Question No 14;

// const cars = {
//     make : "india",
//     model : "20023"
// }
// console.log(cars);

//Question No 15;

// function swaps(a,b,c){
//     [a,b,c] = [b,c,a];
//    return [a,b,c]
// }
// const a = 1;
// const b = 3;
// const c = 6;
// const result = swaps(a , b ,c);
// console.log(result);

//Question No 16;

// let value;
// console.log(value);

//Question No 17;

// function value(user){
//     return user === null;
// }
// let user = null;
// let user2 = 67;
// const result = value(user2);
// console.log(result);

//Question No 18;

// const bike = ['bullet','i love my wife','i love hot girl','i love porn '];
// console.log(bike[3]);


//Question No 19;

// function large(lar){
//     return Math.max.apply(null, lar);
// }
// const lar = [1,4,6,90,68];
// const result = large(lar);
// console.log(result);

//Question No 20;

// let value = null;
// console.log(value);

//Question No 21;

// function factiacl(n){
//     if(n === 0){
//         return 1;
//     }else{
//         return n * factiacl ( n - 1);
//     }

// }
// const n = 108;
// const result = factiacl(n);
// console.log(result);


//Question No 21;

// const marrige = ['i love my wife','i love my girlferind','i love cars','i love school'];
// const remove = marrige.pop();
// console.log(remove);
// console.log(marrige);

//Question No 22;

// function rndom(){
//     return Math.floor(Math.random() * 3 ) + 1 ;
// }
// const result = rndom();
// console.log(result);

//Question No 22;

// function nevegit(nev){
//     if(nev < 0){
//         console.log("this is nevegit");
//     }
//     else{
//       console.log("this is positive");
//     }
//     return nev
// }
// const nev = -8;
// const result = nevegit(nev);
// console.log(result);

//Question No 23

// function about(number){
//     return Math.abs(number);
// }
// const number = 2.99;
// const result = about(number);
// console.log(result);

//Question No 24;

// const arr = [1,4];
// let sum = 0;
// let i;

// for(i = 0;i < arr.length; i++){
//     sum += arr[i];
// }
// console.log(+sum);

//Question No 25;

// let i;
// for( i = 0; i <= 100; i++){
  
 
//     if (i % 2 === 0) {
//     console.log("even", i)
//    }else{
//     console.log("odd", i);
//    }
// }

//Question No 26;


// let sum = 25;
// let pront = prompt("enter you number");
// while( pront != sum){
//     pront = prompt("try agin")
// }
// console.log("you are win ");

//Question No 27;

// let user = prompt("enter your full name");
// let fullUser = "@" + user + user.length;
// console.log(fullUser);

