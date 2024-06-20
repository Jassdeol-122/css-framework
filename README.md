# Custom CSS Framework

##Framework Name - BOOTSTRAP

Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS and JS code, and it's designed to be easily integrated into any HTML code.


## Installation

Include the compiled CSS file in your HTML:

```html
<link rel="stylesheet" href="dist/css/styles.css">
```

##Usage

###Buttons
```html
<button class="button">Primary Button</button>
<button class="button secondary">Secondary Button</button>
<button class="button success">Success Button</button>
```
###Forms
```html
<input type="text" class="input" placeholder="Input field">
```
###Tables
```html
<table class="table">
  <thead>
    <tr>
      <th>Header</th>
      <th>Header</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data</td>
      <td>Data</td>
    </tr>
  </tbody>
</table>
```
##Customization

Customize the framework by modifying the variables in src/scss/_variables.scss.


```scss
// Colors
$primary-color: #007bff;
```


