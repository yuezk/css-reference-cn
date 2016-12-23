---
layout: single
property_name: animation-fill-mode
---

<section id="animation-fill-mode" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-fill-mode" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-fill-mode"><span>#</span>animation-fill-mode</a>
    </h2>
<div class="property-description" markdown="1">
  用来定义动画**开始前**和动画**结束后**的行为。用来告诉浏览器是否将动画的样式应用到动画过程**之外**的元素上。
</div>

      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-fill-mode"></a>
      </div>
  </header>
    <style type="text/css">.animation-fill-mode { animation-delay: 1s;animation-duration: 2s;animation-iteration-count: 1;animation-name: kf-animation-fill-mode;animation-play-state: paused; }</style>

    <style type="text/css">.animation-fill-mode.is-animated { animation-play-state: running; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-fill-mode: none;">animation-fill-mode: none;</code>
        </p>
<div class="example-description" markdown="1">
**动画**的样式不会影响元素**默认**的样式，即：在动画开始前，元素的状态就是它默认样式，并且会在动画结束后恢复成默认的样式。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-fill-mode  square square--pink" id="animation-fill-mode-none">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-fill-mode-none{ animation-fill-mode:none;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-fill-mode: forwards;">animation-fill-mode: forwards;</code>
        </p>
<div class="example-description" markdown="1">
在动画**结束后**，元素的会应用动画中最后一帧的样式。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-fill-mode  square square--pink" id="animation-fill-mode-forwards">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-fill-mode-forwards{ animation-fill-mode:forwards;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-fill-mode: backwards;">animation-fill-mode: backwards;</code>
        </p>
<div class="example-description" markdown="1">
在动画**开始前**，元素会应用动画中第一帧的样式。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-fill-mode  square square--pink" id="animation-fill-mode-backwards">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-fill-mode-backwards{ animation-fill-mode:backwards;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-fill-mode: both;">animation-fill-mode: both;</code>
        </p>
<div class="example-description" markdown="1">
以上两种方式的综合，在动画**开始前**会应用第一帧的样式，在动画**结束后**，会应用最后一帧的样式。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-fill-mode  square square--pink" id="animation-fill-mode-both">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-fill-mode-both{ animation-fill-mode:both;}</style>
    </section>
</section>
