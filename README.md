# PSXBlue
PSX Blueretro Board

Here are the Gerber files needed for my Blueretro compatible board.  This board is designed to only go in original form factor Playstion consoles. I have an idea for adding it to the smaller PSOne, but it will require a custom flex-PCB.

Known Issues:
- There is an apparent issue with the PU-18 model of the PSX (I don't have one for testing), but it will press buttons randomly.  This is an issue with the Blueretro code and not the board.

- You can use original controllers along side bluetooth ones, but not in the same port at the same time.  If I plug a controller into slot one and connect my bluetooth controller to slot one, either only the wired controller will work or neither will work correctly.  

- There is no way to tell the Blueretro to act as controller two if there is no controller connected as player one.  Essentally if I want player two to use a bluetooth controller and I want player one to use a wired controller it's not possible.  Either player one is bluetooth and player two is wired, or both are bluetooth, or both are wired.


Credit to https://github.com/darthcloud/BlueRetro
