# CSSBattle Results - March 01, 2024

## Date: March 01, 2024

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
  <div class="circle"></div>
  <div class="trapezium-top"></div>
  <div class="trapezium-bottom"></div>
  <div class="trapezium-left"></div>
  <div class="trapezium-right"></div>
</div>
<style>
  body {
    background-color: #2bbbf3;
  }
  .circle {
    position: absolute;
    top: 100px;
    left: 150px;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: #ffffff;
  }
  .trapezium-top {
    position: absolute;
    top: 0px;
    left: 166px;
    width: 68px;
    height: 105px;
    clip-path: polygon(0 0, 100% 0, 63.5% 100%, 36.5% 100%);
    background: #ffffff;
  }
  .trapezium-bottom {
    position: absolute;
    bottom: 0px;
    left: 166px;
    width: 68px;
    height: 105px;
    clip-path: polygon(0 0, 100% 0, 63.5% 100%, 36.5% 100%);
    background: #ffffff;
    transform: rotate(180deg);
  }
  .trapezium-left {
    position: absolute;
    top: 105px;
    left: 0px;
    width: 195px;
    height: 90px;
    clip-path: polygon(0 0, 100% 50%, 100% 50%, 0% 100%);
    background: #ffffff;
  }
  .trapezium-right {
    position: absolute;
    top: 105px;
    right: 0px;
    width: 195px;
    height: 90px;
    clip-path: polygon(0 0, 100% 50%, 100% 50%, 0% 100%);
    background: #ffffff;
    transform: rotate(180deg);
  }
</style>
```
