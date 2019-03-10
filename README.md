# dadamachines - Arduino Board Support Package(s)
Board Support Package for Arduino IDE v1.6+.

## Installation
1.  Add the following URL to the Arduino Boards Manager (**File->Preferences**):  
For the **automat** install the **dadamachines - M0 Boards** Package:
```
https://dadamachines.github.io/arduino-board-index/package_dadamachines-m0_index.json
```

For the **doppler** install the **dadamachines - M4 Boards** Package:
```
https://dadamachines.github.io/arduino-board-index/package_dadamachines-m4_index.json
```

![dadamachines-add-arduino-board-support-package-url](img/dadamachines-add-arduino-board-support-package-url.jpg)


2. Then open the Arduino Boards Manager (**Tools->Boards->Boards Manager**) and install the following packages:

For the **automat**:
- **Arduino SAMD Boards (32-bits ARM Cortex-M0+)** by **Arduino**
- **dadamachines - M0 Boards** by **dadamachines**

For the **doppler**:
- **Adafruit SAMD Boards** by **Adafruit** 
- **dadamachines - M4 Boards** by **dadamachines**

![dadamachines-install-arduino-board-support-package](img/dadamachines-install-arduino-board-support-package.jpg)

3. Restart the Arduino IDE

4. Select the **dadamachines** product / board (**Tools->Board(s)->dadamachines - M0 or M4 Boards->dadamachines "product name"**)

5. Find the official software and examples for the **dadamachines** product / board (**File->Examples->Examples for dadamachines "product name"**)
