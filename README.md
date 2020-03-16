# What is this

Get perfect shadows every time for the non-designer.

# Installation

`npm i shadowizard --save`

then..

```
import { shadowizard } from 'shadowizard';

shadowizard({
  shadow_type: 'soft',
  padding: false
});
```

## options

shadowizard supports 2 options, both of wich are optional:

* *shadow_type* - _hard / soft_ - (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)