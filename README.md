# react-native-ybha-hourminute-timepicker

## Installation

```
npm i react-native-ybha-hourminute-timepicker
```

### or

```
yarn add react-native-ybha-hourminute-timepicker
```



## Props

| Prop           | Type     | Description                                    | Default |
| -------------- | -------- | ---------------------------------------------- | ------- |
| maxHour        | number   | Maximum of hour                                | 23      |
| minHour        | number   | Minimum of hour                                | 0      |
| maxMinute      | number   | Maximum of minute                              | 59      |
| minMinute      | number   | Minimum of minute                              | 0      |
| hourInterval   | number   | The interval at which hours can be selected.   | 1       |
| minuteInterval | number   | The interval at which minutes can be selected. | 1       |
| hourUnit       | string   | Add extra text to hour                         | ""      |
| minuteUnit     | string   | Add extra text to minute                       | ""      |
| selectedHour   | string   | Default hour                                   | "0"     |
| selectedMinute | string   | Default minute                                 | "00"    |
| itemStyle      | object   | Item text style                                | {}      |
| textCancel     | string   | Cancel button text                             | Cancel  |
| textConfirm    | string   | Confirm button text                            | Confirm |
| onCancel       | function | Event on Cancel button                         |         |
| onConfirm      | function | Event on Confirm button                        |         |

## Methods

| Method Name | Description      |
| ----------- | ---------------- |
| open        | Open TimePicker  |
| close       | Close TimePicker |

### Note

Always set `ref` to `TimePicker` and call each method by using `this.TimePicker.methodName()` like example above.

## License

This project is licensed under the MIT License 

## Author

Made with ❤️ by [ybha](https://github.com/yassinebelhajamor/).
