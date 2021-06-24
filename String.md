# STRING PRACTICE (15ข้อ)

## PartA-พื้นฐานการประกาศตัวแปรและกำหนดค่า (Declaration and Initialization)
[1.Declare String Variables](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/declare-string-variables)
```js
// Finish and Paste your solution here

var myFirstName = "Sorawee";
var myLastName = "Jareya";
```


[2.Escaping Literal Quotes in StringsPassed](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/escaping-literal-quotes-in-strings)
```js
// Finish and Paste your solution here
var myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line

```

[3.Quoting Strings with Single Quotes](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/quoting-strings-with-single-quotes)
```js
// Finish and Paste your solution here

var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

[4.Escape Sequences in Strings](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/escape-sequences-in-strings)
```js
// Finish and Paste your solution here
var myStr = "FirstLine\n\t\\\SecondLine\nThirdLine"; // Change this line

```

## PartB-การเชื่อมข้อความ( String Concatenate )

[1.Concatenating Strings with Plus Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/concatenating-strings-with-plus-operator)
```js
// Finish and Paste your solution here
var myStr = "This is the start." + " This is the end."; // Change this line

```


[2.Concatenating Strings with the Plus Equals Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/concatenating-strings-with-the-plus-equals-operator)
```js
// Finish and Paste your solution here
var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";

```


[3.Constructing Strings with Variables](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/constructing-strings-with-variables)
```js
// Finish and Paste your solution here
var myName = "Sorawee";
var myStr = "My name is " + myName + "and I am well";

```
[4.Appending Variables to Strings](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/appending-variables-to-strings)
```js
// Finish and Paste your solution here
var someAdjective = "awesome";
var myStr = "Learning to code is ";
myStr += someAdjective;

```

## PartC-การเข้าถึงและแก้ไขแต่ละตัวอักษร( Access and Mutate )

[1.Find the Length of a StringPassed](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/find-the-length-of-a-string)
```js
// Finish and Paste your solution here
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line

lastNameLength = lastName.length;

```

[2.Use Bracket Notation to Find the First Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-first-character-in-a-string)
```js
// Finish and Paste your solution here
var firstLetterOfLastName = "";
var lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0]; // Change this line
```

[3.Use Bracket Notation to Find the Nth Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-nth-character-in-a-string)
```js
// Finish and Paste your solution here

var lastName = "Lovelace";

// Only change code below this line
var thirdLetterOfLastName = lastName[2]; // Change this line
```
[4.Use Bracket Notation to Find the Last Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-last-character-in-a-string)
```js
// Finish and Paste your solution here
var lastName = "Lovelace";

// Only change code below this line
var lastLetterOfLastName = lastName[lastName.length -1]; // Change this line

```
[5.Use Bracket Notation to Find the Nth-to-Last Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-nth-to-last-character-in-a-string)
```js
// Finish and Paste your solution here
var lastName = "Lovelace";

// Only change code below this line
var secondToLastLetterOfLastName = lastName[lastName.length - 2]; // Change this line

```

[6.Understand String Immutability](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/understand-string-immutability)
```js
// Finish and Paste your solution here
var myStr = "Jello World";

// Only change code below this line
myStr = "Hello World"; // Change this line
// Only change code above this line

```
## UseCase
[1.Word Blanks](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/word-blanks)

```js
// Finish and Paste your solution here

var myNoun = "dog";
var myAdjective = "big";
var myVerb = "ran";
var myAdverb = "quickly";

// Only change code below this line
var wordBlanks = "I like " + myAdjective + " animals like " + myNoun + " who " + myVerb + " to me " + myAdverb + " and lick me in the face"; // Change this line
// Only change code above this line

```
