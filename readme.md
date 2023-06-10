# EV charging point simulator based on python and OCPP 1.6 JSON

####  Supported OCPP commands:
- BootNotification
- HeartBeat
- RemoteStartTransaction
- RemoteStopTransaction
- TriggerMessage
- HeartBeat
- MeterValues
- BootNotification
- ClearChargingProfile
- SetChargingProfile
- GetConfiguration
- ChangeConfiguration

#### Install requirements
`python3.11 -m pip install -r requirements.txt`

#### Usage
`python3.11 ocpp_16_charge_point_sim.py <OCPP SERVER IP ADDRESS> <OCPP SERVER PORT> <WS PATH> <CHARGING POINT ID> <VENDOR NAME (OPTIONAL)>`

##### Example

`python3.11 ocpp_16_charge_point_sim.py 192.168.1.10 9000 /ws/path/here/ test_charging_point_id test_charging_point_vendor`
