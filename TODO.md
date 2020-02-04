Upgrades

	v1.03

	* New symetric foot from franferri, easy to glue
	* Nozzle 0.6 to fast print the dog
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
	* Custom PCB can be ordered to JLCPCB online for 2dollars (do they provide a board designer?), make sure the cables go screwed to those boards, instead of solded, to simplify peoples life, also if we go for the non buck converter option but instead a tip that accepts from 4v to 20v input -> output 5v 1a for example, that comes solded with the headsink on it. (https://www.arrow.com/en/research-and-events/articles/battery-power-your-pi)
	* Raspberry Pi Zero W can be more than enough for the base dog, also good for consumption
	* Explain each component in the electronics wiki (and the rationality behind it). Power consumption, specifications that justify its usage, link to buy them
	* Buck converters and BEC create a significant amount of radio noise due the coils they use. TIP's are exchanging energy consumption with heat, if we can have the TIP with a heat sink in the PCB, not touching the PLA, this could be perfect. Maybe using 2 TIP in parallel will divide also the heat in 2 heatsinks. How much hot gets for the RPi power consumption?
	* When my batteries were delivering only 6v, the buck converter was delivering 4.6v or less instead of the preset 5.1v, RaspberryPi was rebooting. Can this be addressed with a TIP? is the same behaviour? TIP will make a lot of sense if they deliver 5v output as the main input source is still in those voltage levels.
	* Large body parts for small printers, that can be screwed safetly, so more people with smaller printers, can access the project
	* Can we do a body plate that can be removed without unassembling the dog?
	* Can the batteries will be screw to the side panels, so they can remain while the electronics are being worked outside of it?
	* Can we just fit the electronics instead of flat, vertically? RaspberryPi Zero W dimensions are 66.0mm x 30.5mm x 5.0mm, PCA9685 dimensions are 62 x 26 mm
	* Francois Chagnon commented about screwing in the horns instead of gluing them, original comment: "one change I would love is being able to use metal horns that can be screwed in rather than glued, like these https://www.amazon.ca/gp/product/B00NOGMK3M"
	* For the electronics part, do we need the screen at all?, if the base endgame of the dog is to be controlled by XBOX one controller via BT, we dont, we can simplify the schema, like With and Without screen. The software must work even if is not detecting the screen
	* Electronic repository, bill of materials, data about each component used in my build, the video about which components used and soldering. From charging batteries to cables and connectors selected and boards modifications.
	* Electronics also the "Align the servos part"
	* 3dprint repo, the video about the 3d printing (timelapse) and assembly.
	* Raspberry Pi, the video of how to get the dog up and running, from pi and empty sd card to have the dog pi working, with the setup of the boards. (maybe PiZeroW and/or Pi4, or both at the same time)
	* Raspberry Pi, also the video for the totally unnecesary development environment
	* The power dilema may be sovled: Linear regulators have better regulation and noise performance but aren’t efficient when then there is a lot of difference between vin and vout, so you have to use a combination of buck and linear regulator ( low dropout regulator :LDO). So we can use the bec 6v 20a and the TIP for lowering the 6v to 5v for the pi.
	* The power dilema, can be extremmely simplified with stepdown but also step up boards like: https://www.pololu.com/product/2574, but noise remains. Asking them in their forum https://forum.pololu.com/t/pololu-5v-step-up-step-down-voltage-regulator-s18v20f5-radio-noise-emi/18775 and also looking for even more adjusted alternatives: https://www.robotshop.com/eu/en/step-up-step-down-voltage-regulator-s7v7f5.html?gclid=Cj0KCQiApt_xBRDxARIsAAMUMu9YM3f-2dydw_v6pDfd_yMBbXO4I5dymHfL3ZbFN4Qkcfah6PYL2XQaAsg8EALw_wcB, Pololu europe prices: https://www.robotshop.com/eu/en/catalogsearch/result/?q=Step-Up+%2F+Step-Down&order=relevance&dir=desc

