# RPiHat_GPIO_Expander
Main motivation behind this design was to design an input/output system for home automation able to control 230VAC equipments without exposing hazardous voltages (as it is usually the case with popular relay expansion boards) as well as support high current requirements. DIN-rail mount relays meet both requirements and can be controlled using a 24V DC voltage and reasonable current levels. The same 24V voltage can also be used for input devices (buttons, switches …) while offering high noise immunity.  

This Raspberry HAT design allows to control up to 8x DIN-rail mount relays (24VDC, ~25mA coil current) and sense up to 8x 24VDC inputs. It also integrates a 24V->5V DCDC converter that may be used to power the Raspberry motherboard and avoid the need for an additional USB adapter and associated wall plug in the distribution panel. 

This repository includes all design informations (eagle schematic/layout, Gerber, BOM, ...) and related documentation
