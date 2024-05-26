# RGB-LED-SPHERE
This is a DIY project, which soldering 132 PCs RGB W2812B LEDs to a strip and frame as sphere. It utilize ESP32 control board to show preset 7 beautiful animations. 

Install the current upstream Arduino IDE at the 1.8 level or later. The current version is at the arduino.cc website. 
https://www.arduino.cc/en/software
Start Arduino and open the Preferences window.
![image](https://github.com/ellineguo/RGB-LED-SPHERE/assets/53522401/7f86a246-7a71-46ca-803a-51943fe48b29)
Enter below link into Additional Board Manager URLs field. You can add multiple URLs, separating them with commas.
https://espressif.github.io/arduino-esp32/package_esp32_index.json
![install_guide_boards_manager_url](https://github.com/ellineguo/RGB-LED-SPHERE/assets/53522401/4ca43edc-c810-4329-a824-2bae552df7c2)
Open Boards Manager from Tools > Board menu and install esp32 platform (and do not forget to select your ESP32 board from Tools > Board menu after installation).
![install_guide_boards_manager_esp32](https://github.com/ellineguo/RGB-LED-SPHERE/assets/53522401/17a074f1-507b-479e-b59d-8d5a82bf1025)
Restart Arduino IDE.

Download and add Arduino NeoPixelBus Library.
Open the "RGB Sphere.ino" file in main to edit and programing your animations!!
