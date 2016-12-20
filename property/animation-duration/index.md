---
layout: single
property_name: animation-duration
---

<section id="animation-duration" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-duration" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-duration"><span>#</span>animation-duration</a>
    </h2>
    <div class="property-description">
      <p>用来定义动画的持续时间。</p>

    </div>

      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-duration"></a>
      </div>
  </header>
    <style type="text/css">.animation-duration { animation-iteration-count: infinite; }</style>

    <style type="text/css">.animation-duration.is-animated { animation-name: fadeAndMove; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-duration: 0s;">animation-duration: 0s;</code>
        </p>
<div class="example-description" markdown="1">
默认的值是 **0 秒**：也就是动画默认不会播放。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-duration  square square--plum" id="animation-duration-0s">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-duration-0s{ animation-duration:0s;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-duration: 1.2s;">animation-duration: 1.2s;</code>
        </p>
<div class="example-description" markdown="1">
你可以使用**十进制**的**秒数**作为该属性的值，单位是 `s`。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-duration  square square--plum" id="animation-duration-12s">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-duration-12s{ animation-duration:1.2s;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-duration: 2400ms;">animation-duration: 2400ms;</code>
        </p>
<div class="example-description" markdown="1">
你也可以使用**毫秒**数作为该属性的值，单位是 `ms`。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-duration  square square--plum" id="animation-duration-2400ms">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-duration-2400ms{ animation-duration:2400ms;}</style>
    </section>
</section>
