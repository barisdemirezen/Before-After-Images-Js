<h1>Before After Images JS</h1>
<b>Simple vanilla javascript library to create before after image sliders :star:</b>
<p>Hi welcome to Slider JS. Slider JS is a simple vanilla javascript library that allows to create before after image slider with mouse movements. It is so easy to use!</p>
<h4><a href="https://barisdemirezen.github.io/before-after/">Click this to get a preview.</a></h4>
<h2>How to use</h2>
<h3>:exclamation: Must requirements</h3>
<p>Just import <b>slider.js</b> to your file and then call function <b>slider();</b></p>
<h4><b>:exclamation: Make sure you defined a width and height for every element with "parent" class. Like example below.</b></h4>

```css
.parent {
 width: 40vw;
 height: 30vw;
}
```

<p>Expected HTML schema can be seen below.</p>

```html
<div class="parent">
  <div class="before">
    <img src="...">
  </div>
  <div class="after">
    <img src="...">
  </div>
</div>
```

<h3>Optional parameters</h3>
<h4>limit</h4>
<p>You can add attribute <b>limit</b> to element with <b>parent</b> class.</p>
<p>Limit parameter must be number between 0 - 100 and default value setted as 0. This parameter limits minimum and maximum sliding point. For example code below, limits slider to between width for 20% and 80%</p>

```html
<div class="parent" limit="20">
  <div class="before">
    <img src="...">
  </div>
  <div class="after">
    <img src="...">
  </div>
</div>
```

<h4>start</h4>
<p>You can add attribute <b>start</b> to element with <b>parent</b> class.</p>
<p>Start parameter must be number between 0 - 100 and default value setted as 50. This parameter defines position of sliding point. For example code below, sets slider position to 30%, which shows 30% of before image and 70% of after image.</p>

```html
<div class="parent" start="30">
  <div class="before">
    <img src="...">
  </div>
  <div class="after">
    <img src="...">
  </div>
</div>
```
<h4>You can also combine <b>limit</b> and <b>start<b></h4>
<h4>You can also use try files directly in <b>"Example"</b> folder to get a quickstart</h4>
<h4><a href="https://www.linkedin.com/in/barış-demirezen-655879190/">Follow me on linkedin</a></h4>

![Image of Slider JS](https://i.ibb.co/3pCjcY0/resim-2021-03-06-195744.png)
