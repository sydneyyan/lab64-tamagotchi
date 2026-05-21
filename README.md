## Setup Instructions
This repo is for the lab64 Tamagotchi Workshop, designed by **Dani Algazi, Finn Hittson,** and **Sydney Yan**

Welcome and we hope you have fun!

For a guide with picture, please see [here](https://docs.google.com/document/d/1xf30KD4tJjHDWuZkQOGdm4FQ10pTro_ldfPIj2dIo68/edit?usp=sharing)
### 1. Install the Arduino IDE
You can find the link [here](https://www.arduino.cc/en/software/).

### 2. Install the correct configuration for the Adafruit ItsyBitsy M4 Express
1. Open **File > Preferences** (Windows) or **Arduino IDE > Settings/Preferences** (Mac).
2. In the **Additional Boards Manager URLs** box, paste this link:  
   `https://adafruit.github.io/arduino-board-index/package_adafruit_index.json`
3. Open the **Boards Manager** (the board icon on the left sidebar).
4. Search for **Adafruit SAMD**.
5. Find **Adafruit SAMD Boards** and click **Install**.

### 3. Download the correct libraries
1. Go to the **Library Manager** in the Arduino IDE.
2. Search for and install **Adafruit SSD1327**.

### 4. Configure your board and port settings
1. Go to **Tools > Board > Adafruit SAMD (32-bits ARM Cortex-M4) Boards**.
2. Select **Adafruit ItsyBitsy M4 Express (SAMD51)**.
3. Make sure your **Port** is selected under **Tools > Port**.

### 5. Clone the repo or download tamagotchi.ino
Download it from the [Tamagotchi Git repository](YOUR_REPO_URL_HERE).

### 6. Upload your code
Upload your code to the board, and you're good to go!
