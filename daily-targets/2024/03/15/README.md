# CSSBattle Results - March 15, 2024

## Date: March 15, 2024

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
<div>
  <div class="trapezium"></div>
  <div class="oval-top"></div>
  <div class="oval-bottom"></div>
</div>
<style>
  body {
    background-color: #ffffcd;
  }
  .trapezium {
    position: absolute;
    top: 50px;
    left: 120px;
    width: 160px;
    height: 160px;
    clip-path: polygon(28.5% 0, 71.5% 0%, 100% 100%, 0 100%);
    background: #e78320;
  }
  .oval-top {
    position: absolute;
    top: 210px;
    left: 100px;
    width: 200px;
    height: 20px;
    border-radius: 75px;
    background: #edaf38;
  }
  .oval-bottom {
    position: absolute;
    top: 230px;
    left: 80px;
    width: 240px;
    height: 20px;
    border-radius: 75px;
    background: #f1d31d;
  }
</style>
```
