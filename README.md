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

Custom property            | Description                        | Default
---------------------------|------------------------------------|--------
`--highlighted-text-color` | The color of the highlighted text. | yellow

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install
