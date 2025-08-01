#  NUCLEO ADC & Sensor Interface Suite

This repository includes embedded systems projects using the STM32 NUCLEO platform to explore analog input reading from light sensors (LDR) and digital data acquisition from a MEMS accelerometer. The projects also demonstrate efficient data handling using DMA and callback mechanisms.

##  Project Contents

### 1. ADC with LDR (Project 3a)
- **Function**: Reads analog values from a Light-Dependent Resistor (LDR) using the ADC.
- **Purpose**: To observe light intensity variations in real time.
- **Learning Outcome**: Basic ADC setup and data conversion from sensor input.

### 2. ADC with DMA + Half Complete Callback (Project 3b)
- **Function**: Continuously reads LDR data using DMA, triggers action halfway through the buffer.
- **Purpose**: Improves ADC efficiency using DMA and interrupt-driven processing.
- **Learning Outcome**: Using `HAL_ADC_ConvHalfCpltCallback` for real-time data streaming.

### 3. MEMS Accelerometer Projects (1b & 1c)
- **Function**: Reads and displays motion data from a MEMS accelerometer.
- **Purpose**: Tracks movement or orientation using multi-axis accelerometer data.
- **Learning Outcome**: SPI/I2C communication, sensor interfacing, and data display.

---

##  Technologies Used

- **Hardware**: STM32 NUCLEO board, LDR, MEMS accelerometer module
- **Software**: STM32CubeIDE, STM32 HAL Drivers
- **Core Concepts**:
  - ADC with DMA
  - Callback functions for real-time control
  - Sensor interfacing (LDR, MEMS)
  - Data visualization/logging

---

## How to Run

1. Open each project folder in **STM32CubeIDE**.
2. Connect STM32 NUCLEO board and relevant sensors (LDR or MEMS accelerometer).
3. Flash the firmware and open a serial terminal if needed.
4. Monitor behavior:
   - Light sensitivity changes (LDR)
   - Buffer callbacks for ADC (DMA)
   - Motion readings from accelerometer
