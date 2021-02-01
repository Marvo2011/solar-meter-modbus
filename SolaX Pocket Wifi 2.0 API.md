# Pocket Wifi 2.0 REST API

**Important**:  You need to send a HTTP **POST** request!  
Firmeware Version: 2.033.20 (Download page: http://de.solaxpower.com/downloads/)

URLs:  
http://5.8.8.8/?optType=ReadRealTimeData  
http://5.8.8.8/?optType=ReadSetData  
http://5.8.8.8/?optType=BatteryMinEnergy&BatteryMinEnergyValue={{{payload}}}&  
http://5.8.8.8/?optType=SolarChargerUseMode&SolarChargerUseModeValue={{{payload}}}&  

**ReadRealTimeData Respone:**
ToDo...

**How you can get it in your local Network?**  
I have installed a old Raspberry Pi with a Wifi dongle, than you should use a apache2 reverse proxy to pass it into your local network. Make sure that the PI is secure the SolaX Poket Wifi 2.0 is unprotected!
