[![](https://img.shields.io/badge/organization-The--101--project-blue.svg)](https://github.com/The-101-project) 
[![](https://img.shields.io/badge/remote-Lock_In_Amplifier_Review-green.svg)](https://github.com/The-101-project/LockInAmplifierReview) 
[![](https://img.shields.io/badge/local-F:\prj\electronics\Lock_In_Amplifier_Review-orange.svg)](https://github.com/soldering-channel)

# tasks

* [BACK_TO_TOP](README.md)


## Generic
- [x] 1. move Redpitaya content from readme to RadPitayaLIA
- [x] 2. dd images
- [x] . Add some conclusions

- [ ] 4. Find the meaning of 90 nV/√Hz and how to emulate that

## RePLIA
- [x] 5. Solve the large image for RP sd-card download issue
- [ ] 6. Find the frequency resolution for RePLIA
- [ ] 7. Compare RePLIA with other RedPitaya LIA solutions
- [x] 8. Backup `RP_Lock-in_copy.img` 3.9GB file
- [x] 9. Backup Start testing RePLIA
- [ ] 10. Make a list with first test results on RePLIA


## Orders
- [x] 11. Order more Redpitaya boards
- [ ] 12. Order Redpitaya compatible WiFi dongles
- [x] 13. Order RedPitaya connectors

## Testing
- [x] 14. Find the Ethernet cable
- [x] **15. Test Redpitaya with Ethernet cable connection to router**
- [ ] 16. Test with Redpitaya oscilloscope, the Lock-In method
- [ ] 17. Connect to Red Pitaya with Putty
- [ ] **18. Add a button to control LED** [LED](https://redpitaya.readthedocs.io/en/latest/developerGuide/software/build/webapp/webexamples/addLEDbut.html)

##  The Lock-in+PID application
- [ ] 19. Test the [The Lock-in+PID application for Red Pitaya](https://marceluda.github.io/rp_lock-in_pid/TheApp/instruments/instruments_01_intro/)
- [ ] 20. View [marcelo luda videos](https://www.youtube.com/c/marceloluda/videos) on Lock-in+PID
- [ ] 21. Check RedPitaya  [Bazaar](https://bazaar.redpitaya.com/) for LIA related applications
    - Oscilloscope+Lock-in+PID (0.1-3) is here too
- [x] 22. Create a new lock-in-pid.md
- [ ] 23. review [rp_lock-in_pid Derivated versions](https://marceluda.github.io/rp_lock-in_pid/Derivated/)
- [ ] 24. Download the papers mentioned in [Lock-in+PID](https://marceluda.github.io/rp_lock-in_pid/)

## Xilinx Vivado 
- [x] 25. View Xilinx Vivado related video [Tutorial 01 How to do Bare Metal Programming with Red Pitaya](https://www.youtube.com/watch?v=XJbEn_-hjYc)
    -  This tutorial shows you how to start bare metal programming with Red Pitaya. It uses one of the scripts that is provided by Red Pitaya to create a Vivado project and the rest is standard workflow.
        - 1. Making a Vivado project
        - 2. Exporting hardware from Vivado to Xilinx SDK
        - 3. Importing Hardware in Xilinx SDK
        - 4. Creating a hello_world application
        - 5. Creating FSBL(First Stage boot loader)
        - 6. Making boot image (BOOT.bin)
        - 7. Copying boot image to SD-Card FAT partition
        - 8. Running it on Red Pitaya

## Programming

- [x] 26. Review [programming examples](https://redpitaya.readthedocs.io/en/latest/appsFeatures/remoteControl/remoteControl.html#examples)

   - **2.3.1.4.1. Digital**
        - 2.3.1.4.1.1. Blink
        - 2.3.1.4.1.2. Bar graph with LEDs
        - 2.3.1.4.1.3. Push button and turn on LED diode
        - 2.3.1.4.1.4. Interactive LED bar graph
   - **2.3.1.4.2. Analog**
        - 2.3.1.4.2.1. Read analog voltage on slow analog input
        - 2.3.1.4.2.2. Set analog voltage on slow analog output
        - 2.3.1.4.2.3. Interactive voltage setting on slow analog output
        - 2.3.1.4.3. Generating signals at RF outputs
        - 2.3.1.4.3.1. Generate continuous signal
        - 2.3.1.4.3.2. Generate signal pulses
        - 2.3.1.4.3.3. Generate signal on external trigger
        - 2.3.1.4.3.4. Custom waveform signal generation
        - 2.3.1.4.3.5. Generate two synchronous signal
        - 2.3.1.4.3.6. Generate two burst asynced signal
        - 2.3.1.4.4. Acquiring signals at RF inputs
        - 2.3.1.4.4.1. On trigger signal acquisition
        - 2.3.1.4.4.2. Signal acquisition on external trigger
        - 2.3.1.4.4.3. Synchronised one pulse signal generation and acquisition
        - 2.3.1.4.4.4. Generating a signal and checking its shape
        - 2.3.1.4.4.5. Sampling rate and decimations
   - **2.3.1.4.5. Digital communication interfaces**
        - 2.3.1.4.5.1. I2C
        - 2.3.1.4.5.2. I2C (HW api)
        - 2.3.1.4.5.3. I2C (HW api for 250-12 only)
        - 2.3.1.4.5.4. SPI
        - 2.3.1.4.5.5. SPI (HW api)
        - 2.3.1.4.5.6. UART
        - 2.3.1.4.5.7. UART (HW api)
    - Additional examples: **Add a button to control LED**
## Other RP LIA
- [ ] 27. Review this **verilog LIA** [ ahesse93/RedPitaya_LockInAmplifier](https://github.com/ahesse93/RedPitaya_LockInAmplifier)
- [ ] 28. Review [github lock-in-amplifier ](https://github.com/topics/lock-in-amplifier)  projects

- [ ] 29. Review (Argentina) [Compact embedded device for lock-in
measurements and experiment active control](https://notablesdelaciencia.conicet.gov.ar/bitstream/handle/11336/147988/CONICET_Digital_Nro.dfbb06a5-b662-4027-9879-b046969bd6a8_A.pdf?sequence=2&isAllowed=y)

## PyRPL
- [ ] 30. Review [PyRPL](https://pyrpl.readthedocs.io/en/latest/) with focus to Lock In Amplifiers
- [ ] 31. lso [https://github.com/lneuhaus/pyrpl](https://github.com/lneuhaus/pyrpl)
- [ ] 32. Review if PyRPL has only 1Hz accuracy [Improvements to my Lock in Amplifier implementation with PyRPL](https://forum.redpitaya.com/viewtopic.php?t=23120)
- [ ] 33. Review PyRPL IQ module here [api  IQ module](https://pyrpl.readthedocs.io/en/latest/api.html#module-pyrpl.hardware_modules.iq)
- [ ] 34. Review [First attempts at locking](https://pyrpl.readthedocs.io/en/latest/user_guide/tutorial/#First-attempts-at-locking)

### PyRPL to gloss

- [ ] 35. review https://github.com/ahesse93/PyRPL-Modification
- [ ] 36. View Interferometer video with PyRPL
- [ ] 37. Review https://github.com/lneuhaus/pyrpl
- [ ] 38. Review https://pyrpl.readthedocs.io/en/latest/

## PSPRT
- [ ] **39. Make a simple diagram for the QEPAS LIA operation**
   - [x] Review my Markdown notes
        - [x] Review PSPRT reports
        - [x] LIA Reference signal output: Sinusiodal
        - [x] Frequency resolution: 0.1 Hz 
        - [x] Frequency resolution: best  possible 0.011 Hz
        - [X] Resonance QEPAS: 12448Hz
        - [x] LPF: 2.5Hz
        - [x] Measurement time for each frequency: 100ms
        - [x] Ramp period: for 1800 points around resonance--> 3min (1800points x 0.1s = 180s)
        - [ ] Modulation
- [ ] 40. Ask DAC/ADC board schematic

----

- [ ] 41. Repeat task 26 workflow