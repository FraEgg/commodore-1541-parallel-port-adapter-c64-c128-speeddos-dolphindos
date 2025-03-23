# <img title="The Multi-Speeder Logo" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/Multi-Speeder_Logo.png?raw=true" alt="Multi-Speeder Logo" style="zoom:25%;" data-align="center">

# Parallelport-Adapter (Duo/Slim) for the Commodore 1541 Disk Drive (SpeedDOS, DolphinDOS) with the C64/C128

<img title="1541-I and 1541-II VIA 6522 Parallelport-Adapter Duo/Slim" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/1541_Paralleladapter_VIA_6522_(Duo)_Low_top_render.png?raw=true" alt="1541-I and 1541-II VIA 6522 Parallelport-Adapter Duo/Slim" data-align="center" style="zoom:80%;">

## Description

This is the parallel cable adapter for the VIA 6522 in the 1541-I or 1541-II disk drive. For standard operation, only one connector for the ribbon cable to the C64/C128 user port adapter is needed. The second connector is designed for the 8x Multi-Speeder, allowing parallel operation of DolphinDos 2 and DolphinDos 3. The parallel cable adapter is installed between the VIA 6522 and the PCB in the 1541-I (UC3) or 1541-II (U6).



<img title="1541-II Paralleladapter" src="https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/1541-II_PCB_inst.jpg?raw=true" alt="1541-II Paralleladapter" data-align="left" style="zoom:80%;">

![Paralleladapter installed on a 1541-II](https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/blob/master/images/1541-II_MS_PCB_inst.jpg?raw=true "Paralleladapter installed on a 1541-II")

Paralleladapter installed on a 1541-II floppy drive.



## Downloads

1. [Gerber PCB Files](https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/raw/refs/heads/master/1541_Paralleladapter_VIA_6522_Low/1541_Paralleladapter_VIA_6522_(Duo).kicad_pcb.zip)

2. [Bill of Materials (BOM)](https://github.com/FraEgg/commodore-1541-parallel-port-adapter-c64-c128-speeddos-dolphindos/raw/refs/heads/master/1541_Paralleladapter_VIA_6522_Low/BOM_1541_Paralleladapter_VIA_6522_(Duo).xls)

3. [PCBWay Shared Project](https://www.pcbway.com/project/shareproject/1541_I_1541_II_Parallel_Adapter_Duo_Slim_Parallel_Cable_Set_for_the_Commodor_57072954.html)
   
   

## Bill of Materials (BOM)

| No  | References | Value         | Footprint    | Datasheet                                             | Description                                                                                                       | Quantity |
| --- | ---------- | ------------- |:------------ | ----------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | -------- |
| 1   | IC1        | MCS6522SOPINS | SOCKETPINS40 | https://www.aliexpress.com/item/32972142300.html      | D0.45-0.6mm PCB Gold Round Female Male Pin Sensor Crystal Socket Dim1.4*7.4mm,No Plastic for 2.54 Hole Pin Header | 1        |
| 2   | J1, J2     | MICMA10B-THT  | MICMA10B     | https://www.aliexpress.com/item/1005008071308576.html | Micromatch Red 2.54mm Pitch Double Row Female IDC Box Header Connector 10P                                        | 2        |
