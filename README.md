# up-time-slider

A material design element that allows a user to select a time from a range of values by moving the slider thumb.

## Usage

Example:

    <up-time-slider
                      zoom="1 day"
                      align="day"
                      min="2015-10-10 12:00" max="2015-10-12" step="30 minutes"
                      tick-interval="4 hours" tick-format="HH"
                      value="{{time}}" pin="HH:mm">

