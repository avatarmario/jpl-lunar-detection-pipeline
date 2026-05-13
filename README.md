# JPL Lunar Detection Pipeline

## Project Overview

The JPL Lunar Detection Pipeline is a simulated open-source computer vision toolset designed to identify and map lunar surface features. The system focuses on detecting craters, boulders, and other geological structures that may be useful for lunar navigation, mission planning, and scientific research.

This project is being completed for a Software Engineering Tools class. The main goal is not to build a fully working production system, but to simulate the software engineering process using tools such as GitHub, Docker, Jira, TestRail, and LaTeX documentation.

## Jira Site

Jira project link:

**[Insert Jira Link Here]**

This link will be updated after the Jira project is created.

## Project Goals

The main goals of this project are:

- Simulate a lunar image detection pipeline.
- Organize a software project using GitHub.
- Use Docker Compose to describe expected services.
- Use Jira to manage project tasks and bugs.
- Use TestRail to document test cases and test runs.
- Use LaTeX to create formal project documentation.
- Create mock data for crater, boulder, and geological structure detections.

## Why This Software Matters

Lunar surface detection tools can help researchers and mission planners understand the Moon’s terrain. Detecting craters, boulders, and geological structures is important because these features can affect rover navigation, landing site selection, and scientific analysis.

In a real mission, this type of software could help identify unsafe terrain, locate scientifically interesting regions, and support future lunar exploration. For this class project, the system uses mock data to represent how such a tool might work.

## Formal Objective Breakdown

The project is divided into four snapshots.

### Snapshot 1: Project Start

The goal of Snapshot 1 is to create the foundation of the project.

Planned work:

- Create the GitHub repository.
- Set up the project folder structure.
- Create the initial README file.
- Create the initial Software Design Document.
- Create the initial Software Requirements Specification.
- Create the first snapshot objective document.
- Define the basic system architecture.
- Plan the first Jira sprint.
- Create initial mock detection data.

### Snapshot 2: Checkpoint 1

The goal of Snapshot 2 is to add the first major feature and begin testing documentation.

Planned work:

- Add simulated boulder detection.
- Update the SDD and SRS documents.
- Add new Jira tasks and bugs.
- Create the first TestRail test run document.
- Update the user manual.
- Update the design specification.
- Update the workflow diagram.

### Snapshot 3: Checkpoint 2

The goal of Snapshot 3 is to add another feature and expand the project documentation.

Planned work:

- Add crater size filtering.
- Add detection history mock data.
- Update the SDD and SRS documents.
- Add new Jira tasks and bugs.
- Create the second TestRail test run document.
- Update the user manual.
- Update the design specification.
- Update the workflow diagram.

### Snapshot 4: Final Submission

The goal of Snapshot 4 is to finalize the project and document future work.

Planned work:

- Add final documentation updates.
- Complete the final TestRail report.
- Add project reflection and future work.
- Update the README.
- Update the SDD and SRS documents.
- Update the design specification.
- Finalize the workflow diagram.
- Submit the GitHub repository.

## Expected System Features

The simulated system is expected to include:

- Lunar image upload.
- Mock image processing.
- Crater detection results.
- Boulder detection results.
- Geological structure detection results.
- Detection confidence scores.
- Detection history.
- Basic dashboard pages.
- Mock database records.
- Docker Compose service planning.

## Technology Stack

| Area | Tool or Technology | Purpose |
|---|---|---|
| Version Control | GitHub | Stores project files and documentation |
| Documentation | LaTeX | Used for formal documents |
| Project Management | Jira | Used for sprint tasks and bug tracking |
| Testing | TestRail | Used for test case and test run documentation |
| Containerization | Docker Compose | Describes the expected software services |
| Frontend | React.js | Simulated user dashboard |
| Backend | Node.js / Express | Simulated API service |
| Detection Service | Python | Simulated computer vision pipeline |
| Database | PostgreSQL | Stores mock image and detection data |

## Project Folder Structure

```text
jpl-lunar-detection-pipeline/
│
├── README.md
├── docker-compose.yml
│
├── docs/
│   ├── SDD.tex
│   ├── SRS.tex
│   ├── DesignSpec.tex
│   ├── UserManual.tex
│   └── SnapshotObjectives/
│       ├── Snapshot1_Start.tex
│       ├── Snapshot2_Checkpoint1.tex
│       ├── Snapshot3_Checkpoint2.tex
│       └── Snapshot4_Final.tex
│
├── diagrams/
│   └── workflow-diagram.png
│
├── jira/
│   └── sprint1_tasks.md
│
├── mock-data/
│   ├── lunar_images_metadata.csv
│   ├── crater_detections.json
│   └── boulder_detections.json
│
└── testrail/
    ├── Snapshot2_TestRail_Report.pdf
    ├── Snapshot3_TestRail_Report.pdf
    └── Snapshot4_TestRail_Report.pdf