# Raspberry-Pi-Relay-Control-gpiozero
This module provides functions for controlling four relays connected to a Raspberry Pi's GPIO pins using the gpiozero library. The relays are connected to pins 4, 22, 6, and 26, respectively.

<h2>Functions:</h2>

<b>blinker(time_delay, relay_sel, blinks):</b> This function turns on and off a selected relay for a specified time delay and number of times. The parameters are: <br>
<b>time_delay:</b> the delay in seconds between each blink
<b>relay_sel:</b> the index of the relay to blink (0 for relay1, 1 for relay2, and so on)
<b>blinks:</b> the number of times to blink the relay
<br>
<br>
<b>switchOn(relay_sel):</b> This function turns on a selected relay. The parameter is: <br>
<b>relay_sel:</b> the index of the relay to turn on (0 for relay1, 1 for relay2, and so on)
<b>switchOff(relay_sel):</b> This function turns off a selected relay. The parameter is:
<b>relay_sel:</b> the index of the relay to turn off (0 for relay1, 1 for relay2, and so on)
Note that the relays are initially set to off (False), and the active_high parameter is set to True to indicate that a high output corresponds to the relay being on.

To use this module, you need to have the gpiozero library installed on your Raspberry Pi. You can import this module into your Python code and call the functions as needed to control the relays.
