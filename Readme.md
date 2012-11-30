# List.css

  Focused, flexible CSS. Useful for lists, forms, etc.

  ![list.css](http://f.cl.ly/items/2y2n291M0H0W0t3Z2u0C/Screen%20Shot%202012-11-30%20at%2010.41.42%20AM.png)

## Installation

    component install matthewmueller/list.css

## Classes:

* `.list`: initialize the main list
* `.list-prepend`: add icon, text, etc. to the front of a list item
* `.list-append`: add icon, text, etc. to the end of the a list item

## Examples:

### Basic:

```html
<ul class="list">
 <li>
   <i class="list-prepend icon-user"></i>
   Username: MattMueller
 </li>
</ul>
```

### Form:

```html
<ul class="list">
 <form action="/login">
    <li>
      <i class="list-prepend icon-user"></i>
      <i class="list-append icon-valid"></i>
      <input type="text" placeholder="username">
    </li>
    <li>
      <i class="list-prepend icon-user"></i>
      <i class="list-append icon-invalid"></i>
      <input type="text" placeholder="password">
    </li>
 </form>
</ul>
```

### Settings:

```html
<ul class="list">
 <li>
   <a href='/account'>
     <i class="list-prepend icon-account"></i>
     <i class="list-append icon-arrow"></i>
     Account
   </a>
 </li>
</ul>
```

## Known Issues:

* Ellipsis won't work on a link that overflows
* You need to place `.list-prepend`, `.list-append` before the list item text or element.

