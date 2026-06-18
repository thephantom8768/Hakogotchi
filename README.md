
## Hakogotchi

Hakogotchi is a modern take on the classic Tamagotchi, combining virtual pet care with real-world environmental interaction. Unlike traditional virtual pets, Hakogotchi's wellbeing is influenced by its surroundings. Players must manage food, entertainment, temperature, humidity, and light levels to keep their pet healthy and happy.

Designed as a "hard mode" Tamagotchi experience, the game encourages players to pay attention to their environment rather than simply pressing buttons. Environmental data collected from onboard sensors directly affects the pet's in-game status and behaviour.

The device is powered by an Orange Pi Zero 3W and features a touchscreen interface for intuitive interaction. Integrated temperature, humidity, and light sensors allow the pet to react to real-world conditions, creating a more immersive and engaging experience. 

Hakogotchi was designed with a form factor inspired by the classic Game Boy, providing a portable and comfortable handheld experience. Its vertically oriented design is wide enough to allow a secure two-handed grip while remaining compact enough for everyday carry.

Hakogotchi was created because i want to have a virtual companion but want a more modern and interactive experience (I don't like irl pets). By combining classic virtual pet gameplay with real-world sensing, Hakogotchi brings the Tamagotchi concept into the present day.

***Features***:
- 🌡️ Real-time temperature monitoring
- 💧 Humidity-based pet mood system
- ☀️ Ambient light interaction
- 📱 Touchscreen controls
- 🎮 Mini-games and activities
- 🔋 Portable battery-powered design

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

## Flashing Firmware (Android 13)
|Step|Instructions|
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|**1. Download Android Image & Tools**| Go to the [Orange Pi Official Resources page](http://www.orangepi.org/html/serviceAndSupport/index.html) and download the ***Android image*** for the Orange Pi Zero 3W. Download [**PhoenixCard**](https://drive.google.com/drive/folders/18zptJe16JLLbcpYjwEE88__DrNNGyoD0?usp=sharing), in Official Tools/Android image burning tool                                                                                                                                             |
|**2. Flash the MicroSD Card**| 1. Insert the MicroSD card into your PC and format it as **FAT32** (avoid Quick Format).<br>2. Open **PhoenixCard**.<br>3. Click **.Img File** and select the downloaded Android image.<br>4. Set the write mode to **Product**.<br>5. Select the correct MicroSD card drive letter.<br>6. Click **Burn** and wait until the process reaches **100%**. |
| **3. Boot the Orange Pi Zero 3W**     | 1. Remove the MicroSD card from the PC and insert it into the Orange Pi Zero 3W.<br>2. Connect an HDMI display, USB keyboard, and mouse.<br>3. Connect the power supply.<br>4. Wait several minutes for the first boot while Android initializes.                                                                                                     |

## Game
Not restricted to my own game, you can download other games that can run

(side-loading required as it does not have full google play service)

My game (Still in progress) will be uploaded here as .apk file when completed (gimmi 2months?).

## Zine
