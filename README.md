# WLED Remote
WLED Remote Controller (Lilygo T4 S3)

My goal was to create a small, portable, touchscreen-based remote to send commands to my WLED controller.

Hardware Components for Remote Controller:
+ **Lilygo T4 S3**
+ **EEMB Lithium Polymer Battery 3.7V 1100mAh (603449)**
+ **Vertical Micro Slide Switch (SS-12D00, 3 Pin, 2 Pos)**
+ **MagSafe Ring**

For that I designed [a complete 3D printable case](https://makerworld.com/en/models/973948#profileId-946226).

![2025-01-10_oclj5dcp1ilm](https://github.com/user-attachments/assets/17b21df0-d27a-4663-83c9-23b3a8c22528)

![2025-01-10_hyt3c2m0mt6z](https://github.com/user-attachments/assets/0c7d9f86-9788-40d1-9297-77a8de6b4660)

![2025-01-10_ktf1zs0ez7rm](https://github.com/user-attachments/assets/7d4672e6-e2c9-4af1-8665-cd3a1e9a613c)

The wireing is quite simple since the lilygo board already has a LiPo battery connector:

<img width="601" alt="Screenshot 2025-01-19 at 09 47 45" src="https://github.com/user-attachments/assets/dcc1ce7e-b38c-4db9-b56b-eba25d8046b3" />

The remote runs on ESPHome and uses LVGL components.

The final GUI supports:
+ **relay control** (page 1)
+ **color & brightness** (page 2)
+ **effects control** (page 3)
+ **settings control** (longpress tab 1)

<img width="1493" alt="Screenshot 2025-01-20 at 17 04 44" src="https://github.com/user-attachments/assets/2ce0e046-93f3-4e5a-af55-67b6e12cfacc" />

![IMG_6638](https://github.com/user-attachments/assets/3d03886c-c3a4-44cb-b24c-e5d24dc3571e)

![IMG_6639](https://github.com/user-attachments/assets/f425c645-aa31-4b33-9a2c-50df2af1b459)
