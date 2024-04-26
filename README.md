# ActiveDisplayIndicator
## or "Hammy & Heskimo's H-Active Hesktop Indicator"

Scrotings!

This is an accessibility utility to visually indicate which monitor is currently actively focused for input on Windows. The utility at present creates an icon in the "System Tray" of Windows. The plan from here is to use the enumerated displays to light specific external LEDs above or below the relevant display. I'll update the repository once that's available, and make the finalized utility also available to just download and install without futzing around with the various dependencies.

I wrote this small utility for one of my oldest and closest friends who is legally blind. He struggled to determine which monitor currently had active focus in terms of human input device. Windows is pretty poor in terms of accessibility, and whilst this would be trivial to implement on Linux, was a little bit of a rabbithole to do successfully on Windows.

You will need the following installed to use it in its current state:

- Python (grab it from the Microsoft Store)
- win10toast (`pip install win10toast`); I'll likely be removing this, it's purely for testing purposes.
- pywin32 (`pip install pywin32`)
- pystray (`pip install pystray`)

Open a terminal in the same directory as it and run `python active_monitor_indicator.py` to start the utility.

I'm hoping to wrap it up into a neat installable utility that people can install and forget about it. If you find some value in it, great!

Numerical icons I modified the colours of for a quick test: <a href="https://www.flaticon.com/free-icons/number-one" title="number one icons">Number one icons created by Hight Quality Icons - Flaticon</a>

If anyone has any difficulties in setting it up, let me know, happy to help!

Peace and love, earthlings!
