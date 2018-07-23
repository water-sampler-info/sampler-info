# sampler-info

## Cable connector part numbers & types for Teledyne ISCO water samplers:
* Battery 2-pin: Amphenol 97-3106A-10SL-4S
* Printer/Computer 6-pin: Amphenol MS3106A14S-6P (available from other mfgs as well)
* Flow meter/pulse 6-pin: Amphenol MS3106A14S-6S

(Wiring information on pg. 4-4 of ISCO 3700 manual, search for it)

### Rain gauge adapter cable part numbers
* 4-pin connector: Amphenol 97-3106A-14S-2P
  * This plugs into the 9-pin port but only uses two pins
  * Red wire goes to pin A
  * Black wire goes to pin D
  * But it actually doesn't matter. Just wire the tipping bucket switch between pins A and D and you're good to go.
  
## Interrogator cable/ISCO sampler to USB adapter
The .pdf schematic shows wiring and required parts for an adapter between a cable with an Amphenol connector and a TTL-USB cable. This will allow you to connect your sampler directly to your USB port. You can easily build this on perfboard or a breadboard. If you want to make pcbs, the zipped gerber contains manufacturing files. Upload the zip file and order from OSH Park, Seeed studio, or any other fine purveyor of circuit boards. Put it in a waterproof box or pot with epoxy. The holes in the board may be used as strain reliefs.
