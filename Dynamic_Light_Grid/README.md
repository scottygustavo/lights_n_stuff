# Dynamic Light Grid using ReactJS and Paho JS MQTT Client
Very wordy title to describe what will hopefully be the final implementation of the Light Grid

## To Do:
  - Update HTML to be modifiable by ReactJS
  - Update JS to implement ReactJS
      - Generate Grid
      - Send mqtt messages based on grid
  - Adjust the CSS to be scalable with increased number of "pixels"


## Design:
  - Number of columns and rows will be specified in a config file
  - Generate the appropriate grid of buttons
  - Check the config file for a saved array (if it is the right size) and implement the colors on the grid

## Future Features:
  - Password
  - Upload an image
  - Save current configuration locally / on server so everything is synced (instead of relying on mqtt updates)
  - Implement animations / video converter