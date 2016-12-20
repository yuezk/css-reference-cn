---
layout: single
property_name: animation-direction
---

<section id="animation-direction" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-direction" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-direction"><span>#</span>animation-direction</a>
    </h2>
    <div class="property-description">
      <p>用来定义动画的播放方向。</p>

    </div>
      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-direction"></a>
      </div>
  </header>

    <style type="text/css">.animation-direction { animation-duration: 2s;animation-iteration-count: infinite; }</style>

    <style type="text/css">.animation-direction.is-animated { animation-name: fadeAndMove; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-direction: normal;">animation-direction: normal;</code>
        </p>
<div class="example-description" markdown="1">
动画默认**向前**播放。当播放到最后时，会从动画的第一帧重新开始播放。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-direction  square square--plum" id="animation-direction-normal">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-direction-normal{ animation-direction:normal;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-direction: reverse;">animation-direction: reverse;</code>
        </p>
<div class="example-description" markdown="1">
动画从**反方向**开始播放，即：从动画定义的最后一帧开始，到动画的第一帧结束。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-direction  square square--plum" id="animation-direction-reverse">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-direction-reverse{ animation-direction:reverse;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-direction: alternate;">animation-direction: alternate;</code>
        </p>
<div class="example-description" markdown="1">
动画开始的时候**向前**播放，之后开始向**反方向**播放：

- 从第一帧开始播放
- 在最后一帧处播放结束
- 然后，又从最后一帧开始播放
- 之后在第一帧处播放结束
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-direction  square square--plum" id="animation-direction-alternate">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-direction-alternate{ animation-direction:alternate;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-direction: alternate-reverse;">animation-direction: alternate-reverse;</code>
        </p>
<div class="example-description" markdown="1">
动画先向**反方向**播放，然后**向前**播放：

- 从最后一帧开始播放
- 在第一帧处播放结束
- 然后，又从第一帧处开始播放
- 之后在最后一帧处播放结束
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-direction  square square--plum" id="animation-direction-alternate-reverse">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-direction-alternate-reverse{ animation-direction:alternate-reverse;}</style>
    </section>
</section>
