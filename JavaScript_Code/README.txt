You will need to rename jstest.txt, main.txt and script.txt to have .js extensions

Better Trois-2 is a bizzare website I made for a Literature class. Other groups made dumb posters, so I decided to make better use of my time and make a dumb website. That made it a fun learning experience.

jstest is an answer to a technical interview question I wrote just this morning.
The challenge was to not use conditional logic for anything but input validation. 
It is meant to be executed in the context of Node.js using code like this:

const { doMath } = require('./jstest.js');

console.log(doMath('add', 1, 2, 3)); // 6
console.log(doMath('subtract', 1, 2, 3, 4, 5)); // -13
console.log(doMath('multiply', 1, 2, 3, 4, 5)); // 120
console.log(doMath('divide', 1, 2, 3, 4, 5)); // .008333333333

I have some more experience in JavaScript and web development, but it was a casual internship doing mostly front-end HTML/CSS in React for a small company. Unfortunately I signed an NDA which prohibits me from sharing the code.
