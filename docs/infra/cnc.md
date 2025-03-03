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


## Wiring at the x-axis
- ⚫ **Black**: Not Connected
- 🔴 **Red**: Not Connected
- 🔵 **Blue**: To Be Determined
- 🟢 **Green**: x-limit switch on the opposite side of the x-axis stepper
- 🟡 **Yellow**: Ground
- 🟣 **Purple**: Not Connected
- ⚪ **White**: Not Connected
- 🟤 **Brown**: limit switch for the x
- 🔴🔵 **Red and Blue Striped**: E-stop button located on the gantry.
- 🟠💿 **Orange and Gray Striped**: E-stop button located on the gantry.

