
# Hakogotchi
Hakogotchi is a tamagotchi that simulates a pets that depends on its environment to survive. Players must carefully manage food, entertainment, light levels, temperature, and humidity to keep their pet healthy and happy. It turns virtual pet care into a challenging environmental management experience, basically tamagotchi on hard mode! 

Basically the modern twist of the vintage button tamagotchi and the size of a smartphone ( a little chunky thou). It is powered by a Radxa Zero 3W that provides modern computing power and the ability for touchscreen to control and play. Moreover, it has temperature, humidity and light sensor that allows the pet to feel the enivronment and affect its stats in-game. 

I wanted to make it because i'm not a pet person but wanted a way to enjoy taking care of something and be entertaining at the same time daily while making it more modern to my taste.

## Wiring Schematic
<img width="1110" height="798" alt="wiring schematics" src="https://github.com/user-attachments/assets/a885ae00-0209-474c-b771-0817165c1d95" />

## 3D Model

<table>
  <tr>
    <td><img width="385" height="616" alt="image" src="https://github.com/user-attachments/assets/cf672c1e-390e-484f-b22d-a77cbd1df89f" />
</td>
    <td><img width="756" height="532" alt="image" src="https://github.com/user-attachments/assets/db9ef7bc-2896-413d-b86b-c950dcc6d430" />
</td>
  </tr>
  <tr>
    <td><img width="661" height="534" alt="image" src="https://github.com/user-attachments/assets/51f8405a-ca68-4b7a-b74b-7155c0798049" />
</td>
    <td><img width="586" height="541" alt="image" src="https://github.com/user-attachments/assets/991854f4-e1e2-4b24-b8a4-ca32d221b3c5" />
</td>
  </tr>
</table>

🟥RED = +wire
⬛BLACK = -wire
🟩GREEN = Data wire
🟧ORANGE = Audio wire

## Bill Of Materials
<img width="1184" height="586" alt="BOM" src="https://github.com/user-attachments/assets/b57151c8-ba51-43d4-a4cf-e52cbc0abcc6" />

## Flashing Firmware (Android)
|Step|Instructions|
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|**1. Download Android Image & Tools**| Go to the Orange Pi Official Resources page and download the Android image for the Orange Pi Zero 3W. Download **PhoenixCard**, the official tool used to flash Android images to Allwinner-based boards.                                                                                                                                             |
|**2. Flash the MicroSD Card**| 1. Insert the MicroSD card into your PC and format it as **FAT32** (avoid Quick Format).<br>2. Open **PhoenixCard**.<br>3. Click **Img File** and select the downloaded Android image.<br>4. Set the write mode to **Product**.<br>5. Select the correct MicroSD card drive letter.<br>6. Click **Burn** and wait until the process reaches **100%**. |
| **3. Boot the Orange Pi Zero 3W**     | 1. Remove the MicroSD card from the PC and insert it into the Orange Pi Zero 3W.<br>2. Connect an HDMI display, USB keyboard, and mouse.<br>3. Connect the power supply.<br>4. Wait several minutes for the first boot while Android initializes.                                                                                                     |
