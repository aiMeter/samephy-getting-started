# samephy-getting-started
Walking you through on ALL ABOUT THE SamePHY BOARD and how to use SamePHY seamlessly !!!.
## Table of Contents
## Brief Introduction
Basicly, SamePHY is an easy development board which (amongst its other uses and capabilities) primarily functions as a gateway of all sorts of radios/wireless communication thereby brigding all similar or dissimilar wireless communication protocol. SamePHY is the final **beakthrough* in the world of IOT (Internet of Things). 

In very simple terms: * A typical dissimilar communication media situation where you have a device A which only has bluetooth on it and you are looking to send message/data to and from another device B equipped with only WiFi, SamePHY is your helper on that !. In another situation where you want to use the bluetooth device A to access the internet or collect data from the internet, SamePHY has come to your rescue !. With your "only-GSM" enabled device, you may also want to send data to and from a WiFi device, don't worry SamePHY would mediate between them and the list goes on and on. You may also want to use SamePHY as gateway in similar communication media e.g WiFi to WiFi ...*

## The SamePHY board 
SamePHY is a highly reconfigurable development board, a gateway of all sorts of radios, an Arduino shield, a HAT for two Raspberry Pi and a host for its “Jobs link here”. Being the gateway of all radio communications currently available is the basis for the name (SamePHY) meaning "Same PHYsical" Layer, as it is the last layer/bridge for all radio communications currently available, be it **THREAD, ZIGBEE, BLUETOOTH(BT/BLE), WIFI, LoRa/LoRaWAN, SigFox & wM-Bus, GSM/GPRS NBIoT/LTE Cat M1 (BC66) ...** The board houses up to 7 CPUs and 2 Ultra Low Power Processors all ranging from instruction sets such as ARM, Intel, RISC-V & Xtensa ISAs with a Board Dimension of 51 x 100mm which is lesser than the size of an Arduino Mega Board<br>
<br>
#### Currently SamePHY board comes in two flavors 
- SamePHY MUSK (also called "Module M")
- SamePHY KANU (also called "Module K")

Both flavors are compatible with the Arduino and Raspberry Pi form factors and they only differ in the type of GSM/GPRS modem on-board - that is, where **Module M** uses **SIMXXX** (a modem series from SIMCOM manufacturers), **Module K** uses **BCXX/MCXX** (a modem series from QUECTEL manufacturers).

#### Features of SamePHY MUSK

- WiFi & BT/BLE
- LoRa/LoRaWAN
- SigFox & wM-Bus
- Zigbee/Thread
- BT, GSM/GPRS & GNSS (SIM868E)
- NBIoT/LTE Cat M1 (SIM7020/SIM7080)
- Matter Bridge
- Arduino Form Factor Compatible
- Raspberry Pi Form Factor Compatible

#### Features of SamePHY KANU 

- WiFi & BT/BLE
- LoRa/LoRaWAN
- SigFox & wM-Bus
- Zigbee/Thread
- BT, GSM/GPRS (MC60)
- NBIoT/LTE Cat M1 (BC66)
- Matter Bridge
- Arduino Form Factor Compatible
- Raspberry Pi Form Factor Compatible

#### General Features Overview of SamePHY
| Features | Description | Side of Board | Variant |
| -------- | ----------- | ------------- | ------- |
| CPU Core | 7 CPUs and 2 Ultra Low Power Processors from ARM, Intel, RISC-V & Xtensa ISAs | Both | |
| SOC | There are 5 SOC's(Systems On Chip) on the board<br>(ESP32, SIMXX, BCXX/MCXX, STM32WLXX, CH552T) | BOTH | |
| ESP32 | WiFi/Bluetooth module chipset from Espressif | TOP (ESP32XX_TOP)<br><br>BOTTOM (ESP32XX_BOTTOM) | 	ESP32 WROOM , ESP32 WROVER <br><br>ESP32-S3, ESP32-H2*, ESP32-C6* |
| SIMXX | GSM/GPRS/GPS modem from SIMCOM<br>(only available on SamePHY MUSK) | TOP | 	SIM868E, SIM7020, SIM7080G |
| BCXX/MCXX | GSM/GPRS/GPS modem from QUECTEL<br>(only available on SamePHY KANU) | TOP |	BC66/BC65, MC66 |
| STM32WLXX | LoRa/LoRaWAN module/chipset from STMicroelectronics | TOP | Wi-e5 |
| CH552T | Intel 8051 based micro controller | TOP | |
| Micro SIM Slot | 	For micro SIMs | TOP | |
| Antennas | 6 x ANTs (Helical, IPEX and PCB ANT Supported) | BOTH | |
| Pinouts | 130 pinouts including GPIO pins and power pins | BOTH | |
| Power Supply Units (PSUs) | USB1, USB3, CH55X Headers, Arduino Headers, Raspberry Pi Headers, Battery, Main AC Supply via Hi-Link PSU or any Cheap 25 x15 mm PSU (3 common form-factor supported) | BOTH | |
| Board Dimension | 51 x 100mm ( < Arduino Mega Board size) |  | |
| USB-to-Serial | CH552T can serve as a dual USB-to-Serial Interface yet supports native development |  | |
| Protections | Automatic Power Supply Unit (PSU) Selectors, Fuses, Level Shifters and Regulators |  | 
| Programming Interfaces | USB1, USB2, USB3 and exposed Header pins that support Device Firmware Updates (DFU) |  | |

 \* means *under test*
 
 Before jumping right into using SamePHY it is worth 
 
 ### Using SamePHY
 
