# Content Sections

[![npm version](http://img.shields.io/npm/v/elr-scss-content-sections.svg)](https://www.npmjs.org/package/elr-scss-content-sections)
[![Build Status](https://github.com/elr-scss-content-sections/workflows/CI/badge.svg)](https://github.com/elr-scss-content-sections/actions?workflow=CI)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-content-sections.svg?style=flat)](https://npmjs.com/package/elr-scss-content-sections)

a scss mixin for content-sections

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-content-sections --save
```

or

```sh
yarn add elr-scss-content-sections
```

## Implementation

### Scss

```scss
@import "elr-scss-content-sections/src/main";

.content-section-wrapper {
  @include elr-content-section;
}
```

### HTML

```html
<section class="content-section-wrapper">
  <div class="content-section">
    <div class="content-holder">
      <div class="heading-group">
        <h3>This is a smaller heading</h3>
        <h2>This is a larger main heading</h2>
      </div>
      <div class="column-holder">
        <div class="content-column">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum minus
            explicabo aliquam repellat eius quibusdam cumque tempore voluptas
            numquam saepe autem exercitationem incidunt atque placeat illum,
            possimus ut modi ullam soluta sit, perferendis quisquam? Voluptatum.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Error
            perferendis nihil nisi eveniet dolore officia id doloribus.
            Distinctio omnis perspiciatis officiis quos dolor!
          </p>
        </div>
      </div>
      <div class="button-holder">
        <button class="elr-button">Button</button>
        <button class="elr-button elr-button-secondary">Button 2</button>
      </div>
    </div>
  </div>
</section>
```

## License

SEE LICENSE IN LICENSE.md
