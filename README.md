# Archetype-c-spacers[![Build Status](https://secure.travis-ci.org/Archetype-CSS/Archetype-c-spacers.png?branch=master)](http://travis-ci.org/Archetype-CSS/Archetype-c-spacers) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

Archetype spacer components for applying uniform paddings and margins
system wide.

## Installation
  * [Bower](http://bower.io): `bower install Archetype-c-spacers`
  * Git: `git clone https://github.com/Archetype-CSS/Archetype-test.git`

## Use
  * `@extend %vertMargined;` - Vertically Separated - Adds top and bottom margins to container
  * `@extend %vertPadded;` - Vertically Padded - Adds top and bottom padding to container
  * `@extend %topMargined;` - Top margined - Adds top margin to container
  * `@extend %topPadded;` - Top Padded - Adds top padding to container
  * `@extend %bottomMargined;` - Bottom margined - Adds bottom margin to container
  * `@extend %bottomPadded;` - Bottom Padded - Adds bottom padding to container
  * `@extend %marginedContainer;` - Margined Container - Adds standard padding unit as side margins
  * `@extend %paddedContainer;` - Padded Container - Adds standard padding unit as side padding
  * `@extend %extraPaddedContainer;` - Extra Padded Container - Adds an extra padding unit as side padding
  * `@extend %fullBleed;` - Full Bleed - allows nested children to bleed to
    edge of parent by applying a negative padding in the same amount
  * `@extend %halfBleed;` - Half Bleed - allows nested children to bleed to edge of parent by applying a negative padding in the same amount
  * `@extend %bleedContainer;` - Bleed Container - allows nested children to
    bleed to edge of parent by applying a negative padding in the same amount
  * `@extend %extraBleedContainer;` - Extra Bleed Container - allows nested
    children to bleed to edge of parent by applying a negative padding in the
    same amount

## Run the Test Locally

```bash
git clone https://github.com/Archetype-CSS/c-spacers.git
cd c-spacers
npm install
grunt
```

### Browser Suport
  * Chrome (latest)
  * Firefox (4+)
  * Opera (latest)
  * Safari (5+)
  * Internet Explorer (8+)

#### License
[MIT](/LICENSE.md)

