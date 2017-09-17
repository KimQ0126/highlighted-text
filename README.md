# highlighted-text

A Polymer Element showing tagged text with highlights.

### Example
```html
<highlighted-text
  text="The <tag>quick brown</tag> fox jumped over the <tag>lazy</tag> dog."
  tags="tag">
</highlighted-text>
```

### Styling

`<highlighted-text>` provides the following custom properties and mixins for styling:

Custom property                  | Description                        | Default
---------------------------------|------------------------------------|--------
`--highlighted-text-color`       | The color of the highlighted text. | yellow
`--highlighted-text-style-mixin` | Custom style mixin for the text.   | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

