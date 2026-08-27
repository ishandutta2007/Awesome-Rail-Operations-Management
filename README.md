# Awesome-Rail-Operations-Management

## Top Rail Operations Management Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Railway Operations Control, Train Planning, Timetabling, Dispatching, Capacity, Asset Intelligence & Operational Optimization*
**Last updated: August 2026**

This repository tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Rail Operations Management**. These tools support railway operators, infrastructure managers, freight railroads, transit agencies, and maintenance organizations with train planning, timetabling, dispatching, traffic management, capacity analysis, rolling-stock management, infrastructure monitoring, predictive maintenance, and operational decision support.

**Examples** include Hitachi Rail, Trapeze Rail, Cubic Rail, Siemens Railigent X, Alstom HealthHub, RailCube, RailSys, OpenTrack, RailComm/Tracsis, and related railway operations platforms.

**Open-source emphasis**: The open-source ecosystem is much smaller than the commercial rail-software market, particularly for safety-critical dispatching and integrated traffic management. However, there are several strong projects covering **railway infrastructure design, capacity analysis, timetable planning, microscopic simulation, signalling simulation, railway mapping, schedule optimization, and operational research**. OSRD is particularly notable because it explicitly combines infrastructure design, capacity analysis, timetabling, simulation, and short-term path requests in an open-source web application. ([OpenRailAssociation/OSRD](https://github.com/OpenRailAssociation/osrd))

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.

## Table of Contents

* [SaaS/Hosted Platforms](#saas-products)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Additional Strong Open-Source Options](#additional-strong-open-source-options)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

* **[Hitachi Rail](https://www.hitachirail.com/)**
  Provides integrated rail operations, control and supervision systems, digital asset management, signalling, SCADA, analytics, and operational decision-support technologies. Hitachi's current HMAX platform brings together operational and asset data across fleets, signalling systems, and infrastructure.

* **[Trapeze Rail](https://www.trapezegroup.com/)**
  Rail operations software supporting transit agencies with scheduling, planning, operations, crew management, dispatching, and related transportation workflows.

* **[Cubic Transportation Systems](https://www.cubic.com/transportation)**
  Provides intelligent transportation and rail/transit technologies covering operations, control, passenger information, fare systems, and connected mobility.

* **[Siemens Railigent X](https://www.siemens.com/railigent)**
  Digital rail platform providing data services, analytics, predictive maintenance, asset intelligence, and decision support for railway operators, maintainers, and asset owners. Railigent X also provides APIs and near-real-time asset data for integration with other applications.

* **[Alstom HealthHub](https://www.alstom.com/)**
  Cloud-based railway health and predictive-maintenance platform continuously monitoring trains, signalling, and infrastructure. HealthHub converts railway-system data into actionable maintenance and operational insights.

* **[RailCube](https://www.railcube.com/)**
  Rail freight operations platform connecting planning, execution, fleet management, workforce management, compliance, and reporting. It provides tools to plan people, trains, and movements while tracking locomotives and wagons.

* **[RailSys](https://www.rmcon.de/)**
  Railway operations and simulation software covering timetable construction, slot management, track possession planning, capacity analysis, and railway simulation. RailSys has been used extensively for timetable-based railway capacity and operations analysis.

* **[OpenTrack Railway Technology](https://www.opentrack.ch/)**
  Railway simulation software for modelling train movements, infrastructure, timetables, conflicts, delays, capacity, and operational scenarios. Despite the name, OpenTrack is a **commercial** railway simulation product rather than an open-source project.

* **[RailComm / Tracsis](https://tracsisus.com/)**
  Rail automation and operations software provider offering computer-aided dispatching, positive train control, yard automation, remote condition monitoring, and related railroad operational technologies. RailComm is now part of Tracsis.

* **[GoalRail](https://goalrail.dev/)**
  Note: the current Goalrail product found under this name is an **AI-assisted software-development control layer**, not a railway operations-management platform. It therefore should not be treated as a rail-operations product despite the name similarity.

* **[Bentley OpenRail](https://www.bentley.com/)**
  Railway engineering and infrastructure-design environment supporting rail alignment, track design, civil engineering, BIM, surveying, and infrastructure planning.

* **[IVU.rail](https://www.ivu.com/)**
  Integrated railway planning and operations platform covering timetables, rolling stock, personnel, dispatching, disruption management, and operational optimization.

* **[GIRO HASTUS](https://www.giro.ca/)**
  Transportation planning and scheduling suite with capabilities for timetable development, vehicle scheduling, crew scheduling, rostering, and operations planning.

* **[HaCon TPS](https://www.hacon.de/)**
  Train planning and railway scheduling technology supporting timetable construction, infrastructure constraints, capacity management, and operational planning.

* **[Thales Ground Transportation Systems](https://www.thalesgroup.com/)**
  Provides rail traffic management, signalling, control, supervision, communications, and digital railway technologies for metro and mainline operations.

* **[Alstom ICONIS](https://www.alstom.com/)**
  Integrated control and supervision technology for railway and metro operations, providing centralized monitoring, traffic management, signalling integration, and operational control.

* **[Rail Operations Centre / Traffic Management Systems](https://www.mobility.siemens.com/)**
  Siemens Mobility provides railway traffic management, control-center, signalling, and operations technologies for coordinating train movements and network capacity.

RailSys and OpenTrack are particularly relevant to the **planning/simulation** side of the category, while platforms such as Railigent X and HealthHub are more focused on **asset intelligence, maintenance, and operational analytics**. Commercial rail operations suites increasingly combine these domains with real-time control, predictive analytics, and decision support.

## Open-Source GitHub Projects

* **[Open Source Railway Designer (OSRD)](https://github.com/OpenRailAssociation/osrd)**
  One of the strongest open-source projects in the category. OSRD is an open-source web application for **railway infrastructure design, capacity analysis, timetabling, simulation, and short-term path requests**. Its simulation engine includes infrastructure, rolling stock, pathfinding, and conflict-detection capabilities. Licensed under LGPL-3.0.

* **[OpenRailwayMap](https://github.com/OpenRailwayMap/OpenRailwayMap)**
  OpenStreetMap-based open-source railway infrastructure mapping project displaying railway lines, tracks, electrification, gauges, signalling-related infrastructure, and other railway attributes. Licensed under GPL-3.0.

* **[OpenRailwayMap Vector](https://github.com/giopera/OpenRailwayMap-vector)**
  Vector-based extension of OpenRailwayMap providing visualization of railway infrastructure, speed limits, train protection, electrification, and railway gauges using modern vector-tile technologies.

* **[OpenRail Association](https://github.com/OpenRailAssociation)**
  Open-source railway-software ecosystem containing OSRD and other railway-focused projects. The organization also hosts projects such as timetable/network-graph tooling and supporting railway-development infrastructure.

* **[Netzgrafik-Editor](https://github.com/OpenRailAssociation)**
  OpenRail project for creating, modifying, and analysing regular-interval timetables and network graphs. Useful for public-transport timetable planning and periodic service design.

* **[openSignalBox](https://github.com/opensignalbox)**
  Open-source software and hardware project for railway signalling simulation. It aims to reproduce authentic signal-box operations through modular software and hardware components.

* **[TS2 Train Signalling Simulator](https://github.com/ts2)**
  Open-source railway signalling simulator in which users dispatch trains across a network while attempting to maintain schedules. Includes a simulator and separate simulation-server components.

* **[Railway Operation Simulator (RailOS)](https://github.com/AlbertBall/railway-dot-exe)**
  Open-source railway operations simulator allowing users to build railways, develop timetables, operate trains, and simulate delays, failures, speed restrictions, and other operational events.

* **[Railway Signaling System](https://github.com/MenakaGodakanda/railway_signaling_system)**
  Open-source C++ project simulating train movement and real-time signalling updates. Useful as an educational foundation for experimenting with railway traffic-control logic.

* **[TrainApp](https://github.com/sairam4123/TrainApp)**
  Open-source Go-based railway simulation project modelling train movement, schedules, track-resource reservations, and conflict avoidance.

* **[Railway Scheduling](https://github.com/marcotallone/railway-scheduling)**
  Open-source research project applying mathematical optimization to railway maintenance scheduling while attempting to minimize passenger delays and satisfy railway-operator constraints.

* **[Robust Railway](https://github.com/transp-or/Robust_Railway)**
  Open-source framework for railway timetable rescheduling under disruptions using exact and heuristic optimization techniques. Designed around minimizing passenger inconvenience, timetable deviations, and operational costs.

* **[OpenRails](https://github.com/openrails/openrails)**
  Open-source/free railway simulator supporting a broad ecosystem of railway simulation content. While primarily a train simulator rather than an enterprise operations-management system, it is useful for railway simulation, testing, education, and operational scenarios.

### Additional Strong Open-Source Options

* **[OpenStreetMap](https://github.com/openstreetmap/openstreetmap-website)** for open railway-network and geographic infrastructure data.
* **[JOSM](https://github.com/openstreetmap/josm)** for detailed editing and maintenance of OpenStreetMap railway infrastructure data.
* **[OpenRailwayMap API](https://github.com/OpenRailwayMap/OpenRailwayMap-api)** for programmatic access to railway infrastructure information and search functionality.
* **[OpenRailwayMap CartoCSS](https://github.com/OpenRailwayMap/OpenRailwayMap-CartoCSS)** for rendering railway infrastructure map layers.
* **[OpenRailwayMap Server Admin](https://github.com/OpenRailwayMap/server-admin)** for infrastructure used to operate self-hosted OpenRailwayMap deployments.
* **[RailML ecosystem](https://www.railml.org/)** for interoperable railway-data exchange and modelling. RailML itself is primarily an open data-exchange standard rather than a complete operations-management application.
* **[OR-Tools](https://github.com/google/or-tools)** for developing custom railway scheduling, routing, crew, rolling-stock, and capacity optimization systems.
* **[Timefold Solver](https://github.com/TimefoldAI/timefold-solver)** for constraint-based optimization that can be adapted to railway scheduling, rostering, routing, and resource allocation.
* **[Pyomo](https://github.com/Pyomo/pyomo)** for mathematical optimization models involving railway timetables, capacity allocation, rolling-stock assignment, and disruption recovery.
* **[NetworkX](https://github.com/networkx/networkx)** for graph-based railway-network analysis, routing, infrastructure modelling, and algorithm experimentation.
* **[MATSim](https://github.com/matsim-org/matsim)** for large-scale transportation simulation and multimodal network modelling, with applications that can incorporate rail operations.
* **[SUMO](https://github.com/eclipse-sumo/sumo)** for open-source transportation simulation and network experimentation. Although primarily associated with road traffic, SUMO can be useful for multimodal and rail-adjacent simulation research.
* **[QGIS](https://github.com/qgis/QGIS)** for geospatial railway infrastructure analysis and visualization.
* **[PostGIS](https://github.com/postgis/postgis)** for spatial databases supporting self-hosted railway infrastructure, asset, and network-management systems.

**Framework for building a self-hosted rail-operations platform**: Combine **OSRD** for railway infrastructure, capacity, timetabling and simulation; **OpenRailwayMap + OpenStreetMap** for network and infrastructure data; **Netzgrafik-Editor** for periodic timetable planning; **openSignalBox/TS2** for signalling simulation; **OR-Tools/Timefold/Pyomo** for optimization; and **PostGIS + QGIS** for geospatial infrastructure management.

The open-source ecosystem is currently strongest in **railway simulation, timetable optimization, infrastructure mapping, research, and signalling simulation** rather than production-grade safety-critical traffic management. In particular, OSRD is the closest open-source project to a modern railway planning/capacity platform, while projects such as OpenRailwayMap and openSignalBox provide complementary infrastructure and signalling capabilities.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. For open-source projects, include the GitHub repository and license where available.
5. Clearly distinguish **enterprise production software**, **research projects**, **simulators**, **standards**, and **development libraries**.
6. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated** list — not exhaustive and not an endorsement.
* Many open-source projects listed here are **building blocks, simulators, research tools, or infrastructure-data platforms rather than direct replacements** for enterprise railway traffic-management systems.
* Safety-critical railway control, signalling, dispatching, interlocking, and traffic-management systems require appropriate certification, validation, redundancy, cybersecurity, and operational safety processes before deployment.
* Always verify the current license, maintenance activity, certification status, security posture, interoperability, and production suitability before using an open-source project in a real railway environment.
* Commercial product capabilities and product names can change as vendors consolidate or update their portfolios.

---

**Made for railway operators, infrastructure managers, transit agencies, freight railroads, timetable planners, dispatchers, railway engineers, researchers, and rail technologists.**
Let's make rail operations management more open, interoperable, data-driven, and efficient.

