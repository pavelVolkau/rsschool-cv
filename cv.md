# **Pavel Volkau**

## **_My Contact Info_**

**Phone:** +375(33) 347 45 99

**E-mail:** lekoo.cwalk@gmail.com

**GitHub:** [pavelVolkau](https://github.com/pavelVolkau)

**Telegram:** [pavelVolkau](http://t.me/pavelVolkau)

**Discord:** Pavel Volkau(@pavelVolkau)

**LinkedIn:** [pavelVolkau](https://www.linkedin.com/in/pavelVolkau/)

---

### **_About myself_**

---

One weekend, I realized that my job is simple and boring (I worked as an electrical engineer). And since during my studies I really liked the lessons related to programming and I was periodically interested in Python, I decided that it was worth trying myself along this path.
The choice fell on the Front-end, because when you study it, you can see what I do and how, and the obvious success motivates me.
I am inquisitive, I love to solve logical/algorithmic problems. I think that my strength is the ability to listen to an alternative point of view and, in the course of a dispute, come to a better solution (even if it is not mine).
I hope one day to get a job in a company where work will bring me pleasure, and communication with colleagues will bring me new interesting knowledge.

---

### **_My skills_**

---

- HTML5
- CSS3 (Preprocessor SASS)
- JavaScript (Fundamentals,Functional Programming,ES6+,DOM, Async, OOP)
- Version control: Git (remote service GitHub)
- Windows OS
- Figma(for web development), Adobe Photoshop(for web development)
- Editors: VSCode

---

### **_Code examples_**

---

_KATA from CODEWARS_

**Details:** The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value.

Note: Your answer should always be 6 characters long, the shorthand with 3 will not work here.

```
function rgb(r, g, b) {
  return [r, g, b]
    .map((e) =>
      e <= 0
        ? '00'
        : e >= 255
        ? 'FF'
        : e.toString(16).length === 1
        ? '0' + e.toString(16).toUpperCase()
        : e.toString(16).toUpperCase()
    )
    .join('')
}
```