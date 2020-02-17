## Button

### Standard

*semantic syntax*
```html
<button class="ui button">Button</button>
```

*angular syntax*
```html
<ui-button>Button</ui-button>
```

### Emphasis
*semantic syntax*
```html
<button class="ui primary button">Primary</button>
```

*angular syntax*
```html
<ui-button class="primary">Primary</ui-button>
```

### Animated
*semantic syntax*
```html
<div class="ui animated button">
  <div class="visible content">Next</div>
  <div class="hidden content">
    <i class="right arrow icon"></i>
  </div>
</div>
```

*angular syntax*
```html
<ui-button class="animated">
  <div class="visible content">Next</div>
  <div class="hidden content">
    <ui-icon class="right arrow"></ui-icon>
  </div>
</ui-button>
```

### Labeled
*semantic syntax*
```html
<div class="ui labeled button">
  <div class="ui button">
    <i class="heart icon"></i> Like
  </div>
  <a class="ui basic label">
    2,048
  </a>
</div>
```

```html
<ui-button class="labeled">
  <ui-button>
    <ui-icon class="heart"></ui-icon> Like
  <ui-button>
  <ui-link class="basic labeled">
    2048
  </ui-link>
</ui-button>
```