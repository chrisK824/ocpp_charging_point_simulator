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
`python3.9 -m pip install -r requirements.txt`

#### Usage
`python3.9 ocpp_16_charge_point_sim.py <OCPP SERVER IP ADDRESS> <OCPP SERVER PORT> <WS PATH> <CHARGING POINT ID> <VENDOR NAME (OPTIONAL)>`

##### Example

`python3.9 ocpp_16_charge_point_sim.py 192.168.1.10 9000 /my/path testChargingPointID "Wallbox Chargers"`
