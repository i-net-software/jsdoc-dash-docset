# JSDoc Dash Template

This is a copy of the original default JSDoc 3 template (http://github.com/jsdoc3/jsdoc). When applied, it genereates:

  1. the JSDoc HTML
  2. a JSON file containing the structure

the output can then be used with the javadoc2DashPlugin (see jsdoc.gradle) to create a JSDoc Dash Docset (https://kapeli.com/docsets).

## Example build.gradle



# JSDoc Default Template README

The default template for JSDoc 3 uses: [the Taffy Database library](http://taffydb.com/) and the [Underscore Template library](http://documentcloud.github.com/underscore/#template).

## Generating Typeface Fonts

The default template uses the [OpenSans](https://www.google.com/fonts/specimen/Open+Sans) typeface. The font files can be regenerated as follows:

1. Open the [OpenSans page at Font Squirrel](<http://www.fontsquirrel.com/fonts/open-sans>).
2. Click on the 'Webfont Kit' tab.
3. Either leave the subset drop-down as 'Western Latin (Default)', or, if we decide we need more glyphs, than change it to 'No Subsetting'.
4. Click the 'DOWNLOAD @FONT-FACE KIT' button.
5. For each typeface variant we plan to use, copy the 'eot', 'svg' and 'woff' files into the 'templates/default/static/fonts' directory.
