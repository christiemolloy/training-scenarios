The split layout is designed to position items horizontally with one item filling the available horizontal space.

In this step we will make a simplified page header where the nav fills the available horizontal space.

1) <strong>Copy code into the `index.html` file.</strong>

Click the `Copy to Editor` button below to add code in the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;header&gt;
  &lt;div&gt;
    Align left.
  &lt;/div&gt;
  &lt;div&gt;
    This element should fill the remaining space between the left and right elements.
  &lt;/div&gt;
  &lt;div&gt;
    Align right.
  &lt;/div&gt;
&lt;/header&gt;
</pre>

2) <strong>Add the split layout class to the parent container.</strong>

Add `pf-l-split` to the page header class, which is the parent container of all the `<div>`s.

<strong>Hint: </strong> `<header class="pf-l-split">`

3) <strong>Add the split item layout class to the children inside of the parent container.</strong>

Add the class `pf-l-split__item` to all of the `<div>`s in the parent container. Remember there are three children.

<strong>Hint: </strong> `<div class="pf-l-split__item">`

4) <strong>Add a class to make the middle child fill the available space.</strong>

Add `pf-m-fill` to the second split item. This will allow the page nav to fill the available horizontal space in the nav.

<strong>Hint: </strong> `<div class="pf-l-split__item pf-m-fill">`