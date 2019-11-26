The gallery layout is designed so that all of its children are of uniform size, displayed horizontally and wrap responsively.

In this step we will layout cards using the gallery layout class.

1) <strong>Copy code into the `index.html` file.</strong>

Click the `Copy to Editor` button below to add multiple card components in the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;div&gt;
  &lt;div class=&quot;pf-c-card&quot;&gt; 
    &lt;div class=&quot;pf-c-card__body&quot;&gt;
      This is a card.
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;pf-c-card&quot;&gt; 
      &lt;div class=&quot;pf-c-card__body&quot;&gt;
        This is a card.
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;pf-c-card&quot;&gt; 
      &lt;div class=&quot;pf-c-card__body&quot;&gt;
        This is a card.
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;pf-c-card&quot;&gt; 
      &lt;div class=&quot;pf-c-card__body&quot;&gt;
        This is a card.
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;pf-c-card&quot;&gt; 
      &lt;div class=&quot;pf-c-card__body&quot;&gt;
        This is a card.
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;pf-c-card&quot;&gt; 
      &lt;div class=&quot;pf-c-card__body&quot;&gt;
        This is a card.
      &lt;/div&gt;
    &lt;/div&gt;
&lt;/div&gt;
</pre>

2) <strong>Add `pf-l-gallery` to the parent wrapper.</strong>

This will structure any children inside of the gallery into a grid layout where the columns don’t extend beyond 250px in width, and when this happens they add more columns and wrap.

<strong>Hint:</strong> `<div class="pf-l-gallery">`

3) <strong>Add `pf-m-gutter` next to the `pf-l-gallery` class that was added in step 2.</strong>

This will add vertical and horizontal spacing of 24px between the card elements.
