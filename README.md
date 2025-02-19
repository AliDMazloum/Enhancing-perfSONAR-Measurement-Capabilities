# Enhancing-perfSONAR-Measurement-Capabilities
This repo contains the source code for the paper: Enhancing perfSONAR Measurement Capabilities using P4 Programmable Switches and Adaptive Sampling

--------------------------------------------------------

Steps to run the program:

    1)  make compile                                        // this step compiles the P4 program.
    
    2)  make run                                            // this step runs the compiled application.
    
    3)  make conf_links                                     // this step enables the ports at the switch.
    
    4)  make start_control_plane_measurements               // this step starts the measurement collection at the control plane.
    
    5)  python3.9 Measurement_collector/main.py             // this script receives the collected measurement from the conrol plane of the 
                                                               switch and plot them on grafana
