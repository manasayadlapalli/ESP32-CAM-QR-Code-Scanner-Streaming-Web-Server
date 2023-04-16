# ESP32-CAM-QR-Code-Scanner-Streaming-Web-Server
Using Arduino IDE

This is CMPE 286 course work project.
<p align="center">
 <img src = "https://user-images.githubusercontent.com/87613567/232347183-57a2839a-0a8a-4afd-9c34-cb6dd1200df5.png" alt = "Tools" height="290" width ="400" />
</p>

### Steps to run the project:
1. Download Arduino IDE on your computer. I found Version 1.8.11 working fine.
2. Once installed, go to Sketch -> include library -> Attach the provided QR code library
3. Change Tools settings as follows
<p align="center">
 <img src = "https://user-images.githubusercontent.com/87613567/232340198-74c998d3-2995-4507-ae10-1ca70696e738.png" alt = "Tools" height="370" width ="400" />
</p>
4. Copy the entire SP32_Cam_QR_Code_Scanner_Stream_Web_Server_SM.ino file and paste it on Arduino IDE. <br/>
5. In the File -> Preferences, update additional board manger URL <br/>
<p align="center">
 <img src = "https://user-images.githubusercontent.com/87613567/232341155-ece81b13-8a9c-4bb2-b9f4-37d130fc4cf6.png" alt = "Tools" height="250" width ="430" />
</p>

5. Connect the ESP32-CAM Ai-Thinker and USB to TTL converter into one piece and connect the entire things to a computer using Micro USB data cable.
<p align="center">
 <img src = "https://user-images.githubusercontent.com/87613567/232341025-5ae1e8ac-f675-4630-be23-f1fdd0ef97db.png" alt = "Tools" height="210" width ="400" />
</p>


6. Now, Click on verify and upload code buttons on IDE. <br/>
7. Open COM serial monitor, paste the server URL on any browser to view the live stream. <br/>
8. Now, you can go ahead and display any QR code to ESP32 CAM to scan it. The data/URL inside the QR code gets displayed on the live streaming HTML page.




