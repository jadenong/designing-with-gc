# Code for my 2020 draft
## Equations

(All lines have the thick, bold, continuous style.)

YELLOW Y1 = |0.633X| / (3 <= X or X <= -3)  
GREEN Y2 = -|0.633X| / (3 <= X or X <= -3)  
YELLOW Y3 = -sqrt(3.6^2 - X^2)  
GREEN Y4 = X^{2/3} + sqrt(5 - X^2) - 0.65  
GREEN Y5 = X^{2/3} - sqrt(5 - X^2)  
PINK Y6 = -10  
LTBLUE Y7 = sqrt(10 * (1-X^2 / 15)) + 5  
LTBLUE Y8 = -Y7 + 12.25  
DARKGRAY Y9 = -Y7  
DARKGRAY Y0 = -Y8  

## Window
ShadeRes = 6  
Xmin = -16.09756098  
Xmax = 16.09756098  
Xscl = 1  
Ymin = -10  
Ymax = 10  
Yscl = 1  
Yres = 1  
\DeltaX = 0.12195121954545  
TraceStep = 0.2439024390909  

## Format
RectGC
CoordOff
GridOff
GridColor: MEDGRAY
Axes: OFF
LabelOff
ExprOff
BorderColor: 4
Background: BLUE
Detect Asymptotes: On
