This is a simple 
[resistor color code](https://en.wikipedia.org/wiki/Electronic_color_code) 
decoder for HP35s calculator.
It supports 4, 5 or 6 bands.
The program displays simple menu with abbreviated colro names. 

![screenshot1](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-2.png)

To select color of a band
press number corresponding to the color and confirm by [R/S].
To display next part of the menu press [R/S] without any number.
To calculate the value pass through all the menus without entering
any number [R/S][R/S][R/S].

The result is pushed to X stack register and sldo pushed to  R register.

Enjoy!

# Step-by-step Tutorial

Let's say resistor whose resistance you want to decode is ths one:

![resistor](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/resistor.png)

1. Run the program

![screenshot1](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-1.png)

and press [ENTER].

2. Menu with color code is displayed

![screenshot1](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-2.png)

BLK stands for black, BWN is brown, RED is red.

3. As the color of first band is brown press "2":

![screenshot3](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-3.png)

and confirm by pressing [R/S]. The value of the first band is stored 
and menu is displayed again:

![screenshot1](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-2.png)

4. Second band is black. Press "1"

![screenshot4](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-4.png)

and confirm by [R/S]. Menu is displayed again:

![screenshot1](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-2.png)

5. Third band is orange, but this color doesn't appear in the menu.
Press [R/S] button to display second part of the menu:

![screenshot5](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-5.png)

ONG here stand for orange, YLW is yellow and GRN is for green.
For orange press "4" and confirm by [R/S]. First menu is displayed again.

6. As this was last band jump through all the menu with [R/S] to display the result:

![screenshot2](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-2.png)

press [R/S]

![screenshot5](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-5.png)

press [R/S]

![screenshot8](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-8.png)

press [R/S]

7. And _voilá_! Result is displayed


![screenshot9](https://raw.githubusercontent.com/petrst/HP35s-Resistor-Color-Code-Calculator/main/screenshots/screenshot-9.png)

10 kΩ
