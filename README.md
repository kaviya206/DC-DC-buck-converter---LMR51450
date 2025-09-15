# LMR51450 Based 7.6V 4A DC-DC Buck Converter

This project implements a **DC-DC Buck Converter** using the **Texas Instruments LMR51450** regulator, designed in **KiCad**.  
The converter steps down a 24V input to a regulated **7.6V output at up to 4A** continuous current.

<img width="1212" height="470" alt="Screenshot (213)" src="https://github.com/user-attachments/assets/671e832e-57f2-44a3-af74-17dd5a0c0171" />


---

## Specifications
- **Input Voltage (VIN):** 24V (nominal)
- **Output Voltage (VOUT):** 7.6V
- **Output Current:** Up to 4A
- **Controller IC:** LMR51450
- **Topology:** Synchronous Buck Converter
- **Efficiency:** ~85–90% (depending on load & PCB layout)

---

## Design Features
- Input protection:
  - Fuse on VIN
  - SMAJ33CA TVS diode for surge/transient protection
- Input capacitors for filtering (electrolytic + ceramic)
- Schottky diode for fast switching and reliability
- Proper output LC filter (inductor + low-ESR capacitors)
- Test points for VIN, VOUT, GND for debugging
- Screw terminal connectors for input/output
- 2-layer PCB routing with wide tracks for high current paths
- Thermal management considerations for MOSFETs and inductor

---

## Tools Used
- **KiCad 9** (schematic & PCB design)
- **KiCad 3D Viewer** (board visualization)

---
**created by,**
kaviya - ECE Student


