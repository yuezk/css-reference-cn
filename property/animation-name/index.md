---
layout: single
property_name: animation-name
---

<section id="animation-name" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="animation-name" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#animation-name"><span>#</span>animation-name</a>
    </h2>
<div class="property-description" markdown="1">
用来定义动画的名称。
</div>

      <div class="property-animation">
        <a class="button property-animation-toggle" data-property-name="animation-name"></a>
      </div>
  </header>

    <style type="text/css">.animation-name { animation-iteration-count: infinite; }</style>

    <style type="text/css">.animation-name.is-animated { animation-duration: 2s; }</style>



    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-name: none;">animation-name: none;</code>
        </p>
<div class="example-description" markdown="1">
如果没有指定动画名称，就不会播放动画。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-name  square square--plum" id="animation-name-none">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-name-none{ animation-name:none;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-name: fadeIn;">animation-name: fadeIn;</code>
        </p>
<div class="example-description" markdown="1">
如果指定了动画名称，那么就会使用该画定义的**关键帧**。

比如，一个名为 `fadeIn` 的动画关键帧定义如下：

```css
@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}
```
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-name  square square--plum" id="animation-name-fadein">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-name-fadein{ animation-name:fadeIn;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="animation-name: moveRight;">animation-name: moveRight;</code>
        </p>
<div class="example-description" markdown="1">
下面是另一个 `moveRight` 的例子：

```css
@keyframes moveRight {
    from {
        transform: translateX(0);
    }
    to {
        transform: translateX(100px);
    }
}
```
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div animation-name  square square--plum" id="animation-name-moveright">Hello<br>World</div>
        </div>
      </aside>
          <style type="text/css">#animation-name-moveright{ animation-name:moveRight;}</style>
    </section>
</section>
