---
layout: single
property_name: animation-play-state
---

<section id="animation-play-state" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-play-state" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-play-state"><span>#</span>animation-play-state</a>
    </h2>
    <div class="property-description">
      <p>用来定义动画是否处于播放状态。</p>
    </div>

      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-play-state"></a>
      </div>
  </header>

    <style type="text/css">.animation-play-state { animation-duration: 2s;animation-iteration-count: infinite; }</style>

    <style type="text/css">.animation-play-state.is-animated { animation-name: fadeAndMove; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-play-state: running;">animation-play-state: running;</code>
        </p>
<div class="example-description" markdown="1">
默认值是 `running`，如果指定了 `animation-duration` 和 `animation-name`，动画就会自动地开始播放。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-play-state  square square--plum" id="animation-play-state-running">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-play-state-running{ animation-play-state:running;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-play-state: paused;">animation-play-state: paused;</code>
        </p>
<div class="example-description" markdown="1">
设置成 `paused` 后，动画会暂定在**第一帧**。

这和没有指定 `animation-duration` 或 `animation-name` 的情况是不一样的。如果动画暂停了，元素会应用动画**第一**帧的样式，而**不是**默认的样式。

在右面这个例子中，方形色块在默认状态下是可见的，但是在动画 `fadeAndMove` 的第一帧中，`opacity` 设置成了 `0`。当动画处于暂停状态时，会「卡」在第一帧，因此元素变得不可见了。

```css
@keyframes fadeAndMove {
  from {
    opacity: 0;
    transform: translateX(0);
  }
  to {
    opacity: 0;
    transform: translateX(100px);
  }
}
```
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-play-state  square square--plum" id="animation-play-state-paused">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-play-state-paused{ animation-play-state:paused;}</style>
    </section>

</section>
