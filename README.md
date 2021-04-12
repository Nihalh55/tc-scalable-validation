# TCP-Scalable-ns3-NEST-validation
The goal is to validate the ns-3 implementation of Scalable TCP using Network Stack Tester (NeST)

## NS-3 Experiments
- Latest version of NS-3 (allinone) and required packages were installed 
- Created a congestion control critical topology for testing wireless network performance
- Ran the topology code for suitable network parameters
- Plotted the graph using GNUPlot; these graphs were used for the overlapped comparison graphs too
  
## NEST Experiments
- Installed NEST and verified installation by running examples in root/examples
- The initial tested examples and results can be found in the **Tcp_Scalable_nest Folder** (Tested for P2P, Single Dumbbell and Dumbbell)
- The **Scalable_NEST_Simulation** folder contains the experiments run with the topology used in NS-3 with offloads enabled; The graphs for this topology can be found in the folder
- The **Scalable_NEST_Simulation_no_offload** folder contains the experiments run with the topology used in NS-3 with offloads enabled; The graphs for this topology can be found in the folder.
- The graphs obtained in the experiment without offloads were used for the overlapped comparison graphs

