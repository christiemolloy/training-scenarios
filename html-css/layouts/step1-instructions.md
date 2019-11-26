The bullseye layout is designed to center a child element within its parent on the horizontal and vertical axes.

In this step we will center the modal component inside of the page.

1) <strong>Copy code into the `index.html` file.</strong>

Click the `Copy to Editor` button below to add a Modal box component in the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;div class=&quot;pf-c-backdrop&quot;&gt;
  &lt;div class=&quot;pf-c-modal-box&quot;&gt;
    &lt;div class=&quot;pf-c-modal-box__body&quot;&gt;
      This is a PatternFly Modal
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

2) <strong>Add the bullseye layout class to the parent container of the modal.</strong>

Add `pf-l-bullseye` to the backdrop container with the class `pf-c-backdrop`.

<strong>Hint: </strong>The modal should be centered in the div on the x and y axes.
