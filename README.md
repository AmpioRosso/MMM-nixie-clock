# MMM-nixie-clock
Retro nixie clock display for [MagicMirror²](https://github.com/MichMich/MagicMirror).

![Nixie](https://raw.githubusercontent.com/Isaac-the-Man/MMM-nixie-clock/master/screenshots/nixie.PNG)

There's also a digit reset animation.

![DigitReset](https://github.com/Isaac-the-Man/MMM-nixie-clock/blob/master/screenshots/digit-reset.gif?raw=true)

## Configuration

There are four configurable options:
| option | description | default |
|--------|-------------|---------|
| size | `'mini'`, `'small'`, `'medium'`, or `'large'`. | `'large'` |
| reflection | set `false` to turn off reflection effect. | `true` |
| timeFormat | `12` hour or `24` hour display. | `24` |
| displaySeconds | `true` for a 6-digit clock or `false` for a 4-digit clock. | `true` |

Sample config file (default):
```js
var config = {
  modules: [
    {
      module: 'MMM-nixie-clock',
      position: 'middle_center',
      config: {
        size: 'large',
        reflection: true,
        timeFormat: 24,
        displaySeconds: true,
      }
    }
  ]
}
```

All image credit to [Dalibor Farny](https://www.daliborfarny.com/).
