# <img src="https://cloud.githubusercontent.com/assets/7833470/10423298/ea833a68-7079-11e5-84f8-0a925ab96893.png" width="60"> Letter Frequency Counter

<img src="https://cloud.githubusercontent.com/assets/1329385/10774272/66b03ef2-7cbd-11e5-8966-a045ef653a22.gif" alt="These may be hard"></a>

## Instructions

Write a function that counts the frequency of letters in a string.

For example, given the word "apple", `letterCount("apple")` should return:

``` javascript
{
  a: 1,
  p: 2,
  l: 1,
  e: 1
}
```

#### Additional Requirements

* Make sure that lower case letters and upper case letters count for the same character.
* Also, ignore spaces and punctuation.

#### Bonuses
* Utilize `filter`, `map` and `reduce` in your solution.
* Create a second function `wordCount` that counts the frequency of words in a paragraph (a string).
* Try out <a href="http://www.codewars.com/kata/character-frequency-1/javascript" target="_blank">this CodeWars challenge</a>.

## Setup
Clone this repo. No need to fork it!

``` bash
cd letter-count # navigate into the project folder
```

#### Checking Your Code: Using "Driver Code"
To manually check your code, you can run:

```bash
# make sure you are inside the letter-count folder
node index.js # write your "Driver Code" in here
```

#### Checking Your Code: Using the Chrome Javascript Console
Alternatively, you can play with your code in the Chrome Javascript Console:

``` bash
# make sure you are inside the letter-count folder
open index.html
```

#### Checking Your Code: Using Jasmine Tests
If you'd like to try using the tests, you need to first install the Jasmine test suite.

``` bash
# make sure you are inside the letter-count folder
npm install # install project dependencies like Jasmine
```

If everything goes well, you should be able to run the Jasmine tests now by typing:

```bash
# make sure you are inside the letter-count folder
npm test
```

<!-- INSTRUCTORS NOTES

{ prerequisites: [ 'forEach', 'in operator', 'hasOwnProperty'],
  topics: ['JS', 'iterators']
}

-->
