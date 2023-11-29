# TODO CSS

If you haven't read `TODO-HTML.md` file, then please go there first so you can prepare some basic structure to work on.

You already did? Perfect! If you have already play around some basic elements inside your `index.html` file, you should see that they are pretty basic, boring and without any style. That's when CSS comes into play. Here you have some basics that you can play around, but you can always do your own reserach and try something new and cool!

#### Targeting elements

To target a specific element you will need a selector.

Selecting whole element:

```css
body {
  font-family: "Sono", sans-serif;
}
```

Selecting class:

```css
.wrapper {
  margin: auto;
}
```

Selecting id:

```css
#logo {
  padding: 0;
}
```

#### Box model

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. ![CSS Box Model](https://www.simplilearn.com/ice9/free_resources_article_thumb/CSS-Box-Model.png)

```css
.wrapper {
  margin: auto;
  padding: 10px;
  border: solid black;
}
```

#### Colors

All modern browsers support the following 140 **[CSS color names](https://www.w3schools.com/cssref/css_colors.php)**

You can use these colors to set different background, font color or border color. If you don't like the name and you want to be more specific, you can use RGB or HEX values.

```css
h1 {
  color: #2800ff;
  backgroudn-color: white;
}
```

#### Display

The display property specifies the display behavior (the type of rengering box) of an element. There are plenty of options for this property, so we recommend to read more about here **[CSS Display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)**

_hint: for our first little page we used display: flex; like this:_

```css
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
```

## Have fun!

These basics should help you to recreate your first website. Remember, if you are stuck or don't know anything, just do your research, google it, read documentations, etc. That's part of the software developer job.
