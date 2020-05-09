# ESP8266 Clock
## ORIGINAL PROJECT
A clock made with NodeMCU ESP8266 with an I2C based 1602 LCD display which shows timelines of 16 different cities all over the world.Utilising pool.ntp.org via NTP for getting the time and day. Using the push button to change the the city of display. The cities can be configured as required.

### Materials -

NodeMCU ESP8266 12E,LCD display 16X2,I2C,Push Button,10k ohms Resistor,Jumper Wires,Breadboard,Power Bank.

### Input

The pushbutton is the input here, when pressed it sends signal to the microcontroller.

### Microcontroller

NodeMCU ESP8266 is used in this project, which recieves signal from the push button and changes the city, hence the time to be displayed in the LCD display.

### Output

The output display used here is the 1602 LCD display, which shows the time of a particular city, and changes the city, hence the time when the ESP8266 sends a signal (when the pushbutton is pressed)

## BETTER SOLUTION

### Input 

A push button is one of the best choices to use here, as the clock is in the vicinity of the user and close to the user. Obviously a motion sensor can be used to make switching cities forwward and backward for more convinience( too expensive) or a remote can be used made of numbers to see a city is displayed as designated to a fixed number.

### Microcontroller

Any microcontroller with a wifi module can be used , but ESP8266 is the best bet as its a wifi microcontroller, ESP32 can be used if the features of the clock need to be expanded as well as if bluetooth based repeater clocks need to be set up. Also ESP32 helps as it has a deep sleep feature.

### Output

An LED display can be used instead of an LCD display, or a 7-segment one can be used as thats its function. But again LED displays can be expensive, and gives higher resolution which is not required unless we want to add features.

## An Alternative Approach

An arduino can be used, and with the millis() function the clock can calculate the difference between a particular time and give out the display correspondingly. But the setting of time may be difficult and a solution shpuld be put up for it.
