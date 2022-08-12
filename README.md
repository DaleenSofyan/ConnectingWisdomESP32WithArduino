<h1>ConnectingWisdomESP32WithArduino</h1>

<h2>Step 1 - Download Arduino IDE 1.8.19</h2>
<p>Click on the link below to install Arduino:</P>
https://www.arduino.cc/en/software

<h2>Step 2 - Start Arduino and open Preferences window</h2>

<p>Enter the following Code into Additional
Board Manager URLs field. You can add multiple URLs, separating them with
commas.</p>

    https://dl.espressif.com/dl/package esp32 index.json 


<h2> Step 3 - Plog the Board into your PC</h2>
<p> You can do this using any cable that matches with the the board.</p>


<h2>Step 4 - Installing bord driver</h2>
<p>Open Boards Manager from Tools then go to Board menu and install esp32 platform
(and don't forget to select your ESP32 board from Tools > Board menu after
installation).</p>

<h2>Step 5 - Select ESP32 Wrover Module</h2>
<p>Click on Tools then go to board: ESP32 Wrover Module and select either Dev Module or Wrover Module.</p>

<h2>Step 6 - Select the Port</h2>
<p> To figure out which one, you need to right click on the start menu, go to Device Manager and search for ports, it will display which one.
after this you need to go to Tools then to ports and select it.</p>
