# ToolChangerSwing
Tool Changer Swing is a toy example that shows how contribute TCPs to PolyScope as well as access the list of available TCPs in PolyScope. 
In the installation contribution, the user can define a tool change position, enable/disable different tool TCPs and define a translational offset between the toolfange and all the enabled tool TCPs.

In the program node contribution, the user can select a TCP for the new tool from the list of all available TCPs in PolyScope. When the program node is executed, the robot will move to the user-defined tool change position, change the tool (simulated by a waiting period) and finally change the active TCP to the selected TCP.

Information:
* Available from:
  * URCap API version 1.5.0.
  * PolyScope version 3.8.0/5.2.0.

Main API interfaces: TCPContributionModel, TCPModel.
