# Jal Suraksha — FHTC Monitoring Dashboard Prototype

Responsive HTML/CSS/JavaScript dashboard for a student demonstration.

## Run
Open `index.html` in a modern browser. Chart.js and Google Fonts load from CDNs, so those enhancements need an internet connection.

## GitHub Pages
Upload `index.html`, `style.css`, `app.js`, and `README.md` to the root of a GitHub repository. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.

## Interactions
- Responsive sidebar navigation
- Simulated sensor refresh
- Chart.js trend and report charts
- Schematic map with clickable infrastructure markers
- Alert acknowledgement and resolution
- Add local demo complaints
- Export sample CSV
- Edit demonstration thresholds

## Important limitations
All readings, counts, locations, incident records, confidence values and performance metrics are fictional sample data. The map is schematic, not GPS-accurate. This frontend has no real sensor connection, backend, authentication, persistent database, trained AI model, or IMIS/Sujal Gaon API integration. The AI insight is an illustrative scenario, not a model prediction. Sensor readings do not establish potability; appropriate field/laboratory testing is still needed. Do not enter real household personal data.

## Suggested next steps
1. Add a Flask/FastAPI backend and PostgreSQL.
2. Replace demo values with authenticated sensor gateway data.
3. Add household/asset records, role-based access and audit logs.
4. Train and validate anomaly detection with labelled historical data.
5. Integrate government platforms only with authorized API access and documented data contracts.
