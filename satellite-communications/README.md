# Satellite Communications and Constellation Analysis

This section presents selected projects related to satellite communications, orbital access analysis and multi-satellite network architectures, developed during the MSc in Space Systems at UPM.

The projects cover satellite orbit propagation, ground-station visibility, communication-link geometry, inter-satellite links, constellation design and routing, RF link budgets and Adaptive Coding and Modulation.

The work was developed mainly using MATLAB and the Satellite Communications Toolbox, combining orbital simulation, communication-system modelling, network analysis and engineering trade-offs.

## Projects

### [LEO–MEO Satellite Communications and Adaptive Coding & Modulation](./leo-meo-communications-acm/LEO_MEO_Communications_ACM_Analysis.pdf)

Communication-system analysis of a multi-orbit LEO–MEO architecture inspired by the IRIS² constellation.

The project includes constellation definition, ground-to-LEO Ka-band link budgeting, adaptive MODCOD selection, throughput estimation and RF inter-satellite link analysis between LEO–LEO and LEO–MEO spacecraft.

Main activities include:

- LEO and MEO constellation definition and coverage analysis
- Ground-to-satellite access analysis
- Ka-band uplink link budget
- EIRP and G/T calculation
- C/N and link-margin assessment
- Adaptive Coding and Modulation (ACM)
- MODCOD selection and throughput estimation
- RF inter-satellite link analysis
- LEO–MEO transmitter and receiver dimensioning
- Power, antenna and ADCS trade-offs

### [Satellite Constellation Routing and Inter-Satellite Link Analysis](./constellation-routing-isl/Constellation_Routing_ISL_Analysis.pdf)

Design and analysis of a Walker Star constellation and its associated ground and inter-satellite communication network.

The project includes constellation phasing, ground-station visibility, antenna-resource assessment, inter-plane and intra-plane ISL topology generation, graph-based routing and end-to-end latency analysis.

Main activities include:

- Walker Star constellation generation
- Phasing-factor calculation
- Ground-station visibility analysis
- Simultaneous-access assessment
- Ground-station antenna sizing trade-offs
- Intra-plane and inter-plane ISL definition
- Dynamic satellite network topology generation
- Graph-based shortest-path routing
- Hop-count analysis
- End-to-end LEO latency assessment
- Comparison against GEO communications latency
- GSL selection trade-offs

### [Satellite Orbit, Ground Access and Link Dynamics Analysis](./orbit-access-link-analysis/Orbit_Access_Link_Analysis.pdf)

Orbital and communications analysis of an Earth-observation CubeSat using real TLE data.

The project evaluates orbit characteristics, ground tracks, visibility from multiple ground stations, data-download capacity, inter-satellite access and communication-link dynamics throughout satellite passes.

Main activities include:

- TLE-based orbit propagation
- Sun-synchronous orbit assessment
- Ground-track visualization
- Ground-station access analysis
- Pass duration and maximum-latency evaluation
- Downlink data-capacity estimation
- Inter-satellite link availability
- Azimuth, elevation and range analysis
- Free-space propagation losses
- Link latency
- Doppler-shift assessment

## Tools and Methods

- MATLAB
- Satellite Communications Toolbox
- Orbital propagation from TLE and Keplerian elements
- Walker constellation modelling
- Graph-based network routing
- Link-budget analysis
- Adaptive Coding and Modulation
- RF inter-satellite links
- Ground-segment access analysis

> These projects were developed in an academic context as part of the MSc in Space Systems at UPM. Some activities were completed individually and others as team projects.
