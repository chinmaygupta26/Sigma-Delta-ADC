# Sigma-Delta Analog-To-Digital Converter (ADC)
## Implementation of Sigma-Delta ADC using MATLAB and FPGA  
Sigma-Delta Analog to Digital Converters have a wide range of applications in the signal-processing domain for designing 
effective communication systems on hardware
devices. This paper attempts the implementation 
of the converter by splitting the circuit into 
analog and digital part. The Input and Analog 
part are simulated through MATLAB and the 
Digital part is passed through Atlas DE0-NanoSoC FPGA board using FIL (FPGA in the Loop 
Simulation). The initial input (delayed to match 
the output), the output digital approximation and 
the error (difference of the two signals) is 
observed through scope on MATLAB.
