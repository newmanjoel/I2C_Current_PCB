# I2C_Current_PCB

# Ideas
Use a RP2040 interfacing with an an ADC and DAC to send/receive current. 

Should be able to interface with the RP2040 over I2C, USB, or Ethernet.

## Adc
Should be at least 12 bit (to account for noise in the system). Can be buffered by op amp to give it more power for sending.

## Dac
Should be as good as the Adc. Need to decide if I want hall effect or resistor. If I go with resistor I should buffer with differential amp into Adc.

