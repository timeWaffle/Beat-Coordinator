# Beat-Coordinator

**beatChan Beat Time Coordinator**

This is a simple webpage intended to assist with Global Beat Time coordination. This grid will help to identify the best Beat Time for all parties and assist in understanding individual Beat Time ranges and translation.

https://beatchan.neocities.org/

1. First, we attempt to derive your current timezone from the browser.
2. Next, select the timezone offset of your coordinating parties:

   - I am in UTC -7
   - Alice is in UTC +2
   - John is in UTC -3
   - Tony is in UTC -4
3. Adjust 'Your Timezone' if we did not derive it correctly.
4. Observe the table below displaying a breakdown of Beat Hours and localized TradTime.
5. Coordinate your optimal times.

### Time Table Layout

- The first row of the table is Beat Time separated by Hour.
- The second row of the table is _**your**_ current timezone and offset.
- The following rows display the time breakdown for the timezones you have selected above.

| Beat Time  | @041 | @083 | @125 | @166 | @208 | @250 | @291 | @333 | @375 | @416 | @458 | @500 |
|-------------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| You (UTC -7)| 17:00 | _**18:00**_ | _**19:00**_ | _**20:00**_ | _**21:00**_ | _**22:00**_ | _**23:00**_ | _**00:00**_ | _**01:00**_ | _**02:00**_ | _**03:00**_ | _**04:00**_ |
| Alice (UTC +2) | _**02:00**_ | _**03:00**_ | _**04:00**_ | _**05:00**_ | 06:00 | 07:00 | 08:00 | 09:00 | 10:00 | 11:00 | 12:00 | 13:00 |
| John (UTC -3) | _**21:00**_ | _**22:00**_ | _**23:00**_ | _**00:00**_ | _**01:00**_ | _**02:00**_ | _**03:00**_ | _**04:00**_ | _**05:00**_ | 06:00 | 07:00 | 08:00 |
| Tony (UTC -4) | _**20:00**_ | _**21:00**_ | _**22:00**_ | _**23:00**_ | _**00:00**_ | _**01:00**_ | _**02:00**_ | _**03:00**_ | _**04:00**_ | _**05:00**_ | 06:00 | 07:00 |

**Color Legend:**

- **Dark cells** indicate Nighttime (6 PM to 5 AM). (Bold and Italicized in our example above)
- **Light cells** indicate Daytime (6 AM to 5 PM).

You can use the **'Toggle 24hr/12hr Time Format'** button to switch between time formats. 

### Why do all of this?

Perception. Our objective is to assist in altering our perceptions of the use of Beat Time and its usefulness in global time coordination.

This short video can help explain.

*Swatch Internet Time*
https://www.youtube.com/watch?v=4ROTh6gZz3Y

### Future Enhancements

1. **Highlight the 'Current Time' column:**
   - Provide a visual indication of the current time for the user.

2. **Mobile Optimization:**
   - Adjust the viewport and background image for mobile devices.

3. **Code Refactor:**
   - Refactor the JavaScript for cleaner and more efficient code.
  
### Known Issues

1. **Missing .5 TZ Offsets**
   - Focus is on main timezone offsets for sanity sake.
  
2 **No DST (Daylight Savings Time) Considerations**
  - I have no idea what will break when US/EU/AUS exit/enter DST.
  - We *should* still just pick up the correct offset from the browser.
