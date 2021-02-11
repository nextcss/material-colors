# Next.css Material Colors Module

Material Colors Module is part of Next.css framework. This module contains original Material Color Palette CSS styles for your Next.css project. You can use in all modern websites with module bundlers, like webpack, rollup, parcel.

## How to Install

You can install with npm or yarn package managers.

```
npm i @nextcss/material-colors
yarn add @nextcss/material-colors
```

Simple import to your project, and add class rules to you HTML tags.
Check available selector rules below.

```javascript
import '@nextcss/material-colors';
```

## Features

- Text colors (foreground)
- Background colors
- Border colors
- Hover states
- Active states
- Focus states
- Focus-In states

## How to use

```html
<!-- Set background color -->
<h1 class="bg-blue-500">...</h1>

<!-- Set background, border and text colors -->
<div class="bg-pink-50 bo-pink-100 fg-pink-700">...</div>

<!-- Set text color, background and hover state background -->
<button class="fg-white bg-blue-500 hover:bg-blue-700">...</button>
```

Selector formula
**`[state:]prefix-color[-scale]`**

#### state

After _state_ must use colon, _state_ is not required.
`hover`,`active`,`focus`,`focus-in`

#### prefix

After _prefix_ must use hyphen, _state_ is required.
`fg` - foreground, `bg` - background, `bo` - border

#### color (scalable)

After _color_ must be set _scale_ value. _color_ is required.
`red`, `pink`, `purple`, `deep-purple`, `indigo`, `blue`, `light-blue`,`cyan`,`teal`,`green`,`light-green`,`lime`,`yellow`,`amber`,`orange`,`deep-orange`,`brown`,`grey`,`blues-grey`

#### color (not scalable)

After _color_ can not set _scale_ value. _color_ is required.
`black`,`white`

#### scale

Before _scale_ must use hyphen, _scale_ is required for scalable _color_ only.
`100`,`200`,`300`,`400`,`500`,`600`,`700`,`800`,`900`

## License

MIT License. Copyright (c) 2021 Zsolt Tovis
