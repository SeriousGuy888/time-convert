# What is it?
 A NodeJS package for converting seconds to formatted time!
 Time can be converted and returned in JSON format, in words, and more.

# Intallation
 `npm i seconds-time-formatter`

# How to Use
 ```
  const timeFormatter = require("seconds-time-formatter")

  console.log(timeFormatter.timeConvert({
    seconds: 513215645,
    format: "words",
    monthsAndWeeks: true
  }))
 ```