# Alert

<p class="tiadian-text-lead">Display success, warning and error messages.</p>

## Usage

To apply this component, add the `tiadian-alert` attribute to a block element.

```html
<div tiadian-alert></div>
```

```example
<div tiadian-alert>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
```

***

## Close button

To create a close button and enable its functionality, add the `.tiadian-alert-close` class to a `<button>` or `<a>` element inside the alert box. To apply a close icon, add the `tiadian-close` attribute from the [Close component](close.md).

```html
<div tiadian-alert>
    <a class="tiadian-alert-close" tiadian-close></a>
</div>
```

```example
<div tiadian-alert>
    <a class="tiadian-alert-close" tiadian-close></a>
    <h3>Notice</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
</div>
```

***

## Style modifiers

There are several style modifiers available. Just add one of the following classes to apply a different look.

| Class               | Description                               |
|:--------------------|:------------------------------------------|
| `.tiadian-alert-primary` | Give the message a prominent styling.     |
| `.tiadian-alert-success` | Indicates success or a positive message.  |
| `.tiadian-alert-warning` | Indicates a message containing a warning. |
| `.tiadian-alert-danger`  | Indicates an important or error message.  |

```example
<div class="tiadian-alert-primary" tiadian-alert>
    <a class="tiadian-alert-close" tiadian-close></a>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
</div>

<div class="tiadian-alert-success" tiadian-alert>
    <a class="tiadian-alert-close" tiadian-close></a>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
</div>

<div class="tiadian-alert-warning" tiadian-alert>
    <a class="tiadian-alert-close" tiadian-close></a>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
</div>

<div class="tiadian-alert-danger" tiadian-alert>
    <a class="tiadian-alert-close" tiadian-close></a>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
</div>
```

***

## Component options

Any of these options can be applied to the component attribute. Separate multiple options with a semicolon. [Learn more](javascript.md#component-configuration)

| Option      | Value           | Default           | Description                                              |
|:------------|:----------------|:------------------|:---------------------------------------------------------|
| `animation` | Boolean, String | `true`            | Fade out or use the [Animation component](animation.md). |
| `duration`  | Number          | `150`             | Animation duration in milliseconds.                      |
| `sel-close` | CSS selector    | `.tiadian-alert-close` | The close trigger element.                               |

`animation` is the _Primary_ option and its key may be omitted, if it's the only option in the attribute value.

```html
<span tiadian-toggle=".my-class"></span>
```

***

## JavaScript

Learn more about [JavaScript components](javascript.md#programmatic-use).

### Initialization

```js
TIAdian.alert(element, options);
```

### Events

The following events will be triggered on elements with this component attached:

| Name         | Description                                                              |
|:-------------|:-------------------------------------------------------------------------|
| `beforehide` | Fires before an item is hidden. Can prevent hiding by calling `preventDefault()` on the event. |
| `hide`       | Fires after an item is hidden.                                           |

### Methods

The following methods are available for the component:

#### Close

```js
TIAdian.alert(element).close();
```

Closes and removes the Alert.
