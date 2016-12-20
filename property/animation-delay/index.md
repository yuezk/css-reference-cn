---
layout: single
property_name: animation-delay
---

<section id="animation-delay" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-delay" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-delay"><span>#</span>animation-delay</a>
    </h2>
<div class="property-description" markdown="1">
用来定义动画**开始**前的延时时间。该延时时间只会在动画**首次**缓动的时候有效。
</div>
      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-delay"></a>
      </div>
  </header>

    <style type="text/css">.animation-delay { animation-duration: 5s;animation-iteration-count: infinite; }</style>

    <style type="text/css">.animation-delay.is-animated { animation-name: fadeAndMove; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-delay: 0s;">animation-delay: 0s;</code>
        </p>
<div class="example-description" markdown="1">
该动画将会延时 **0 秒**，也就是说，它会立即开始。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-delay  square square--plum" id="animation-delay-0s">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-delay-0s{ animation-delay:0s;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-delay: 1.2s;">animation-delay: 1.2s;</code>
        </p>
<div class="example-description" markdown="1">
你可以使用**十进制**的**秒数**作为该属性的值，单位是 `s`。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-delay  square square--plum" id="animation-delay-12s">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-delay-12s{ animation-delay:1.2s;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-delay: 2400ms;">animation-delay: 2400ms;</code>
        </p>
<div class="example-description" markdown="1">
你也可以使用**毫秒**数作为该属性的值，单位是 `ms`。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-delay  square square--plum" id="animation-delay-2400ms">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-delay-2400ms{ animation-delay:2400ms;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-delay: -500ms;">animation-delay: -500ms;</code>
        </p>
<div class="example-description" markdown="1">
你也可以使用**负数**作为该属性的值：以这个例子为例，该动画会从 `500ms` 处的状态开始播放。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-delay  square square--plum" id="animation-delay--500ms">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-delay--500ms{ animation-delay:-500ms;}</style>
    </section>
</section>
