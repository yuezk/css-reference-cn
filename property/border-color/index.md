---
layout: single
property_name: border-color
---

<section id="border-color" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="border-color" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#border-color"><span>#</span>border-color</a>
    </h2>
    <div class="property-description">
      <p>定义元素的边框颜色。</p>
    </div>
  </header>

    <style type="text/css">.border-color { border-style: solid;border-width: 4px; }</style>




    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-color: transparent;">border-color: transparent;</code>
        </p>
        <div class="example-description">
          <p>如果给边框设置了一个 <strong>transparent</strong> 颜色，边框仍然会占用 <code>border-width</code> 定义的<em>空间</em>大小。</p>

        </div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-color " id="border-color-transparent">Hello world</div>
        </div>
      </aside>
          <style type="text/css">#border-color-transparent{ border-color:transparent;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-color: red;">border-color: red;</code>
        </p>
        <div class="example-description">
          <p>你可以使用 <strong><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/color_value">超过 140 种颜色名称</a></strong>。</p>

        </div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-color " id="border-color-red">Hello world</div>
        </div>
      </aside>
          <style type="text/css">#border-color-red{ border-color:red;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-color: #05ffb0;">border-color: #05ffb0;</code>
        </p>
        <div class="example-description">
          <p>你可以使用 <strong>十六进制</strong> 的颜色编码。</p>

        </div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-color " id="border-color-05ffb0">Hello world</div>
        </div>
      </aside>
          <style type="text/css">#border-color-05ffb0{ border-color:#05ffb0;}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-color: rgb(50, 115, 220);">border-color: rgb(50, 115, 220);</code>
        </p>
<div class="example-description" markdown="1">
你可以使用 **rgb()** 的颜色编码格式：

- 第一个参数表示 `红色(red)`
- 第二个参数表示 `绿色(green)`
- 第三个参数表示 `蓝色(blue)`

每个的值的取值范围在 **0** 到 **255** 之间。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-color " id="border-color-rgb50-115-220">Hello world</div>
        </div>
      </aside>
          <style type="text/css">#border-color-rgb50-115-220{ border-color:rgb(50, 115, 220);}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-color: rgba(50, 115, 220, 0.3);">border-color: rgba(50, 115, 220, 0.3);</code>
        </p>
<div class="example-description" markdown="1">
你可以使用**rgba()** 的颜色编码格式：

- 前 3 个值和 `rgb()` 的一致
- 第 4 个值设置的 `alpha` 通道的值，用来定义颜色的不透明度。

alpha 值的取值范围在 **0**(透明) 到 **1**(不透明) 之间。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-color " id="border-color-rgba50-115-220-03">Hello world</div>
        </div>
      </aside>
          <style type="text/css">#border-color-rgba50-115-220-03{ border-color:rgba(50, 115, 220, 0.3);}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-color: hsl(14, 100%, 53%);">border-color: hsl(14, 100%, 53%);</code>
        </p>
<div class="example-description" markdown="1">
你可以使用 **hsl()** 的颜色编码格式：

- 第一个值表示 `色调(hue)`，取值范围在 **0** 到 **359** 之间
- 第二个值表示 `饱和度(saturation)`，取值范围在 **0%** 到 **100%** 之间
- 第三个值表示 `亮度(luminosity)`，取值范围在 **0%** 到 **100%** 之间
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-color " id="border-color-hsl14-100-53">Hello world</div>
        </div>
      </aside>
          <style type="text/css">#border-color-hsl14-100-53{ border-color:hsl(14, 100%, 53%);}</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-color: hsla(14, 100%, 53%, 0.6);">border-color: hsla(14, 100%, 53%, 0.6);</code>
        </p>
<div class="example-description" markdown="1">
你可以使用 **hsla()** 的颜色编码格式：

- 前三个值和 `hue()` 的一致
- 第 4 个值设置的 `alpha` 通道的值，用来定义颜色的不透明度。

alpha 值的取值范围在 **0**(透明) 到 **1**(不透明) 之间。
</div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-color " id="border-color-hsla14-100-53-06">Hello world</div>
        </div>
      </aside>
          <style type="text/css">#border-color-hsla14-100-53-06{ border-color:hsla(14, 100%, 53%, 0.6);}</style>
    </section>
</section>
