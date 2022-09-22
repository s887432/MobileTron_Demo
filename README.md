# MobileTron_Demo
## MobileTron_PLC
the PLC simularor in Arduino Uno<br>
sending data via UART<br>

Data format<br>
<MACHINE_ID><DATETIME>,<DATA_1>,<DATA_2>,<DATA_3>

## 0000_mobiletron_buildroot_ext_microchip.patch
the buildroot_external_microchip patch<br>
adding<br>
modbus library<br>
mosquitto<br>
paho_c<br>
paho_c++<br>
python_paho<br>
python_pip<br>
moved root file system from SD card to emmc<br>

## csvGenerate
example code to generate csv file

## mqtt
example code for mqtt which used paho library

## tcp_cliser
TCP client-server example

## uartReceiver
example code to receive data via UART
