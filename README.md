# AD7124-4 24bit Analog Sensor FeatherWing Design Files

This is a new Feather compatible board for reading precision analog sensors like load cells, thermocouples, and strain gauges. It uses the AD7124-4, a 4 channel, 24 bit, differential ADC (Can also be configured as 7 single ended channels). Like the [6 Channel 24 bit Featherwing](https://github.com/NHBSystems/6Ch-24bit-FeatherWing-PCB) this board is designed for lower power, monitoring type applications, however it can also be configured for significantly higher sampling rates than the AD7794. The board also includes a low pass anti-aliasing filter on the inputs, a 5th input pin for a shield wire connection, and software enabled excitation voltage without using an additional pin.

**Specifications**

- RMS noise down to 23 nV at 9.4 SPS
- Low power operation with 3 conversion power modes
- Power-down current of 5 μA maximum (AD7124 chip)
- Low noise, programmable gain instrumentation amplifier (1 to 128)
- Band gap reference with 10 ppm/°C drift typical
- Simultaneous 50 Hz/60 Hz rejection at 25 SPS
- Update rate: Up to 19200 sps (per datasheet for single channel)
- 4 differential analog inputs, (or 7 single ended)
- Independent configuration of each channel
- Low pass anti-aliasing filter on inputs
- 5 pin connections with excitation, ground, and shield for each channel
- Shield can be tied to chassis or to ground (trace jumper on bottom)
- On board 2.5v LDO controlled in software without needing additional pin
- Software enabled bias voltage on all channels (for reading thermocouples)


This board can be purchased assembled here: [24 bit Analog Sensor FeatherWing](https://www.tindie.com/products/24680/)


<a href="https://www.tindie.com/stores/jtinker/?ref=offsite_badges&utm_source=sellers_jtinker&utm_medium=badges&utm_campaign=badge_medium"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-mediums.png" alt="I sell on Tindie" width="150" height="78"></a>

