<h1 align="center">codeWars_Fundamentals_WCS_Bootcamp</h1>
<h2 align="center">First level of Wild Code School CodeWars 💣 package</h2>
<h4 align="center"><i>Last update: 20181213</i></h4>

***

## Recap

#### 121 Repeat string: repeat()
#### 132 Remove First and Last Character: slice(), split(), shift(), pop()
#### 141 Vowel Count: charAt(), match(), filter(), includes()
#### 151 Jaden Casing Strings: map(), replace()
#### 152 Mumblig: map(), repeat(), join()
#### 161 Find the odd int: filter(), reduce(), find()
#### 162 Duplicate encoder: indexOf(), lastIndexOf(), map(), replace()
#### 171 Convert string to camel case: map(), replace(), chatAt(), split()
#### 172 Count the smiley faces: filter(), reduce()

***

## Item 111 Even or Odd :balloon:

_**Create a function (or write a script in Shell) that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.**_

[Play](https://www.codewars.com/kata/even-or-odd)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/111_even_or_odd.js)


## Item 112 Opposite number :sparkles:

_**Very simple, given a number, find its opposite.**_

[Play](https://www.codewars.com/kata/opposite-number)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/blob/master/112_opposite_number.js)


## Item 121 String repeat :rocket:

_**Write a function called repeatStr which repeats the given string string exactly n times.**_
```
repeatStr(6, "I") // "IIIIII"
repeatStr(5, "Hello") // "HelloHelloHelloHelloHello"
```

[Play](https://www.codewars.com/kata/string-repeat)

[Check](#)

[js repeat() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/repeat) :fr:
> La méthode repeat() construit et renvoie une nouvelle chaine de caractères qui contient le nombre de copie demandée de la   > chaine de caractères sur laquelle la méthode a été appelée, concaténées les unes aux autres.
> _str.repeat(compte);_


## Item 122 Jenny's secret message :heart:

_**Jenny has written a function that returns a greeting for a user. However, she's in love with Johnny, and would like to greet him slightly different. She added a special case to her function, but she made a mistake.  
Can you help her?**_

[Play](https://www.codewars.com/kata/jennys-secret-message)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/122_jennys_secret_message.js)


## Item 131 Convert boolean values to strings 'Yes' or ‘No' :dancer:

_**Complete the method that takes a boolean value and return a "Yes" string for true, or a "No" string for false.**_

[Play](https://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/131_convert_boolean_values_to_strings.js)


## Item 132 Remove First and Last Character :jack_o_lantern:

_**It's pretty straightforward. Your goal is to create a function that removes the first and last characters of a string. You're given one parameter, the original string. You don't have to worry with strings with less than two characters.**_

[Play](https://www.codewars.com/kata/remove-first-and-last-character)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/132_remove_first_and_last_character.js)

:warning: substring() function use is not recommended anymore

[js slice() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/slice) :fr:
> La méthode slice() extrait une section d'une chaine de caractères et la retourne comme une nouvelle chaine de caractères. La
> chaîne de caractères courante n'est pas modifiée.  
> _str.slice(indiceDebut, indiceFin);_

[js split() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/split) :fr:
> La méthode split() permet de diviser une chaîne de caractères à partir d'un séparateur pour fournir un tableau de sous
> chaînes.   
> _str.split([séparateur[, qtéMax]]);_

[js shift() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Array/shift) :fr:
> La méthode shift() permet de retirer le premier élément d'un tableau et de renvoyer cet élément. Cette méthode modifie la
> longueur du tableau.   
> _arr.shift();_

[js pop() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Array/pop) :fr:
> La méthode pop() supprime le dernier élément d'un tableau et retourne cet élément. Cette méthode modifie la longueur du
> tableau.   
> _arr.pop();_


## Item 141 Vowel Count :ghost:

_**Return the number (count) of vowels in the given string.  
We will consider a, e, i, o, and u as vowels for this Kata.  
The input string will only consist of lower case letters and/or spaces.**_

[Play](https://www.codewars.com/kata/vowel-count)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/141_vowel_count.js)

[js charAt() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/charAt) :fr:
> La méthode charAt() renvoie une nouvelle chaîne contenant le caractère (ou, plus précisément, le point de code UTF-16)  à la > position indiquée en argument.   
> _str.charAt(index);_

[js match() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/match) :fr:
> La méthode match() permet d'obtenir le tableau des correspondances entre la chaîne courante et une expression rationnelle.  
> _str.match(regexp);_

[js filter() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Array/filter) :fr:
> La méthode filter() crée et retourne un nouveau tableau contenant tous les éléments du tableau d'origine qui remplissent une
> condition déterminée par la fonction callback.  
> _arr.filter(callback); // callback(elementCourant[, index[, tableauEntier]])
> var nouveauTableau = arr.filter(callback, thisArg);_

[js includes() function on MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/includes) :fr:  
> La méthode includes() détermine si une chaîne de caractères est contenue dans une autre et renvoie true ou false selon le 
> cas de figure.
> _str.includes(chaîneRecherchée);_


## Item 142 Get middle character :princess:

_**You are going to be given a word. Your job is to return the middle character of the word. If the word's length is odd, return the middle character. If the word's length is even, return the middle 2 characters.
Examples:**_
```
Kata.getMiddle("test") should return "es"
Kata.getMiddle("testing") should return "t"
```

[Play](https://www.codewars.com/kata/get-the-middle-character)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/142_get_middle_character.js)


## Item 151 Jaden Casing Strings :heartpulse:

_**Jaden Smith, the son of Will Smith, is the star of films such as The Karate Kid (2010) and After Earth (2013). Jaden is also known for some of his philosophy that he delivers via Twitter. When writing on Twitter, he is known for almost always capitalizing every word.  
Your task is to convert strings to how they would be written by Jaden Smith. The strings are actual quotes from Jaden Smith, but they are not capitalized in the same way he originally typed them.  
Example:**_
```
Not Jaden-Cased: "How can mirrors be real if our eyes aren't real"
Jaden-Cased:     "How Can Mirrors Be Real If Our Eyes Aren't Real"
```
_**Note that the Java version expects a return value of null for an empty string or null.**_

[Play](https://www.codewars.com/kata/jaden-casing-strings)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/151_jaden_casing_strings.js)

[Some great help](https://medium.freecodecamp.org/three-ways-to-title-case-a-sentence-in-javascript-676a9175eb27) :gb:

##### map(), ES5 & ES6
##### replace()


## Item 152 Mumbling :unicorn:

_**This time no story, no theory. The examples below show you how to write function accum:   
Examples:**_
```
accum("abcd") -> "A-Bb-Ccc-Dddd"
accum("RqaEzty") -> "R-Qq-Aaa-Eeee-Zzzzz-Tttttt-Yyyyyyy"
accum("cwAt") -> "C-Ww-Aaa-Tttt"
```

[Play](https://www.codewars.com/kata/mumbling)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/152_mumbling.js)

##### map()
##### repeat()
##### join()


## Item 161 Find the odd int :dolphin:

_**Given an array, find the int that appears an odd number of times.
There will always be only one integer that appears an odd number of times.**_

[Play](https://www.codewars.com/kata/find-the-odd-int/train/javascript)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/152_find_the_odd.js)

##### filter() 
##### reduce()
##### find()


## Item 162 Duplicate encoder :sunny:

_**The goal of this exercise is to convert a string to a new string where each character in the new string is '(' if that character appears only once in the original string, or ')' if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.  
Examples:  
"din" => "((("  
"recede" => "()()()"  
"Success" => ")())())"  
"(( @" => "))(("**_

[Play](https://www.codewars.com/kata/duplicate-encoder)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/162_duplicate_encoder.js)

[JS indexOf() on MDN :fr:](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/indexOf)
> La méthode indexOf() renvoie l'indice de la première occurence de la valeur cherchée au sein de la chaîne courante (à partir 
> de indexDébut). Elle renvoie -1 si la valeur cherchée n'est pas trouvée.

[JS lastIndexOf() on MDN :fr:](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/String/lastIndexOf)
> La méthode lastIndexOf() renvoie l'indice, dans la chaîne courante, de la dernière occurence de la valeur donnée en 
> argument. Si cette sous-chaîne n'est pas trouvée, la méthode renvoie -1. La recherche s'effectue de la fin vers le début de 
> la chaîne, à partir de indiceDébut.

##### map()
##### replace()


## Item 171 Convert string to camel case :innocent:

_**Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized.  
Examples:**_
```js
toCamelCase("the-stealth-warrior") // returns "theStealthWarrior"
toCamelCase("The_Stealth_Warrior") // returns "TheStealthWarrior"
````

[Play](https://www.codewars.com/kata/convert-string-to-camel-case)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/blob/master/171_convert_string_to_camel_case.js)

##### map(), ES5 & ES6
##### replace()
##### charAt()
##### split() with a regex


## Item 172 Count the smiley faces :smiley:

_**Given an array (arr) as an argument complete the function countSmileys that should return the total number of smiling faces.  
Rules for a smiling face:  
-Each smiley face must contain a valid pair of eyes. Eyes can be marked as : or ;  
-A smiley face can have a nose but it does not have to. Valid characters for a nose are - or ~  
-Every smiling face must have a smiling mouth that should be marked with either ) or D.  
No additional characters are allowed except for those mentioned.  
Valid smiley face examples:  
:) :D ;-D :~)  
Invalid smiley faces:  
;( :> :} :]   
Example cases:**_  
```js
countSmileys([':)', ';(', ';}', ':-D']);       // should return 2;
countSmileys([';D', ':-(', ':-)', ';~)']);     // should return 3;
countSmileys([';]', ':[', ';*', ':$', ';-D']); // should return 1;
```
_**Note: In case of an empty array return 0. You will not be tested with invalid input (input will always be an array). Order of the face (eyes, nose, mouth) elements will always be the same**_  

[Play](https://www.codewars.com/kata/count-the-smiley-faces)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/blob/master/172_count_the_smiley_faces.js)

##### Regex construction ([] instead of () + escape, use of the |, {0, 1} and not \*, add ^ and $)
##### the filter()
##### the reduce()

## Item 181 Are they the "same"? :mag:

_**Given two arrays a and b write a function comp(a, b) (compSame(a, b) in Clojure) that checks whether the two arrays have the "same" elements, with the same multiplicities. "Same" means, here, that the elements in b are the elements in a squared, regardless of the order.
Examples
Valid arrays**_
```js
a = [121, 144, 19, 161, 19, 144, 19, 11]  
b = [121, 14641, 20736, 361, 25921, 361, 20736, 361]
```
_**comp(a, b) returns true because in b 121 is the square of 11, 14641 is the square of 121, 20736 the square of 144, 361 the square of 19, 25921 the square of 161, and so on. It gets obvious if we write b's elements in terms of squares:**_
```js
a = [121, 144, 19, 161, 19, 144, 19, 11] 
b = [11*11, 121*121, 144*144, 19*19, 161*161, 19*19, 144*144, 19*19]
```
_**Invalid arrays
If we change the first number to something else, comp may not return true anymore:**_
```js
a = [121, 144, 19, 161, 19, 144, 19, 11]  
b = [132, 14641, 20736, 361, 25921, 361, 20736, 361]
```
_**comp(a,b) returns false because in b 132 is not the square of any number of a.**_
```js
a = [121, 144, 19, 161, 19, 144, 19, 11]  
b = [121, 14641, 20736, 36100, 25921, 361, 20736, 361]
```
_**comp(a,b) returns false because in b 36100 is not the square of any number of a.  
Remarks  
a or b might be [] (all languages except R, Shell). a or b might be nil or null or None or nothing (except in Haskell, Elixir, C++, Rust, R, Shell).  
If a or b are nil (or null or None), the problem doesn't make sense so return false.  
If a or b are empty the result is evident by itself.**_

[Play](https://www.codewars.com/kata/are-they-the-same)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/edit/master/181_are_they_the_same.js)

##### map(), sort(), toString()


## Item 182 Consecutive strings :point_right: :point_right:

_**You are given an array strarr of strings and an integer k. Your task is to return the first longest string consisting of k consecutive strings taken in the array.  
#Example: longest_consec(["zone", "abigail", "theta", "form", "libe", "zas", "theta", "abigail"], 2) --> "abigailtheta"  
n being the length of the string array, if n = 0 or k > n or k <= 0 return "".**_

[Play](https://www.codewars.com/kata/consecutive-strings)

[Check](https://github.com/codingk8/codeWars_Fundamentals_WCS_Bootcamp/blob/master/182_consecutive_strings.js)

##### To be finished

## Item 191

[Play](https://www.codewars.com/kata/consecutive-strings)

[Check](h


## Item 192

[Play](#)

[Check](#)


## Item 1 10 1

[Play](#)

[Check](#)


## Item 1 10 2 :gift:

[Play](#)

[Check](#)


***

<h2 align="center">And just because we love :alien: don't we?!</h2>
<p align="center"><img src="https://media.giphy.com/media/TNk5NDanFOmv6/giphy.gif" alt="The truth is out there"/></p>
  
***

