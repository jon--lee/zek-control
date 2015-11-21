#### For OS X Yosemite (10.10.x)
Install [Xbox controller driver](http://tattiebogle.net/index.php/ProjectRoot/Xbox360Controller/OsxDriver) version 0.11. Other drivers may interpret buttons on the Xbox controller differently.
Do not download the most recent version (0.12) as it is not compatible with Yosemite.
Follow driver instructions and restart machine.

Open system preferences and you should see an icon "Xbox 360 Controllers" in the bottom row.
Click that and plug in the controller to ensure it is recognized in "Device."

You can run test_joystick.py with `$ python test_joystick.py` and test the buttons and joysticks. All the code in this repo assumes that the driver
recognizes the d-pad as buttons 0-3 rather than as a "hat." If your buttons are interpreted as anything else, ensure you downloaded the correct driver.

Exit test_joystick.py and connect the arduinos. Check in the arduino IDE for the USB ports
and change them if necessary in IzzyRun.py and TurnTable.py.

Run IzzyRun.py with `$ python IzzyRun.py`



