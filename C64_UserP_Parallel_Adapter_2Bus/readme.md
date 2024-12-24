# C64/C128 Userport-Apadpter to the 1541/1571 Disk Drives

<img title="C64/C128 Userport Adapter" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/C64_UserP_Parallel_Adapter_2Bus_top_render.png?raw=true" alt="C64/C128 Userport Adapter" data-align="center" style="zoom:80%;">

## Description

This is the adapter for the user port of the C64 or C128. The adapter features a reset button and two parallel port connectors for the Commodore 1541 or Commodore 1571 disk drives. If two disk drives are to be operated with parallel cables, it is essential that both drives are powered on for parallel transfer to function correctly. The user port is passed through the PCB 1:1 to the back, allowing additional devices to be connected.



<img title="Parallelkabel Set" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/1541-Prallelcable_Set.jpg?raw=true" alt="Parallelkabel Set" data-align="left" style="zoom:80%;">The parallel cable set with the C64/C128 user port adapter.



## Downloads

1. [Gerber PCB Files](https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/raw/refs/heads/master/C64_UserP_Parallel_Adapter_2Bus/UP-PAR-Adaptor.kicad_pcb.zip)

2. [Bill of Materials (BOM)](https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/raw/refs/heads/master/C64_UserP_Parallel_Adapter_2Bus/BOM_User_Port_Parallel-Adapter.xls)

3. PCBWay Shared Project
   


## Bill of Materials (BOM)

| No  | References | Value        | Footprint | Datasheet                                             | Description                                                                                                       | Quantity |
| --- | ---------- | ------------ |:--------- | ----------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | -------- |
| 1   | SW1        | JTP-1130     | JTP-1130  | https://www.aliexpress.com/item/1005005810426286.html | 6X6x5mm 4PIN dip TACT push button switch Micro key power tactile switches 6x6x5 6*6*5MM                           | 1        |
| 2   | J3, J4     | 2X05WV       | 2X05WV    | https://www.aliexpress.com/item/1005007307830993.html | Pin 2.54mm IDC Socket Header Male Socket                                                                          | 2        |
| 3   | J1         | C64-USERPORT | USERPORT  | https://www.aliexpress.com/item/1005005951317282.html | LOT 805 Series 24 Pin Game Card Socket Edge Connector 3.96MM Pitch Female JAMMA Connector for Arcade Game Machine | 1        |
