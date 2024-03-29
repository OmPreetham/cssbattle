# CSSBattle Results - March 18, 2024

## Date: March 18, 2024

## Instructions

```html
<!-- OBJECTIVE -->
<!-- Write HTML/CSS in this editor and replicate the given target image in the least code possible. What you write here, renders as it is -->

<!-- SCORING -->
<!-- The score is calculated based on the number of characters you use (this comment included :P) and how close you replicate the image. Read the FAQS (https://cssbattle.dev/faqs) for more info. -->

<!-- IMPORTANT: remove the comments before submitting -->
```

### Screenshots

#### Result Screen

![Result Screen](screenshots/result-screen.png)

#### CSS Photo

![CSS Photo](screenshots/css-image.png)

### HTML Code

```html
<div class="container">
  <div class="trapezium"></div>
  <div class="square"></div>
  <div class="rectangle"></div>
</div>
<style>
  body {
    background-color: #c31c1d;
  }
  .trapezium {
    position: absolute;
    top: 70px;
    left: 80px;
    width: 240px;
    height: 160px;
    background: #660301;
    clip-path: polygon(25% 0, 75% 0%, 100% 100%, 0 100%);
  }
  .square {
    position: absolute;
    top: 150px;
    left: 180px;
    width: 40px;
    height: 40px;
    background-color: #c31c1d;
  }
  .rectangle {
    position: absolute;
    top: 190px;
    left: 140px;
    width: 120px;
    height: 40px;
    background-color: #c31c1d;
  }
</style>
```
