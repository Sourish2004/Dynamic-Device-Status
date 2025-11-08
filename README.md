# Dynamic Device Status Web App

### Setup Instructions
1. Create PostgreSQL database: `device_db`
2. Run schema.sql to create tables.
3. Insert sample data.
4. Run Flask backend: `python app.py`
5. Open `index.html` in browser.

### API Endpoints
- `/companies`: Get list of companies.
- `/devices/<company_id>`: Get devices and their statuses.

### Features
- Real-time device monitoring.
- Auto-refresh every 10 seconds.
- Responsive, color-coded tiles.

### Assumptions
- Device is online if a reading exists within last 2 minutes.
