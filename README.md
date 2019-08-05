# select2-tab-fix

A jquery plugin that fixes the select2 packages tab index problem, where the tab index is broken when focus is set to a select2 input

## Usage Note

All select inputs MUST have a unique id attribute or the tab index wont work correctly

### Install

Install with bower.
```
bower select2-tab-fix
```

### Include

Include these files
```
<script src="bower_components/select2-tab-fix/src/select2-tab-fix.min.js"></script>
```

### Use

When user opens a `select2` input and closes the dropdown, `focus` automatically goes to the next input in current `form`, If current `select2` element has `noAutoMove` attribute then focus dose not move to the next element automatically, so user must hit a `tab` or `shift+tab`.

When `moveToNextElement` event is fired on an input, then focus goes to the next input element in current form.
