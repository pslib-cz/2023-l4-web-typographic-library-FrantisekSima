[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/zprwltzm)
# Typography CSS library
**Author:** *[František Šíma](https://github.com/FrantisekSima)*
## Desription
Shaman Typography Library (STL) is a free-to-use typography library created as a school project. The main purpose was to create simple an easy-to-use library for simple websites focused on desktop usage.
This libarray contains basic text and heading styles, several types of editable buttons, simple table style and image style.
## Demo site
Link to **[demo](https://pslib-cz.github.io/2023-l4-web-typographic-library-FrantisekSima/)** site for preview.
## Content
1. [Implemantation](#Implementation)
2. [Colors](#Colors)
3. [Headings](#Headings)
4. [Text](#Text)
5. [Font](#Fonts)
6. [Components](#Components)   
       7.1. [Buttons](#Buttons)  
       7.2. [Tables](#Tables)
7. [Usage](#Usage)
## Implementation
Implementation of STL is very easy.
1. Download [Typography.css](css/ShamanTL.css)
2. Copy CSS file into your project
3. Link CSS file by using stylesheet in your HTML.

```html
<link href="ShamanTL.css" rel="stylesheet">
```
## Colors
STL uses a quiet a bit of colors and while creating this library author experimented with lot of them. As result, he decided to have `:root` contain even colors he didn't use in the end.
As a result final appearance is this:

```html
:root {
    --black: #000000;
    --white: #FFFFFF;
    --stl-color: #46ffdd;
    --blue: #1298FF;
    --light-green: #33ff55;
    --dark-green: #004b0c;
    --green: #27b63f;
    --green-visited: #00a01b;
    --blue-active: #03b7c4;]
    --red: #ff4646;
    --table-transparent: #5ccbffad;
}
```
## Headings
In STL you can use heading from `<h1>` to `<h6>`. Font sizes are like this:
* `<h1>`=45px 
* `<h2>`=38px
* `<h3>`=30px
* `<h4>`=25px
* `<h5>`=20px
* `<h6>`=15px


## Text 
Font size in the whole document is set to `19px`. Even though this size is a bit unusual in desktop usage can be practical and even on phone leters are not too big.
Other tags author desided to change are `<code>`, `<a>` and `<b>`.

## Font
STL uses [Montserrat](https://fonts.google.com/specimen/Montserrat) as it's main and only font. However any use of STL can change the font base don their own liking.

## Components

### Buttons
Buttons are one of the main focus of STL. To create a button all you have to do is add `class:"button"` on you tag `<a>`.
```html
<a class="button" href="#">Example</a>
```
You can also add more variant by adding a second class to the `<a>` tag, like this:
```html
 <a class="button button--basic" href="#">Example</a>
```
```html 
<a class="button button--dark" href="#">Example</a>
```
```html 
<a class="button button--rednotif" href="#">Example</a>
```
```html
<a class="button button--subnotif" href="#">Example</a>
```

### Tables

## Usage
...
## Components
### First
### Second
