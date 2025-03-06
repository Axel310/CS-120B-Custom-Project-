			                          # CS-120B-Custom-Project-
           				 Custom Laboratory Project for CS-EE120B Embedded Systems 
                     			 Title: "The Scary Maze Game" 

Description: 
  The scary maze game is a two-dimensional game where the player controls an in-game character, where they will use a joystick to navigate from left to right, up and down to complete the maze. If the user fails to complete the maze, the user will be jumpscared by a sprite and message and will be forced to restart the maze. However, if the user completes the maze, the display will upload another happy sprite with a message followed.
	The three complexities that were used in this porject include the usage of the ST7735S Display, the two sprites I created on the ST7735S, and passive buzzer, which I used to create a background song for the maze, and the sound effects for the jumpscare and completing the maze.

Build Upons: 
  1. ST7735S Display
  2. 2 Sprites that were created via C programming
  3. Music and Sound effects created using the component --> Passive Buzzer

User Guide: 
  Initially the user will be prompted with a black screen, the user will have the ability to turn on/off the display with the button. Once the user presses the button, the display will turn on, and “start game” and “exit game” will display. If the user presses the exit option, the game will be exited. If the user selects “start game”, the game will start and background music will play as the user navigates through the maze. If the user hits the white walls they will fail the maze, and will be jumpscared by a sprite and a sound effect. After the jumpscare, the user has the option to turn the system off with the button or reset the game with a joystick press. However, if the user completes the maze the game will display a happy face sprite and a sound effect will output on the passive buzzer. 

Hardware Components: 
1. ATMega328 Microcontroller
2. ATMega328 EEPROM to store game state
3. Bread board
4. Joystick (input)
5. Start and Restart (input) (1 Button programmed to both turn on and off game) 
6. HiLetgo ST7735S Display (128 x 160)
7. Sound Buzzer

Wiring Diagram: 

![image](https://github.com/user-attachments/assets/3d8f43d9-37f7-4808-943b-3491eba02bbc)
![image](https://github.com/user-attachments/assets/c61f3752-e425-4892-a899-5959e329fccd)


Link to Video: 
https://youtu.be/l-LC4amEOqI




