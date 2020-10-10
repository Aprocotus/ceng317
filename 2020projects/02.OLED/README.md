# CENG 317 Proposal
1. Basic info
     1. Name: 
     2. Date: 
     3. Section:
     4. Effector choice: OLED
2. I will make a USB serial device, that will receive input for an effector, via [Seeed Studio assembly](https://www.seeedstudio.com/fusion_pcb.html). This can be connected via a USB cable to a PC and PuTTY can be used for debugging. It can then also be connected to a Pi via USB but not necessarily this term. 
3. Preliminary Bill of Materials
    1. OPL: [Seeed](https://www.seeedstudio.com/opl.html)
    2. MPN: QG-2864KSWEG01
	3. Qty: 1
	4. Link: https://datasheet.lcsc.com/szlcsc/1811151642_Shenzhen-Allvision-Tech-QG-2864KSWEG01_C85007.pdf
    5. Description:	OLED Display module;30P-L26.7*W19.26*H1.4mm  (Seeed OPL, note page 15 of datasheet as well as safety precautions)
	6. Manufacturer: Allvision
	7. Package: 
4. Specifications
    1. What does it sense/effect?
	2. How accurate is it?
    3. Voltage range:
	4. Current draw:
	5. Protocol: SPI
	6. Footprint:
	7. STM32 Pins used: 3.3V, GND, PA15, PB3, PB5, PB10, PB11
	8. Additional components needed: 4.7kOhm resistor plus entire breakout board circuit.
5. References:    
[Fritzing for Inventors](https://learning-oreilly-com.ezproxy.humber.ca/library/view/fritzing-for-inventors/9780071844642/ch01.html#ch01)    
[Beginning STM32 Chapters 12 and 13 especially Figure 12-4](https://learning-oreilly-com.ezproxy.humber.ca/library/view/beginning-stm32-developing/9781484236246/html/465982_1_En_1_Chapter.xhtml)      
[Schematic for a breakout board for a similar display](https://cdn-learn.adafruit.com/assets/assets/000/093/884/original/adafruit_products_0-96in_OLED_sch.png?1596746114)     
[Code](https://github.com/Apress/Beg-STM32-Devel-FreeRTOS-libopencm3-GCC/tree/master/rtos/oled)     
[Hand soldering OLED](https://www.youtube.com/watch?v=ywh_6SPNrSg)