# Power Architecture

Battery:
3S Li-ion/LiPo

Voltage:
11.1V nominal
12.6V full


Power tree:

Battery
 |
 +---- Motor Driver
 |
 +---- Buck
          |
          +---- 5V
          |
          +---- 3.3V
                 |
                 + STM32
                 + ESP32
                 + Sensors