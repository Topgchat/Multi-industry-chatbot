A multi-industry, human-like chatbot built with FastAPI. Ready-to-deploy on Render, with sample tenants for multiple online industries and a demo frontend to showcase and test the chatbot.

⸻

Features
	•	FastAPI backend with multi-tenant support
	•	Sample tenants for industries:
	•	E-commerce Fashion
	•	Real Estate Agency
	•	Health Clinic
	•	Restaurant / Café
	•	Education & Courses
	•	Human-like responses tailored to each tenant
	•	Demo frontend (web/index.html) and embeddable widget (web/widget.html)
	•	Ready-to-deploy configuration for Render
 ├─ app/
│   ├─ clients.json        # Tenant definitions
│   └─ main.py             # FastAPI backend
├─ web/
│   ├─ index.html          # Demo frontend
│   └─ widget.html         # Widget for embedding
├─ requirements.txt        # Python dependencies
├─ Procfile                # For Render deployment
├─ render.yaml             # Render configuration
└─ README.md               # This file
