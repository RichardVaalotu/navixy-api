---
title: /input_name
description: /input_name
---

## list()
Returns descriptions of all sensor inputs existing in the system. 

#### parameters
No parameters.

#### return
For every input following properties are returned: *input_name* and *description*.

*input_name* is an enum member, same as in [sensor object](./sensor.md).

*description* is made in current user's language (according to [locale settings](../../../commons/user/settings/settings.md)).

Example:

```js
{
  "success": true,
  "list": [
    {
      "input_name": "analog_1", 
      "description": "Sensor analógico #1"
    },
    …
    {
      "input_name": "can_coolant_t",
	  "description": "CAN: Temperatura del refrigerante"
    },
	…
  ]
}
```

#### errors
No specific errors
