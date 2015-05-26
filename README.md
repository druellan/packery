# Packery Fork

This is a fork of the Packery project (https://github.com/metafizzy/packery).

### New Features

##### Ability to lock items
Specifies elements are *locked* within the layout. These are special layout elements which will **be** laid out by Packery, but could have some restrictions on their behaviour.
On this implementation, locked elements are not affected by user interaction, and try to retain its position.

```
"itemSelector": ".item",
"lock": ".locked"
```

This implementation was inspired by https://github.com/metafizzy/packery/pull/203 that extends the `stamp` property to achieve a similar effect.

### Special Dependencies

You might need a version of Outlayer that has the ´lock´ item property implemented:
* https://github.com/druellan/outlayer