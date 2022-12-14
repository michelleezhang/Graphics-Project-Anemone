# Graphics-Project-Anemone
This project consists of two assemblies of rigid 3D parts – an anemone and a clownfish. The anemone spins, its tentacles sway, and the fish travels continuously across the screen, swaying side to side and flapping its fins. There are several components that the user can control. Users can drag their mouse on the screen to rotate the fish, effectively changing its orientation as it moves. Pressing the “L” key on the keyboard will spin the anemone faster to the left, while pressing the “R” key on the keyboard will spin the anemone faster to the right. An input box is provided on the screen to allow users to adjust the initial rotation angle of the anemone’s tentacles, causing them to curl and unfurl from a different initial configuration, depending on the number inputted. In order to use this feature, users should type a number into the box and press the “Submit” button. There are also checkboxes provided for three components of the project: the anemone base, the anemone tentacles, and the fish. Checking (and unchecking) these boxes allows the user to pause (and unpause) the movement of the selected component.

# Notes
** JS Event Listeners **

When users move, click or drag the mouse and when they press a key on the keyboard the operating system create a simple text-based 'event' message.

Your Javascript program can respond to 'events' if you:

a) tell JavaScript to 'listen' for each event that should trigger an action within your program: call the 'addEventListener()' function, and 

b) write your own 'event-handler' function for each of the user-triggered actions; Javascript's 'event-listener' will call your 'event-handler' function each time it 'hears' the triggering event from users.

The 'keyDown' and 'keyUp' events respond to ALL keys on the keyboard, including shift,alt,ctrl,arrow, pgUp, pgDn,f1,f2...f12 etc. 
