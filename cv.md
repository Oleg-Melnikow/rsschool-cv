# Oleg Melnikow

### My contacts:

**Email:** oleg.melnikau@gmail.com<br>
[Linkedin:](https://www.linkedin.com/in/melleg)<br>
[GitHub:](https://github.com/Oleg-Melnikow)<br>


### About myself:

Hi friends! I’m Front-end Developer. I got a technical education.<br>
I like what l’ve been studying, and it increases my motivation to learn programming more and more. I’m constantly studying by myself using the professional literature. This is a necessity for achieving my goals.<br>
I want to professionally develop and improve my skills. I would like to hold on this way and make my dreams come true. 

### My Skills

1. HTML5, CSS, SCSS, Material UI;
2. JavaScript, TypeScript;
3. React, REST API.


### Code example:

__3 ways to remove duplicates in an Array__

*1. Use Set*

```javascript
let chars = ['A', 'B', 'A', 'C', 'B'];
let uniqueChars = [...new Set(chars)];

console.log(uniqueChars);
```

*2. Using the indexOf() and filter() methods*

```javascript
let chars = ['A', 'B', 'A', 'C', 'B'];

let dupChars = chars.filter((element, index) => {
    return chars.indexOf(element) !== index;
});

console.log(dupChars);
```

*3. Using the includes() and forEach() methods*

```javascript
let chars = ['A', 'B', 'A', 'C', 'B'];

let uniqueChars = [];
chars.forEach((element) => {
    if (!uniqueChars.includes(element)) {
        uniqueChars.push(element);
    }
});

console.log(uniqueChars);
```