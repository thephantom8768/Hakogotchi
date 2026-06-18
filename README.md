
<table>
<tr>
<td width="40%">

<img width="400" height="617" alt="dPA1mnMY" src="https://github.com/user-attachments/assets/ee7d8db4-c5e1-4ee8-8495-638d8d1ff8ce" />


</td>

<td width="60%">

<h3>Hakogotchi</h3>

Hakogotchi is an environment-aware virtual pet inspired by the classic Tamagotchi. Using real-world temperature, humidity, and light data, players must care for their pet while managing the environment around it.

Built on the Orange Pi Zero 3W, Hakogotchi combines touchscreen controls, environmental sensors, and a Game Boy-inspired handheld design to create a modern virtual companion experience.

**Features:**
- 🌡️ Real-time temperature monitoring  
- 💧 Humidity-based pet mood system  
- ☀️ Ambient light interaction  
- 📱 Touchscreen controls  
- 🎮 Mini-games and activities  
- 🔋 Portable battery-powered design  

***Inspiration:***

I've always wanted to have a companion but don't want the heavy responsibilities of IRL pets. Thus with Hakogotchi, I can still simulate having a pet without the stress and long-term commitment of real-life care.

</td>
</tr>
</table>


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
