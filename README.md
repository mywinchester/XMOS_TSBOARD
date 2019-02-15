# XMOS_TSBOARD
An test board for XMOS + DSD1794 audio DAC hardware solution.

## Please make sure:
- You had been review all schematics and you know where was right or wrong.
- You had been check BOM table with your components supplier.
- You can bear all the risks of production failure.

## Description
- Power supply can be DC_5V or USB for this board. When **J1**__Pin1_ connected to **J1**__Pin2_, DC_5V supplied power, when **J1**__Pin3_ connected to **J1**__Pin2_, it suppiled by USB.
    - **ALARM: DO NOT CONNECT J1 _Pin1_ AND _Pin3_ AT THE SAME TIME!**

- **J2**__Pin1_ connected to **J2**__Pin2_, DC power whill direct through the circuit; When **J2**__Pin3_ connected to **J2**__Pin2_, DC power will pass the isolated power module(if it exists) then powering the circuit.
    - **ALARM: DO NOT CONNECT J2__Pin1_ AND J2_Pin3_ AT THE SAME TIME!**

## Connect me
E-mail: `winchester.mygod@hotmail.com`

Twitter: `@MygodMak`

I will check inbox in my free time.

---
### END