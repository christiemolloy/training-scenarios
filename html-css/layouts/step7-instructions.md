The flex layout is based on the CSS flex properties where the layout determines how a flex item will grow or shrink to fit the space available in its container. The system relies on a default spacer value that is applied to flex items.

In this step we will layout items in a card using flex.

1) <strong>Copy code into the `index.html` file.</strong>

Click the `Copy to Editor` button below to add code in the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;div class=&quot;pf-c-card&quot; style=&quot;width: 450px&quot;&gt; 
  &lt;div class=&quot;pf-c-card__body&quot;&gt;
    &lt;span&gt;
      &lt;h2&gt;PatternFly-Elements&lt;/h2&gt;
      &lt;p&gt;Working repo for PatternFly 4&lt;/p&gt;
    &lt;/span&gt;
    &lt;button class=&quot;pf-c-button pf-m-primary&quot;&gt;
      Primary
    &lt;/button&gt;
  &lt;/div&gt;
  &lt;div class=&quot;pf-c-card__footer&quot;&gt;
    &lt;button class=&quot;pf-c-button pf-m-secondary&quot;&gt;
      Secondary
    &lt;/button&gt;
    &lt;button class=&quot;pf-c-button pf-m-secondary&quot;&gt;
      Secondary
    &lt;/button&gt;
    &lt;button class=&quot;pf-c-button pf-m-secondary&quot;&gt;
      Secondary
    &lt;/button&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

2) <strong>Change the card body to lay out horizontally.</strong>

a) <strong>Set the layout of the card body to use flex.</strong>

Add `pf-l-flex` to `pf-c-card__body`.

b) <strong>Set the direction of the card body to use row.</strong>
  
Add `pf-m-row` to `pf-c-card__body`.

c) <strong>Add space between the text and the button.</strong> 

This can be done by using the modifier `pf-m-justify-content-space-between`.

3) <strong>Change the card footer to lay out the buttons.</strong>

a) <strong>Set the layout of the card footer to be flex.</strong>

Add `pf-l-flex` to the `pf-c-card__footer`.

b) <strong>Add space between the buttons.</strong>

Add `pf-m-justify-content-space-between` to the `pf-c-card__footer`.
