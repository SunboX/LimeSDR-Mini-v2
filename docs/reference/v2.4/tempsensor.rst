Board temperature control
#########################

LimeSDR-Mini has integrated temperature sensor which controls FAN to keep board in operating temperature range. FAN must be connected to J9 (0.1” pitch) connector. FAN control voltage y default is 5V, but it can be changed to 3.3V by resistors.

Fan will be turned on if board will heat up to 55°C and FAN will be turned off if board will cool down to 45°C.

.. figure:: /images/LimeSDR-Mini_v2.2_temp_hysteresis.png
  :width: 600
  
  Figure 9: FAN control temperature hysteresis 




