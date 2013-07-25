# [Sass CSS3 Mixins! The Cross-Browser CSS3 Sass Library]

By: [Majid Hazari](http://www.majidhazari.ir), [@majidhazari](https://twitter.com/#!/majidhazari)

List of CSS3 Sass Mixins File to be `@imported` and `@included` as you need

The purpose of this library is to facilitate the use of CSS3 on different browsers avoiding HARD TO READ and NEVER
ENDING css files

## Version

v0.2 Beta

## Mixins available:

<table>
 <tr>
   <th>Mixins</th>
   <th>Arguments (with default values)</th>
 </tr>
 
 <tr>
   <td>background-gradient</td>
   <td>Start Color: #3C3C3C, End Color: #999999</td>
 </tr>
 <tr>
   <td>background-size</td>
   <td>Width: 100%, Height: 100%</td>
 </tr>
 <tr>
   <td>border-radius</td>
   <td>Radius: 5px</td>
 </tr>
 <tr>
   <td>border-radius-separate</td>
   <td>Top Left: 5px, Top Left: 5px, Bottom Left: 5px, Bottom Right: 5px</td>
 </tr>
 <tr>
   <td>box</td>
   <td>Orientation: horizontal, Pack: center, Align: center</td>
 </tr>
 <tr>
   <td>box-rgba</td>
   <td>R: 60, G: 3, B: 12, Opacity: 0.23, Color: #3C3C3C</td>
 </tr>
 <tr>
   <td>box-shadow</td>
   <td>X: 2px, Y: 2px, Blur: 5px, Color: rgba(0,0,0,.4)</td>
 </tr>
 <tr>
   <td>box-sizing</td>
   <td>Type: border-box</td>
 </tr>
 <tr>
   <td>columns</td>
   <td>Count: 3, Gap: 10</td>
 </tr>
 <tr>
   <td>double-borders</td>
   <td>Color One: #3C3C3C, Color Two: #999999, Radius: 0</td>
 </tr>
 <tr>
   <td>flex</td>
   <td>Value: 1</td>
 </tr>
 <tr>
   <td>flip</td>
   <td>Value: ScaleX: -1</td>
 </tr>
 <tr>
   <td>font-face</td>
   <td>Value: Font Family: myFont, Eot File Src: myFont.eot, Woff File Src: myFont.woff, Ttf File Src: myFont.ttf</td>
 </tr>
 <tr>
   <td>opacity</td>
   <td>Opacity: 0.5</td>
 </tr>
 <tr>
   <td>outline radius</td>
   <td>Radius: 5px</td>
 </tr>
 <tr>
   <td>resize</td>
   <td>Direction: both</td>
 </tr>
 <tr>
   <td>rotate</td>
   <td>Degree: 0, M11: 0, M12: 0, M21: 0, M22: 0</td>
 </tr>
 <tr>
   <td>text-shadow</td>
   <td>X: 2px, Y: 2px, Blur: 5px, Color: rgba(0,0,0,.4)</td>
 </tr>
 <tr>
   <td>transform</td>
   <td>Parameters: null</td>
 </tr>
 <tr>
   <td>transition</td>
   <td>What: all, Length: 1s, Easing: ease-in-out</td>
 </tr>
 <tr>
   <td>triple-borders</td>
   <td>Color One: #3C3C3C, Color Two: #999999, Color Three: #000000, Radius: 0</td>
 </tr>       
</table>

## Examples and Instructions

```sass
   // Import the mixins
   @import "css3-mixins.scss"

   // Call Mixins
   @include opacity();
   @include border-radius(3px); 
   @include transition(color, .5s, ease-in); 
```

## Changelog

* Initial Release
* Beta Release

## Licence

Copyright &copy; 2013 Majid Hazari
