# List.css

  Focused, flexible CSS. Useful for lists, forms, etc.

  ![list.css](http://f.cl.ly/items/2y2n291M0H0W0t3Z2u0C/Screen%20Shot%202012-11-30%20at%2010.41.42%20AM.png)

## Installation

    component install matthewmueller/list.css

## Classes:

* `.list`: initialize the main list
* `.list-prepend`: add icon, text, etc. to the front of a list item
* `.list-append`: add icon, text, etc. to the end of the a list item

You need to place `.list-prepend`, `.list-append` before the list item text/element.

## Basic Example:

```html
<ul class="list">
 <li>
   <i class="list-prepend icon-user"></i>
   <i class="list-append icon-arrow"></i>
   Username: MattMueller
 </li>
</ul>
```

## Form Example:

```html
<ul class="list">
 <form action="/finish">
    <li>
      <i class="list-prepend icon-user"></i>
      <i class="list-append icon-arrow"></i>
      <input type="text" placeholder="username:">
    </li>
 </form>
</ul>
```
