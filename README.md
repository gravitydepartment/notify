# GravDept Notify

Simple notifications with useful options.

[![Gravity Department](http://gravitydept.com/_themes/gravdept/img/logo-footer.png)](http://gravitydept.com/)

## Demo

[todo]

## Features

[todo]

## Dependencies

- jQuery

## Usage

[todo]

Include the script in your page:

```html
<script src="path/to/notify.js"></script>
```

Initialize with the options you need:

```javascript
var config = {
    positionX:   'right',  // {string} "right|left"
    positionY:   'bottom', // {string} "top|bottom"
    timeFade:    250,      // {number} milliseconds to fade out
    timeVisible: 5000      // {number} milliseconds the notification is visible
};

notify.init(config);
```

Trigger notifications with options:

```javascript
notify.add({
    title: 'Talk less. Smile more.',
    body: 'No one else was in the room where it happened.',
    persist: true,
    status: 'warn'
});
```
