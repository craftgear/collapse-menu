collapse-menu
=============

A menu list which collapses its child elements into paper-menu-button when the viewport is smaller than the specified width.

You can simply replace existed core-menu with collapse-menu.

Use the `query` attribute to configure the `collapse-menu` with a CSS breakpoint so it knows when to collapse.

##### Install
```
bower install --save craftgear/collapse-menu
```

##### Example

    <link rel="import" href="./bower_components/collapse-menu/collapse-menu.html">

    <collapse-menu query="max-width: 500px">
        <core-item><a href="#!index">TOP</a></core-item>
        <core-item><a href="#!list">LIST</a></core-item>
        <core-item><a href="#!about">ABOUT</a></core-item>
    </collapse-menu>

## Acknowledgement
This element is heavily inspired by Rob Dodson's [collapse-toolbar](https://github.com/robdodson/collapse-toolbar).


    
