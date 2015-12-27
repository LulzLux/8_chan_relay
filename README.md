# 8_chan_relay
8 channel arduino relay w/analog buttons

an 8 outlet ups w/o a battery or dc charging circuit. 
ac rails & heat surge reset button connected to ac plug.
hot (+) rail segmented w/18awg soldered to each segment====
hot wires connect to no (normally open) on relay +|_ \_|
hot wire on reset connects serially to com on relays |_com\_|
5v 700ma powering arduino
5v 1.5a powering relay (isolated rail)

//

channel 8 & others were unstable - probably due to arduino's 5v was connectd to 7-12v barrel input. 



