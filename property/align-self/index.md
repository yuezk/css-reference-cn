---
layout: single
property_name: align-self
---

<section id="align-self" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="align-self" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#align-self"><span>#</span>align-self</a>
    </h2>
<div class="property-description" markdown="1">
和 `align-items` 的作用类似，但是只对 flex 容器中**单个**的项目起作用，而不是对所有的项目起作用。
</div>
  </header>

    <style type="text/css">.align-self { align-items: center;background: hsl(0, 0%, 95%);display: flex;height: 200px;justify-content: center;padding: 0; }</style>


    <style type="text/css">.align-self .square { height: 50px;margin: 0 2px;width: calc(20% - 4px); }.align-self .square:nth-child(2) { background: #05ffb0;color: #310736; }.align-self .square:nth-child(4) { height: 75px; }.align-self .line { left: 2px;position: absolute;right: 2px; }.align-self .line--default { top: 50%; }.align-self .line--default:before { content: "Items"; }.align-self .line--red:before { content: "Self"; }</style>


    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-self: auto;">align-self: auto;</code>
        </p>
<div class="example-description" markdown="1">
这种情况下，flex 容器的项目会使用 `align-items` 设置的值。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-self " id="align-self-auto"><p class="square square--plum">1</p><p class="square target">Target</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--default"></div><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-self-auto{ align-self:auto;}</style>
        <style type="text/css">#align-self-auto .target { align-self: auto; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-self: flex-start;">align-self: flex-start;</code>
        </p>
<div class="example-description" markdown="1">
如果 flex 容器设置了 `align-items: center`，而某一项又设置了 `align-self: flex-start` 的属性，那么，这一项就会在侧轴(cross axis)的开始位置对齐。

默认情况下，这意味着该项会在**垂直方向**靠**上**对齐。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-self " id="align-self-flex-start"><p class="square square--plum">1</p><p class="square target">Target</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--default"></div><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-self-flex-start{ align-self:flex-start;}</style>
        <style type="text/css">#align-self-flex-start .target { align-self: flex-start; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-self: flex-end;">align-self: flex-end;</code>
        </p>
<div class="example-description" markdown="1">
如果 flex 容器设置了 `align-items: center`，而某一项又设置了 `align-self: flex-end` 的属性，那么，这一项就会在侧轴(cross axis)的结束位置对齐。

默认情况下，这意味着该项会在**垂直方向**靠**下**对齐。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-self " id="align-self-flex-end"><p class="square square--plum">1</p><p class="square target">Target</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--default"></div><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-self-flex-end{ align-self:flex-end;}</style>
        <style type="text/css">#align-self-flex-end .line--red { bottom: 0; }#align-self-flex-end .target { align-self: flex-end; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-self: center;">align-self: center;</code>
        </p>
<div class="example-description" markdown="1">
如果 flex 容器设置了 `align-items: flex-start`，而某一项又设置了 `align-self: center` 的属性，那么，这一项就会靠侧轴(cross axis)的中间位置对齐。

默认情况下，这意味着该项会在**垂直方向**上**居中**对齐。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-self " id="align-self-center"><p class="square square--plum">1</p><p class="square target">Target</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--default"></div><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-self-center{ align-self:center;}</style>
        <style type="text/css">#align-self-center{ align-items: flex-start; }</style>
        <style type="text/css">#align-self-center .line--default { top: 0; }#align-self-center .line--red { top: 50%; }#align-self-center .target { align-self: center; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-self: baseline;">align-self: baseline;</code>
        </p>

<div class="example-description" markdown="1">
如果 flex 容器设置了 `align-items: center`，而某一项又设置了 `align-self: baseline` 的属性，那么，这一项就会靠侧轴(cross axis)的基线位置对齐。

默认情况下，这意味着该项会沿着文本的基线对齐。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-self " id="align-self-baseline"><p class="square square--plum">1</p><p class="square target">Target</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--default"></div><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-self-baseline{ align-self:baseline;}</style>
        <style type="text/css">#align-self-baseline .line--default { top: 50%; }#align-self-baseline .line--red { top: 30px; }#align-self-baseline .target { align-self: baseline; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-self: stretch;">align-self: stretch;</code>
        </p>

<div class="example-description" markdown="1">
如果 flex 容器设置了 `align-items: center`，而某一项又设置了 `align-self: stretch` 的属性，那么，这一项就会撑满整个侧轴(cross axis)。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-self " id="align-self-stretch"><p class="square square--plum">1</p><p class="square target">Target</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--default"></div><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-self-stretch{ align-self:stretch;}</style>
        <style type="text/css">#align-self-stretch .line--default { top: 50%; }#align-self-stretch .line--red { display: none; }#align-self-stretch .target { align-self: stretch;height: auto; }</style>
    </section>
</section>
