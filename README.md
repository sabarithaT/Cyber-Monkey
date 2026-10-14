# Cyber Monkey — Unified Cybersecurity Operations Platform

Cyber Monkey is an AI-powered cybersecurity operations platform designed to organize security investigations, evidence collection, tool execution, threat analysis, and reporting through a unified interface.

## Key Features

- **Overview Dashboard:** View investigation statistics, findings, and tool execution status.
- **SOC Monitoring:** Organize security logs and imported findings.
- **Penetration Testing:** Manage authorized security assessments and document findings.
- **OSINT Investigation:** Organize open-source intelligence results.
- **Malware Analysis:** Support static file profiling and structured analysis imports.
- **Digital Forensics:** Manage forensic evidence and investigation records.
- **Network Monitoring:** Organize network security findings.
- **Threat Intelligence:** Track indicators and related investigation information.
- **Reports:** Support investigation documentation and reporting.

## Technology Stack

- Frontend: React/Vite (verify against the project configuration)
- Backend: Python and FastAPI/Uvicorn
- Database: Embedded PostgreSQL through pgserver
- API documentation: OpenAPI/Swagger UI

## Running the Project

1. Install the dependencies specified by the project.
2. Configure the required environment variables.
3. Follow the project's setup instructions.
4. Start the application using the documented startup command.

```bash
python cybermonkey.py start
```

Frontend: `http://localhost:5173`

Backend API: `http://127.0.0.1:8000`

API documentation: `http://127.0.0.1:8000/api/docs`

## Security Notice

Use the platform only for systems you own or are explicitly authorized to assess. Do not commit credentials, secrets, private investigation data, or local environment files.

## Project Status

Local development version. Features and integrations should be validated before production deployment.
