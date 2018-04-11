# calendar_memo

## Thai Buddhist Calendar

- From 1941, Buddhist Yr 1 = Gregorian Yr 543 so Gregorian Yr 2018 = Buddhist Yr 2561

### Refs
- https://www.timeanddate.com/calendar/buddhist-calendar.html
- https://en.wikipedia.org/wiki/Buddhist_calendar
- https://en.wikipedia.org/wiki/Thai_calendar
- https://en.wikipedia.org/wiki/Thai_solar_calendar
- https://github.com/jojosati/bootstrap-datepicker-thai
- https://blogs.transparent.com/thai/what-year-is-it-in-thailand/
- http://worldtimer.net/Calendar/index.php?y=1940&h=th&c=Thailand


## Iranian Solar Hijri Calendar
- The Solar Hijri year begins about 21 March of each Gregorian year and ends about 20 March of the next year

- In the Iranian calendar, every week begins on Saturday and ends on Friday. The names of the days of the week are as follows: shambe (natively spelled "shanbeh", شنبه), yekshambe, doshambe, seshambe, chæharshambe, panjshambe and jom'e

- Anchor date: Sunday, 1 Farvardin 1372, which equals 21 March 1993

- SH yr 1 = Gregorian Yr 622 so SH yr 1395 = Gregorian Yr 2017


### Refs
- https://en.wikipedia.org/wiki/Solar_Hijri_calendar


## Utils
```js
function leapYear(year)
{
  return ((year % 4 == 0) && (year % 100 != 0)) || (year % 400 == 0);
}
```
