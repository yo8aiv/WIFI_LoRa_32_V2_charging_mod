Tutorial for use with meshtastic , device WIFI_LoRa_32_V2.1

as V2 devices are using TP4054 wich seems by (generally) default has a 10k resistor on pin5 PROG
wich in turn sets charging current to onky 100mA if a liPo baterry is used to power the board

Sollution is to change R9 to a smaller value 1.6k wich will increase chargin current to 600mAh
![alt text](https://github.com/yo8aiv/WIFI_LoRa_32_V2_charging_mod/blob/main/WIFI-LoRa-32-V2.1.png)
