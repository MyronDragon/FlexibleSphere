\# FlexibleSphere Obj\_Args

\- Obj\_Arg0: Maximum scale of the object, multiplied by 10000. Default is 10000.

\- Obj\_Arg1: Minimum scale of the object, multiplied by 10000. Default is 1000.

\- Obj\_Arg2: Scaling rate of the object, multiplied by 10000. Default is 20.

\- Obj\_Arg3: If set to 1, the object disappears after reaching the minimum scale.

\- SW\_DEAD: Gets activated when it vanishes. Obj\_arg3 must be set to 1 for this to be possible.

\- SW\_A: Enables the shrinking and growing once activated.



\# How tu use it?
on `/ObjectData/ProductMapObjDataTable.arc` and `/ProductMapObjDataTable/ProductMapObjDataTable.bcsv` add :
`ModelName` : `FlexibleSandPlanetPartsA`

`ModelName` : `ScaleDownRelayPlanet`

`ClassName` : `FlexibleSphere`



for `ScaleDownRelayPlanet`, effect and particle are needed, Don't forget to add it to your `Effect.arc` by using \[pygapa from Aurum](https://github.com/SunakazeKun/pygapa) or \[the forked pygapa version from AwesomeTMC](https://github.com/AwesomeTMC/pygapa)

