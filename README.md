# final-project
Temperature sensor for logging temp over night to review in the morning.
DHT11 sensor collects the data and shares it with the user. 
LED is used for quick temp check so you do not have to log into your computer.
Temp read script is used to read and log data onto an excel spread sheet.
Run by opening terminal on a computer and searching for the file, Once found type python then file name to run.


Hardware
1 esp32
1 breadboard 
1 DHT11
1 resistor (220 ohm)
1 led 
1 usb cable
jumper wires

Setup Hardware Connecting DHT11 and LED to esp32

1. Make sure that the esp32 is disconected from the computer.
2. connect DHT11 to breadboard (check pinout to see whats Positive negative and S)
3. Connect 3v3 on the esp32 to positive rail on breadboard with jumper wire.
4. Connect grnd on the esp32 to negative rail on breadboard with jumper wire.
5. Connect positive on DHT11 to the positive rail on the breadboard with jumper wire.
6. connect negative on DHT11 to the negative rail on the breadboard with jumper wire.
7. connect S on DHT11 to D34 on Esp32 with jumper wire.
8. Connect LED to breadboard. Be sure to see which side is long (positive) and which side is short (negative)
9. Connect short side (negative) to the negative rail with a jumper wire.
10. Connect the long side (positive) to one side of the resistor (220 ohms)
11. connect the other side of the resistor to D4 on the esp32.
12. Check to see if your wiring is correct.
   
Exicuting on the computer

1. Once done connect the esp32 to the computer 
2. open thonny and save esp32 to your esp32 as main.py (Change com to one that your computer is using)
3. Run the script when saved.
4. check Repl to see if the script is running.
5. if running exit the repl and open terminal on computer
6. navigate to file that has temp read in it.
7. once in file type Python temp read
8. the script should initialize and start recording data from the DHT11 and storing it in a csv file in the folder that the script was initialized from.
9. Check folder to see if csv has been created.
10. congratulations you are done.   
    
