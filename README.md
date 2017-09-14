# auto-paginated-image-gallery

A Polymer Element showing a paginated-image-gallery element that automatically handles pagination.

### Example
```html
<auto-paginated-image-gallery
  images="[[images]]">
</auto-paginated-image-gallery>
```

### Styling

`<auto-paginated-image-gallery>` provides the following custom properties and mixins for styling:

Custom property                                   | Description                                  | Default
--------------------------------------------------|----------------------------------------------|--------
`--auto-paginated-image-gallery-hovering-color`   | The background color of the hovering images. | none
`--auto-paginated-image-gallery-loading-spinner`  | Mixin applied to the loading-spinner.        | none
`--auto-paginated-image-gallery-max-height`       | Maximum height of the gallery.               | 160px
`--auto-paginated-image-gallery-scroll-threshold` | Mixin applied to the iron-scroll-threshold.  | none
`--auto-paginated-image-gallery-selected-color`   | The background color of the selected images. | none
`--auto-paginated-image-gallery-show-more-button` | Mixin applied to the show more button.       | none

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

