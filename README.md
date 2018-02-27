
# SassComponent 
[Live on CodePen.io](https://codepen.io/davidsells/project/editor/DNKKLm)
# Sass Grid Example

This project bootstrapped my investigation of generalizing.  It was the programmatic approach to CSS that was of interest.  The exploration was into programmatic SASS to create a customizable CSS component.

https://css-tricks.com/browser-compatibility-css-grid-layouts-simple-sass-mixins/



# A Bubble Menu

I was flipping through various menu implementations on codepen.io and this one caught my eye.  It had elements that were at least a little interesting: animation, no-javascript and somewhat pleasing to the eye.  

https://codepen.io/VincentCostentin/pen/yDFLJ?q=animated%20menu&order=popularity&depth=everything&show_forks=false



# CSS to SASS

The CSS code is faily standard.  I wanted to implement it in SCSS.   There are some very good tools on line to convert CSS into SCSS code.  I checked-out a few tools and this one did a very good job.  It even extracted constants which is a real bonus.

http://sebastianpontow.de/css2compass/





# General Usage.

containerSize - The Size (square) of the div containing menu

    $containerSize: 600;

Size of the centre button (square)

    $baseButtonSize: 200;

First level flyout buttons size (square)

    $firstLevelButtonSize: 160;

offset of inner circle of First level flyout buttons

    $offset: 20;

Number of First Level Flyout Buttons

    $numberOfMenus: 8;

Offset of the buttons
for instance if there were 4 buttons at 0deg offset (and angleOfCoverage, below, where 360)
the buttons would be at: 0, 90, 180, 270
at 45deg offset they would be at: 45, 135, 225, 315

    $angleOffset: 45deg;

The angle of coverage of the First Level buttons
How far arround the center the FirstLevelButtons are placed
 
    $angleOfCoverage: 360;

Second level flyout buttons size (square)

    $secondLevelButtonSize: 100;

The angle of coverage of the Second Level buttons
 How far arround the center the SecondLevelButtons are placed
 
    $angleOfCoverageSecondLevel: 360;

Number of Second Level Flyout Buttons

    $secondLevelNumberOfMenus: 5;

offset of inner circle of Second level flyout buttons

    $inset_level: 20; // Inset of inner second level ball

inset of of Second level flyout buttons with respect to center ball's circumference

    $first_level_inset: -10;

setting for fonts used

    $font_0: Roboto;
    $font_1: sans-serif;