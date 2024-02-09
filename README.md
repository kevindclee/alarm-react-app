
# :alarm_clock:alarm-react-app
Alarm application built with <img src="https://img.shields.io/badge/React-gray?logo=react"> <br/>
This project was built under alternative username [@ldc-bootcamp01](https://github.com/ldc-bootcamp01) during the En-core Playdata bootcamp.

## Overview
With this Alarm application, you can:
- Add, delete, and modify alarm functionality
- When the designated time is reached, the alarm rings, and you can turn off the alarm with the off button 

## React Component Composition

![React Component Chart](/public/react_component_chart.png "React Component Chart")

- ![#FF8C00](https://via.placeholder.com/15/FF8C00/FF8C00.png) `Form` : A component for adding `Alarm` to the `Alarms` component
  - You can add an alarm after entering the alarm title, AM/PM, hour, and minute information. 

- ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `Header` : Component consisting of app title, current time, and `Form` component
  - Current time is updated every second

- ![#6495ED](https://via.placeholder.com/15/6495ED/6495ED.png) `Alarm` : Component holding information of a single alarm
  - You can double click on the alarm title to edit it
  - Press the X button on the right side of the alarm to delete it
  - When the time of each alarm matches the current time, the alarm sound rings, and the 'Turn Off Alarm' button is generated
  - Pressing the 'Turn Off Alarm' button stops the alarm sound

- ![#9400D3](https://via.placeholder.com/15/9400D3/9400D3.png) `Alarms` : List of `Alarm` components

- ![#228B22](https://via.placeholder.com/15/228B22/228B22.png) `MainFooter` : Component displaying the count of `Alarm` components

- ![#0000FF](https://via.placeholder.com/15/0000FF/0000FF.png) `Main` : Component consisting of `Alarms` and `MainFooter` components

## Requirements

```
git clone https://github.com/ldc-bootcamp01/alarm-react-app.git
npm i (install)
npm start
```
