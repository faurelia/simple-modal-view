# Simple Modal View

A modal component without using the jQuery library.

## Basic Usage

### Installation

Include the CSS and JS files.
```html
<link href="modal.css" rel="stylesheet"/>
<script type="application/javascript" src="modal.js"></script>
```

### Add the Trigger

```html
<button data-target="modal_dialog_ID" data-toggle="modal">Launch modal</button>
```

### Create the Modal

```html
<div id="modal_dialog_ID" class="modal">
    <div class="modal-window">
        <span class="close" data-dismiss="modal">&times;</span>
        ...
    </div>
</div>
```

### Demo
See [modal.html](https://faurelia.github.io/simple-modal-view/modal.html) for examples.
