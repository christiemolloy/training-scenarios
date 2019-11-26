The level layout is designed to distribute space between children evenly and center them on the x-axis. By default the children are placed horizontally and wrap responsively.

In this step, we will layout a title and button on the horizontal axis.

1) <strong>Copy code into the `index.html` file.</strong>

Click the `Copy to Editor` button below to add a card with a title and button component to the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;div class=&quot;pf-c-card&quot;&gt;
  &lt;div class=&quot;pf-c-card__body&quot;&gt;
    &lt;h1 class=&quot;pf-c-title pf-m-xl&quot;&gt;
      Large title
    &lt;/h1&gt;
    &lt;button class=&quot;pf-c-button pf-m-primary&quot;&gt;
      Click me
    &lt;/button&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

2) <strong>Add the level layout class to the card container.</strong>

Add `pf-l-level` to the parent container of the title and button elements. 

<strong>Hint: </strong>Add it to `pf-c-card__body`.

The title and button should now aligned on the x-axis.
