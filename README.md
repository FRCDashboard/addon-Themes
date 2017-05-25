# FRC Dashboard Themes
This addon adds a select box to choose the theme of your dashboard. You can choose from several premade themes or add your own.

## Installation
1. Copy the contents of `themes.html` to where the comments above the portions of the document say they should go.
2. Copy `themes.js` into the `components` directory of your FRCDashboard system.
3. Link the script from `index.html`, for example:

```html
<script src="components/themes.js"></script>
```

4. Copy all stylesheets in `css` into the `css` directory of your FRCDashboard system.
5. If necessary, change the keys of the NetworkTables values used in `multicamera.js` to the keys your robot code uses.

Alternatively, you could just copy all the JavaScipt code into `ui.js` or other preexisting JavaScript script, but that's a bit tougher to keep organized.

## Examples
### Red Alliance
![Red theme](screenshots/red.png)
### Blue Alliance
![Blue theme](screenshots/blue.png)
### Rainbow
![Rainbow theme](screenshots/rainbow.gif)
### Light
![Light theme](screenshots/light.png)
### Dark
![Dark theme](screenshots/dark.png)
