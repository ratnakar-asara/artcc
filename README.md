# artcc

```
peer chaincode deploy -l golang -n mycc -c '{"Function": "init", "Args":["INITIALIZE"]}'

peer chaincode invoke -l golang -n mycc -c '{"Function": "PostUser", "Args":["100", "USER", "Ashley Hart", "TRD",  "Morrisville Parkway, #216, Morrisville, NC 27560", "9198063535", "ashley@itpeople.com", "SUNTRUST", "0001732345", "0234678"]}'

peer chaincode query -l golang -n mycc -c '{"Function": "GetUser", "Args": ["100"]}'
```
