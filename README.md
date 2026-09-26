# Awesome-Emergency-Department-Flow-Management

I’ve kept the same structure as the previous ecosystem READMEs, but for this category I’ve made an important distinction: there are relatively few mature open-source products that are direct Qventus/TeleTracking-style ED-flow platforms, so the OSS section combines the closest operational platforms with open-source hospital systems, ED simulators, queue/flow tooling, FHIR infrastructure, optimization engines, and command-center building blocks. For example, Zephyrus explicitly includes live ED operations and hospital-wide capacity management, while EDSim is an open-source ED operations simulator. 
GitHub
+1

Top Emergency Department Flow Management Platforms Ecosystem
Top Emergency Department Flow Management Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Emergency Department Flow, Patient Throughput, Bed Management, Capacity Management, Hospital Command Centers & Care Coordination
Last updated: September 2026

This repository tracks notable Emergency Department (ED) Flow Management and Hospital Patient Flow platforms and open-source projects for managing emergency-care throughput, patient queues, bed capacity, admissions, transfers, discharge coordination, bottlenecks, staffing, and hospital-wide operational flow.

Examples include Qventus, LeanTaaS, TeleTracking, Central Logic, Hospital IQ, GE Command Center, Oracle Health Patient Flow, CareAware Patient Flow, Care Logistics, Medworxx, and related hospital command-center and capacity-management platforms.

Open-source emphasis: The Open-Source section prioritizes projects that can be used to build self-hosted ED-flow and hospital-operations systems, including hospital information systems, ED dashboards, command centers, patient-flow applications, discrete-event simulators, queue-management systems, optimization engines, interoperability platforms, FHIR infrastructure, analytics platforms, and workflow orchestration tools.

Because mature open-source equivalents of commercial ED command-center platforms are still relatively uncommon, supporting projects are explicitly identified rather than presented as direct one-to-one replacements.

Contributions welcome! Please add missing platforms, open-source hospital-flow projects, simulation frameworks, healthcare interoperability tools, optimization engines, and operational analytics projects.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Qventus
AI-powered healthcare operations platform with an Emergency Department solution designed to predict crowding, identify emerging bottlenecks, optimize ED process steps, coordinate ancillary services, and support hospital-wide patient flow.

LeanTaaS iQueue
AI and machine-learning-powered hospital capacity-management platform covering inpatient flow, staffing, operating rooms, and infusion centers. Its inpatient-flow capabilities address capacity constraints, admissions, discharges, patient placement, and ED boarding.

TeleTracking Operations IQ
Enterprise hospital-operations platform providing patient-flow, throughput, transfer-center, capacity, transport, environmental-services, and command-center capabilities. Its Throughput module coordinates the acute-care journey from admission through discharge.

Central Logic
Patient-flow and transfer-center technology historically focused on managing patient access, transfers, referrals, bed availability, and hospital capacity. Central Logic developed dedicated bed-management functionality through its Core platform.

Hospital IQ
Hospital operations and workflow-automation platform focused on capacity management, workforce management, patient flow, and operational optimization. Hospital IQ was acquired by LeanTaaS in January 2023 and its capabilities became part of the combined LeanTaaS organization.

GE HealthCare Command Center
Hospital command-center technology designed to provide operational visibility and decision support across patient flow, capacity, staffing, transfers, and other hospital operations.

Oracle Health Patient Flow
Patient-flow platform providing near-real-time visibility into bed utilization, length of stay, transfers, discharge information, bed management, environmental services, and patient transportation.

Oracle Health Command Center Dashboard
Enterprise command-center capability providing near-real-time visibility, predictive analytics, bed-capacity insights, staffing-demand information, and patient-flow forecasting.

Oracle Health CareAware Patient Flow
Patient-flow technology originating in the Cerner CareAware portfolio, supporting movement of patients and equipment, clinically appropriate bed placement, environmental-services requests, and transportation workflows.

Care Logistics
Hospital operations and command-center platform built around patient throughput, progression, bed placement, staffing coordination, diagnostics, transport, environmental services, and centralized operational coordination.

Medworxx
Healthcare workflow and patient-flow technology associated with hospital operational management, utilization, clinical workflow, and capacity-management use cases.

Innovaccer
Healthcare data and AI platform with workflow, analytics, automation, and operational capabilities that can support patient-access and healthcare operations use cases. Its current Flow product is primarily positioned around financial and revenue-cycle automation rather than being a dedicated ED command-center product.

QGenda
Healthcare workforce-management platform supporting physician and clinical staffing, scheduling, capacity planning, and resource allocation that can complement ED flow-management programs.

RLDatix
Healthcare operations and workforce platform covering staffing, patient safety, clinical operations, and workflow coordination that can complement patient-flow programs.

symplr
Healthcare operations platform with workforce, enterprise-resource, and operational-management capabilities that can complement hospital throughput and capacity-management workflows.

CarePort
Care-transition and post-acute coordination platform supporting referrals, discharge planning, placement, and transitions across healthcare organizations.

WellSky
Healthcare software platform spanning acute care, post-acute care, care coordination, discharge, referral management, and operational workflows.

Epic
Enterprise EHR platform with patient-flow, capacity, bed-management, emergency-department, command-center, and operational analytics capabilities integrated into its broader clinical information system.

MEDITECH
Enterprise EHR platform supporting emergency, inpatient, scheduling, patient-flow, bed-management, and operational workflows.

Altera Digital Health
Healthcare IT platform provider whose acute-care systems include EHR and operational capabilities supporting patient-flow and hospital operations.

Change Healthcare Enterprise Visibility
Enterprise healthcare visibility and analytics technology associated with hospital operations and patient-flow use cases.

CareAware Capacity Management
Hospital capacity-management ecosystem associated with Oracle Health/Cerner technology, integrating patient-flow, care-view, transfer-center, and command-center capabilities.

PeraHealth
Clinical surveillance and deterioration-management platform that can provide operational signals useful for patient-flow and capacity decisions.

Open-Source GitHub Projects

Zephyrus
Open-source hospital operations command-center project combining live Emergency Department operations, real-time demand and capacity, bed tracking, patient-flow visualization, perioperative operations, staffing, and process intelligence. Its ED module includes census, door-to-provider, LWBS, boarding, EMS inbound, and NEDOCS-related metrics.

MedCore
Open-source hospital information system covering outpatient, inpatient, emergency, surgery, pharmacy, laboratory, billing, and hospital operations. Its emergency module includes five-level triage, clinical scoring, a live ER board, and real-time updates.

CARE HMIS
Open-source hospital information system from the Open Healthcare Network covering clinical and operational workflows across outpatient, emergency, inpatient, laboratory, pharmacy, billing, queues, beds, wards, departments, and dashboards. It is particularly useful as a foundation for building patient-flow applications around an open hospital-information core.

EDSim
Open-source agentic simulator for Emergency Department operations. It models ED workflows using autonomous doctor, nurse, triage, and patient agents and is designed as a research and experimentation environment for studying ED crowding, workflow, and patient-flow behavior.

Hospital ED Throughput Simulation
Open-source discrete-event simulation of ED patient flow using SimPy, including experiments comparing staffing interventions and stochastic operational scenarios.

PulseGrid AI
Open-source emergency medical command-dashboard prototype combining emergency patient intake, triage, hospital capacity, ambulance routing, dynamic priority queues, maps, and real-time WebSocket updates.

JeevanSetu
Open-source AI-assisted emergency triage and hospital-routing project designed around clinical triage, hospital capacity, referral routing, and patient-flow coordination.

OpenMRS
Open-source medical-record platform that can provide the clinical and encounter-management foundation around which emergency registration, triage, queue, and patient-flow workflows can be built.

Bahmni
Open-source hospital information system built around OpenMRS and related components, providing registration, clinical workflows, laboratory, pharmacy, billing, and hospital-management functionality.

GNU Health
Free and open-source health and hospital information system covering clinical, administrative, and health-management workflows.

OpenEMR
Open-source electronic health-record and medical-practice-management system that can provide patient, encounter, scheduling, and clinical workflow primitives.

HospitalRun
Open-source hospital information system designed around patient records, clinical workflows, inventory, and hospital operations.

Open Hospital
Open-source hospital information-management system covering patients, admissions, visits, laboratory, pharmacy, and administrative workflows.

GNUmed
Open-source medical-practice and clinical-information tooling that can serve as a building block for healthcare workflow applications.

Additional Strong Open-Source Options

SimPy
Open-source discrete-event simulation framework for Python. It is highly useful for modeling ED arrivals, triage queues, treatment resources, boarding, staffing, diagnostic bottlenecks, and discharge processes.

salabim
Python discrete-event simulation framework suitable for modeling healthcare queues, patient flow, staffing, beds, and resource utilization.

Mesa
Python agent-based modeling framework useful for creating simulations of patients, clinicians, beds, departments, ambulances, and operational decision-making.

OR-Tools
Open-source optimization toolkit from Google supporting constraint programming, linear programming, routing, scheduling, and assignment problems. It can be used for ED staffing, bed allocation, patient routing, and resource scheduling.

Pyomo
Open-source Python optimization-modeling framework useful for mathematical optimization of staffing, bed allocation, patient-flow, and hospital-capacity problems.

PuLP
Python linear-programming modeler useful for resource allocation, staffing, scheduling, and capacity optimization.

Optuna
Open-source hyperparameter-optimization framework useful for tuning predictive models used in demand forecasting, length-of-stay prediction, and patient-flow optimization.

scikit-learn
Open-source machine-learning framework useful for ED demand forecasting, length-of-stay prediction, queue-risk prediction, readmission models, and operational analytics.

XGBoost
Gradient-boosting framework useful for predicting ED arrivals, admissions, length of stay, boarding risk, discharge probability, and other operational outcomes.

LightGBM
High-performance gradient-boosting framework useful for large-scale healthcare-demand and patient-flow prediction.

PyTorch
Open-source deep-learning framework useful for demand forecasting, patient-flow prediction, time-series modeling, and optimization-related ML applications.

Darts
Python time-series forecasting library useful for predicting ED arrivals, bed demand, admissions, discharges, staffing requirements, and other operational time series.

Nixtla StatsForecast
High-performance time-series forecasting library useful for large-scale demand forecasting and capacity planning.

Apache Superset
Open-source analytics and dashboard platform useful for constructing ED operational dashboards, throughput metrics, wait-time reports, and hospital command-center visualizations.

Metabase
Open-source BI platform useful for self-service operational analytics over ED, bed-management, staffing, and patient-flow datasets.

Grafana
Open-source observability and visualization platform suitable for real-time hospital operational dashboards and command-center displays.

Apache Kafka
Open-source event-streaming platform useful for transporting real-time patient-flow, bed-status, ADT, transport, EVS, and operational events.

Apache Flink
Open-source stream-processing engine useful for real-time patient-flow analytics, event processing, capacity calculations, and operational alerts.

Apache Spark
Distributed analytics engine useful for large-scale historical analysis of ED arrivals, throughput, length of stay, boarding, staffing, and capacity.

Apache Airflow
Open-source workflow orchestrator useful for scheduling ETL, operational analytics, forecasting, reporting, and hospital-capacity workflows.

FHIRbase
Open-source FHIR server technology useful for exposing healthcare data through interoperable APIs to patient-flow applications.

HAPI FHIR
Open-source Java implementation of HL7 FHIR providing server and client libraries that can serve as the interoperability layer between EHRs and patient-flow applications.

Medplum
Open-source healthcare developer platform centered around FHIR, providing APIs, workflows, data models, and application infrastructure useful for building healthcare operational applications.

LinuxForHealth FHIR Server
Open-source enterprise FHIR server suitable for healthcare interoperability and integration with patient-flow and hospital command-center applications.

NextGen Connect
Open-source healthcare integration engine formerly known as Mirth Connect, useful for connecting EHR, ADT, laboratory, patient-flow, bed-management, and operational systems.

OpenHIM
Open-source health-information mediator useful for orchestrating interoperability between multiple healthcare information systems and services.

OpenTelemetry
Open-source telemetry framework that can provide infrastructure and application observability for hospital command-center systems.

PostgreSQL
Open-source relational database suitable for storing patients, encounters, beds, queues, operational events, resources, and historical flow data.

TimescaleDB
Open-source PostgreSQL extension optimized for time-series data, useful for storing high-frequency operational events and real-time hospital metrics.

ClickHouse
Open-source analytical database useful for high-volume event analytics, operational dashboards, patient-flow histories, and command-center reporting.

Redis
In-memory data store useful for real-time queues, patient-flow state, operational alerts, caching, and low-latency command-center applications.

Temporal
Open-source durable workflow orchestration platform useful for coordinating complex patient-flow-related operational workflows and long-running hospital processes.

Camunda
Open-source workflow and process-orchestration platform useful for modeling and automating admission, transfer, discharge, escalation, transport, and bed-management processes.

Node-RED
Open-source flow-based programming platform useful for connecting healthcare systems, processing operational events, and rapidly prototyping patient-flow automations.

Keycloak
Open-source identity and access-management platform useful for securing multi-user hospital command-center applications and operational dashboards.

Open Policy Agent
Open-source policy engine useful for enforcing role-based operational policies and authorization rules in patient-flow systems.

Framework for building a self-hosted Emergency Department Flow Management platform: Combine CARE HMIS / OpenMRS / Bahmni / MedCore as the hospital-information foundation; Zephyrus / PulseGrid / custom React dashboards for the command-center and ED operational layer; HAPI FHIR / Medplum / LinuxForHealth FHIR / NextGen Connect / OpenHIM for interoperability; Kafka / Flink / Redis for real-time event processing; PostgreSQL / TimescaleDB / ClickHouse for operational data; Grafana / Superset / Metabase for dashboards; OR-Tools / Pyomo / PuLP for resource optimization; SimPy / salabim / Mesa / EDSim for simulation and what-if analysis; scikit-learn / XGBoost / LightGBM / Darts / StatsForecast for forecasting and predictive analytics; and Temporal / Camunda / Node-RED for workflow orchestration.

A practical architecture can therefore cover ED arrival forecasting → triage → queue management → treatment-room allocation → diagnostics → admission decision → bed matching → transport → inpatient placement → discharge → capacity forecasting, while maintaining a real-time operational picture for a hospital command center.

How to Contribute

Fork this repository.

Add the platform or open-source project to the appropriate section.

Prefer official product websites for SaaS platforms.

Prefer official GitHub repositories for open-source projects.

Keep descriptions concise and technically accurate.

Prioritize actively maintained projects.

Clearly distinguish complete patient-flow platforms from simulation frameworks, hospital information systems, interoperability tools, and infrastructure components.

Submit a pull request with your changes.

Disclaimer

This is a curated ecosystem rather than a ranking or endorsement.

Commercial platforms differ substantially in their coverage of ED operations, inpatient flow, bed management, transfer centers, command centers, staffing, predictive analytics, workflow automation, and EHR integration.

Some platforms listed here are dedicated patient-flow or hospital-command-center products, while others are broader healthcare platforms that provide capabilities relevant to ED flow management.

The Open-Source section intentionally includes both complete or near-complete hospital/ED applications and building blocks that can be assembled into an ED-flow platform.

An open-source project should not be assumed to provide clinical decision support, validated medical algorithms, production-grade patient safety controls, or the same functionality as a commercial hospital operations platform.

Healthcare software handling real patient data must be evaluated for privacy, security, regulatory compliance, clinical safety, interoperability, availability, auditability, and operational reliability before deployment.

Open-source availability, licensing, features, supported standards, and project activity can change over time.

Made for emergency physicians, ED nurses, hospital operations teams, bed managers, command-center teams, health-system CIOs, data engineers, healthcare AI engineers & organizations building the next generation of Emergency Department Flow Management platforms.
Let's make hospital flow more open, interoperable, data-driven, composable & self-hostable.

Reorganize open-source projects by function
Add a comparison matrix for platforms
