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

### My Experience:

#### Application for searching images using Flickr.

**When building the application I used:**
_Material UI, TypeScript, React, Redux, Redux-Thunk, Axios,
React-Router-Dom, hooks and etc._

**Implemented:**

- division of logic into UI, BLL, DAL;
- saving, deleting and rendering images from LocalStorage;
- tracking user activity (if there is no user activity popup pops up);
- deboucing with a custom hook useDebounce;
- coverage of application reducers with tests;
- pagination of images;
- error processing;
- redirect to the page not found;

[View source code](https://github.com/Oleg-Melnikow/Search_Picture)<br>
[Watch app](https://oleg-melnikow.github.io/Search_Picture)<br>

### Education:

**Belarusian State University of Informatics and Radioelectronics**
Industrial electronics
**JS / Front-End Development the Rolling Scopes School (Issued Sep 2023, Expired Jul 2024)**
[Certificate](https://app.rs.school/certificate/g61paur5)

### Languages:

English: \- Pre-Intermediate (A2)<br>
Russian: \- Native
