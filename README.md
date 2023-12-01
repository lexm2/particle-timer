## To open the timer simply download the HTML file in this repo and go to its file location and open it with your browser

## To edit scroll down to the start of the script tag and change the values under the sections

### Time
1. **promtForTime:** If true will prompt you for the amount of minuets you would like the timer to count down from on startup
2. **useEndDate:** Enable to count down to specific date, this format is much larger and you will likely want to reduce your font size
	1. ***endDates:*** The end dates **endDateYear, endDateMonth, endDateDay, endDateHour, endDateMin** specify the exact time and date the timer will count down to
3.  **mins:** Provided that **promtForTime** and **useEndDate** are both false this variable will be the amount of mins the timer counts down from
4. **secs:** Same as **mins** but for seconds
### Customization
1. **fontSize:** The font size is proportional to the window width (***ww***), to make the font bigger reduce the divisor to increase the font size. Be careful because **particlesPer** is not proportional so larger font sizes will have more particles
2. **particlesPer:** The amount of particles in the timer, larger values give more particles and vise versa
3. **colors:** This is an array of hex values that correlates to the different color values of the particles. This works for any amount of colors. Hex values are surrounded in quotes and followed by a comma
4. **endText:** The string of text displayed at the end of the time 
5. **font:** This is an array of fonts, not all fonts work, to ensure your font works check if it is a web-safe font.
### Physics
**mouseIncrement:** This is the amount of size of the force circle increases each click
**orbitRadius:** This is the radius of the circle of particles around the time
**particleRadiusMax:** The maximum size each particle can be
**particleRadiusMin:** The minimum size each particle can be
**frictionMax:** The largest value of friction that can be applied to a particle
**frictionMin:** The smallest value of friction that can be applied to a particle
**accelFactor:** Smaller values for less acceleration and vise versa

