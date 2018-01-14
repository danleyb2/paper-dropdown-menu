[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/PolymerElements/paper-dropdown-menu)
[![Build status](https://travis-ci.org/PolymerElements/paper-dropdown-menu.svg?branch=master)](https://travis-ci.org/PolymerElements/paper-dropdown-menu)

## &lt;paper-dropdown-menu-aligned&gt;

Material design: [Dropdown menus](https://www.google.com/design/spec/components/buttons.html#buttons-dropdown-buttons)

> **This has the difference of the dropdown taking the same width as the trigger and positioned below so the trigger
    is always visible**
    
### paper-dropdown-menu
 ![screenshot paper-dropdown-menu](https://i.imgur.com/98LK4xD.png) [![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdanleyb2%2Fpaper-dropdown-menu-aligned.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdanleyb2%2Fpaper-dropdown-menu-aligned?ref=badge_shield)

 
### paper-dropdown-menu-aligned
 ![screenshot paper-dropdown-menu-aligned](https://i.imgur.com/VCwJVee.png)    

    
    
`paper-dropdown-menu-aligned` is similar to a native browser select element.
`paper-dropdown-menu-aligned` works with selectable content.

<!---

```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-dropdown-menu-aligned.html">
    <link rel="import" href="../paper-item/paper-item.html">
    <link rel="import" href="../paper-listbox/paper-listbox.html">
    <link rel="import" href="../iron-demo-helpers/demo-pages-shared-styles.html">
    <style is="custom-style" include="demo-pages-shared-styles">
      paper-dropdown-menu-aligned, paper-listbox {
        width: 250px;
      }
      paper-dropdown-menu-aligned {
        height: 200px;
        margin: auto;
        display: block;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-dropdown-menu-aligned label="Dinosaurs">
  <paper-listbox slot="dropdown-content" selected="1">
    <paper-item>allosaurus</paper-item>
    <paper-item>brontosaurus</paper-item>
    <paper-item>carcharodontosaurus</paper-item>
    <paper-item>diplodocus</paper-item>
  </paper-listbox>
</paper-dropdown-menu-aligned>
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdanleyb2%2Fpaper-dropdown-menu-aligned.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdanleyb2%2Fpaper-dropdown-menu-aligned?ref=badge_large)