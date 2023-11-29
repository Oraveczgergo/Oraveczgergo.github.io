# TODO HTML

Your new site is all yours so it doesn't matter if you break it! If you brake something, you can always use keyboard shortcut `Ctrl + Z` to go back one step, so don't be afraid.

In `index.html` you will build structure of your page using different elements. Here are some basic ones which you will need to recreate given page. Don't forget to give your elements proper *class* or *id* so you can then target them in CSS. You can always do your own research and find more interesting elements to play with.

#### Headings

Heading elements allow you to specify that certain parts of your content are headings or subheadings. You can use up to 6 heading levels `<h1 - h6>`:

```html
<h1>Lovely h1 heading</h1>
```

#### Paragraphs

You can use paragraphs tags to add simple text:

```html
<p>Add text here</p>
```

#### Images

Too embed image to your HTML file you can use `<img>` tag:

```html
<img src="images/logo.png" alt="Main logo" class="logo" title="Click me!" />
```

`src=""` is source attribute, where we specified the location of the image. It can be static file or url.

`alt=""` is an alternative attribute which specifies descriptive text for users who cannot see the image.

`title=""` attribute is text that user can see when he hovers over the image with cursor.

#### Lists

Most common list types are ordered and unordered lists.

Unordered lists are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in a `<ul>` element.

Ordered lists are for lists where the order of the items does matter, such as a recipe. These are wrapped in an `<ol>` element.

```html
<ul>
  <li>frontend developers</li>
  <li>backend developers</li>
  <li>fullstack developers</li>
</ul>
```

#### Links

Links are very important — they are what makes the web a web! To add a link, we need to use a simple element `<a>` — "a" being the short form for "anchor".

```html
<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>
```

## Style it!

When you done playing around with all those lovely tags into your HTML you can clearly see, that they doesn't look exactly nice. What you have to do is to give them some styling. Head into `TODO-CSS.md` file to see some basic options of styling. After that, play around in `style.css` to see the results.
