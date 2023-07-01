# Double-O-Ships

## How to

Use the following functions.

I hope they are self explanatory... I've written this somewhere in 2010 I think, so I barely remember what I did back then.

```
native CreateShip(modelid,Float:x,Float:y,Float:a);
native CreateShipEx(modelid,Float:x,Float:y,Float:a,respawndelay);
native DestroyShip(shipid);
native UpdateShipPos(shipid,Float:x,Float:y,Float:a);
native MoveShip(shipid,Float:speed);
native GetShipCommandoBridge(shipid,&Float:x,&Float:y,&Float:z);
native GetShipSpeed(shipid,&Float:speed);
native GetShipModel(shipid);
native GetPlayerShipID(playerid);
native SetShipPos(shipid,Float:x,Float:y);
native SetShipZAngle(shipid,Float:a);
native GetShipPos(shipid,&Float:x,&Float:y);
native GetShipZAngle(shipid,&Float:a);
native IsValidShip(shipid);
native IsValidShipModel(modelid);
native GetDefaultShipPositions(modelid,object,&Float:x,&Float:y,&Float:z,&Float:rx,&Float:ry,&Float:rz);
native GetShipCorners(shipid,Float:corner_x[4],Float:corner_y[4]);
native IsPlayerOnShip(playerid,shipid);
native GetShipCaptain(shipid);
native GetShipName(shipid,name[],len);
native SetShipHealth(shipid,Float:health);
native GetShipHealth(shipid,&Float:health);
native RepairShip(shipid);
native GetShipMaxHealth(shipid,&Float:maxhealth);
native ActivateShipHorn(shipid);
native GetPlayerShipCameraPos(playerid,&Float:x,&Float:y,&Float:z);
```

## Links

https://www.youtube.com/watch?v=JLLqyAtCAnk

## License

Please do whatever you want with this script.
