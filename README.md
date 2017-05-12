# Currentsensor ACS713

A small, 44mmx30mm PCB that utilises the ACS713 current sensor device. The output range is 0-30A with a resolution of 0.133V/Amp or by using the additional buffer amplifier, it can provide a 0-5A range at a convenient 1V/Amp range.

The bandwidth and output range are configurable, please read the comments in the schamtic and the design notes here:
http://www.ianstedman.co.uk/Projects/Current_monitor/current_monitor.html

The circuit corrects for the offset in the outut of the ACS713 and utilises the Microchip MCP602 op-amp for rail to rail output.
