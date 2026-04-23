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

| Name    | Utility class |
| -------- | ------- |
| 1977  | `.filter-1977`    |
| Aden | `.filter-aden`     |
| Amaro    | `.filter-amaro`    |
| Ashby | `.filter-ashby`    |
| Brannan | `.filter-brannan`    |
| Brooklyn | `.filter-brooklyn`    |
| Charmes | `.filter-charmes`    |
| Clarendon | `.filter-clarendon`    |
| Crema | `.filter-crema`    |
| Dogpatch | `.filter-dogpatch`    |
| Earlybird | `.filter-earlybird`    |
| Gingham | `.filter-gingham`    |
| Ginza | `.filter-ginza`    |
| Hefe | `.filter-hefe`    |
| Helena | `.filter-helena`    |
| Hudson | `.filter-hudson`    |
| Inkwell | `.filter-inkwell`    |
| Kelvin | `.filter-kelvin`    |
| Juno | `.filter-juno`    |
| Lark | `.filter-lark`    |
| Lofi | `.filter-lofi`    |
| Ludwig | `.filter-ludwig`    |
| Maven | `.filter-maven`    |
| Mayfair | `.filter-mayfair`    |
| Moon | `.filter-moon`    |
| Nashville | `.filter-nashville`    |
| Perpetua | `.filter-perpetua`    |
| Poprocket | `.filter-poprocket`    |
| Reyes | `.filter-reyes`    |
| Rise | `.filter-rise`    |
| Sierra | `.filter-sierra`    |
| Skyline | `.filter-skyline`    |
| Slumber | `.filter-slumber`    |
| Stinson | `.filter-stinson`    |
| Sutro | `.filter-sutro`    |
| Toaster | `.filter-toaster`    |
| Valencia | `.filter-valencia`    |
| Vesper | `.filter-vesper`    |
| Walden | `.filter-walden`    |
| Willow | `.filter-willow`    |
| xPro II | `.filter-xpro-ii`    |

## Preview

![Preview of the filters](https://raw.githubusercontent.com/bgebelein/tailwind-css-instagram-filters/refs/heads/main/images/filter.webp)