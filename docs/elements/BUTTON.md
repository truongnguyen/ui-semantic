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
    <i class="right arrow icon"></i>
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

*angular syntax*
```html
<ui-button class="labeled">
  <ui-button>
    <i class="heart icon"></i> Like
  <ui-button>
  <ui-link class="basic labeled">
    2048
  </ui-link>
</ui-button>
```

### Icon
*semantic syntax*
```html
<button class="ui icon button">
  <i class="cloud icon"></i>
</button>
```

*angular syntax*
```html
<ui-button class="icon">
  <i class="cloud icon"></i>
</ui-button>
```

### Labeled Icon
*semantic syntax*
```html
<button class="ui labeled icon button">
  <i class="pause icon"></i>
  Pause
</button>
```

*angular syntax*
```html
<ui-button class="labeled icon">
  <i class="pause icon"></i>
  Pause
</ui-button>
```

### Basic
*semantic syntax*
```html
<button class="ui primary basic button">Primary</button>
```

*angular syntax*
```html
<ui-button class="primary basic">Primary<ui-button>
```

### Circular
*semantic syntax*
```html
<button class="circular ui icon button">
  <i class="icon settings"></i>
</button>
```

*angular syntax*
```html
<ui-buttton class="circular icon">
  <i class="icon settings">
</ui-button>
```

### Groups
#### Buttons
*semantic syntax*
```html
<div class="ui buttons">
  <button class="ui button">One</button>
  <button class="ui button">Two</button>
  <button class="ui button">Three</button>
</div>
```

*angular syntax*
```html
<ui-buttons>
  <ui-button>One</ui-button>
  <ui-button>Two</ui-button>
  <ui-button>Three</ui-button>
</ui-buttons>
```

#### Icon Buttons
*semantic syntax*
```html
<div class="ui icon buttons">
  <button class="ui button"><i class="align left icon"></i></button>
  <button class="ui button"><i class="align center icon"></i></button>
  <button class="ui button"><i class="align right icon"></i></button>
  <button class="ui button"><i class="align justify icon"></i></button>
</div>
```

*angular syntax*
```html
<ui-buttons class="icon">
  <ui-button><i class="align left icon"></ui-button>
  <ui-button><i class="align center icon"></ui-button>
  <ui-button><i class="align right icon"></ui-button>
  <ui-button><i class="align justify icon"></ui-button>
</ui-buttons>
```

### Conditionals
*semantic syntax*
```html
<div class="ui buttons">
  <button class="ui button">Cancel</button>
  <div class="or"></div>
  <button class="ui positive button">Save</button>
</div>
```

*angular syntax*
```html
<ui-buttons>
  <ui-button>Cancel</ui-button>
  <div class="or"></div>
  <ui-button class="positive">Save</ui-button>
</ui-buttons>
```