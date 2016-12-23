---
layout: single
property_name: animation-iteration-count
---

<section id="animation-iteration-count" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-iteration-count" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-iteration-count"><span>#</span>animation-iteration-count</a>
    </h2>
    <div class="property-description">
      <p>用来定义动画的播放次数。</p>
    </div>

      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-iteration-count"></a>
      </div>
  </header>

    <style type="text/css">.animation-iteration-count { animation-duration: 2s; }</style>

    <style type="text/css">.animation-iteration-count.is-animated { animation-name: fadeAndMove; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-iteration-count: 1;">animation-iteration-count: 1;</code>
        </p>
<div class="example-description" markdown="1">
动画只会播放**一次**。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-iteration-count  square square--plum" id="animation-iteration-count-1">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-iteration-count-1{ animation-iteration-count:1;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-iteration-count: 2;">animation-iteration-count: 2;</code>
        </p>
<div class="example-description" markdown="1">
你可以设置一个**整数**值，用来定义动画**具体**的播放次数。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-iteration-count  square square--plum" id="animation-iteration-count-2">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-iteration-count-2{ animation-iteration-count:2;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-iteration-count: infinite;">animation-iteration-count: infinite;</code>
        </p>
<div class="example-description" markdown="1">
通过使用关键词 `infinite`，动画会无限循环播放下去。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-iteration-count  square square--plum" id="animation-iteration-count-infinite">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-iteration-count-infinite{ animation-iteration-count:infinite;}</style>
    </section>

</section>
