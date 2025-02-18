# Python-Dronekit-library
Download the dronekit library by using below command  </br>
```pip install dronekit``` </br>
from dronekit import connect </br>
Connect to UDP endpoint.</br>
vehicle = connect('127.0.0.1:14550', wait_ready=True)</br>
se returned Vehicle object to query device state - e.g. to get the mode:</br>
print("Mode: %s" % vehicle.mode.name)</br>
