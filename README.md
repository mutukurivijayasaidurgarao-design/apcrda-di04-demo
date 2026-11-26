**APCRDA DI-04 – Grievance Management Workflow Demo**

An interactive web-based prototype demonstrating a digital grievance management workflow for citizens and government departments. The demo allows citizens to register complaints, select departments, upload issue photographs, provide location details using GPS, and track complaint status. It demonstrates a Main Office verification process, department assignment, work progress updates, resolution submission with after-photos, and complaint closure.

**Technologies:** HTML5, CSS3, JavaScript, Browser LocalStorage, Geolocation API.

**Note:** This is a demonstration prototype, not a complete production application. Data is stored locally in the browser, and notifications are simulated. Backend integration, real authentication, OTP verification, and actual email/SMS notifications are not implemented.

Open working_model.html in a modern browser.
Demo flow: Public submit -> Main Office verify/correct/forward -> Department mark progress and upload after-photo -> Main Office verify/close -> appreciation message appears.
This is a front-end prototype. Data is stored in browser localStorage. Authentication/OTP, real server/database, secure file storage and actual email/SMS delivery are not implemented. Do not enter real personal data.
Production stack proposal: React, FastAPI, PostgreSQL, SQLAlchemy, Pydantic, JWT/OTP, Leaflet/OpenStreetMap, secure object storage, approved email/SMS gateway, Pytest.
No AI/ML is used.
