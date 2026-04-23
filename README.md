# tailwind-css-instagram-filters
A Tailwind CSS plugin, that adds 44 Instagram like filter utility classes.

## Installation

`npm install tailwind-css-instagram-filters`

In your Tailwind CSS stlye.css:

```CSS
@import "./path/to/node_modules/tailwind-css-instagram-filters/tailwind-css-instagram-filters.css";
```

## Usage

```HTML
<img src="some.jpg" alt="Description" class="filter-1977">
```

## Caution

This plugin uses pseudo elements (::before and ::after) in order to add colored overlays to the elements you apply the filters to.
This is necessary to achieve the desired effect, but it also means that if you apply these filters to elements that already use pseudo elements for styling, you may encounter unexpected results or conflicts in the styling.
To avoid this, it's recommended to use these filters on elements that do not have existing pseudo element styles, or to carefully manage the CSS to ensure that the pseudo elements do not interfere with each other.

Always test your styles thoroughly when using these filters in combination with other CSS that utilizes pseudo elements!

## List of filters

- 1977
- Aden
- Amaro
- Ashby
- Brannan
- Brooklyn
- Charmes
- Clarendon
- Crema
- Dogpatch
- Earlybird
- Gingham
- Ginza
- Hefe
- Helena
- Hudson
- Inkwell
- Kelvin
- Juno
- Lark
- Lofi
- Ludwig
- Maven
- Mayfair
- Moon
- Nashville
- Perpetua
- Poprocket
- Reyes
- Rise
- Sierra
- Skyline
- Slumber
- Stinson
- Sutro
- Toaster
- Valencia
- Vesper
- Walden
- Willow
- xPro II