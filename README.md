
# saucy-insults 😈

**Generate funny, spicy, and Shakespearean insults for your JavaScript projects!**

---

## What is this?

`saucy-insults` is a fun JavaScript package that gives you clever, funny, and sometimes naughty insults on demand! Whether you want light teasing, spicy comebacks, or classic Shakespeare-style burns, this package has you covered.

---

## Features

- Get random insults of different types  
- Create custom insults targeting anyone you want  
- Choose between three styles:  
  - **light** (fun and mild)  
  - **spicy** (more daring and cheeky)  
  - **shakespearean** (old-school, fancy insults)

---

## Installation

Run this command to install the package:

```bash
npm install saucy-insults
```

---

## How to use

Import the package in your JavaScript code:

```js
const insults = require('saucy-insults');
```

### Get a random insult

```js
console.log(insults.random()); // default is light insult
console.log(insults.random('spicy')); // get a spicy insult
console.log(insults.random('shakespearean')); // get a Shakespearean insult
```

### Generate a custom insult targeting someone

```js
console.log(insults.custom({ target: 'Alex', level: 'spicy' }));
```

### Get multiple insults at once

```js
console.log(insults.list(5, 'light')); // get 5 light insults
```

---

## API Reference

### `random(level)`

- Returns a single random insult.
- `level` (optional) — `"light" | "spicy" | "shakespearean"`. Default: `"light"`

### `custom(options)`

- Returns a custom insult with the target's name included.
- `options` — Object:
  - `target`: *string* — name of the person to insult
  - `level`: *string* — insult style (`"light"`, `"spicy"`, or `"shakespearean"`)

### `list(count, level)`

- Returns an array of insults.
- `count`: *number* — how many insults you want
- `level`: *string* — insult style

---

## Why use this?

- Perfect for prank apps, chatbots, games, or just some harmless fun  
- Easy to integrate with any JavaScript project  
- No external dependencies

---
