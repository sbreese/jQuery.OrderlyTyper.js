## With OrderlyTyper, text phrases are rotated IN ORDER (and not selected at RAMDOM).  This prevents the phrases from repeating and losing the interest of the visitor.

## Usage
jquery.OrderlyTyper.js can be used one of two ways:

### Type once with typeTo()

If you just want to use the effect once, use `typeTo()`. It can be used as follows:

```javascript
$('h3').typeTo("New Text");
```

This will do a one-time transition.

### Type indefinitely with OrderlyTyper()

Now let's say you want to loop over a set of strings for the typing effect. Easy!

```javascript
$('[data-OrderlyTyper-targets]').typer();
```

That code will start the effect on all elements with the `data-OrderlyTyper-targets` attribute.

You obviously need to supply it with some source data. The `data-OrderlyTyper-targets` attribute can be either a comma-separated string or a piece of JSON.

### Options

There are some options that are available to you as well:

```javascript
// Defaults
{
  highlightSpeed    : 20,
  typeSpeed         : 100,
  clearDelay        : 500,
  typeDelay         : 200,
  clearOnHighlight  : true,
  typerDataAttr     : 'data-typer-targets',
  typerInterval     : 2000
}
```

Set the options individually:

```javascript
$.typer.options.highlightSpeed = 500;
```
## About

jQyery.OrderlyTyper.js is an enhanced version of jquery.typer.js.  jquery.typer.js was originally developed for [LayerVault](http://layervault.com) by [Kelly Sutton](http://kellysutton.com).
