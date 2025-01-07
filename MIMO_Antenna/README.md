# MIMO Antenna Simulation

## Overview
This project involves the design and simulation of a **MIMO (Multiple-Input Multiple-Output)** antenna system for wireless communication applications. The design focuses on achieving high gain and minimizing mutual coupling between antenna elements.

## Key Specifications
- **Frequency Range**: 2.4 GHz (Wi-Fi Band)
- **Number of Elements**: 2 (for simplicity)
- **Performance Goals**:
  - S-parameters: Return loss < -10 dB.
  - Isolation: S12 < -20 dB.

## Tools Used
- **Simulation Software**: HFSS (or CST Studio Suite)
- **Post-Processing**: MATLAB (for data visualization).

## Results
- **Radiation Pattern**:
  ![Radiation Pattern](RadiationPattern.png)

- **S-Parameters**:
  ![S-Parameters](SParameters.png)

- **Performance Metrics**:
  | Parameter        | Value   |
  |------------------|---------|
  | Gain             | 7.2 dB  |
  | Isolation (S12)  | -25 dB  |

## Challenges and Solutions
- **Challenge**: High mutual coupling between elements.  
  **Solution**: Added a decoupling structure (e.g., a defected ground plane).

- **Challenge**: Achieving compact size while maintaining efficiency.  
  **Solution**: Optimized element spacing and geometry.

## Next Steps
- Fabricate and test the MIMO antenna.
- Expand the design to a 4x4 MIMO system.
