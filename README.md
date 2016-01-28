# StratosphereIPS Argus VirtualBox Image

This is a virtual machine that automatically runs the Argus program already configured to send the flows to the Stratosphere Project servers.
It runs argus automatically when it starts and sends the flows as are read by argus from the eth0 inteface.

Please edit the file /root/stratosphere-argus/argus.conf and change the ID of the argus from VMX to your ID. If you don't have an argus id, please ask one to stratosphereips@agents.fel.cvut.cz

For space reasons, we moved the vm to this [location](https://mcfp.felk.cvut.cz/publicDatasets/StratosphereIPS-Argus-VirtualBox/Stratosphere-Argus.ova.gz)

The default credentials are:
- root / stratosphere
- stratosphere / stratosphere

Please change them.

The vm also automatically uses the linux FW to stop any connection going from the network to this vm. So no one should be able to connect to this machine from the outside.
