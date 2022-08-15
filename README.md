# esphome-garden-pump

ESPHome garden pump controller script

Assuming pumps are DC motors driven with PWM trough MOSFETs

Power ant on-time is regulated separately for each channel (script shows only one channel)

Switch allows to activate each pump for specified time and with specified power (60s is max running time for anti-flood protection reasons)

Settings are saved to ESP memory
