---
layout: single
property_name: align-content
---

<section id="align-content" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="align-content" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#align-content"><span>#</span>align-content</a>
    </h2>
    <div class="property-description">
      <p>用来定义 flex 容器中每一行的对齐方式。当且仅当设置了 <code>flex-wrap: wrap</code>属性，并且在 flex 容器中存在<strong>多行</strong>的情况下起作用。</p>
    </div>
  </header>

    <style type="text/css">.align-content { background: hsl(0, 0%, 95%);display: flex;flex-wrap: wrap;height: 300px;padding: 0; }</style>


    <style type="text/css">.align-content .square { height: 46px;margin: 2px;width: 30%; }.align-content .square:nth-child(2) { height: 96px; }.align-content .box { height: 150px;left: 0;position: absolute;right: 0;top: 0; }.align-content .box--red:before { content: "First line"; }.align-content .box--green { top: 150px; }.align-content .box--green:before { content: "Second line"; }</style>


    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-content: stretch;">align-content: stretch;</code>
        </p>
<div class="example-description" markdown="1">

每一行将会拉伸以便填充满剩余的空间。

在这个例子中，外部容器的高度是 `300px`。除了第二个容器的高是 `100px` 之外，其他的容器都是 `100px` 高。

- 第一行的高度是 **100px** 高
- 每二行是 **50px** 高
- 剩余的空间是 **150px** 高

剩余的空间被这两行平均分配，于是有：

- 第一行变成了 **175px** 高
- 第二行变成了 **125px** 高

</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-content " id="align-content-stretch"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="box box--red"></div><div class="box box--green"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-content-stretch{ align-content:stretch;}</style>
        <style type="text/css">#align-content-stretch .box--red { height: 175px; }#align-content-stretch .box--green { height: 125px;top: 175px; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-content: flex-start;">align-content: flex-start;</code>
        </p>
<div class="example-description" markdown="1">
每一行只占用它**自身所需**的空间。它们会聚集在 flex 容器侧轴 (cross axis) **开始**的地方。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-content " id="align-content-flex-start"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="box box--red"></div><div class="box box--green"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-content-flex-start{ align-content:flex-start;}</style>
        <style type="text/css">#align-content-flex-start .box--red { height: 100px; }#align-content-flex-start .box--green { height: 50px;top: 100px; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-content: flex-end;">align-content: flex-end;</code>
        </p>
<div class="example-description" markdown="1">
每一行只占用它**自身所需**的空间。它们会聚集在 flex 容器侧轴 (cross axis) **结束**的地方。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-content " id="align-content-flex-end"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="box box--red"></div><div class="box box--green"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-content-flex-end{ align-content:flex-end;}</style>
        <style type="text/css">#align-content-flex-end .box--red { height: 100px;top: 150px; }#align-content-flex-end .box--green { height: 50px;top: 250px; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-content: center;">align-content: center;</code>
        </p>
<div class="example-description" markdown="1">

每一行只占用它**自身所需**的空间。它们会聚集在 flex 容器侧轴 (cross axis) **中间**的地方。

</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-content " id="align-content-center"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="box box--red"></div><div class="box box--green"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-content-center{ align-content:center;}</style>
        <style type="text/css">#align-content-center .box--red { height: 100px;top: 75px; }#align-content-center .box--green { height: 50px;top: 175px; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-content: space-between;">align-content: space-between;</code>
        </p>
<div class="example-description" markdown="1">
每一行只占用它**自身所需**的空间。**剩余空间**会出现在各行之间。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-content " id="align-content-space-between"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="box box--red"></div><div class="box box--green"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-content-space-between{ align-content:space-between;}</style>
        <style type="text/css">#align-content-space-between .box--red { height: 100px;top: 0; }#align-content-space-between .box--green { height: 50px;top: 250px; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="align-content: space-around;">align-content: space-around;</code>
        </p>
<div class="example-description" markdown="1">
每一行只占用它**自身所需**的空间。**剩余空间**会出现在各行之间。**剩余的空间**会平均分布并**环绕**在各行之间，即：在首行之前，两行之间，以及末行之后。

</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div align-content " id="align-content-space-around"><p class="square square--plum">1</p><p class="square square--plum">2</p><p class="square square--plum">3</p><p class="square square--plum">4</p><p class="square square--plum">5</p><div class="box box--red"></div><div class="box box--green"></div></div>
        </div>
      </aside>
          <style type="text/css">#align-content-space-around{ align-content:space-around;}</style>
        <style type="text/css">#align-content-space-around .box--red { height: 100px;top: 38px; }#align-content-space-around .box--green { height: 50px;top: 213px; }</style>
    </section>
</section>
