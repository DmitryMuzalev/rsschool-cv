# Muzalev Dmitriy

---

## Contacts:

- **Address:** Pushkino, Moscow Oblast, Russia
- **E-mail:** muzalev771@gmail.com
- **Telegram:** [@muzalev771](https://t.me/muzalev771)

## About Me:

I'm 28 and I want to become a front-end developer. I'm diligent.

## Skills:

- **HTML**
- **CSS** (Preprocessor SCSS, BEM methodology)
- **JavaScript** (Fundamentals, Functional Programming, DOM)
- **Git** (remote service GitHub)
- **VSCode**
- **Prepros**
- **Figma**, **Photoshop**, **Zeplin**

## Code example:

**IP Address to Number KATA from CODEWARS:**

> An IPv4 address is a 32-bit number that identifies a device on the internet.
> While computers read and write IP addresses as a 32-bit number, we prefer to read them in dotted-decimal notation, which is basically the number split into 4 chunks of 8 bits, converted to decimal, and delmited by a dot.
> In this kata, you will create the function ipToNum that takes an ip address and converts it to a number, as well as the function numToIp that takes a number and converts it to an IP address string. Input will always be valid.

**My solution:**

```
function ipToNum(ip) {
  return Number.parseInt(
    ip
      .split(".")
      .map((e) => Number(e).toString(2).padStart(8, "0"))
      .join(""),
    2
  );
}

function numToIp(num) {
  return num
    .toString(2)
    .padStart(32, "0")
    .match(/.{1,8}/g)
    .map((e) => Number.parseInt(e, 2))
    .join(".");
}
```

## Education:

Master, Mytischi Branch of Bauman Moscow State Technical University
(Space Faculty, Specialization: Informatics and Computer Engineering)

## Experience:

No

## English:

Currently Level A1
