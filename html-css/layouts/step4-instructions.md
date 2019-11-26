The Stack Layout is designed to position items vertically, with one item filling the available vertical space. 

## Task: Edit the card body so that the text fills the available vertical space.

1) <strong>Copy code into the index.html file.</strong>

Click the <strong>Copy to Editor</strong> button below to add a Card component in the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;div class=&quot;pf-c-card&quot; style=&quot;height: 450px; width: 300px;&quot;&gt;
  &lt;div class=&quot;pf-c-card__body&quot;&gt;
    &lt;h1 class=&quot;pf-c-title pf-m-2xl&quot;&gt;
      This is a title
    &lt;/h1&gt;
    &lt;div&gt;
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    &lt;/div&gt;
    &lt;button class=&quot;pf-c-button pf-m-link pf-m-inline&quot;&gt;
      Footer Link Button
    &lt;/button&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

2) <strong>Add the stack layout class to the parent container.</strong>

Add `pf-l-stack` to `pf-c-card__body`.

<strong>Hint: </strong>`<div class="pf-c-card__body pf-l-stack">`

3) <strong>Add `pf-l-stack__item` to all of the children inside of the container.</strong>

This includes adding the `pf-l-stack__item` class to the `<h1 class="pf-c-title">` , `<div>`  and `<button class="pf-c-button">` containers.

4) <strong>Add a class to make the middle child fill the available space.</strong>

To the middle `<div>` add the class `pf-m-fill` next to the `pf-l-stack__item` class that is already there. This will allow that div to fill the available vertical space.

<strong>Hint: </strong>`<div class="pf-l-stack__item pf-m-fill">`
