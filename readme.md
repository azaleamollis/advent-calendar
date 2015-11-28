# Advent Calendar



This is a regular Advent Calendar built in JS, with 24 doors for the days of Advent (Dec 1 - Dec 24). A door can only be opened **on** or **after** the specific date on it.
This means that the Calendar is **inactive before December**.


## How to Test the Calendar before December?


In order to test the Calendar before December, please comment out the month checker in the `/scripts/calendar.js` file, in *line 24* in the following way:

```javascript
if( /* ( currentDate.getMonth() + 1 ) < 11 || */ currentDate.getDate() < day ) {
```

This way the Calendar will only check the day of the current month, but not the current month of the year, so it can be tested before December.