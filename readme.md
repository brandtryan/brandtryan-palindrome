# Phrase object (with palindrome detector)

This is a sample NPM module I created while reading [*Learn Enough JavaScript to Be Dangerous*](https://www.learnenough.com/javascript-tutorial) by Michael Hartl.

The module can be used as follows:

```
$ npm install --global brandtryan-palindrome
$ vim test.js
let Phrase = require("brandtryan-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```