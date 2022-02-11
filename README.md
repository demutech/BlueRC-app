# BlueRC-app is an android app for adaptive universal ESP32 bluetooth remote control base on bluetooth communication. 

It works together with BlueRC Shield for ESP32 D1 R32 or Arduino Uno and ESP32BlueRC-EEPROM Arduino sketch.

Software requirements smartphone > Android 3.2. <br>
Hardware requirements see repository ESP32-BlueRC-project.

# Operation Manual 
1. Download BlueRC App V1.0, and install it on your android mobile phone.

2. Power on your ESP32 BlueRC hardware.

    ![Sensor-shield-with-ir-transmitter-module-small](https://user-images.githubusercontent.com/13086712/153450858-13bf97f1-aab4-4c2b-aac0-fc99e75df266.jpg)

3. Launch the app, if your bluetooth is not opened, app will ask you for permission, click on accept.
    ![App-ui-small](https://user-images.githubusercontent.com/13086712/153447898-6402ca69-1594-4861-ae32-7a877686b7f4.jpg)
    ![Bluetooth-permission-small](https://user-images.githubusercontent.com/13086712/153448866-d77c2f2c-8dd6-422a-b3ac-0093ebc0a420.jpg)

4. Click on the 3-point symbol in the upper-right corner, then click on the menu "Connetct BT Device". 
   In the very first time you have to pair your ESP32 BlueRC Shield, click on "Scan for devices", 
   then wait until "ESP32BlueRC-Shield" appears under "Other Available Devices", click on it, then confirm pairing. 
   In the line of Status should show now "connected:ESP32BlueRC-Shield". Now you can begin learning the buttons.
   
    ![Main-menu-small](https://user-images.githubusercontent.com/13086712/153449058-d5607910-5fc6-441b-a427-26010ea24e1a.jpg)
    ![Connect-menu-small](https://user-images.githubusercontent.com/13086712/153449480-7348e842-1338-4266-b6f8-ae58c5ddf36b.jpg)

5. Learning: Longclick button "LEARN", system message shows "Learning beginns, please press a button within 10 seconds...",
   then press the button which you want to learn. After that, press the same button on your TV remote control. 
   The ir code of this button will automatically stored in the hardware. Immediately you can use this button.
   
6. Repeat step 5 for other buttons.

7. Once the hardware is paired, you just need to click on "ESP32BlueRC-Shield" under "Paired Devices", Scan is not necessary.

That's it. Congratulations and enjoy your BlueRC!
