## Ivan Basalaev
## Contacts
Contact me at:

    - Email: ibasalaev@icloud.com
    - Discord: vxrossa#7225
    - VK: vk.com/1basalaev
---
## Summary
I'm a master's student at the Gubkin National University of Oil and Gas who is planning on studying programming and becoming a front-end developer. Right now my main goal is to learn the basics of programming and front-end programming.

I started learning HTML and CSS in school several years ago and right now I have enough experience to build simple websites with some responsive elements.
My degree didn't specialize in programming languages, however I have experience with MatLab and Python for simple calculations. Right now I'm learning JavaScript and also plan on learning React.

I consider myself a hardworking and punctual student who is extremely interested in web-design and especially web development.


---
## Skills
- HTML/CSS;
- SASS/SCSS;
- Bootstrap 5;
- Git version control;
- Adobe Photoshop, Illustrator;
- JavaScript Basics;
- Sublime Text, **VSCode**, Atom.
---
## Code examples

Square every digit of a number and concatenate them (7 kyu).
For example, if we run 9119 through the function, 811181 will come out, because 92 is 81 and 12 is 1.

[Link to CodeWars](https://www.codewars.com/kata/546e2562b03326a88e000020)

```javascript
function sqConcat (num) {
    return +num.toString().split("").map(x => Math.pow(x,2)).join("");
}
console.log(sqConcat(989);
// 817281
```
A simple function for writing how much coins you have (in russian).
```javascript
function coinFlip(amount) {
    const amountLength = amount.toString().length;
    const amountLast = amount.toString().split('')[amountLength - 1];
    let coinNum = 0;
    if (amountLast === '1') {
        coinNum = 'монета';
    } else if (amountLast === '2' || amountLast === '3' || amountLast === '4') {
        coinNum = 'монеты';
    } else {
        coinNum = 'монет';
    }
    console.log(`У вас ${amount} ${coinNum}`);
}
coinFlip(19);
// У вас 19 монет
coinFlip(21);
// У вас 21 монета
coinFlip(24);
// У вас 24 монеты
```
---
## Work experience

No previous work experience (only internships in Oil companies).

---
## Languages

English: C1/C2 Advanced according to EFSet:
    - Reading at 91%
    - Listening at 96%

I have also passed several international exams by Cambridge English, the last one being "Cambridge FCE". I'm planning on passing Cambridge CAE in the next few years.

