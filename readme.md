# name still to be decided ... 

A minimal and opinionated TUI tool to automate weight tracking and calorie adjustment targets. 

## Name Candidates

* **sbilancia**
* **FitByte**
* **GarmOut**
* ~~but (bulk + cut)~~
* **panza**
* **buzza**
* weight overflow
* ~~kalory/kalories (kilobyte + calories)
* dumb-scale/dumbilancia
* yourprotein
* gymshrimp/gymtonno/gymnemo/gymfat/gymmouse/gymouse
* ~~herbadeath/acqualife~~
* ~~clickness instead of fitness~~ 

## Implementation Plan (TODOs)

- [ ] **Garmin Integration:** Connect to the Garmin account to automatically fetch the latest logged weight and body composition data.
- [ ] **Target Calculation:** Compute the next weekly weight target (e.g., a 0.5% decrease) along with the min/max tolerance intervals.
- [ ] **Google Calendar Sync:** Authenticate with the Google Calendar API to automatically create the target events (format: `🥅XX,XXXkg (min:YY,YYY - max:ZZ,ZZZ)`).
- [ ] **TUI Interface:** Build a terminal user interface to visualize current progress, adjust the weekly delta percentages, and force manual syncs.
- [ ] calories diary that pulls data from whichever app i'd use (a new account of myfitnesspal, or chronometer, etc)
