# DigitalClock
A 12-hour digital clock made out of logic gates and flip-flops and implemented in Logisim.

This project incorporates the logisim 7-segment-display driver created here: https://github.com/marceloboeira/logisim-7-segment-display-driver.

<img width="818" alt="Screen Shot 2022-12-27 at 10 19 57 PM" src="https://user-images.githubusercontent.com/55850506/209768025-ab157a2d-e297-4307-b2e8-43ed95fc72f2.png">

How to open this project:

1: clone this repository with `git clone https://github.com/CooperCollier/DigitalClock --recursive`. The recursive tag is necessary to include the 7-segment-display driver.

2: Open the file clock.circ in logisim.

3: Under the 'simulate' tab, set 'tick frequency' to 2Hz.

4: Under the 'simulate' tab, set 'ticks enabled' to true.

How to use the clock:

Press the SET TIME button to make the clock enter or exit the SET TIME state. When the clock is in the SET TIME state, the SET TIME LED will be turned on. When the clock enters the SET TIME state, the time is immediately reset to 12:00 AM. 

Press the +MIN and +HOUR buttons to change the displayed time. These buttons are only active when the clock is in the SET TIME state.
