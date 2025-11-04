
# AI_PPT-main

Project: AI PPT Converter — a small workspace containing a backend, frontend, and utilities to convert images into PowerPoint slides.

Overview
- Main folder: `AI_PPT-main` (this repository root)
- Key subfolders:
	- `backend/` — Flask (or FastAPI) backend: app and services for PPTX manipulation
	- `frontend/` — React + Vite frontend
	- `AI_Image_PPT_Converter/` — a small demo app and utilities

How to run (quick)
1. Backend
	 - Open a terminal in `backend/`.
	 - Create a virtualenv and install requirements:
		 ```powershell
		 python -m venv .venv; .\.venv\Scripts\Activate; pip install -r requirements.txt
		 ```
	 - Run the app (example):
		 ```powershell
		 python app.py
		 ```

2. Frontend
	 - Open a terminal in `frontend/`.
	 - Install dependencies and run dev server (requires Node.js + npm/yarn):
		 ```powershell
		 npm install
		 npm run dev
		 ```

Notes
- This README was added and populated automatically during the GitHub upload process.
- After I create/push the repo I recommend you rotate (revoke + recreate) the PAT you shared, since tokens are sensitive.

License
- Add a license file if you want this repo public. I can add a `LICENSE` file on request.

Contact / Next steps
- If you'd like any of the following, tell me and I'll add them before or after pushing:
	- Make repo public/private change
	- Add a `LICENSE` (MIT, Apache-2.0, etc.)
	- Add GitHub Actions CI for tests or linting

