# HowtoArduino

## Setup

for using arduino ide, you have to give the usb port permission

```
ls -l /dev/ttyUSB*
sudo usermod -a -G dialout <username>
```

## Serial communication

The arduino IDE contains a window that displays the serial data received from the 

```
void setup() {
  Serial.begin(115200);
  Serial.println("Hello Arduino\n");
}
```
