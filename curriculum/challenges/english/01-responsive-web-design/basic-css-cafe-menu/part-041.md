---
id: 5f3cade9993019e26313fa8e
title: Part 41
challengeType: 0
isHidden: true
---

## Description
<section id='description'>

Now that you know it works, change the other `article` elements so that the `p` elements are on the same line with no space between them.  You also need to apply the applicable styles `flavor` and `price` to the corresponding `p` elements.

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Test 1
    testString: ''

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Camper Cafe Menu</title>
    <link href="styles.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div class="menu">
      <header>
        <h1>CAMPER CAFE</h1>
        <p>Est. 2020</p>
      </header>
      <main>
        <section>
          <h2>Coffees</h2>
          <article class="item">
            <p class="flavor">French Vanilla</p><p class="price">3.00</p>
          </article>
          --fcc-editable-region--
          <article class="item">
            <p>Carmel Macchiato</p>
            <p>3.75</p>
          </article>
          <article class="item">
            <p>Pumpkin Spice</p>
            <p>3.50</p>
          </article>
          <article class="item">
            <p>Hazelnut</p>
            <p>4.00</p>
          </article>
          <article class="item">
            <p>Mocha</p>
            <p>4.50</p>
          </article>
          --fcc-editable-region--
        </section>
      </main>
    </div>
  </body>
<html>
```

</div>

<div id='css-seed'>

```css
body {
  background-image: url(https://tinyurl.com/coffee-beans-fcc);
}

h1, h2, p {
  text-align: center;
}

.menu {
  width: 80%;
  background-color: burlywood;
  margin-left: auto;
  margin-right: auto;
}

.item p {
  display: inline-block;
}

.flavor {
  text-align: left;
  width: 50%;
}

.price {
  text-align: right;
  width: 50%;
}
```

</div>

</section>
