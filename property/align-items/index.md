---
layout: single
property_name: align-items
---

<section id="align-items" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="align-items" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#align-items"><span>#</span>align-items</a>
    </h2>
<div class="property-description" markdown="1">
用来定义 flex 容器中每一行里面的每一项在**侧轴(cross axis)**方向上的对齐方式。
</div>
  </header>

    <style type="text/css">.align-items { background: hsl(0, 0%, 95%);display: flex;height: 200px;justify-content: center;padding: 0; }</style>

    <style type="text/css">.align-items .square { height: 50px;margin: 0 2px;width: calc(20% - 4px); }.align-items .square:nth-child(2) { height: 100px; }.align-items .square:nth-child(4) { height: 75px; }.align-items .line { left: 2px;position: absolute;right: 2px; }</style>


    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-items: flex-start;">align-items: flex-start;</code>
        </p>
<div class="example-description" markdown="1">
flex 容器的每一项靠**侧轴(cross axis)**的**开始**位置对齐。

默认情况下，**侧轴(cross axis)**是垂直方向的。也就是说 flex 容器的每一项是在**垂直**方向上靠**上**对齐的。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-items " id="align-items-flex-start"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-items-flex-start{ align-items:flex-start;}</style>
        <style type="text/css">#align-items-flex-start .line { top: 0; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-items: flex-end;">align-items: flex-end;</code>
        </p>
<div class="example-description" markdown="1">
flex 容器的每一项靠**侧轴(cross axis)**的**结束**位置对齐。

默认情况下，**侧轴(cross axis)**是垂直方向的。也就是说 flex 容器的每一项是在**垂直**方向上靠**下**对齐的。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-items " id="align-items-flex-end"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-items-flex-end{ align-items:flex-end;}</style>
        <style type="text/css">#align-items-flex-end .line { bottom: 0; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-items: center;">align-items: center;</code>
        </p>
<div class="example-description" markdown="1">
flex 容器的每一项靠**侧轴(cross axis)**的**中间**对齐。

默认情况下，**侧轴(cross axis)**是垂直方向的。也就是说 flex 容器的每一项是在**垂直**方向上**居中**对齐的。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-items " id="align-items-center"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-items-center{ align-items:center;}</style>
        <style type="text/css">#align-items-center .line { top: 50%; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-items: baseline;">align-items: baseline;</code>
        </p>
<div class="example-description" markdown="1">
flex 容器的每一项靠**侧轴(cross axis)**的**基线(baseline)**对齐。

默认情况下，**侧轴(cross axis)**是垂直方向的。也就是说 flex 容器的每一项会按照它所包含文本的**基线(baseline)**对齐，即：每一项的文本**基线(baseline)**是一样的。如右侧示例。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-items " id="align-items-baseline"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-items-baseline{ align-items:baseline;}</style>
        <style type="text/css">#align-items-baseline .line { top: 55px; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-items: stretch;">align-items: stretch;</code>
        </p>
<div class="example-description" markdown="1">
flex 容器的每一项会撑满整个**侧轴(cross axis)**方向

默认情况下，**侧轴(cross axis)**是垂直方向的。也就是说 flex 容器的每一项会填充满整个垂直方向上的空间。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-items " id="align-items-stretch"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="line line--red"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-items-stretch{ align-items:stretch;}</style>
        <style type="text/css">#align-items-stretch .square { height: auto; }#align-items-stretch .square:nth-child(2) { height: auto; }#align-items-stretch .square:nth-child(4) { height: auto; }#align-items-stretch .line { display: none; }</style>
    </section>
</section>
