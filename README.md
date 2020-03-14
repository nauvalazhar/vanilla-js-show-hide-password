# Toggle HTML Password Input Semantically
This is a very small library for creating password toggle buttons semantically.

# Usage
It's simple.
1. Download the JS file
2. Import into your markup
```html
<script src="toggle-password.js"></script>
```
3. Write your markup:
```html
<!-- define you input password -->
<input type="password" id="password">

<!-- create the button toggle -->
<button data-toggle="password" data-target="#password">Toggle</button>
```
4. Done

This library will scan all elements in the document that have the `data-toggle="password"` attribute. So you don't need to initiate anything.

**Note:** You can add the `data-class-active` attribute to define a class when the button is active (or input in" text "mode)

For example:
```html
<button data-toggle="password" data-target="#password" data-class-active="is-active">Toggle</button>

<style>
  .is-active {
    background-color: red;
  }
</style>
```

# License
MIT License
