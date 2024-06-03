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


// // Question No = 13


// for(let i = 0; i < 10; i++){
// console.log(i);
// }


// Question No = 14

// function multi(a,b){
//  return a * b;

// }console.log(multi(7,8));

// Question No = 15

// const myName = ("ankit");
// const lastName = ("gill");
// console.log(myName,lastName);

// Question No = 4

// function square(a,b,){
//    return Math.sqrt(a * a + b * b );
// }console.log(square(3,4))

// Question No = 16

// const fruitName = ["mango", "apple","banna"];
// console.log(fruitName);

// Question No = 17

// function leng(int){ 
// return int.length;
// }

// const str = "ankit"; 
// const lent = leng(str);

// console.log(`${lent}`)

// Question No 18

// const num = [1,23,3,4,5]
// let sume = Math.min(...num)
// console.log(sume);


// Question No 19

// function find(){
//     let sum = 1;
//  if(sum % 2 === 0){
//     return console.log("even");
//  }else{
//     console.log("odd");
//  }
// }
// find();

// Question No 20

// function join(s1,s2){
// return s1 + s2;
// } 
// const s1 = "ankit";
// const s2 = " gill";
// const result = join(s1,s2);
// console.log(result);

//Question No = 21;

// function last(arry){
// return arry[arry.length -1];
// }
// const arry = ["ankit","gill","payal","jatin","rahul"];
// const result = last(arry);
// console.log(result);

// Questioin No = 22;
// const arry = ["ankit","gill",7];
// console.log(arry);

//Question No = 23

// function revers(rev){
//   return rev.reverse();
// }
// const rev = ["ankit","jatin","payal"];
// const result = revers(rev);
// console.log(result);

//Question No = 24

// function upper(str){
//     return str.toUpperCase();
// }
// const str = ["ankit"];
// const solve = upper(...str);
// console.log(solve);


//Question No = 25

// function upper(str){
//     return str.toLowerCase();
// }
// const str = ["ANKIT"];
// const solve = upper(...str);
// console.log(solve);

//Question No = 26

// function type(vare){
//  return typeof vare;
// }
// const vare = false;
// const answer = type(vare);
// console.log(answer);

// Question No 27

// function getCheck(get){
//     return get.includes("");
// }
// const get = "ankit";
// const sum = getCheck(get);
// console.log(sum);

// Question No 28

// const color = ['red','blue','green','yellow'];
// console.log(color);



// Question No 29

// function first(str){
//   return  str.charAt(0);

// }
// const str = "ankit";
// const result = first(str);
// console.log(result);

//Question No 30
// const cars = ['thar','bmw','ode','bullet'];
// cars.shift();
// console.log(cars);

//Question No 31

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

//Question No 32;

// function element(str){
//    return str.join();
// };

// const str = ["ankit","gill","payal"];
// const result = element(str);
// console.log(result);

//Question No 33;

// function splet(word){
//     return word.split(" ");
// }
// const word = "I LOVE MY WIFE ";
// const result = splet(word);
// console.log(result);

// Question No 34;

// function  short(asin){
//     return asin.sort((a,b) => a - b);
// }
// const asin = [102,3949,847,9844,974,934];
// const result = short(asin);
// console.log(result);

//Question No 35;
// function white(space){
//     return space.trim();
// }
// const space = '  ankit  ';
// const result  = white(space);
// console.log(result);

//Question No 36;

// function shorts(dsin){
//     return dsin.sort((a,b) => a > b ? -1 : 1);
// }
// const dsin = [0,4,7,546,7,5,75,646];
// const result = shorts(dsin);
// console.log(result);

//Question No 37;

// function date(carnt){
//     return   new Date();
// }
// const carnt = "this is a current time";
// const result = date(carnt);
// console.log(result);

//Question No 40;

// const right = true;
// const result = typeof right
// console.log(result)

//Question No 41;

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

//Question No 42;

// const friut = ['orange','mango','papa'];
// const result = friut.length;
// console.log(result);

//Question No 43;

// function first(arr,n){
//     return arr.slice(0 ,n);
// }
// const arr = ["thar",'scropyo','fourten','manstanh','beloro'];
// const n = 1;
// const result = first(arr,n);
// console.log(result);

//Question No 44;

// const cars = {
//     make : "india",
//     model : "20023"
// }
// console.log(cars);

//Question No 45;

// function swaps(a,b,c){
//     [a,b,c] = [b,c,a];
//    return [a,b,c]
// }
// const a = 1;
// const b = 3;
// const c = 6;
// const result = swaps(a , b ,c);
// console.log(result);

//Question No 46;

// let value;
// console.log(value);

//Question No 47;

// function value(user){
//     return user === null;
// }
// let user = null;
// let user2 = 67;
// const result = value(user2);
// console.log(result);

//Question No 48;

// const bike = ['bullet','i love my wife','i love hot girl','i love porn '];
// console.log(bike[3]);


//Question No 49;

// function large(lar){
//     return Math.max.apply(null, lar);
// }
// const lar = [1,4,6,90,68];
// const result = large(lar);
// console.log(result);

//Question No 50;

// let value = null;
// console.log(value);

//Question No 51;

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


//Question No 52;

// const marrige = ['i love my wife','i love my girlferind','i love cars','i love school'];
// const remove = marrige.pop();
// console.log(remove);
// console.log(marrige);

//Question No 53;

// function rndom(){
//     return Math.floor(Math.random() * 3 ) + 1 ;
// }
// const result = rndom();
// console.log(result);

//Question No 54;

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

//Question No 56

// function about(number){
//     return Math.abs(number);
// }
// const number = 2.99;
// const result = about(number);
// console.log(result);

//Question No 57;

// const arr = [1,4];
// let sum = 0;
// let i;

// for(i = 0;i < arr.length; i++){
//     sum += arr[i];
// }
// console.log(+sum);

//Question No 60;

// let i;
// for( i = 0; i <= 100; i++){
  
 
//     if (i % 2 === 0) {
//     console.log("even", i)
//    }else{
//     console.log("odd", i);
//    }
// }

//Question No 61;


// let sum = 25;
// let pront = prompt("enter you number");
// while( pront != sum){
//     pront = prompt("try agin")
// }
// console.log("you are win ");

//Question No 62
// function one(arr){
// let sum = 0;
// for(let i = 0; i < arr.length; i++){
//       sum +=arr[i]
   
// }
// return sum/arr.length;
// }
// const arr = [4,4,7];
// const result = one(arr);
// console.log(result);

//Question No = 63

// function sum(a,b){
//     return a + b;
// }
//  const answer = sum(4,9);
//  console.log(answer);

//Question No = 64

// function product(x,y){
//     return x * y;
// }

// const answer = product(3,4);
// console.log(answer);


//Question No = 65

// const myName = "ankitgill";
// console.log(myName);

//Question No = 66

// const str = "ankit"
// function upper(str){
//     return str.toUpperCase();
// }
// console.log(upper(str));

//Question No = 67

// const str = "ANKITGILL"
// function upper(str){
//     return str.toLowerCase();
// }
// console.log(upper(str));


//Question No = 68

// const arr = [1,5,8,0];
// const answer = arr[0];
// console.log(answer);


//Question No = 69

// const arr = [1,5,8,0,7,8,9,7,6,89,0,68];
// const answer = arr[11];
// console.log(answer);


//Question No = 70

// function arry(str){
//     return str[0];
// }
// const str = ["Ankit","payal","jatin","mohit"];
// const result = arry(str);
// console.log(result);

//Question No = 71

// function arry(str){
//     return str[3];
// }
// const str = ["Ankit","payal","jatin","mohit"];
// const result = arry(str);
// console.log(result);

//Question No = 72

// const str = "ankit";
// const answer = str.length;
// console.log(answer);

//Question No = 73

// function positive(num){

//     if(num > 0){
//         console.log("Positive");

//     }else{
//         console.log("Negitive");
//     }
//     return num;
// }

// const num = 8;
// const answer = positive(num);
// console.log(answer);

//Question N0 = 74

// function even(num){
//     return num % 2 === 0;
  
// }
// const num = 8;
// const answer = even(num);
// console.log(answer);


//Question N0 = 75

//  function even(num){
//     return num % 2 !== 0;
  
//  }
// const num = 7;
//  const answer = even(num);
//  console.log(answer);

//Question N0 = 76

// const boolen = true;
// console.log(boolen);

//Question N0 = 77

// const car = "thar";
// const result = typeof car;
// console.log(result);

//Question N0 = 78

// function date(time){
//     return new Date;
// }
// let time;
// const result = date(time);
// console.log(result);

//Question N0 = 79

// function randm(num){
//     return Math.floor((Math.random(num) * 10) + 1 );
// }
// let num;
// const result = randm(num);
// console.log(result);

//Question N0 = 80

// function number(square){
//     return square * square;
// }
// const square = 5;
// const result = number(square);
// console.log(result);

//Question N0 = 81

// function join(a,b){
//   return a + b;
// }
// const a = "ankit"
// const b = "gill"
// console.log(join(a,b));

//Question N0 = 82

// function absult(value){
//     return Math.abs(value);
// }
// const value = -2.7;
// const result = absult(value);
// console.log(result);

//Question No = 1

// const myName = "ankitgill";
// console.log(myName);

//Question No = 2

// function sum(a,b){
//     return a + b;
// }
// const result = sum(2,6);
// console.log(result);

//Question No = 3

// const myName = "ankit";
// const lastNmae = "gill";
// const result = myName + " " +lastNmae;
// console.log(result);


//Question No = 4
// let num = -1;
// function isnumber(num){
//     if(num > 0){
//         console.log("positive");
//     }else if( num  === 0){
//         console.log("this is Zero");
//     }else{
//         console.log("negative");
//     }
//     return num
// }
// console.log(isnumber(num));

//Question No 5

// for(let i = 0; i  < 10; i++){
//     console.log(i);
// }

//Question No 6 to 8

// const arr = [1,2,3,4,5];
// const asscee = arr[2];
// const add = arr.push(6);
// console.log(arr);

//Question No 9  to 10 

// const book = {
//     title : "Atotmic Habit",
//     author : "Jamce clear",
//     year :  2006,
//     getDescription: function () {
//       return `${this.title} is a ${this.genre} novel written by ${this.author} in ${this.year}.`
//     }
// }

// console.log(book);

//Question No 11

// function gree(name){
//     return name + "gill"  ;
// }
// const name = "ankit"
// console.log(gree(name));

//Question No 12

// function isSize(str){
//     return str.length;
// }
// const str = "ankit";
// const result = isSize(str);
// console.log(result);

//Question No 13

// const num = [1,4,5,69,89,0];
// let text = " ";
// function print(arr){
//     return arr.join(" ");
// }
// console.log(print(num));

//Question No 14

// function even(num){
//   return num.filter(function(arr){
//     return arr % 2 === 0;
//   })
// }
// const number = [12,43,6,77,8,2,6];
// const result = even(number);
// console.log(result);

//Question No 15;

// switch(new Date().getDay()){
//  case 0:
//   day = "Sunday";
//   break;
//   case 1:
//     day = "Monday";
//     break;
//    case 2:
//     day = "Tuesday";
//     break;
//     case 3:
//     day = "Wednesday";
//     break;
//     case 4:
//     day = "Thursday";
//     break;
//     case 5:
//     day = "Friday";
//     case 6:
//     day = "Saturday";
//     break;
//   default:
//     day = "Unknown day";
// }
// console.log(day);


//Question No 16

// let myName = `ankit`
// let result = `hello ${myName} welcome to web sid`
// console.log(result);

//Question No  17

// function isFind(a,b){
//    if(a === undefined){
//     a = 2;
//    }
//    return a * b;
// }
// console.log(isFind(3,4));
// console.log(isFind(undefined,4));


//Question No 18

// let myFunction = (a, b) => a * b;
// console.log(myFunction(20,5));

//Question No 19

// function create(arr){
//     return arr.map((value) => value -1);
// }
// const arr = [1,5,7,89,7];
// const result = create(arr);
// console.log(result);


// let user = prompt("enter your full name");
// let fullUser = "@" + user + user.length;
// console.log(fullUser);

