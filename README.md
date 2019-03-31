# Twitter Bootstrap Countdown Plugin
This plugin counts down to a specific date/time while obeying specified timezone

# Requirements
- Twitter Bootstrap 4.x
- jQuery 3.x

# Usage
``` javascript
$('#countdown').countdown({
    year: 2016,   // YYYY Format
    month: 1,     // 1-12
    day: 1,       // 1-31
    hour: 21,     // 24 hour format 0-23
    minute: 30,   // 0-59
    second: 0,    // 0-59
    timezone: -6, // http://en.wikipedia.org/wiki/List_of_tz_database_time_zones
    labels: true, // Show/Hide label elements
    onFinish: function () {
        ...
    }  // Executes client side when timer is zero
});
```