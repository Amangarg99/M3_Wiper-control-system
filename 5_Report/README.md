
## INTRODUCTION

Wiper is used to remove dust or rain drops from the mirror to get a clear view. Almost all vehicles equipped with wipers . A wiper generally consist of an arm, pivoting at one end with a long rubber blade attached to the other. The wiper swings back and forth to clear the mirror . It is installed both on rear and front mirror for driver's convinience and safety.

## OBJECTIVE

To clear the dust and rain drops from the mirror to avoid any accidents.

## RESEARCH

Researched from Youtube , Google and other websites to learn about the existing functionalities.

## SOFTWARE REQUIREMENT

STM32 CUBE IDE

## STM32F407VG Discovery board

The STM32F407 Discovery board uses STM32F407VGT6 Microcontroller which has ARM Cortex-M4F Processor, which is capable of running upto 168Mhz. This MCU has many peripherals such as GPIO ports, TIMERS, ADCs, DACs, Flash Memory, SRAM, SPI, UART ect. The processor and peripherals talk via BUS-Interface. There are three busses available :-

I-BUS (Instruction Bus)
D-BUS (Data Bus)
S-BUS (System Bus)
I-BUS This bus connects the Instruction bus of the Cortex®-M4 with FPU(Floating point unit) core to the BusMatrix. This bus is used by the core to fetch instructions. The target of this bus is a memory containing code (internal Flash memory/SRAM or external memories through the FSMC/FMC).

D-BUS This bus connects the databus of the Cortex®-M4 with FPU to the 64-Kbyte CCM data RAM to the BusMatrix. This bus is used by the core for literal load and debug access. The target of this bus is a memory containing code or data (internal Flash memory or external memories through the FSMC/FMC).

S-BUS This bus connects the system bus of the Cortex®-M4 with FPU core to a BusMatrix. This bus is used to access data located in a peripheral or in SRAM. Instructions may also be fetched on this bus (less efficient than ICode). The targets of this bus are the internal SRAM1, SRAM2 and SRAM3, the AHB1 peripherals including the APB peripherals, the AHB2 peripherals and the external memories through the FSMC/FMC.

So instructions and data use I-bus and D-bus respectively, All the other peripheral uses System bus. The Cortex-M4 processor contains three external Advanced High-performance Bus (AHB)-Lite bus interface and one Advanced Peripheral Bus (APB) interface. The GPIOs are connected to AHB1 bus which has a maximum speed of 150Mhz and is divided into two buses as APB1 and APB2. APB1 runs at 42Mhz(max) and APB2 runs at 82Mhz(max). The different peripherals such as SPI, UART, TIMERs, ADCs, DACs, etc are connected to either APB1/APB2 buses. And the AHB2(168Mhz max) is connected to Camera and USB OTG interfaces, AHB3 is connected to External memory controller.


## SWOT ANALYSIS

### STRENGTH

Reduce the chances of accidents during heavy rainfall 

### WEAKNESS

Maintainance can be expensive and you have to check if the water is sufficient is car to clean the mirror.

### OPPORTUNITIES

Technology inventions may reduce the cost.

### THREATS

Acceptance after purchasing as it has major role to play in terms of safety
