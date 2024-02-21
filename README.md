# Mechanism
- A PCB chess board for the ABB arm robot
- This PCB includes: 768 WS2815 leds, 64 hall sensors A3144, STM32F1C8T6, 4 MUX 16 - 4
- A magnet will be installed at the bottom of each chess to recognize its position through a hall sensor and announced by the leds. When it moves, the new position will be updated.

# PCB designing
- The top layer includes only leds and hall sensors in order to convenience, the remained components are in the bottom layer
- There are calculated repentances in order to make wiring and locating easier ( between odd cells in odd rows; between even cells in even rows; between odd cells in even rows; between even cells in odd rows)
- Here are 2 first cells in odd rows (top layer):
![image](https://github.com/doanminh2203/PCB-Chess-Board/assets/153622274/320e342b-0f71-467c-a348-4e977b1e9b29)
- Here are 2 first cells in odd rows (bottom layer):
![image](https://github.com/doanminh2203/PCB-Chess-Board/assets/153622274/a34ec632-c5ee-4da2-a4d3-46c448b11f61)

- Here is 2 first cells in even rows (top layer):
  ![image](https://github.com/doanminh2203/PCB-Chess-Board/assets/153622274/cafa992d-50ef-42d4-b57f-60ba3dcb8ab0)
- Here are 2 first cells in even rows (bottom layer):
 ![image](https://github.com/doanminh2203/PCB-Chess-Board/assets/153622274/aed1e6bc-6dff-4b6c-84b5-50cee25ccd1c)




