# Oleg Melnikow

<img width="120" height="120" alt="photo" style="border-radius: 20px;" src="https://avatars.githubusercontent.com/u/14839880?v=4" />

### My contacts:

**Location:** Minsk, Belarus
**Email:** oleg.melnikau@gmail.com<br>
**Linkedin:** [Oleg Melnikov](https://www.linkedin.com/in/melleg)<br>
**GitHub:** [Oleg-Melnikow](https://github.com/Oleg-Melnikow)<br>

### About myself:

I want to Front-end Developer. I got a technical education. I like what l’ve been studying, and it increases my motivation to learn programming more and more. I’m constantly studying by myself using the professional literature. This is a necessity for achieving my goals. I want to professionally develop and improve my skills. I would like to hold on this way and make my dreams come true.

### My Skills:

1. JavaScript, TypeScript;
2. HTML5, CSS3, SCSS;
3. React.

### Code example:

**3 ways to remove duplicates in an Array**

_1. Use Set_

```javascript
let chars = ["A", "B", "A", "C", "B"];
let uniqueChars = [...new Set(chars)];

console.log(uniqueChars);
```

_2. Using the indexOf() and filter() methods_

```javascript
let chars = ["A", "B", "A", "C", "B"];

let dupChars = chars.filter((element, index) => {
  return chars.indexOf(element) !== index;
});

console.log(dupChars);
```

_3. Using the includes() and forEach() methods_

```javascript
let chars = ["A", "B", "A", "C", "B"];

let uniqueChars = [];
chars.forEach((element) => {
  if (!uniqueChars.includes(element)) {
    uniqueChars.push(element);
  }
});

console.log(uniqueChars);
```
