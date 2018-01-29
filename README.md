# MQBSimosLogVariables
Collect 0x22 ReadLocalIdentifier variables and conversions for use in Torque and other logging software.

Compatible with Simos18 cars like MQB / MK7 VW Golf R, GTI, 1.8, Audi S3/A3, etc.

# To Use with Torque
Copy CSV to /sdcard/.torque/extendedpids
Visit Torque settings and open the Custom PIDs pane, then press "..." and "Settings from Group". Your CSV should appear in the list.
# To use otherwise
The equations should be self explanatory. In the CSV everything has 0x22 (ReadLocalIdentifier) prepended to it as to Torque, a "PID" is a full ELM327 command. If you're adding the "PIDs" to something like a CANbus logger or dashboard, you may not need the 0x22 or it may be selected through a different mechanism.
# Will this show me boost over 20psi?
YES. The Charge Pressure Actual is the output from the Pressure Upstream Throttle sensor and will measure 0-3bar, just like the actual sensor.
