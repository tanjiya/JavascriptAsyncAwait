# GET Weather Data using async-await

- Used Javascript async-await To Fetch Weather Data for Few Location

## Used The Following Function:

- get(url) {} to Get The Respone from Weather API
- successHandler(data) {} to Push The Content to HTML File
- failHandler(status) {} to Handle Error
- tempToF(kelvin) {} to Convert The Temparature from Kelvin to Farenheit

## To Remind What Actually async-await Does

- async-await Are Syntactic Augar. Meaning that They Simply Provide Short Hand Syntax for Writing Code using An Existing Coding Practice.

- In that Case, async-await Code Create and Works with Promises under The Hood.

## async-await in Old Browser

- asynce-await Won't Work in Old inspite of Having Promise Polyfill
- It Need to Transpile The Code into Promises
- We can use https://babeljs.io/ to Make The Code Compatible in Old Browser
