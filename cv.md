# Gaponenko Anton
## Junior Frontend developer
*********
## contact information:  
* phone: +7 (928) 361 47-60
* email: anton.gap99@gmail.com
* tg: antonics
* discord: antonics
* Anton.Gaponenko (antongap99)#4429
*********
## About me
I have been studying web development for about a year, and  continue to improve my skills. In order to find a job and further improve soft and hard skills

*********
## skills
* html, css, scss, less
* js, typescript, react, next.js
* redux(redux-toolkit), zustand
* webpack, vite
* jest
* node.js, express.js
* docker

## Code example
```
function firstNonRepeatingLetter(s) {
  const letters = s.split('');
  const result =  letters.find((letter, index, arr) => {
    const array = [...arr].join('').toLowerCase().split('');
    array.splice(index, 1);
    return !array.includes(letter.toLowerCase());
  });

  return result || '';
}
```