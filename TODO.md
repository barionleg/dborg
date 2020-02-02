Upgrades

	v1.03

	* New symetric foot from franferri, easy to glue
	* Front and rear shoulder, the same for easy maintenance of legs (avoiding having to unasemble the full body)
	* Covers need to be easy to remove and add, to simplify the development, connections and rechagrge batteries
	* Batteries may be mounted instead of flat, over their smallest side, so more can be accomodated
	* The battery holder must present the screws to the outside, instead of hanging to the base plate, so remove the batteries becomes a minute of work if needed.
	* All batteries connection cables must be hold where the batteries are for simplicity, instead of where the electronics are
	* The body of the dog must be longer to simplify to accomodate more electronics.
	* In the repo of assembly parts, having the components in 3d versions and the hole holders for them is needed to simplify users modifications
	* The cables where the shoulder servos are, coming from the front plate or back plate are "interfering" with the servos, put some hole walls and internal sides to make the cables pass from there (this also gets us more room to
	put cables safely)
	* Front and back must be easy to unassemble
	* The top cover has 2 sides that actually interfere with the shoulders and we had to cut the edges off, this needs to be fixed
	* Clear alignment servos instructions
	* Custom PCB can be ordered to JLCPCB online for 2dollars
	* Raspberry Pi Zero W can be more than enough for the base dog, also good for consumption
	* Explain each component in the electronics wiki (and the rationality behind it). Power consumption, specifications that justify its usage, link to buy them
	* Buck converters and BEC create a significant amount of radio noise due the coils they use. TIP's are exchanging energy consumption with heat, if we can have the TIP with a heat sink in the PCB, not touching the PLA, this could be perfect. Maybe using 2 TIP in parallel will divide also the heat in 2 heatsinks. How much hot gets for the RPi power consumption?
	* When my batteries were delivering only 6v, the buck converter was delivering 4.6v or less instead of the preset 5.1v, RaspberryPi was rebooting. Can this be addressed with a TIP? is the same behaviour? TIP will make a lot of sense if they deliver 5v output as the main input source is still in those voltage levels.
	* Large body parts for small printers, that can be screwed safetly, so more people with smaller printers, can access the project
	* Can we do a body plate that can be removed without unassembling the dog?
	* Can the batteries will be screw to the side panels, so they can remain while the electronics are being worked outside of it?
	* Can we just fit the electronics instead of flat, vertically? RaspberryPi Zero W dimensions are 66.0mm x 30.5mm x 5.0mm, PCA9685 dimensions are 62 x 26 mm




