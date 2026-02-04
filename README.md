🚀 Local Route Planner (Singapore Edition)

A lightweight, free-to-use Bulk Route Optimizer designed for delivery drivers, service workers, and logistics planning. Built specifically with Singapore's geography in mind.

✨ Features
- Bulk Address Import: Paste dozens of addresses at once.
- Smart Optimization: Uses the Nearest Neighbor algorithm to solve the Traveling Salesperson Problem (TSP).
- Real Road Routing: Powered by OSRM to provide actual driving paths, not just straight lines.
- Error Tracking: A permanent "Needs Attention" box catches addresses that couldn't be geocoded.
- Round Trip Logic: Automatically calculates a route that returns to your starting point.

🛠️ Built With
- Leaflet.js: For the interactive map interface.
- OpenStreetMap: For map tiles and data.
- Nominatim API: For free address-to-coordinate conversion (Geocoding).
- OSRM: For high-speed routing and road geometry.

🚦 How to Use
- Paste Addresses: Enter one address or postal code per line into the text area.
- Add List: Click "Add List." The app will process each address one by one (including a 1.1s delay to comply with Nominatim's fair use policy).
- Review Errors: Check the red "Not Found" box for any typos or invalid addresses.
- Optimize: Click "Optimize Route" to generate the shortest loop starting from your first location.
- Export: Click "Copy List" to grab the optimized sequence for WhatsApp or Excel.

⚠️ Free Usage Policies
- This project uses public, community-funded servers. To ensure continued access:
- Rate Limiting: The code includes a mandatory delay between geocoding requests to respect the 1-request-per-second limit
- Usage: Intended for personal or small-scale use. For heavy commercial loads, consider hosting your own OSRM instance.

👨‍💻 Local Development
Simply clone the repository and open index.html using a local server (like VS Code Live Server). No API keys or complicated installations required.
