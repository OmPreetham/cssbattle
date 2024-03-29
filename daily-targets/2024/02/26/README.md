# CSSBattle Results - February 26, 2024

## Date: February 26, 2024

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
<div class="square">
  <div class="b-circle">
    <div class="s-circle"></div>
  </div>
  <div class="s-circle"></div>
  <div class="s-circle"></div>
  <div class="s-circle"></div>
  <div class="s-circle"></div>
</div>
<style>
  body {
    background-color: #feff89;
  }
  .square {
    position: absolute;
    top: 50px;
    left: 100px;
    width: 200px;
    height: 200px;
    background: #f59426;
  }
  .b-circle {
    position: absolute;
    top: 50px;
    left: 50px;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: #feff89;
  }
  .s-circle {
    position: absolute;
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #8a0a06;
  }
  .s-circle:nth-of-type(1) {
    top: 35px;
    left: 35px;
  }
  .s-circle:nth-of-type(2) {
    top: 20px;
    left: 20px;
  }
  .s-circle:nth-of-type(3) {
    top: 20px;
    right: 20px;
  }
  .s-circle:nth-of-type(4) {
    bottom: 20px;
    left: 20px;
  }
  .s-circle:nth-of-type(5) {
    bottom: 20px;
    right: 20px;
  }
</style>
```
