# minimit-update
Fork on minimits update-Plugin [project site](http://www.minimit.com/projects/code/minimit-update-plugin)
minimit:[github](https://github.com/minimit/minimit-update), Website [minimit.com](http://www.minimit.com), Twitter [beaver82minimit](http://twitter.com/beaver82minimit)

**Simple plugin to have a fullscreen browser and javascript detection.**

Just put the php settings and the php include as shown in the source code, you can set the language and the browser's versions you want to check.

It has a fixed design where you can change the logo and the colors from the settings. The warning text is translated to English, Spagnish, German, French and Italian.

Usage
-------

``` php
/* general */
$muLang = "en"; // en it es fr de
/* required browser version */
$muIeVersion = 8;
$muFfVersion = 3.6;
$muSafVersion = 4;
$muOprVersion = 11;
$muChrVersion = 18;
/* graphic settings */
$muImage = "logo.png";
$muTextColor = "#484848";
$muInnerColor = "#ffffff";
$muOuterColor = "#e5e7e9";
include("minimit-update.php");
```

Acknowledgements
-------
Copyright © 2013 Riccardo Caroli. Licensed under [MIT license](http://www.opensource.org/licenses/mit-license.php).
