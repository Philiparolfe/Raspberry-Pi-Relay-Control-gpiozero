# Raspberry-Pi-Relay-Control-gpiozero
<p>This module provides functions for controlling four relays connected to a Raspberry Pi's GPIO pins using the gpiozero library. The relays are connected to pins 4, 22, 6, and 26, respectively.</p>
<h3>Functions:</h3>
<ul>
  <li><code>blinker(time_delay, relay_sel, blinks)</code>: This function turns on and off a selected relay for a specified time delay and number of times. The parameters are:
    <ul>
      <li><code>time_delay</code>: the delay in seconds between each blink</li>
      <li><code>relay_sel</code>: the index of the relay to blink (0 for relay1, 1 for relay2, and so on)</li>
      <li><code>blinks</code>: the number of times to blink the relay</li>
    </ul>
  </li>
  <li><code>switchOn(relay_sel)</code>: This function turns on a selected relay. The parameter is:
    <ul>
      <li><code>relay_sel</code>: the index of the relay to turn on (0 for relay1, 1 for relay2, and so on)</li>
    </ul>
  </li>
  <li><code>switchOff(relay_sel)</code>: This function turns off a selected relay. The parameter is:
    <ul>
      <li><code>relay_sel</code>: the index of the relay to turn off (0 for relay1, 1 for relay2, and so on)</li>
    </ul>
  </li>
</ul>
<p>Note that the relays are initially set to off (False), and the active_high parameter is set to True to indicate that a high output corresponds to the relay being on.</p>
<p>To use this module, you need to have the gpiozero library installed on your Raspberry Pi. You can import this module into your Python code and call the functions as needed to control the relays.</p>
