txstate.zip
-----
This zip file contains the configuration files used by the training video.

The key files are:
 
Agent:
txstate.xml – device xml for this model with the TwinDemo configuration.
agent.cfg – configure file for MTConnect agent. Currently use demo.metalogi.io for data points. This should be changed to your MTConnect adapter.
 
twin/objs:
txstate.obj – 3D OBJ model file for the device
 
Once unzipped, go to Agent directory and run “agent run” assuming you have MTConnect agent already installed. And then enter http://localhost:7979/twin/index.html?device=txstate to view the TwinDemo simulation. Note that the data range of x,y,z,c position is invalid for this device as this set up is using another device’s data.
 
