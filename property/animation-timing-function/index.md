---
layout: single
property_name: animation-timing-function
---

<section id="animation-timing-function" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-timing-function" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-timing-function"><span>#</span>animation-timing-function</a>
    </h2>
<div class="property-description" markdown="1">
用来定义动画的**开始值**和**结束值**的计算方式。
</div>

      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-timing-function"></a>
      </div>
  </header>

    <style type="text/css">.animation-timing-function { animation-duration: 3s;animation-fill-mode: forwards; }</style>

    <style type="text/css">.animation-timing-function.is-animated { animation-name: moveRight; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: ease;">animation-timing-function: ease;</code>
        </p>
<div class="example-description" markdown="1">
动画开始时慢，中间部分加速，然后在结束前速度减慢。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-ease">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-ease{ animation-timing-function:ease;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: ease-in;">animation-timing-function: ease-in;</code>
        </p>
<div class="example-description" markdown="1">
动画开始时慢，然后在结束之前逐渐加速。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-ease-in">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-ease-in{ animation-timing-function:ease-in;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: ease-out;">animation-timing-function: ease-out;</code>
        </p>
<div class="example-description" markdown="1">
动画开始时快，然后在结束之前逐渐减速。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-ease-out">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-ease-out{ animation-timing-function:ease-out;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: ease-in-out;">animation-timing-function: ease-in-out;</code>
        </p>
<div class="example-description" markdown="1">
效果和 `ease` 类似，但是更加明显。

动画会快速开始，然后在结束之前逐渐减速。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-ease-in-out">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-ease-in-out{ animation-timing-function:ease-in-out;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: linear;">animation-timing-function: linear;</code>
        </p>
<div class="example-description" markdown="1">
动画以**恒定**的速度匀速运动。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-linear">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-linear{ animation-timing-function:linear;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: step-start;">animation-timing-function: step-start;</code>
        </p>
<div class="example-description" markdown="1">
动画直接跳到了**结束状态**。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-step-start">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-step-start{ animation-timing-function:step-start;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: step-end;">animation-timing-function: step-end;</code>
        </p>
<div class="example-description" markdown="1">
动画开始处于**初始状态**，当动画结束时，直接跳到了**结束状态**。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-step-end">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-step-end{ animation-timing-function:step-end;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-timing-function: steps(4, end);">animation-timing-function: steps(4, end);</code>
        </p>
<div class="example-description" markdown="1">
通过给 `steps()` 函数传入一个**整数**值，你可以定义动画在结束前的具体步数。元素的状态并**不是**逐渐变化的，而是从一个状态直接**跳到**另一个状态。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-timing-function  square square--plum" id="animation-timing-function-steps4-end">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-timing-function-steps4-end{ animation-timing-function:steps(4, end);}</style>
    </section>
</section>
