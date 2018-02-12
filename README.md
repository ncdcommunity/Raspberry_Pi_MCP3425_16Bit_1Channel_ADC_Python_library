[![ MCP3425](MCP3425_I2C.png)](https://store.ncd.io/product/mcp3425-16-bit-1-channel-analog-to-digital-converter-i2c-mini-module/).

#  MCP3425

The MCP3425 is a 1-Channel Analog to Digital Converter with 16-Bit resolution, ideally suited for low-speed high-resolution sensor monitoring.The MCP3425 is capable of reading analog voltages at 15 samples per second with 16-Bit resolution or 240 samples per second at 12-bit resolution. The MCP3425 has an x1, x2, x4, x8 programmable gain amplifier, making it an ideal choice for monitoring extremely low-voltage sensors. The MCP3425 has a single differential input, capable of monitoring a full scale range of 4.096VDC or ±2.048v differentially.
This Device is available from www.ncd.io 

[SKU: MCP3425]

(https://store.ncd.io/product/mcp3425-16-bit-1-channel-analog-to-digital-converter-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MCP3425 16bit 1channel ADC With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mcp3425-16-bit-1-channel-analog-to-digital-converter-i2c-mini-module/">MCP3425 16bit 1channel ADC</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MCP3425.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
