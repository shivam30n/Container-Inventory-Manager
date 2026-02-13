# Container-Inventory-Manager
A high-fidelity, browser-based inventory management dashboard designed for terminal operations. This application manages container stock for multiple shipping lines (Wan Hai & Turkon) with specific equipment nomenclature standards and an industrial-grade user interface.

⚡ Key Features
Multi-Registry Support: Separate dashboards for Wan Hai Lines and Turkon Line.

Dynamic Validation: Enforces specific equipment codes per line:

Wan Hai: 20STD / 40H/C (as per daily report receive from Yard)

Turkon: 20DV / 40HC (as per daily report receive from Yard)

Inventory Lifecycle: Track units from "Available Stock" to "Allotted" with detailed booking, vessel, and party information.

Real-Time KPIs: Live counters for 20' and 40' stock levels.

Industrial UI: High-contrast, dark-mode aesthetic with "JetBrains Mono" typography and responsive design.

Bulk Import: Add massive lists of containers via a text-area batch importer.

🚀 How to Run
This is a Single File Application. No server, Node.js, or database installation is required.

Download the CIM.html file.

Double-click to open it in any modern web browser (Chrome, Edge, Firefox, Safari).

The app is ready to use immediately.

📖 How to Use
Select Registry: Choose between Wan Hai or Turkon on the landing page.

Import Stock: Click "Import Stock" and paste your list. Format: UNIT_NUMBER TYPE (e.g., WHLU1234567 20STD).

Search & Filter: Use the top bar to filter by size or search for specific Unit IDs.

Allot Units: Click "Allot" on any empty unit to assign it to a Booking, Party, and Vessel.

Edit/Reset: Click the edit icon on allotted units to modify details or "Unallot" them to return them to stock.

⚠️ Disclaimer & Data Persistence
Please read carefully before use:

Local Storage Dependency:
This application is built for demonstration and prototyping purposes. It runs entirely in your web browser and stores data using the browser's Local Storage (Cache).

No Cloud Backup: Data is not saved to a server or cloud database.

Data Volatility: If you clear your browser's cache, history, or cookies, all inventory records will be permanently erased.

Device Specific: Data entered on one computer will not appear on another.

This tool is excellent for daily temporary tracking, UI/UX demos, or training, but it should not be used as the primary database for critical mission-sensitive operations without integrating a backend service.

