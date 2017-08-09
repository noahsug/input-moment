# yet-another-datetime-picker
React datetime picker powered by [momentjs](http://momentjs.com)

The design is from https://dribbble.com/shots/1439965-Due-Date-and-Time-Picker.

The icon is from [ionicons](http://ionicons.com/).

### Demo
http://noahsug.github.io/input-moment

### Usage
``` javascript
<DatetimePicker
  moment={this.state.moment}
  onChange={this.handleChange}
  onSave={this.handleSave}
  prevMonthIcon="ion-ios-arrow-left" // default
  nextMonthIcon="ion-ios-arrow-right" // default
  type="datetime" // default, other values are "date" or "type"
/>
```
Check [app.js](https://github.com/noahsug/input-moment/blob/master/example/app.js) for a working example.

## This repo is forked from [moment-input](https://www.npmjs.com/package/input-moment) with the following changes
- Specify type="time" or type="date" to have a date-only or time-only input.
- Buttons to move forward or backwards between years.
- CSS tweaks + make all icons customizable.
- Fixed package / build issues.

### Installation
``` sh
npm i yet-another-datetime-picker --save
```

**Notice:** This module requires [moment](https://www.npmjs.com/package/moment) as a [peerDependency](https://docs.npmjs.com/files/package.json#peerdependencies).

### Development
- npm install
- npm run build
- npm start
- http://localhost:8888/example

### License
ISC
