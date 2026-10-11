# Starbie
Motion and button controlled pet with an OLED display, humidity and temperature sensor and motion sensor.
It is controlled by an ESP32 C3 Supermini.
This is a guide, by SharKing Studios from Half-Life.
<img width="579" height="613" alt="image" src="https://github.com/user-attachments/assets/d56fd7dd-5942-4371-8885-3f922458eafa" />
<img width="1166" height="548" alt="image" src="https://github.com/user-attachments/assets/cd37cde7-6ccd-40a5-b8c6-01660a125d24" />
<img width="788" height="832" alt="image" src="https://github.com/user-attachments/assets/f23978a5-991a-48a4-b627-c8c1127258c9" />

Instructions
1. Solder the 10K ohm resistor onto the top left corner of the board.
2. Solder the MPU6050 onto the middle area of the board with pinheaders.
3. Solder the mechanical switches into their corners on the PCB.
4. Solder on the OLED display in the middle of the board, above the MPU6050.
5. Solder the DHT11 in between the resistor and the OLED.
6. Finally solder the ESP32 onto the right side of the board so that the USBC port just hangs off the egde.
7. You can also add some small stickers onto the tips of the corners or on the back if you have them, but this is completely optional.
And you're done!


| PART               | PURPOSE                                                                 | QTY | PRICE | TOTAL | VENDOR |

| ESP32 C3 Supermini | Control the screen and take inputs from the other parts.                |  1  | $3.05 | $3.05 | AliExpress |

| MPU6050            | Measure when and how far the starbie moves, and the temperature.        |  1  | $6.35 | $6.35 | AliExpress |

| DHT11              | Measures temperature and humidity.                                      |  1  | $1.33 | $1.33 | AliExpress |

| 0.96" OLED Display | Show the user the character, special effects, humidity and temperature. |  1  | $2.69 | $2.69 | AliExpress |

| 10KΩ Resistor      | Limit the power going to the DHT11.                                     |  1  | $3.35 | $3.35 | AliExpress |
