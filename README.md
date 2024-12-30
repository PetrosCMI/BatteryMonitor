# BatteryMonitorAft
Monitor the aft battery bank voltages
ESPHome device configuration to:
 - Monitor 3 voltages using INA3221
 - Send data over secure connection to remote MQTT broker
 - OTA updates using HTTPS request when device receives specific MQTT message
