# WLED Remote
WLED Remote Controller (Lilygo T4 S3)

My goal was to create a small, portable, touchscreen-based remote to send commands to my WLED controller.

Hardware Components for Remote Controller:
+ **Lilygo T4 S3**
+ **EEMB Lithium Polymer Battery 3.7V 1100mAh (603449)**
+ **Vertical Micro Slide Switch (SS-12D00, 3 Pin, 2 Pos)**
+ **MagSafe Ring**

For that I designed [a complete 3D printable case](https://makerworld.com/en/models/973948#profileId-946226).

The wireing is quite simple since the lilygo board already has a LiPo battery connector:

<img width="601" alt="Screenshot 2025-01-19 at 09 47 45" src="https://github.com/user-attachments/assets/dcc1ce7e-b38c-4db9-b56b-eba25d8046b3" />

The remote runs on ESPHome and uses LVGL components.

The final GUI supports:
+ **relay control** (page 1)
+ **color & brightness** (page 2)
+ **effects control** (page 3)

<img width="1427" alt="Screenshot 2025-01-19 at 09 49 38" src="https://github.com/user-attachments/assets/a721e742-237e-4a8e-8eee-b7703a0a6554" />
