# Awesome-Smart-Water-Utility-Leak-Detection-Software

## Top Smart Water Utility Leak Detection Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Acoustic Leak Detection, Pressure Anomaly Monitoring & Non-Revenue Water Reduction*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Smart Water Utility Leak Detection Software**. These tools help water utilities identify leaks in distribution networks using acoustic sensors, pressure transient analysis, flow telemetry, satellite imagery, and machine learning — reducing non-revenue water losses and extending infrastructure lifespan.



**Examples** include Asterra (Utilis), Pluto AI, Ketos, FIDO Tech, WINT Water Intelligence, SewerAI, Innovyze, Xylem Vue, Badger Meter, and Kamstrup (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom anomaly detection, and transparent hydraulic modeling — ideal for water utilities prioritizing data sovereignty, researchers advancing leak detection algorithms, and municipalities avoiding per-sensor licensing fees.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Asterra (Utilis)](https://asterra.io/)**  

  Satellite-based leak detection using L-band synthetic aperture radar (SAR) to identify potable water leaks from space. Detects leaks across entire distribution networks without ground sensors. Used by 600+ utilities worldwide.



- **[Pluto AI](https://pluto.ai/)**  

  AI-powered water intelligence platform for leak detection, water quality monitoring, and operational analytics across utility networks.



- **[Ketos](https://ketos.co/)**  

  Water quality and leak detection platform with IoT sensors and cloud analytics for utilities and commercial buildings.



- **[FIDO Tech](https://fidotech.com/)**  

  Acoustic leak detection platform using AI to distinguish background noise from actual leaks. Deployed by utilities globally for non-revenue water reduction.



- **[WINT Water Intelligence](https://wint.ai/)**  

  AI-powered water leak detection and conservation platform for commercial buildings, real estate portfolios, and industrial facilities. Detects leaks in real time and automatically shuts off water supply.



- **[SewerAI](https://sewerai.com/)**  

  AI-powered sewer inspection platform using computer vision to identify defects, cracks, and root intrusion in wastewater infrastructure.



- **[Innovyze (Autodesk)](https://www.innovyze.com/)**  

  Water infrastructure modeling and analytics platform including InfoWorks WS Pro for hydraulic modeling and leak detection.



- **[Xylem Vue](https://www.xylem.com/)**  

  Smart water management platform with leak detection, pressure monitoring, and asset management for utilities.



- **[Badger Meter](https://www.badgermeter.com/)**  

  Water metering and smart water solutions with AMI/AMR, flow monitoring, and leak detection capabilities.



- **[Kamstrup](https://www.kamstrup.com/)**  

  Smart metering and water management solutions with leak detection, remote reading, and analytics for utilities.



## Open-Source GitHub Projects



- **[SIAM](https://www.sciencedirect.com/science/article/pii/S2665963826000321)**  

  Open-source framework for identifying anomalies in water distribution networks. Uses whitening transformation of heterogeneous sensor data (pressure, flow, water tower level) to detect pipe bursts and incipient leaks without requiring network topology or demand patterns. **Automatically identifies nominal operational periods for training** from continuous sensor time series. Modular architecture allows swapping segmentation, clustering, and statistical methods. Validated on L-Town WDN benchmark (782 nodes, 905 pipes, 33 pressure sensors, 5-minute intervals). Detects 9 of 12 active leaks without delay; incipient leaks detected with expected lag. Published May 2026 .



- **[WNTR (Water Network Tool for Resilience)](https://github.com/USEPA/WNTR)**  

  Open-source Python package from Sandia National Laboratories and U.S. EPA for analyzing water distribution system resilience. Features infrastructure damage estimation, preparedness strategy evaluation, response action prioritization, and worst-case scenario identification. Includes hydraulic and water quality simulation, sensor placement optimization, and disaster recovery scenario analysis. Used by water utilities, universities, and government agencies for capital planning and resilience analysis. Available on USEPA GitHub .



- **[SCADA-LTS](https://sourceforge.net/projects/scada-lts/)**  

  Open-source SCADA platform with no license limitations on tags, users, dashboards, protocols, or installations. Supports OPC UA, Modbus TCP/RTU, BACnet/IP, MQTT, SNMP, DNP3, IEC 60870-5-101/104, M-Bus, AMQP for utility telemetry. Real-time and historical trending with configurable data logging, advanced alarm management, multi-user RBAC, and SQL connectivity. Runs on Linux, Windows, Docker. GPLv2 licensed. Suitable for water utility SCADA integration and pressure/flow anomaly monitoring .



- **[EPANET](https://github.com/OpenWaterAnalytics/EPANET)**  

  The Water Distribution System Hydraulic and Water Quality Analysis Toolkit. Industry-standard open-source engine for modeling water distribution networks, simulating hydraulic behavior, and evaluating pressure-dependent leakage. MIT licensed, 253 GitHub stars, actively maintained. Foundation for many commercial and open-source leak detection tools .



- **[Smart Water Leak Detection (Sukrut10k)](https://github.com/Sukrut10k/Smart-Water-Leak-Detection)**  

  AI-powered leak detection system using machine learning (Random Forest, Decision Tree, Logistic Regression, SVM) on IoT sensor data (pressure, flow rate, vibration, temperature). Features **Streamlit dashboard with real-time leak prediction**, what-if analysis with interactive sliders, zone map with GIS geo-visualization (Folium/Plotly), batch prediction via CSV upload, feature importance analytics, and **AI assistant (Groq LLaMA)** for leak trend queries and dynamic plot generation .



- **[STAC CDSE Leak Hunter](https://zenodo.org/records/18599546)**  

  Deterministic and AI-augmented framework for detecting **surface moisture anomalies** using Sentinel-2 multi-temporal analysis. Built on Copernicus Data Space Ecosystem with NDMI (Normalized Difference Moisture Index), adaptive thresholding, and lightweight AI anomaly ranking. Integrates ERA5-Land meteorological data for environmental context validation. Full scene traceability through STAC API. Designed for water utilities and public administrations. Python-based, v1.29.6.2 published February 2026 .



- **[WIA-SOC-008 Water Supply Standard](https://github.com/WIA-Official/wia-standards-public)**  

  Open standard for smart water supply systems defining data formats, APIs, communication protocols, and integration patterns. Includes **AI-powered leak detection with 97%+ accuracy**, minimum detectable leak of 0.1 L/min, average detection time under 48 hours, false positive rate under 5%, and location accuracy ±15 meters. Supports acoustic sensors (hydrophones), pressure transient analysis, flow rate monitoring, and AI pattern recognition. JSON-LD based data format, RESTful/WebSocket APIs, OPC UA/Modbus/DNP3 SCADA integration. MIT licensed reference implementations .



- **[ESPHome Water Leak Detector](https://github.com/mrahmadt/ESPHome-Water-Leak-Detector)**  

  DIY water leak detection using YF-B10-S flow sensor with ESPHome and Home Assistant. Detects hidden leaks (toilet tank leaks, faulty taps, pipe issues) that floor-based sensors miss. Real-time notifications and alerts. Includes ESPHome YAML, Home Assistant automation, and configuration.yaml. Requires plumbing work but is low-cost and highly customizable .



- **[AquOculus](https://latamt.ieeer9.org/index.php/transactions/article/view/10125)**  

  Cost-effective Advanced Metering Infrastructure (AMI) for urban water distribution. ESP32-based optoelectronic pulse counter that works with **any water meter model** without requiring specific color, metallic, or magnetic parts on the indicator. Communicates consumed water volume via Wi-Fi for Leakage Detection and Localization (LDL). Open-source software repository provided for reproducibility. TRL 3 prototype. Aimed at enabling massive AMR installation by water distribution companies .



- **[LoRaWAN Water Monitoring System](https://indico.ufla.br/event/2/contributions/754/)**  

  Open-source IoT system for sectorized water consumption monitoring on university campuses. Uses SAGATECH US-5.0 pulse-output meters, LoRaWAN communication (Browan gateway), ChirpStack v4 network server, Python processing, MySQL database, and Grafana visualization. Validated over 46 days across 11 consumption points with 96%+ packet delivery rate and relative errors within ±0.5% (INMETRO ±2% standard). Open-source reference implementation .



### Additional Strong Open-Source Options



- **[X-WHAT](https://link.springer.com/article/10.1007/s11269-026-04817-7)** — Open-source Excel-based model for looped water distribution network design and optimization. Solves Water Flow Problem (WFP) and Design Optimization Model (DOM) using Excel Solver. Transparent workbook with browser-based WebGUI .

- **[OOPNET](https://katalog.lib.cas.cz/EdsRecord/edsdoj,edsdoj.6e331e923ad04396af5601d0c579a399)** — Object-Oriented Python framework for water distribution network analysis with pressure-dependent consumption simulator. Handles networks up to 19,647 pipes and 17,986 nodes .

- **[pyanglianwater](https://github.com/pantherale0/pyanglianwater)** — Python client for retrieving smart meter usage data from Anglian Water. MIT licensed, integrated with Home Assistant .

- **Whole-House Water Leak Controller** — ESP32-based whole-house water leak detection and shutoff system with MQTT communication .



**Frameworks for building custom systems**: Combine **SIAM** for sensor anomaly detection without topology requirements, **WNTR** for hydraulic resilience analysis and disaster scenario planning, **SCADA-LTS** for utility telemetry integration and alarm management, **Smart Water Leak Detection** for ML-based prediction with interactive dashboards, and **STAC CDSE Leak Hunter** for satellite-based surface moisture detection to build a complete self-hosted water utility leak detection stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Water utility leak detection tools must comply with environmental regulations, drinking water safety standards (Safe Drinking Water Act, EU Drinking Water Directive), and utility operational requirements. False negatives in leak detection can result in significant water loss and infrastructure damage.

- Self-hosted open-source solutions require proper security hardening, sensor calibration, and validation against known leak events before operational deployment.



---



**Made for water utility operators, distribution network engineers, non-revenue water managers, and developers building smart water infrastructure platforms.**  

Let's make smart water utility leak detection more open, accurate, and water-efficient.
