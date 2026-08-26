# Richard Hanly

**Software Developer | Full-Stack Applications, Data Systems, Cloud Infrastructure, and Backend Engineering**

I am a software developer and Digital Services Specialist who builds practical software around real operational problems.

My work spans full-stack applications, backend APIs, data systems, analytics, cloud infrastructure, automation, and systems engineering. I am especially interested in projects where software has to do more than simply run — it needs to handle real data, fit an existing workflow, recover from failures, and remain understandable to the people who use or maintain it.

[Portfolio](https://richardhanly.dev) ·
[LinkedIn](https://www.linkedin.com/in/richardhanly/) ·
[GitHub](https://github.com/richardrhanly-us) ·
[Email](mailto:richardrhanly@gmail.com)

---

## Featured Projects

### SortView — AMH Analytics Platform

**Python · FastAPI · PostgreSQL · Streamlit · Alembic · Data Pipelines**

[Live Application](https://sortview.streamlit.app/?guest=1) ·
[Source Code](https://github.com/richardrhanly-us/amh-analytics-dashboard) ·
[Portfolio Case Study](https://richardhanly.dev/projects/sortview)

SortView is an analytics platform for Automated Materials Handler activity in library operations. It collects machine-generated sorter logs, converts them into structured records, stores them in PostgreSQL, and makes the resulting operational data available through an interactive dashboard.

**Highlights**

- Built a Windows-side agent that automatically reads and uploads sorter logs.
- Developed a FastAPI ingestion backend with validation and structured data processing.
- Designed PostgreSQL storage and Alembic migrations for persistent operational records.
- Built dashboards for live activity, historical analysis, reports, alerts, and troubleshooting.
- Added authentication and organization- and branch-level access controls.
- Developed the project around a real library operations workflow rather than a sample dataset.

**Demonstrates:** full-stack system design, backend development, data ingestion, database modeling, analytics, testing, deployment, and operational software development.

---

### Cloud Reliability Lab

**AWS · Terraform · Linux · nginx · systemd · CloudWatch · Systems Manager**

[Source Code](https://github.com/richardrhanly-us/cloud-reliability-lab) ·
[Portfolio Case Study](https://richardhanly.dev/projects/cloud-reliability-lab)

A hands-on cloud reliability environment built to gain practical experience provisioning, operating, monitoring, breaking, and recovering an application hosted in AWS.

The lab uses Terraform to provision an Amazon Linux EC2 environment and automatically bootstrap a FastAPI service behind nginx. systemd manages the application process, AWS Systems Manager provides administrative access without public SSH, and CloudWatch centralizes application, nginx, and system lifecycle logs.

**Highlights**

- Provisioned AWS networking, EC2, IAM, monitoring, and supporting infrastructure with Terraform.
- Configured S3-backed remote Terraform state with versioning, encryption, and state locking.
- Automated EC2 application setup through Terraform `user_data`.
- Configured nginx as the public reverse proxy while keeping Uvicorn bound to localhost.
- Added systemd automatic recovery for unexpected application-process failures.
- Forwarded application, nginx, and systemd lifecycle events into CloudWatch.
- Created a log-derived custom failure metric and CloudWatch alarm.
- Intentionally terminated the application process and verified automatic recovery, centralized failure logging, and alarm activation.
- Replaced the EC2 instance through Terraform and verified that the complete environment rebuilt successfully from code.

**Demonstrates:** Infrastructure as Code, AWS administration, Linux service management, observability, failure recovery, incident testing, secure remote administration, and infrastructure reproducibility.

---

### Water Utility GIS Operations Dashboard

**React · TypeScript · ArcGIS Maps SDK · Vitest · GitHub Actions**

[Live Application](https://water-utility-gis.vercel.app/) ·
[Source Code](https://github.com/richardrhanly-us/water-utility-gis) ·
[Portfolio Case Study](https://richardhanly.dev/projects/water-utility-gis)

An interactive GIS application built around simulated water-utility infrastructure and operational workflows.

The dashboard provides a map-based interface for exploring water mains, hydrants, valves, and service zones while supporting filtering, asset inspection, and spatial analysis.

**Highlights**

- Built an interactive ArcGIS map in React and TypeScript.
- Added asset filtering by type, status, material, condition, and installation year.
- Created context-aware asset inspection for water mains, hydrants, and valves.
- Implemented geodesic buffer analysis around selected water mains.
- Identified nearby hydrants and valves through spatial intersection.
- Added automated Vitest coverage and GitHub Actions CI.
- Built the project around utility-operations use cases rather than a generic GIS demonstration.

**Demonstrates:** GIS application development, React and TypeScript, spatial analysis, domain-oriented software design, testing, and interactive visualization.

---

## Additional Featured Work

### RotationLab

**React · TypeScript · FastAPI · Python · NBA Data**

[Live Application](https://rotation-lab.vercel.app/) ·
[Source Code](https://github.com/richardrhanly-us/RotationLab) ·
[Portfolio Case Study](https://richardhanly.dev/projects/rotationlab)

A full-stack basketball analytics application for exploring how different five-player combinations perform together and how lineup changes may affect a rotation.

The application includes lineup rankings, side-by-side comparison, player replacement analysis, four-player core analysis, efficiency metrics, filtering, and an analytics API.

---

### Library AI Assistant

**Python · FastAPI · Streamlit · OpenAI API · Chroma · Pytest**

[Live Application](https://library-ai-assistant.streamlit.app/) ·
[Source Code](https://github.com/richardrhanly-us/library-ai-assistant) ·
[Portfolio Case Study](https://richardhanly.dev/projects/library-ai)

A retrieval-augmented generation application that processes uploaded documents, stores vector embeddings, retrieves relevant passages, and generates answers grounded in the source material.

The project includes document ingestion, text extraction and chunking, semantic retrieval, source tracking, duplicate handling, document management, and automated service and API tests.

---

### FlowBoard

**React · TypeScript · Vite · Supabase · PostgreSQL · dnd-kit**

[Live Application](https://next-play-task-board-black.vercel.app/) ·
[Source Code](https://github.com/richardrhanly-us/next-play-task-board) ·
[Portfolio Case Study](https://richardhanly.dev/projects/flowboard)

A full-stack task-management application with authentication, drag-and-drop workflows, priorities, filtering, responsive design, keyboard shortcuts, and persistent Supabase storage.

---

### Aircraft Mission Systems Simulator

**C++17 · CMake · CTest · UDP · JSON**

[Source Code](https://github.com/richardrhanly-us/aircraft-mission-simulator) ·
[Portfolio Case Study](https://richardhanly.dev/projects/aircraft-simulator)

A distributed C++ simulation that models aircraft telemetry, mission-control commands, UDP communication, fault detection, acknowledgments, and message validation.

The system detects missing, duplicate, out-of-order, stale, recovered, and restarted telemetry streams and includes automated tests for protocol and fault-handling behavior.

---

### NBA Player Performance Prediction

**Python · pandas · scikit-learn · Streamlit · NBA Data**

[Live Application](https://edgeanalyticsnba.streamlit.app/) ·
[Source Code](https://github.com/richardrhanly-us/NBA_Player_Performance_Data_Pipeline) ·
[Portfolio Case Study](https://richardhanly.dev/projects/nba-prediction)

A basketball analytics application that processes player game logs, engineers statistical features, and uses regression models to estimate scoring performance and evaluate player betting lines.

---

### Homelab Network Infrastructure

**Linux · Docker · UniFi · Pi-hole · Unbound · Portainer · Uptime Kuma**

[Source Code](https://github.com/richardrhanly-us/homelab-network-infrastructure) ·
[Portfolio Case Study](https://richardhanly.dev/projects/homelab)

A working home infrastructure environment used for Linux administration, networking, DNS filtering, containerized services, monitoring, and infrastructure experimentation.

---

## Technical Skills

**Languages**

Python · C++ · Java · TypeScript · JavaScript · SQL · HTML · CSS · Bash · PowerShell

**Frontend**

React · TypeScript · Vite · Streamlit · HTML · CSS

**Backend**

FastAPI · REST APIs · Python services · Google Apps Script

**Data and Databases**

PostgreSQL · Supabase · Neon · pandas · scikit-learn · Chroma · vector search · data pipelines

**Cloud and Infrastructure**

AWS · EC2 · VPC · IAM · Systems Manager · CloudWatch · S3 · Terraform · Linux · nginx · systemd · Docker

**Testing and Engineering**

pytest · Vitest · CTest · GitHub Actions · input validation · API testing · fault handling · CI · infrastructure testing

**Systems and Networking**

UDP · TCP/IP · Linux administration · reverse proxies · service management · DNS · VLANs · network troubleshooting

---

## Professional Background

I work as a **Digital Services Specialist at New Braunfels Public Library**, where I support and troubleshoot public and staff technology, digital platforms, automated materials-handling equipment, library systems, and operational workflows.

That experience strongly influences how I approach software development. I tend to start with the workflow first: understand what people are trying to accomplish, identify where the friction is, and then build something that improves the process.

It has also given me practical experience working with systems that have to remain understandable and maintainable outside of a development environment.

---

## Education

**Bachelor of Applied Science in Software Development**  
Austin Community College  
Graduated August 2026

---

## Current Focus

I am currently continuing to build experience in:

- backend and API engineering
- AWS and Infrastructure as Code
- Linux systems administration
- cloud observability and reliability
- automated testing and CI
- data-driven application development
- full-stack React and TypeScript development
- systems programming and distributed-system concepts

---

## Portfolio

More detailed project case studies, architecture diagrams, walkthrough videos, and live applications are available at:

### [richardhanly.dev](https://richardhanly.dev)

---

## Contact

- **Portfolio:** [richardhanly.dev](https://richardhanly.dev)
- **LinkedIn:** [linkedin.com/in/richardhanly](https://www.linkedin.com/in/richardhanly/)
- **GitHub:** [github.com/richardrhanly-us](https://github.com/richardrhanly-us)
- **Email:** [richardrhanly@gmail.com](mailto:richardrhanly@gmail.com)
