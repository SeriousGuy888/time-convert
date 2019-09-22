# What is it?
 A NodeJS package for converting seconds to formatted time!
 Time can be converted and returned in JSON format, in words, and more.

# Intallation
 `npm i seconds-time-formatter`

# How to Use
 ```
  // Require the package
  const timeFormatter = require("seconds-time-formatter")

  console.log(
    timeFormatter.timeConvert({
      seconds: 513215645, // Amount of seconds
      format: "words", // In what format you want the output to be  returned.
      monthsAndWeeks: true
      // By default false, because of how it's hard to convert days and weeks to months.
      // If you do enable it, 1 month = 4 weeks. If not, 1 year = 365 days.
    }
  ))
 ```

# Options

### Seconds
 The amount of seconds you want to convert.

 ```
  const timeFormatter = require("seconds-time-formatter")

  console.log(
    timeFormatter.timeConvert({
      seconds: 132
    }
  ))

  // Will output 0y0M0w0d0h2m12s
 ```