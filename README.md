# Unicode Fonts

A lightweight JavaScript library for transforming text into Unicode-based typographic variants, enabling stylized text output for various scripts and styles.

---

## Installation

```bash
npm install @apcmncs/unicode-fonts
```

---

## Usage

```js
const { toUnicodeVariant } = require("@apcmncs/unicode-fonts");

console.log(toUnicodeVariant("Aphichat Maneechansuk", "bold")); // => 𝐀𝐩𝐡𝐢𝐜𝐡𝐚𝐭 𝐌𝐚𝐧𝐞𝐞𝐜𝐡𝐚𝐧𝐬𝐮𝐤
console.log(toUnicodeVariant("123456789", "bold")); // => 𝟏𝟐𝟑𝟒𝟓𝟔𝟕𝟖𝟗
```
