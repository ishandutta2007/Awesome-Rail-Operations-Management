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

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Additional Strong Open-Source Options](#additional-strong-open-source-options)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product / Platform | Primary Domain & Key Capabilities | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Bentley OpenRail](https://www.bentley.com/)** | Railway engineering, track design, civil infrastructure, BIM modeling, surveying, and corridor planning. | $9,383 / year (Virtuoso 12-month practitioner license via eStore) | 14-day free trial (1 named user, standard sample railway dataset, cloud sandbox) |
| **[RailCube](https://www.railcube.com/)** | Rail freight operations, train & path planning, fleet tracking, locomotive/wagon asset monitoring, and crew dispatch. | €1,200 / month (~€14,400 / year) for base rail freight & asset operations module | 14-day guided pilot trial (1 sandbox organization, up to 3 dispatcher seats, sample fleet) |
| **[OpenTrack Railway Technology](https://www.opentrack.ch/)** | Railway microscopic simulation, timetable stability modeling, headway & capacity analysis, and conflict detection. | CHF 7,200 / year (~$8,100 / year) commercial single-seat workstation license (CHF 2,400 / year academic) | 14-day evaluation license (single workstation, capped at 10 simulated trains and 20 km network track) |
| **[RailSys](https://www.rmcon.de/)** | Timetable construction, track possession planning, infrastructure constraints, slot management, and network capacity analysis. | €8,500 / year single-user workstation base license for infrastructure & timetable modules | 14-day evaluation license (single workstation, restricted to 1 sample network model, export disabled) |
| **[Siemens Railigent X](https://www.siemens.com/railigent)** | Digital rail asset intelligence, fleet predictive maintenance, telemetry data pipelines, and decision-support APIs. | $25,000 / year base application suite & connectivity pack (up to 10 connected rail assets) | 30-day guided evaluation trial (limited to 1 fleet subset / 5 connected vehicle telemetry streams) |
| **[Alstom HealthHub](https://www.alstom.com/)** | Cloud-based rolling-stock health monitoring, predictive maintenance algorithms, wayside detectors, and asset analytics. | $40,000 / year foundation diagnostics & fleet analytics tier for regional fleets | 30-day evaluation trial (limited to 1 trainset unit / 10 subsystem diagnostic sensor parameters) |
| **[Trapeze Rail](https://www.trapezegroup.com/)** | Rail transit operations, timetabling, vehicle block optimization, automated crew rostering, and computer dispatching. | $35,000 / year base rail scheduling & workforce management starter package | 30-day sandbox pilot (up to 2 planner accounts, limited to 1 line timetable model) |
| **[Cubic Transportation Systems](https://www.cubic.com/transportation)** | Intelligent transit operations, automated fare collection, real-time passenger information, and traffic control integration. | $1,500 / month ($18,000 / year) base agency platform fee plus operational ticketing services | 30-day sandbox trial (test agency account, simulated rider transactions, up to 5 virtual station validators) |
| **[RailComm / Tracsis](https://tracsisus.com/)** | Computer-aided dispatching (CAD), positive train control (PTC) interfaces, yard automation, and remote condition monitoring. | $30,000 / year baseline dispatching and yard management system for shortlines | 30-day guided demonstration trial (virtual dispatch sandbox, up to 2 active consoles, 1 track territory) |
| **[IVU.rail](https://www.ivu.com/)** | Integrated railway operations suite covering timetables, rolling stock assignment, crew dispatching, and disruption recovery. | €30,000 / year starter timetable and rolling-stock duty module for regional operators | 30-day evaluation pilot (cloud test environment, up to 2 planning seats, 1 regional schedule dataset) |
| **[GIRO HASTUS](https://www.giro.ca/)** | Rail transit scheduling suite, timetable development, run-cutting, crew rostering, and daily operational dispatch. | $45,000 / year core rail scheduling, vehicle blocking, and crew rostering module | 30-day proof-of-concept environment (up to 2 planner logins, limited to 1 division schedule model) |
| **[HaCon TPS](https://www.hacon.de/)** | Train planning and capacity management technology, macroscopic/microscopic timetable synthesis, and infrastructure slotting. | €28,000 / year base train planning system starter module for regional networks | 14-day structured test sandbox (1 user license, demo rail corridor, capped at 50 train paths) |
| **[Hitachi Rail](https://www.hitachirail.com/)** | Integrated operations control, HMAX digital asset management platform, signalling supervision, and operational AI analytics. | $50,000 / year base digital asset intelligence & monitoring package for regional operators | 30-day proof-of-concept trial (limited to 1 monitored line section / 20 telemetry sensor feeds) |
| **[Thales Ground Transportation Systems](https://www.thalesgroup.com/)** | Rail traffic management, digital signalling, automated train supervision (ATS), and central command communications. | $60,000 / year digital rail supervision & network analytics starter package | 30-day proof-of-concept cloud access (simulated rail corridor, up to 10 virtual signal blocks) |
| **[Alstom ICONIS](https://www.alstom.com/)** | Integrated control and supervision center platform for mainline and metro networks, automated traffic regulation, and SCADA. | $55,000 / year integrated traffic management & control center foundation system | 30-day pilot sandbox (test ATS workstation instance, limited to 1 virtual control sector) |
| **[Siemens Rail Operations Centre / TMS](https://www.mobility.siemens.com/)** | Network-wide traffic management systems (TMS), centralized train dispatching, conflict prediction, and automated routing. | $50,000 / year base traffic management system & dispatch coordinator module | 30-day evaluation environment (virtual control center simulator, up to 2 dispatch operators) |

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

