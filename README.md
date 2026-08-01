# The-Sax32TM
This is a simple devboard utilizing the ESP32-S3-WROOM-1 chip. Designed by me to really understand how the ESP32 works and all those little components on the front do, while also giving me a little more experience with creating devboards now.  (Being displayed at Opensauce!)

**[THE WORKING VIDEO DEMO!!](https://youtu.be/G2ZkvX7cIcQ)**


**FINAL SHOTS:**
<img width="2268" height="4032" alt="IMG_7620" src="https://github.com/user-attachments/assets/020830fd-4b2a-4f09-8972-68cd36ada17e" />
<img width="4032" height="2268" alt="IMG_7621" src="https://github.com/user-attachments/assets/b9000e8b-87db-4aab-aace-88950728bd40" />
<img width="4032" height="2268" alt="IMG_7622" src="https://github.com/user-attachments/assets/098c3c2c-266a-4a94-a916-f4b190bb6ffa" />



**3D VIEWER:**
[Sax32 BOM.csv](https://github.com/user-attachments/files/30619961/Sax32.BOM.csv)


<img width="796" height="504" alt="image" src="https://github.com/user-attachments/assets/d669e20d-862d-4d42-918e-6fb07c967994" />
<img width="975" height="630" alt="image" src="https://github.com/user-attachments/assets/b508f2fa-8a46-4d8d-bf1a-0a0b047adc8a" />


**THE SCHEMATIC:**

<img width="1359" height="925" alt="image" src="https://github.com/user-attachments/assets/e37aa620-f566-408c-b0fa-07ebe4b64414" />


**PCB EDITOR:**


<img width="357" height="723" alt="Screenshot 2026-06-14 at 10 48 29 AM" src="https://github.com/user-attachments/assets/a28b498a-0e37-44fb-acac-e5d89e40d6bd" />

Id,Designator,Footprint,Quantity,Comment,Supplier and ref
1,"BOOT, RST",SW_Push_SPST_NO_Alps_SKRK,2,SW_SPST,
2,"C1, C4",C_0603_1608Metric,2,100nf,
3,"C2, C5",C_0603_1608Metric,2,10uf,
4,C3,C_0603_1608Metric,1,22uf,
5,D1,LED_0603_1608Metric,1,RED,
6,D2,LED_0603_1608Metric,1,GREEN,
7,D3,LED_0603_1608Metric,1,BLUE,
8,"J1, J2",PinHeader_1x20_P2.54mm_Vertical,2,Conn_01x20_Pin,
9,J3,USB_C_Receptacle_HRO_TYPE-C-31-M-12,1,USB_C_Receptacle_USB2.0_16P,
10,"R1, R2, R3, R4, R5, R6",R_0603_1608Metric,6,5.1k,
11,U1,SOT-223-3_TabPin2,1,LD1117S33TR_SOT223,
12,U3,ESP32-S3-WROOM-1,1,ESP32-S3-WROOM-1,
