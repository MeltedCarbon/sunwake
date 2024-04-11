# Sunwake

Sunwake is a project created to replace traditional alarm clocks. It and its counterpart component Noisewake are intended to slowly increase the presence of light and white noise (and rain sounds if it's actually raining in your location) within a space to imitate a sunrise, providing for a much more natural and pleasant waking up in the morning.

I created it to replace my alarm clock in an attempt to improve upon my overall happiness, health, and energy levels throughout the day.

## In its current state, it's definitely a tinkerer's project, with only the basic working functionality within the code. There's no GUI for the Noisewake script or outside control with the Arduino code.


# How it works

I created a 3D model and print of a box to enclose an LED-compatible rotating dimmer switch (primitive rheostat) coupled to a servo motor with a couple set screws, with an Arduino Uno to control it based off of a real-time clock module. At the target time specified in the code, it will rotate the switch from 0% to 100% over the course of however many minutes it is set to (for example, 30min)

On the other hand, Noisewake is a simple Python script which runs on a separate computer (in my case - a Raspberry Pi) to slowly increase the volume of white noise (as well as rain sounds if it is actually raining at specified location with Open-Meteo API) also over the course of a set amount of minutes.

# Why is there no code?
(Yet). The project is still a work in progress. It needs some further testing, as well as refining of the 3D model, as it's not currently at a point where it can be used without doing a decent bit of modifying to the result. However if you would like to contact me about the code to use it in its current state, create an issue on the issues tab.
