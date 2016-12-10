---
layout: single
property_name: border-collapse
---

<section id="border-collapse" class="property">
  <header class="property-header">
    {% include section-nav.html property_name="border-collapse" %}
    <h2 class="property-name">
      <a href="{{site.url}}/#border-collapse"><span>#</span>border-collapse</a>
    </h2>
    <div class="property-description">
      <p>用来定义<strong>表格</strong>的边框是否合并。</p>
    </div>
  </header>


    <style type="text/css">.border-collapse table { width: 100%; }.border-collapse td { border-bottom: 4px solid hsl(348, 100%, 61%);border-left: 4px solid #05ffb0;border-right: 4px solid hsl(48, 100%, 67%);border-top: 4px solid hsl(217, 71%, 53%);padding: 0.4em 0.5em; }</style>


    <section class="example">
      <header class="example-header">
        <p class="example-name">
            <code class="example-default" data-tooltip="This is the property's default value">默认</code>


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-collapse: separate;">border-collapse: separate;</code>
        </p>
        <div class="example-description">
          <p>每一个<strong>单元格</strong>都会独立显示各自的边框。</p>
          <p>在这个例子中，每个单元格都设置了一个 <strong>4px</strong> 宽的 <code>border-width</code>。最终的效果就是相邻两个单元格之间的边框宽度是 <strong>8px</strong>。</p>

        </div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-collapse " id="border-collapse-separate"><table><tr><td><strong>Name</strong></td><td><strong>Instrument</strong></td></tr><tr><td>John Lennon</td><td>Rhythm Guitar</td></tr><tr><td>Paul McCartney</td><td>Bass</td></tr><tr><td>George Harrison</td><td>Lead Guitar</td></tr><tr><td>Ringo Starr</td><td>Drums</td></tr></table></div>
        </div>
      </aside>
          <style type="text/css">#border-collapse-separate{ border-collapse:separate;}</style>
        <style type="text/css">#border-collapse-separate table { border-collapse: separate; }</style>
    </section>
    <section class="example">
      <header class="example-header">
        <p class="example-name">


          <code class="example-value" data-tooltip="Click to copy" data-clipboard-text="border-collapse: collapse;">border-collapse: collapse;</code>
        </p>
        <div class="example-description">
          <p>相邻的单元格会将边框<strong>合并</strong>成一个。</p>

          <p markdown="1">**位置靠前**的单元格的边框会*覆盖*位置靠后的单元格的边框。</p>

        </div>
      </header>

      <aside class="example-preview">
        <div class="example-browser"><i></i><i></i><i></i></div>
        <div class="example-output">
          <div class="example-output-div border-collapse " id="border-collapse-collapse"><table><tr><td><strong>Name</strong></td><td><strong>Instrument</strong></td></tr><tr><td>John Lennon</td><td>Rhythm Guitar</td></tr><tr><td>Paul McCartney</td><td>Bass</td></tr><tr><td>George Harrison</td><td>Lead Guitar</td></tr><tr><td>Ringo Starr</td><td>Drums</td></tr></table></div>
        </div>
      </aside>
          <style type="text/css">#border-collapse-collapse{ border-collapse:collapse;}</style>
        <style type="text/css">#border-collapse-collapse table { border-collapse: collapse; }</style>
    </section>

</section>
