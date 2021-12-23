# SpaceVNXSDR-hardware
- [ ] Pre Placement:
- [ ] DDR PL pending IO planning project in vivado.
- [ ] Power Supply Design Review.
  - [ ] Initial bootstrap of power sequencer.
  - [ ] Select an inductor for TPS7H4010-SEP.
  - [ ] Finish adding pasives for TPS73801-SEP.
  - [ ] Confirm Radiation Hardness of DDR3/DDR3L termination supply regulator.
- [ ] Clock Tree review.
  - [x] Select Local Oscilator.
  - [x] Defined system clock (two diferential clocks one primary and one auxiliary).
- [ ] Confirm LMS7002 IO bank asignment by creating a floorplan in vivado, also decide on power delivered to that bank.
- [ ] Minor review on RGMII and Ethernet interfaces (Confirm Magnetics...).
- [ ] Minor review on CAN interfaces, lacking some pasives on SN55HVD233-SEP and protection of the transceiver side from the VNX Connector.
- [ ] Update [RFDIO](https://wiki.myriadrf.org/RFDIO) connector on baseboard to Hirose FX10A-80S.
