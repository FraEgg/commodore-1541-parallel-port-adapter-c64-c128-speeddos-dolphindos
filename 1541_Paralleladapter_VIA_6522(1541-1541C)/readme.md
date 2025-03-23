<img title="The Multi-Speeder Logo" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/Multi-Speeder_Logo.png?raw=true" alt="Multi-Speeder Logo" style="zoom:25%;" data-align="center">

# Parallelport-Adapter for the Commodore 1541-I and 1541C Disk Drive (SpeedDOS, DolphinDOS) with the C64/C128

<img title="1541-I and 1541C VIA 6522 Parallelport-Adapter" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/1541_Paralleladapter_VIA%206522_(1541C)_top_render.png?raw=true" alt="1541-I and 1541C VIA 6522 Parallelport-Adapter" data-align="center" style="zoom:80%;">

## Description

This is the parallel cable adapter for the VIA 6522 in the 1541-I or 1541C disk drive. For standard operation, only one connector for the ribbon cable to the C64/C128 user port adapter is needed. The parallel cable adapter is installed between the VIA 6522 and the PCB in the 1541-I (UC3) or 1541C (U3).



<img title="1541-I / 1541C Paralleladapter" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/1541-I-MS-inst.jpg?raw=true" alt="1541-I / 1541C Paralleladapter" data-align="left" style="zoom:80%;">On the left you can see the parallel adapter installed in the UC3 VIA 6522 socket of the 1541-I floppy disk drive. Next to it (right) is the 8x Switchless Multi-Speeder on the 6502 CPU socket.



## Downloads

1. [Gerber PCB Files](https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/raw/refs/heads/master/1541_Paralleladapter_VIA_6522(1541-1541C)/1541%20SpeedDos%20Paralleladapter%20VIA%206522.kicad_pcb.zip)

2. [Bill of Materials (BOM)](https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/raw/refs/heads/master/1541_Paralleladapter_VIA_6522(1541-1541C)/BOM_1541_Paralleladapter_VIA_6522.xls)

3. [PCBWay Shared Project](https://www.pcbway.com/project/shareproject/1541_I_1541C_Parallel_Adapter_Parallel_Cable_Set_for_the_Commodore_1541_Disk_D_a27176a6.html)
   
   

## Bill of Materials (BOM)

| No  | References | Value         | Footprint     | Datasheet                                                                                          | Description                                                                                | Quantity |
| --- | ---------- | ------------- |:------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | -------- |
| 1   | PCB1       | 2x20 CONN HDR | DIL40_PINS_SS | https://www.digikey.de/de/products/detail/mill-max-manufacturing-corp/334-40-140-00-020000/7746412 | Male Header Single Row 40 Pin (2x20 Pin) 2.54mm Pin Connector Strip Round Needle Connector | 1        |
| 2   | UC3-1      | MCS6522SOCKET | GS40P         | https://www.aliexpress.com/item/1005001488096624.html                                              | Round Hole IC socket Connector DIP 40 pin Socket DIP40                                     | 1        |
| 3   | J1         | 2X05WV        | 2X05WV        | https://www.aliexpress.com/item/1005007307830993.html                                              | Pin 2.54mm IDC Socket Header Male Socket                                                   | 1        |
