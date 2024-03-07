# TC Slider
This is a simple pure CSS slider. You will be able to easily create simple and attractive sliders. It is also possible to customize the size and time of the animation. In the example, the default setting is for 3 slides. You can simply add slides by adding a breakpoint to the `@keyframes`.

## Supported browsers
Due to the use of simple CSS codes, different browsers have no problem to displaying it.

## Installation
* Include the CSS stylesheet at the end of `<head>` element:
```html
 <link rel="stylesheet" href="/path/to/style.css">
```
* Put HTML codes in your page:
```html
<div class="tcSlider">
  <div class="slider">
    <a class="slide" href="#">
      <div class="slider_img" style="background-image:url(img/1.jpg)"></div>
      <div class="slider_link">Slide 01 text</div>
    </a>
    <div class="slide">
      <div class="slider_img" style="background-image:url(img/2.jpg)"></div>
      <a class="slider_link" href="#">Slide 02 text</a>
    </div>
    <div class="slide">
      <div class="slider_img" style="background-image:url(img/2.jpg)"></div>
      <a class="slider_link" href="#">Slide 02 text</a>
    </div>
</div>
```

## Settings:
* We use width and aspect ratio to adjust the size of images. You can simply set them in the first block of the CSS file.
```css
:root {
  /* set width */
  --slide-width: 800px;

  /* set aspect ratio (width/height) */
  --slide-aspect: 3;
}
```
* Another setting we have is the timing of animation. You can set this variable in the first block of the css file.
```css
:root {
  /* set full animation time */
  --slide-time: 15s;
}
```
