# We can ignore this file
This file is made to keep tracking process:
## Monday 08 August, 2022
Time to catch up ⏱️ or do extra work ⭐
1. [x] Learn about for of loop (It is not mandatory for the Readme)
* for of video
* for of examples
2. [x] Follow this JavaScript Array Filter video (It is not mandatory for the Readme)
3. [x] Follow this JavaScript Array Reduce video (It is not mandatory for the Readme)
4. [x] Follow this JavaScript Array Map video (It is not mandatory for the Readme)

## Tuesday 09 August, 2022
Time to catch up ⏱️ or do extra work ⭐
1. [x] Watch this Regular Expressions (RegEx) video (It is not mandatory for the Readme).
2. [x] Read Regular Expressions - MDN documentation (It is not mandatory for the Readme).
3. [x] Learn about replace in this video (It is not mandatory for the Readme).
4. [x] Read replace - MDN documentation (It is not mandatory for the Readme).
5. [x] Check Regexr, a tool to test your regular expressions (It is not mandatory for the Readme).
6. [x] A complete Regular Expressions video (It is not mandatory for the Readme).

Notes: To learn .replace() we must understand firs the Regex expressions.

## Wednesday 10 August, 2022
Time to catch up ⏱️ or do extra work ⭐

## Thursday 11 August, 2022
1. [x] ✨Complete your 2nd Core Challenge. This is one of the requirements for the certification, where you'll boost your dev professional-brand.

## Friday 12 August, 2022
Extra (It is not mandatory for the Readme) ⭐

2. [x] Simple Validation Of A Username exercise
```JavaScript
function validateUsr(username) {
  //first atempt: res =  /^(?=.*\d)(?=.*[a-z]).{16,}$/g/.test(username) 
  res =  /^([a-z]+|\d+|_){4,16}$/.test(username); 
  return res
}
//^ means start from the beginning of the string
//[] any character including a-z this case
// | is a boolean
// \d+ multiple digits
// _ underscore
// {4,16} from 4 to 16 digits long
```

4. [x] Get Number From String exercise
```JavaScript
function getNumberFromString(s) {
  //first attempt:  s.replace(/(\w*)/g, "\s"); replace all words for spaces my first thought(?);
  //tell the function to replace the argument (express in the parenthesis using regex expression);
  return +s.replace(/\D/g, ''); // \D means express the things that are NOT digits into '' (spaces of the string);
  //g is global
  //the + in s.replace indicates for position 
}
```
5. [x] String Cleaning exercise
```JavaScript
function stringClean(s){
  // Function will return the cleaned string
  //remove all the numbers
  return s.replace(/\d/g, '');
}
```
7. [x] Password Validation exercise
```JavaScript
// assign your RegExp to REGEXP
const REGEXP = /^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])[a-zA-Z0-9]{6,}$/;
```
