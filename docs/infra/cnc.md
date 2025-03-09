# CNC Machine

The space has a 3 axis CNC machine based on the High-Z S-720 from [CNC-STEP](https://www.cnc-step.com/high-z-s-720-cnc-router-720-x-420-x-110-mm-trapezium-screws/). To use the machine either 1T, Elvis, Teus or Sander should be present. 

## Safety
The machine has two E-stops (emergency stops). One is located on the x-axis gantry and another one on the controller electronics box. When pressed they cut the voltage to the spindle, motors and controller board. ``TODO: FACT CHECK``. 

When operating the machine:
- Don't go near the moving axis or spindle
- Always Wear earprotection
- Don't leave it unattended
- Stay attentive and be ready to hit the e-stop

## Getting started guide

# Wiring 

Overview of wiring.

## Wiring at the gantry E-stop distribution box 
### 12-part cable
- 🔵 **Blue**: x1-limit switch
- 🟢 **Green**: x2-limit switch
- 💿 **Gray**: y-limit switch
- 🌸 **Pink**: z-limit switch 
- 🟡 **Yellow**: Ground
- 🧬 **Shielding**: Ground
- 🟤 **Brown**: c-limit switch
- 🔴🔵 **Red and Blue Striped**: E-stop button located on the gantry.
- 🟠💿 **Orange and Gray Striped**: E-stop button located on the gantry.
- 🔴 **Red**: Not Connected
- ⚫ **Black**: Not Connected
- 🟣 **Purple**: Not Connected
- ⚪ **White**: Not Connected
### 3-part cable for the x2 limit-switch 
- 🟢 **Green**: x2-limit switch
- ⚪ **White**: Ground
- 🟤 **Brown**: Not Connected
## Wiring at the DB9 ST-connector  

1) 🟤 **Brown**: c-limit switch  
2) 🔵 **Blue**: x1-limit switch  
3) 💿 **Gray**: y-limit switch  
4) 🌸 **Pink**: z-limit switch  
5) 🔴🔵 **Red and Blue Striped**: E-stop button located on the gantry.  
6) ⚫ **Black**: Not Connected  
7) 🟢 **Green**: x2-limit switch  
8) 🟠💿 **Orange and Gray Striped**: E-stop button located on the gantry.  
9) 🟡 **Yellow**: Ground  
10) 🧬 **Shielding**: Ground

## Extra
### Communication

You can connect to the controller over USB or using the network. 

## USB

1. Download putty
2. Choose "Session"
3. Select the checkbox for Serial.
4. Continue

Then it you will see the IP adress of the machine. At the moment it is ´´10.51.3.252´´

## Network 

1. Grab the IP using the USB method.
2. Go to the addres

**Settings**
Interface IP mode, default value driver dependent, set to 0 for static addres: ´´$3x1=0´´




