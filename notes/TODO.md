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
	- [ ] make flipflop default value 0 instead of E
	- [x] d-flipflop
		- has enable and value.
		- build from nand (for transistors)
- [ ] add bus
    - [ ] a registers connect to A in alu

# Circuitjs
- [ ] implement alu in transistors logic
