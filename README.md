# TissueSlabSimulationDemo
This repository demonstrates using the SCIRun problem solving environment to simulate extracellular voltage fields.

The main SCIRun network includes two moveable electrodes and a moveable scar zone. There are two domains, blood (homogeneous isotropic conductivity) and tissue (anisotropic conductivity defiend by fiber directions). The network calculates potential throughout both domains by solving laplace's equation with the stimulation voltages as boundary condutuions, no flow boundary at the domain outter edges. The network also calculates the voltage gradient and can display steamlines of it.


![stimulation network](/images/stimNetwork.png?raw=true "Network View of Stimulation Network")


![stimulation results](/images/results.png?raw=true "Results from simulation")
