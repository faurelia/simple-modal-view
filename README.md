# Simple Modal View

A modal component without using the jQuery library.

## Basic Usage

### Installation

Add the stylesheet and js link in the `<head>` part.
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

### Notes
See `modal.html` for further examples.