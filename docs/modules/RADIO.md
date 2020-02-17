## Radio

### Standard
*semantic syntax*
```html
<div class="ui radio checkbox">
  <input type="radio" name="radio" checked="checked">
  <label>Radio choice</label>
</div>
```

*angular syntax*
```html
<ui-radio>Radio choice<ui-radio>
```

### Group
*semantic syntax*
```html
<div class="ui form">
  <div class="grouped fields">
    <label>How often do you use checkboxes?</label>
    <div class="field">
      <div class="ui radio checkbox">
        <input type="radio" name="example2" checked="checked">
        <label>Once a week</label>
      </div>
    </div>
    <div class="field">
      <div class="ui radio checkbox">
        <input type="radio" name="example2">
        <label>2-3 times a week</label>
      </div>
    </div>
  </div>
</div>
```

*angular syntax*
```html
<div class="ui form">
  <div class="grouped fields">
    <label>How often do you use checkboxes?</label>
    <div class="field">
      <ui-radio name="example">Once a week</ui-radio>
    </div>
    <div class="field">
      <ui-radio name="example">2-3 times a week</ui-radio>
    </div>
  </div>
</div>
<ui-form>
```