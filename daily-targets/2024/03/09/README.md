# CSSBattle Results - March 09, 2024

## Date: March 09, 2024

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
  <div class="t b l"></div>
  <div class="t s l"></div>
  <div class="t r l"></div>
</div>
<style>
  body {
    background: #712b2b;
  }
  .t {
    position: absolute;
    width: 80px;
    height: 60px;
    clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
    background: #f79091;
  }
  .l {
    left: 160px;
  }
  .r {
    transform: rotate(180deg);
    bottom: 45px;
  }
  .b {
    transform: scale(2.5);
    top: 90px;
    background: #d04a4c;
  }
  .s {
    top: 45px;
  }
</style>
```
