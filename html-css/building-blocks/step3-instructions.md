In PatternFly, layouts allow for organizing and grouping elements. There are seven different layouts in PatternFly, but in this module we will cover just one. You can explore our "layout" module which does a deep dive into layouts.

Let's add a bullseye layout class to the html markup to demonstrate the power of using PatternFly's layout classes.

1) <strong>Copy code into the `index.html` file.</strong>

Click the `Copy to Editor` button below to add html for a card component to the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;div&gt;
  &lt;div class=&quot;pf-c-card&quot;&gt;
    &lt;div class=&quot;pf-c-card__header pf-c-title pf-m-md&quot;&gt;
      Header
    &lt;/div&gt;
    &lt;div class=&quot;pf-c-card__body&quot;&gt;
      Body
    &lt;/div&gt;
    &lt;div class=&quot;pf-c-card__footer&quot;&gt;
      Footer
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

2) <strong>Add the bullseye layout class to the card.</strong>

This will position the card to be centered horizontally and vertically on the page.

Find the outer `<div>` wrapper on Line 1 and add the class `pf-l-bullseye`.

<strong>Hint: </strong>`<div class="pf-l-bullseye">`

Once the browser reloads, you should see that the card is now centered in the middle of the page!

<strong>Note: </strong>It’s important to follow the documentation for layouts because it will demonstrate where to add the layout class. The documentation for bullseye is [here](https://www.patternfly.org/v4/documentation/core/layouts/bullseye). In the documentation it specifies that you should add the class `pf-l-bullseye` to the parent container of its child.
