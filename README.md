# IR Sensor Distance Measurement System

## Description
This project implements a complete sensor interfacing and signal processing system to measure distance using an IR proximity sensor. The system includes analog signal conditioning, sampling, and analog-to-digital conversion.

## Features
- Analog signal processing
- Amplifier circuit for signal conditioning
- Sampling and ADC conversion
- Distance output display using microcontroller

## Components Used
- IR proximity analog sensor
- Operational amplifier (for signal amplification)
- Sampling circuit
- ADC0808 (initially used)
- STM32 microcontroller (used after ADC0808 failure)
- OLED display

## Working
The IR sensor provides an analog voltage based on distance. This signal is amplified using an analog amplifier circuit. The amplified signal is then sampled and converted into digital form using ADC.

Initially, ADC0808 was used for conversion, but due to hardware issues, the system was modified to use the internal ADC of STM32. The processed digital output is then displayed on an OLED display.

## Output
Refer to the uploaded video for working demonstration.

## Author
Rishika
