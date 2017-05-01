# Fabricator Forms and Buttons Styling

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

## Installing

With Fabricator and NPM, simply require this library into your project and restart the Fabricator Grunt build process.

`npm install fabcss.lists --save`

If you are not using Fabricator, you will need to include into your Less build `src/FABCSS.lists.les`.

## Usage

Variables available in this file you can override:

```
@listBulletPosition: outside; // inside or outside
@listColor: false;
@listLineHeight: false;
@listMarginBottom: false;
@listMarginLeft: 20px; // false to disable
@liMarginBottom: 2px; // false to disable
@nestedListMarginBottom: 20px;
@nestedListMarginLeft: 20px;
@listBulletStyle: disc; // disc, circle, square, etc

@dlMarginBottom: 20px;
@dtColor: lighten(#000, 35%);
@dtFont: false;
@dtFontSize: 20px;
@dtMarginBottom: 2px;
@ddColor: lighten(#000, 65%);
@ddFont: false;
@ddFontSize: false;
@ddMarginBottom: 10px;
```
