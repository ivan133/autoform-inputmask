# Autoform Inputmask

### Install

```js
meteor add theara:inputmask

meteor add ivan133:autoform-inputmask
```
### Usage

```js
// SimpleSchema
............
autoform: {
    type: "inputmask",
    afFieldInput: {
        inputmaskOptions: inputmaskOptions.integer()
    }
}
```

- inputmaskOptions.currency()
- inputmaskOptions.integer()
- inputmaskOptions.percentage()
- or custom

### Changelog
- v 0.4.8 (2018-10-17)
    - update autoform version restriction
- v 0.4.7 (2016-02-02)
    - update readme
- v 0.0.1 (2015-08-31)
    - init
