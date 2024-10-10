# Logisim
- [ ] add RAM
	- [ ] 16k in sizeq
- [ ] add features using ram
- [ ] map opcodes
- [/] add registers
	- they need 3 key things:
		- load - using flipflops as "locks"
		- enable - to output to the bus
		- clock - to act only on clock signal
	- [ ] check registers are working with on clock up
	- [x] d-flipflop
		- has enable and value.
		- build from nand (for transistors)

# Circuitjs
- [ ] implement alu in transistors logic