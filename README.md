# 3D Dice Roller
3D Dice Roller is a WebGL-based application that allows users to roll customizable 3D dice with realistic physics. The application supports dice with 4, 6, 8, and 12 sides, rendered as 3D shapes with textures and lighting. The result of each roll is determined by real-time physics simulation.

# User Manual
To run the application properly, the machine should be capable of:
1. Running WebGL 2 in the web browser
To check if your browser supports WebGL 2 you can access this link:
```
https://get.webgl.org/webgl2/
```

2. Starting a local server
Starting a local server can be done using Python inside the directory of the HTML file
```python
python -m http.server 8080
```
After starting the local server, in your web browser, you should be able to access this link:
```
http://localhost:8080/dices.html
```

You can now use the 3D Dice Roller Application

![image](https://github.com/user-attachments/assets/625dd8cb-0db9-4416-ac08-d0560b2bd967)

Clicking D4, D6, D8, and D12 buttons will add a specific Die in the rolling field

![image](https://github.com/user-attachments/assets/3a85b592-5c9b-4a5b-aa7b-fbd1c84086ec)

The maximum number of dice in the field is 2, if you try to add more, you will receive this alert message:

![image](https://github.com/user-attachments/assets/6392b082-895d-4c87-bec4-244b56582877)

After adding your chosen Dice, you can click the 'Roll' button or simply press spacebar to start rolling the dices

![image](https://github.com/user-attachments/assets/e6f28937-0c66-4a18-9562-d0e4fed6268e)

After rolling, you will now be able to see the value of your roll at the bottom side of the window

![image](https://github.com/user-attachments/assets/69113c65-821d-4812-9cf0-820c65a0df33)
![image](https://github.com/user-attachments/assets/b6914b6b-2196-4cfc-826a-909821f40343)


Receiving a High Roll when using 2 dices will show some lighting effects as an indication

![image](https://github.com/user-attachments/assets/83010d35-5f0c-4646-bd33-1c9ae790327d)

To Terminate the application, simply stop the server by Pressing Ctrl + C in the terminal where you've started the local server

![image](https://github.com/user-attachments/assets/d4e9e495-419d-44ce-9f72-475546a3c873)







