---
title: "Typography"
---

<div class="pl-pattern">
### Fonts

Font load and fallback order: __Segoe UI, Helvetica Neue, Tahoma, Arial, sans-serif__

#### Font availability

{::nomarkdown}
<dl>
    <dt>Arial</dt>
    <dd>Ships with most operating systems.</dd>
    <dt>Source Sans Pro</dt>
    <dd>Downloadable Google font.</dd>
    <dt>Tahoma, Arial</dt>
    <dd>Ships with most operating systems.</dd>
</dl>
{:/nomarkdown}

&nbsp;

</div>

<div class="pl-pattern">
### Weights

{::nomarkdown}
<div class="pl-preview">
<div style="font-size: 15px">
    <p style="font-weight: 700">700 - Bold: The quick brown fox jumps over the lazy dog</p>
    <p style="font-weight: 400">400 - Regular: The quick brown fox jumps over the lazy dog</p>
</div>
</div>
{:/nomarkdown}

{% highlight html %}
<p style="font-weight: 700">700 - Bold: The quick brown fox jumps over the lazy dog</p>
<p style="font-weight: 400">400 - Regular: The quick brown fox jumps over the lazy dog</p>
{% endhighlight %}

</div>

<div class="pl-pattern">
### Styles

#### Optima
{::nomarkdown}
<div class="pl-preview">
<table class="table table-borderless table-valign" style="width: 550px;">
    <tbody>
        <tr>
            <td>Display 3</td>
            <td><h1 class="display3">Regular 56px</h1></td>
        </tr>
        <tr>
            <td>h1. Display 2</td>
            <td><h1>Regular 40px</h1></td>
        </tr>
        <tr>
            <td>h3. Headline</td>
            <td><h3 class="headline">Semibold 20px</h3></td>
        </tr>
        <tr>
            <td>h4. Title</td>
            <td><h4>Semibold 18px</h4></td>
        </tr>
        <tr>
            <td>h5. Subhead</td>
            <td><h5>Semibold 16px</h5></td>
        </tr>
        <tr>
            <td>h6.</td>
            <td><h6>Semibold 14px</h6></td>
        </tr>
        <tr>
            <td>Body</td>
            <td><div class="body">Regular 13px/14px</div></td>
        </tr>
        <tr>
            <td>Caption</td>
            <td><div class="caption">Regular 12px/13px</div></td>
        </tr>
    </tbody>
</table>
</div>
{:/nomarkdown}

{% highlight html %}
<h1 class="display3">Regular 56px</h1>
<h1>Regular 40px</h1>
<h2>Regular 25px</h2>
<h3>Bold 20px</h3>
<h4>Bold 18px</h4>
<h5>Bold 16px</h5>
<h6>Bold 14px</h6>
<p>Regular 13px/14px</p>
<div class="caption">Regular 12px/13px</div>
{% endhighlight %}

&nbsp;

#### Pairings
{::nomarkdown}
<div class="pl-preview">
<div style="max-width: 650px; line-height: 1.8;">
    <h1>Welcome to the NCBA</h1>
    <h2 class="text-muted normal" style="margin-top: 18px;">You're in the right place.</h2>
    <h6 class="text-muted">July 27, 2020</h6>
    <hr>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur a rutrum est, eget ultricies metus. In in libero purus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aliquam erat volutpat. Phasellus dapibus elementum massa. Proin gravida iaculis metus, rutrum ornare dui pulvinar lacinia. Nulla vel nunc quis nibh ultrices dictum a non ante. Suspendisse ac lacinia arcu, nec pharetra velit.</p>
    <p>Praesent vitae euismod velit. Sed leo nisl, bibendum at enim vel, lobortis vulputate nisl. Suspendisse congue mollis odio, sed tincidunt ligula aliquet sit amet. Nam eu ipsum odio. Vestibulum sed rutrum neque. Cras facilisis id lectus nec eleifend. Proin blandit placerat mauris a venenatis. Donec vel dignissim mauris. Nullam commodo dolor varius orci hendrerit viverra. Donec in ornare nisl, a ultrices nibh. Quisque quis congue eros. Duis vehicula nibh lectus, et convallis erat suscipit in. Sed id aliquet massa. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Cras tempor convallis arcu, ultricies lacinia diam feugiat non.</p>
    <h3>Article Subhead</h3>
    <p>Aenean ultricies dolor lorem, id porttitor est pretium interdum. Nulla dapibus, lorem vitae accumsan sollicitudin, tortor purus sodales eros, tincidunt condimentum tortor ante et nibh. Etiam auctor vehicula diam, nec rhoncus sapien vestibulum in. Praesent vitae aliquam erat, in ullamcorper tortor. Morbi lacinia lacus ac nisl consequat, ut molestie ligula fringilla. Vestibulum dolor erat, cursus eu interdum quis, accumsan nec augue. Suspendisse porta diam et mattis auctor. Pellentesque placerat, massa sit amet euismod ullamcorper, leo sapien ornare augue, a dignissim nibh est eu risus. Sed ut auctor enim, nec dapibus elit. Nunc vitae massa at nibh eleifend commodo non id tortor.</p>
    <h4>Article Subhead 2</h4>
    <p>Cras rhoncus dolor in nulla varius vestibulum. Phasellus facilisis, sem non accumsan eleifend, dui purus interdum eros, id vestibulum augue lectus a ex. 
        <ul class="list-unstyled">
            <li><a href="">Etiam auctor vehicula diam</a></li>
            <li><a href="">Cursus eu interdum quis</a></li>
            <li><a href="">A dignissim nibh est</a></li>
        </ul>
    </p>
    <h3>Article Subhead 2</h3>
    <p>Vestibulum sollicitudin elementum scelerisque. Nullam gravida faucibus magna, in iaculis urna sodales at. Nunc aliquam mi non eros sagittis eleifend. Nullam et accumsan sapien. Vivamus porttitor facilisis risus, et porttitor ex sodales vitae. Nulla vitae feugiat purus. Aenean imperdiet tortor vel augue efficitur eleifend. Nullam vulputate, purus eu sagittis blandit, libero dolor euismod massa, sed semper dui odio eu dolor. Ut ac libero id augue ultrices malesuada.
    <ul class="list-unstyled">
        <li><a href="">Ultrices malesuada</a></li>
    </ul></p>
</div>
</div>
{:/nomarkdown}

{% highlight html %}
<h2>Large display 1 heading</h2>
<h3>A headline</h3>
<p style="margin-bottom: 32px;">One morning, when Gregor Samsa woke from troubled dreams, he found himself transformed in his bed into a horrible vermin. He lay on his armour-like back, and if he lifted his head a little he could see his brown belly, slightly domed and divided by arches into stiff sections.</p>
<h4>Smaller title</h4>
<h5>Subhead</h5>
<p style="margin-bottom: 32px;">One morning, when Gregor Samsa woke from troubled dreams, he found himself transformed in his bed into a horrible vermin. He lay on his armour-like back, and if he lifted his head a little he could see his brown belly, slightly domed and divided by arches into stiff sections.</p>
<h5>Another subhead</h5>
<p style="margin-bottom: 32px;">One morning, when Gregor Samsa woke from troubled dreams, he found himself transformed in his bed into a horrible vermin. He lay on his armour-like back, and if he lifted his head a little he could see his brown belly, slightly domed and divided by arches into stiff sections.</p>
{% endhighlight %}
</div>

<div class="pl-pattern">
### Lists

#### Unordered
{::nomarkdown}
<div class="pl-preview">
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3
        <ul>
            <li>Nested list item 1 </li>
            <li>Nested list item 2 </li>
        </ul>
    </li>
</ul>
</div>
{:/nomarkdown}

{% highlight html %}
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3
        <ul>
            <li>Nested list item 1 </li>
            <li>Nested list item 2 </li>
        </ul>
    </li>
</ul>
{% endhighlight %}

#### Ordered
{::nomarkdown}
<div class="pl-preview">
<ol>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3
        <ol>
            <li>Nested list item 1 </li>
            <li>Nested list item 2 </li>
        </ol>
    </li>
</ol>
</div>
{:/nomarkdown}

{% highlight html %}
<ol>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3
        <ol>
            <li>Nested list item 1 </li>
            <li>Nested list item 2 </li>
        </ol>
    </li>
</ol>
{% endhighlight %}
</div>

<div class="pl-pattern">
### Colors

{::nomarkdown}
<div class="pl-preview">
<p class="text-primary">This is text-primary</p>
<p class="text-warning">This is text-warning</p>
<p class="text-success">This is text-success</p>
<p class="text-danger">This is text-danger</p>
<p class="text-info">This is text-info</p>
<p class="text-muted">This is text-muted</p>
</div>
{:/nomarkdown}

{% highlight html %}
<p class="text-primary">This is text-primary</p>
<p class="text-warning">This is text-warning</p>
<p class="text-success">This is text-success</p>
<p class="text-danger">This is text-danger</p>
<p class="text-info">This is text-info</p>
<p class="text-muted">This is text-muted</p>
{% endhighlight %}

</div>
