# elastic-client-filter-builder

An element which builds an elasticjs filter based on the set attributes.

Example:
```html
    <elastic-client-filter-builder
        type="terms"
        field="field"
        values="values"
        ejs-filter="{{ejsFilter}}">
    </elastic-client-filter-builder>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install
