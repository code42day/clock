
# clock

  Clock UI component for use in time-picker

## Installation

    $ component install code42day/clock

## Example

```js
var Clock = require('clock');
var clock = new Clock;
clock.el.appendTo('body');
clock.select({
	hour: 11,
	minute: 30
});
```

## Events

  - `change` (time, complete) - when the selected time is modified
  	`time` is an object with `hour` and `minute` properties,
  	`complete` is true only if both hours and minutes have been clicked by the user

## API

### Clock#select(time)

Select the given `time` ({ hour, minute }).

## License

  MIT
