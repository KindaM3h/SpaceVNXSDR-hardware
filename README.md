# SpaceVNXSDR-hardware
TODO's regarding [BaseBoard](SpaceVNXBaseBoard):
- [ ] Schematics:
- [ ]  [DDR3 for PL](https://www.intel.com/content/dam/www/public/us/en/documents/white-papers/ia-ddr2-ecc-so-dimm-paper.pdf) (72-bit ECC) could be implemented with a standart [204-pin SODIM connector](https://www.te.com/usa-en/product-CAT-D33037-SO1339.html?q=&n=531259&type=products&samples=N&inStoreWithoutPL=false&instock=N) in order to reduce stackup cost by using a [Module](https://media-www.micron.com/-/media/client/global/documents/products/data-sheet/modules/sodimm/jtf16c256_512_1gx64hz.pdf?rev=92a9360308b84bd182ce55b117fec160).
- [ ]  Change Non-Volatile Memory from NOR QSPI to a [MRAM](https://www.everspin.com/AppNotes) for better radiation hardness.
- [ ]  Adapt DaughterBoard interface to comply with [SYZYGY](https://syzygyfpga.io/specification/) TXR-4 tranceiver peripheral specification.
- [x]  Documentation:
- [x]  Add Outputjob file similar to [this](https://github.com/KindaM3h/SpaceVNXDaughterBoard/blob/5bddf40d4c2867f65b3ace6bd9e41c5fd28d74c9/SpaceVNXDaughterBoard.OutJob).

TODO's regarding [DaughterBoard](SpaceVNXDaughterBoard):
- [ ] Schematics:
- [x] Select and add ADC.
- [ ] Power tree!
- [ ] Route:
- [ ] RF required changes detected after simulation.
