
```
git submodule add https://github.com/EloiStree/2025_11_21_gdp_int_s2w_input_multiplayer.git addons/2025_11_21_gdp_int_s2w_input_multiplayer
git submodule update --init --recursive
```



# 2025_11_21_gdp_int_s2w_input_multiplayer

> A tool to make a multiplayer game with lots of players using keyboard, gamepad and mouse.



I would like to make code games wiht hundred of playing in it.  
They can interact in the game with fake keyboard, gamepad and mouse.  

This code with turn 16 bytes IID S2W format to in game struct value array.

keyboard on windows is 255 true of false.   
XInput Gamepad is composed of two joystick and around 18   
A mouse as percent on the screen.    


See
- https://github.com/EloiStree/2024_08_29_ScratchToWarcraft/issues
- https://github.com/EloiStree/OpenUPM_PushGenericIID/blob/main/Runtime/STRUCT/Gamepad/GamepadByteId2020Byte99.cs
- https://github.com/EloiStree/OpenUPM_PushGenericIID/blob/main/Runtime/STRUCT/Gamepad/GamepadId2020Extra.cs
