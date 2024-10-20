### Project title : Conversation mission deck

### Description

Our conversation mission deck is an innovative solution to enhance the group travel experience for young adults, especially for first-year UQ international students. Two problems we found within this demographic were the prevalence of conflicting preferences and the lack of communication between group members. As such, the conversation mission deck features providing question prompts and secret missions to engage group members in conversation and various fun activities. The prompts are designed to help with their decision making and manage their preferences whilst secret missions create fun memories, and valuable bonds and improve overall travelling experiences. 

### Technologies used

The conversation mission deck consists of an Arduino Uno board, Liquid Crystal Display (LCD) screen and breadboard to manage external wiring and switches. Code for the device is uploaded from Arduino IDE.

### Requirements and Installation

- **Arduino IDE:** The Code for this project is run in Arduino IDE, if you do not have it installed, download it here: https://www.arduino.cc/en/software
- **LiquidCrystal Library:** You will need to have the LiquidCrystal library by Arduino to run the code. If this is not automatically downloaded, go to tools, manage llibrary and search “liquidcrystal” to download.
- **Hardware Setup:**
   - Components required:
      - 1 LCD module
      - 1 breadboard
      - 1 Arduino Uno board
      - 5 button switches
      - 1 potentiometer
      - 1 220 ohm resistor
      - 5 10k ohm resistors
      - 16 Male to female dupont wires
      - Plug to plug jumper wires

 - **Wiring Instructions:**
      - For wiring format refer to images shown below and standard LCD and Arduino controller board connections with breadboard intermediary.
      - Wiring notes: Wiring follows standard LCD wiring setup with potentiometer. Buttons are connected to 10k ohm resistors, LCD display connected to a 220 ohm resistor. Buttons on card connected to pin 2 and 8, pin 2 for left button prompts, pin 8 for right button secret missions. Remaining 3 buttons set up on pins 11, 12, 13.


**Refer to the following Arduino components and breadboard as shown in the image below to set up the prototype:**
 
![image](https://github.com/user-attachments/assets/8129e1a8-21e4-47e2-bbd0-1acdfba3d144)
![image](https://github.com/user-attachments/assets/4a347829-c3af-486b-84e5-56df4bddae3e)
![image](https://github.com/user-attachments/assets/3ad9a65a-08fc-4de6-b517-993a6216c061)

### Usage instructions

**Controller module:** Three buttons are set up on the breadboard to control different prompts and mission sets used for tourist groups at different locations and times. The leftmost button in the orientation of the image below switches the prompts and missions set to the one generated for COEX Mall, Seoul, Korea at 4pm. The middle button is for Sydney Opera House, Sydney, Australia at 10:03am and the rightmost button is for Shinjuku, Tokyo, Japan at 7:04pm. This was designed to simulate the user’s experience when using this device at different locations and times.

![image](https://github.com/user-attachments/assets/4f39b647-f5f7-497a-a30b-1b6cb70fc085)


A potentiometer (white) is also installed in the following configuration to control the brightness of the LCD screen display.

 
![image](https://github.com/user-attachments/assets/bd050ea4-aba9-4c9c-b175-ce744d85b44b)

**Display module:**  Pressing the left button allows users to be shown a question prompt on the LCD screen whilst the right button provides secret missions for the group to take part in. 
![image](https://github.com/user-attachments/assets/b09a153c-fd8f-4428-9615-6fb39c4d29a0)


### Source Code

The source code for the Conversation Mission Deck can be found  [here](https://github.com/brianch01/DECO3500-The_Visionaries/blob/main/src/conversationMissionDeck/conversationMissionDeck.ino)
