Kerbal Controller: Summary

After 3 years of development and 3 iterations, covering 7 versions of KSP, the Kerbal Controller is finally completed. This iteration of the controller uses KRPC, a python plugin for KSP, to remotely control the game via a Raspberry Pi, instead of using the slow and unreliable KSPSerialIO which uses a serial link from an Arduino. Digital signals from switches are directly handled by the Pi, while analog signals are handled by an Arduino Mega connected to the Pi via serial link. The Raspberry Pi can run multiple clients at once, allowing rapid communication between the game and the control panel. 3 clients are used: One for a digital uplink, one for an analog uplink, and one for a telemetry downlink. The result is a reliable and low-latency system that is infinitely expandable and customizable. Development on this project is certainly not stopping here, with autopilot, map visualization, and more in the works.