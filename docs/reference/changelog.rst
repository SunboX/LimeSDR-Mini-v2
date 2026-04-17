Changelog
#########

RF loopback
***********

LimeSDR Mini v2.X encountered a change of shunt transistor VT3 in the RF feedback attenuator chain due to the original part becoming EOL. The original part BFT92,215 had a small output capacitance of around 1.2 pF, whereas the new RF transistor ZVN4525E6TA has a larger output capacitance of 11 pF. An extract of the schematic is presented in Figure 1.

.. figure:: /images/LimeSDR-Mini_Attenuator_v1_vs_v2.png
  :width: 600
  
  Figure 1: LimeSDR Mini RF loopback attenuator implementation on v1.x and v2.x boards

The increased shunt capacitance affects a frequency response of the attenuator. The attenuation is −46 dB at 1 GHz and −52 dB at 2.1 GHz for the new LimeSDR-Mini v2.X board. The frequency response shown in Figure 2 can be used as a reference RF loopback attenuation in the supported frequency range. 

.. figure:: /images/LimeSDR-Mini_v2.2_RF_LB_response.png
  :width: 600
  
  Figure 2: LimeSDR Mini v2.x RF loopback frequency response