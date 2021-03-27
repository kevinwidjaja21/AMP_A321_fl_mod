# AMP_A321_fl_mod
Flight model improvement for project mega pack A321

The project aims to improves the flight model of Project Mega Pack A321 with flight models of A32NX mod done by Fly-by-wire. Changes are made to match the specification of A321 such as:
- Maintain the wing area of original PMP setting od 1380 sqft.
- Move the position of aerodaynamic centre, horizontal tail and vertical tail to match the A321 3D model.
- Reduce cruise lift tuning from 1 to 0.972 to emulate the effect of using wingtip fence instead of sharklet [1].
. Increase induced drag from 1 to 1.01 to emulate the effect of using wingtip fence instead of sharklet [1].
- Change flaps angles and speed limits to match EASA TCDS No.: EASA.A.064 documents [2]
- Change flaps lift and drag scalar to match landing angle of attack of A32NX.
- Change slats speed limits to match EASA TCDS No.: EASA.A.064 documents [2].
- Change engine thrust specific fuel consumtion from 0.3 to 0.36 [3].

To install, simply copy `AMP_A321_fl_mod` folder and drop it in to your community folder.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Because this is a modification of Project Mega Pack A321, this work is also licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>

## Reference
[1] A. Alonso, "Analysis of Drag Reduction in Wingtip Devices", Bachelor, Universidad Carlos III de Madrid, 2021. Available: https://e-archivo.uc3m.es/bitstream/handle/10016/27640/TFG_Andrea_Mosquera_Alonso_2017.pdf. [Accessed: 27- Mar- 2021].

[2] TYPE-CERTIFICATE DATA SHEET No. EASA.A.064 for AIRBUS A318 – A319 – A320 – A321, 47th ed. European Union Aviation Safety Agency, 2021. Available: https://www.easa.europa.eu/sites/default/files/dfu/TCDS_EASA%20A%20064_%20Airbus_%20A318_A319_A320_A321_Iss_47.pdf [Accessed: 27- Mar- 2021].

[3] N. Meier, "Civil Turbojet/Turbofan Specifications", Jet-engine.net, 2005. [Online]. Available: https://www.jet-engine.net/civtfspec.html. [Accessed: 27- Mar- 2021].
