### QoS (Quality of service) ###

<<<<<<< HEAD
This is a Linux bash script that will set up tc to limit the outgoing bandwidth for connections to the Wednesdaydudecoin network. It limits outbound TCP traffic with a source or destination port of 9669, but not if the destination IP is within a LAN (defined as 192.168.x.x).
=======
This is a Linux bash script that will set up tc to limit the outgoing bandwidth for connections to the Wednesdaydudecoin network. It limits outbound TCP traffic with a source or destination port of 9333, but not if the destination IP is within a LAN (defined as 192.168.x.x).
>>>>>>> b533965b470a0bc12482b1e2b24487e167e38ce1

This means one can have an always-on wednesdaydudecoind instance running, and another local wednesdaydudecoind/wednesdaydudecoin-qt instance which connects to this node and receives blocks from it.
