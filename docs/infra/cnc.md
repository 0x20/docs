# CNC Machine

Work in progress. 

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


## Wiring at the gantry E-stop distribution box 
### 12-part cable
- 🔵 **Blue**: x1-limit switch
- 🟢 **Green**: x2-limit switch
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
