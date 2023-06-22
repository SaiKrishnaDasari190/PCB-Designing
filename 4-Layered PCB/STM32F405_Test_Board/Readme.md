# STM32F405 Test Board Revision-1

I have designed a 4 layered STM32F4-based PCB, which is completely with SMD (Surface-Mount Device) components (excluding Input Power Screw terminal and USB).This PCB is simple and cost efficient.

**Features 💡 :**

🔺**Input Voltage :** 4.5V - 12V (Capable of holding upto 24V)🦾

__1. STM32F405 MCU Circuit__

    🔸 **Decoupling Capacitors :** These capacitors help stabilize the power supply for the MCU, reducing noise and voltage fluctuations.
    
    🔸**VDDA Filtering :** This filtering helps provide a clean and stable analog power supply for the MCU's analog components.
    
    🔸**Boot Loader Switch :** This allows you to switch between different firmware/bootloader versions during development or for firmware updates.
    
    🔸**Crystal Oscillator :** The crystal oscillator provides an accurate clock source for the MCU.
    
    🔸**I2C Pull-ups :** Pull-up resistors are necessary for the I2C communication lines to ensure proper voltage levels.

__2. Power Circuitry (Buck Converter)__

    🔸**Reverse Polarity Protection :** This feature protects the board from damage if the input power supply is connected with reverse polarity.
    
    🔸**Volage Regulation :** The buck converter regulates the input voltage to provide a stable and suitable voltage level for the components on the board.
    
    🔸**Fusing :** Fuses are used as protection devices to limit the current in case of a fault or short circuit.
    
    🔸**Filtering :** Filtering components, such as capacitors and inductors, help reduce noise and provide a clean power supply to the components.
    
    🔸**Power Indicator LED :** This LED indicates the presence of power on the board, providing a visual confirmation.
    
   
__3. Communication Protocols__

     🔸**USB (Universal Serial Bus) :** The USB interface allows for communication and data transfer with external devices and to dump the code as well.
     
     🔸**UART (Universal Asynchronous Receiver/Transmitter) :** UART is a standard asynchronous serial communication protocol used for connecting various peripherals and devices.
     
     🔸**I2C (Inter-Integrated Circuit) :**  I2C is a popular serial communication protocol for connecting multiple devices on a bus, using a master-slave configuration.
     
     🔸**SWD (Serial Wire Debug) :** SWD is a debug interface commonly used for programming and debugging microcontrollers.

Overall, This PCB design cover the essential components and features required for a STM32F4-based system.
