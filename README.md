**Work-In-Progress**: [Gerbers ready](https://github.com/mwrnd/QSFP_Breakout/releases/tag/v0.1.1-alpha) but not yet ordered.


# QSFP Breakout

[QSFP](https://en.wikipedia.org/wiki/Small_Form-factor_Pluggable#QSFP) to [U.FL/UMCC Connector](https://en.wikipedia.org/wiki/Hirose_U.FL) breakout.

Additional I2C circuitry is due to this being a stepping stone project for an [OpenCAPI](https://files.openpower.foundation/s/xSQPe6ypoakKQdq/download/25Gbps-spec-20171108.pdf) to **dual** QSFP design. OpenCAPI has only a single I2C interface.


# PCB Layout

![QSFP Breakout PCB Layout](img/QSFP_Breakout_PCB_Layout.png)

All differential signals are length-matched to within 1mm of a 25mm total length, both inter-pair and intra-pair.


# Schematic

![QSFP Breakout Schematic](img/QSFP_Breakout_Schematic.png)


# PCB Layer Stackup

4-Layer PCB stackup taken from [JLCPCB](https://jlcpcb.com/capabilities/pcb-capabilities).

![PCB Layer Stackup](img/Layer_Stackup.png)

100-ohm Differential Impedance parameters were calculated using the [DigiKey Online Calculator](https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-pcb-trace-impedance).

![PCB Differential Impedance Calculation](img/PCB_Impedance_100ohm_0.2329mm_0.2032mm_on_0.21mm_7628.png)

