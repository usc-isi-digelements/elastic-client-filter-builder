# elastic-client-filter-builder

A Polymer Element which builds an elasticjs filter based on the set attributes.

### Example
```html
<elastic-client-filter-builder
  type="terms"
  field="field"
  values="values"
  ejs-filter="{{ejsFilter}}">
</elastic-client-filter-builder>
```

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

