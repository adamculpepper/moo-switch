# Toggle Switchy
A CSS only toggle switch for form input radios (not Bootstrap dependent)

## Preview
<img src="/assets/img/github-preview-toggly-switchy.png">

## Installation

### CSS
```<link rel="stylesheet" href="toggle-switchy.css">```

### HTML
```
<label for="ID_HERE" class="toggle-switchy">
	<input checked type="checkbox" id="ID_HERE">
	<span class="toggle">
		<span class="switch"></span>
	</span>
</label>
```

## Options

| Option | Data Attribute |
| ------ | ------ |
| Rounded | `data-style="rounded"`
| No Text | `data-text="false"`
| Sizes | `data-size="xl"`<br>`data-size="lg"`<br>medium (default)<br>`data-size="sm"`<br>`data-size="xs"`
| Colors | `data-color="red"`<br>`data-color="orange"`<br>`data-color="yellow"`<br>`data-color="green"`<br>`data-color="blue"`<br>`data-color="purple"`<br>`data-color="gray"`
| Labels | `data-label="left"`<br>label on right (default)<br>


#### Todo
* ~~slide animation for the toggle switch~~
* ~~fade the On/Off label in and out when clicked~~
* ~~add disable functionality~~

#### See also [Toggle Radios](https://github.com/adamculpepper/toggle-radios) - A CSS only toggle switch for form input checkboxes (not Bootstrap dependent)

