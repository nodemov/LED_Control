# LED_Control
Control LED Brightness. Adjust LED brightness using an Arduino , express.js ,node.js, ngrok,johnny-five,serialport

SETUP
1. Upload arduino_control.ino to arduino UNO Borad
2. Set pin led pin out 5
3. Install all library : npm install
4. Test Javascript control board using johnny-five : node blink_led.js
5. Edit thsi code var serialPort = new SerialPort("/COM7", { baudRate: 9600 }); // using /COM...
6. Run full code : node brightness_control.js
7. Go to  http://localhost:8080 scroll brightness 🔆  
8. Setting Up localhost to online using ngrok : ./ngrok http 8080
