# Orbital Gateway Ventures - A NASA Space Apps Challenge Prototype
Welcome to the Orbital Gateway Ventures prototype, a user-facing web interface designed for the NASA International Space Apps Challenge. This project presents a multi-phase business concept for a commercial hub in Low Earth Orbit, showcasing services from space tourism to orbital debris mitigation.

[Live Demo Link Here] ← (Insert your live GitHub Pages link here once you deploy it)

## Project Overview
Orbital Gateway Ventures is a conceptual business with a mission to build a multi-purpose commercial hub in Low Earth Orbit. This prototype provides an interactive interface for potential clients—from individual adventurers to large-scale government and corporate agencies—to explore our phased service offerings:

Phase 1: Curated Space Tourism: An exclusive, high-end experience for private astronauts, establishing the brand and generating initial capital.

Phase 2: The Gateway Hub: The development and deployment of a proprietary, modular space station for commercial leasing, research, and logistics.

Phase 3: Orbital Services: Leveraging the Gateway's infrastructure to provide critical environmental services, including orbital debris monitoring and removal.

## NASA Data Integration
A core requirement of the Space Apps Challenge is the innovative use of NASA's open data. This prototype integrates several key NASA resources to create a dynamic and data-rich user experience:

1. NASA EPIC API (Earth Polychromatic Imaging Camera)
Implementation: The "Plan Your View from Orbit" section features a live, automated slideshow of the latest full-disk images of Earth.

Source: The data is fetched directly from the EPIC API, which provides imagery from the DSCOVR satellite positioned a million miles away. This gives potential space tourists an authentic preview of what they will see.

2. NASA Orbital Debris Program Office (ODPO) Models
Implementation: The "Orbital Services" tab includes a 3D, interactive visualization of Earth and the surrounding orbital debris field.

Source: While the visualization uses a conceptual simulation for performance and clarity, the statistics presented (number of tracked objects, risk of collision cascade) are based directly on the authoritative models and data published by NASA's ODPO. This grounds our proposed environmental services in real-world scientific data.

## Features
Interactive Service Tabs: A clean, tab-based navigation to explore the three distinct business phases.

Live Satellite Imagery: An automated slideshow powered by the NASA EPIC API.

3D Debris Visualization: An interactive three.js canvas simulating the orbital debris environment around Earth.

Dynamic UI Elements: A functional contact form that provides user feedback without reloading the page, and interactive modals for more detailed information.

Fully Responsive Design: A modern interface that is optimized for viewing on desktops, tablets, and mobile devices.

Self-Contained: The entire project runs from a single index.html file with no backend dependencies, making it highly portable and easy to deploy.

## How to Run Locally
Since this project is a self-contained HTML file, you can run it locally without any special tools.

Clone or download this repository.

Navigate to the project folder.

Open the index.html file in your favorite web browser (e.g., Chrome, Firefox, Safari).

## Technologies Used
HTML5

Tailwind CSS (via CDN)

JavaScript (ES6)

three.js (for 3D visualization, via CDN)
