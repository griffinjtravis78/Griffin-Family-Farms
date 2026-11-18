# Griffin Family Farms - Indoor Crop & UPC Tray Tracker

A lightweight, mobile-responsive Progressive Web App (PWA) built for **Griffin Family Farms** in Newton County, MO. Designed to track active microgreen and micro herb tray batches from sowing to harvest, integrate UPC tray labels for the Clabel CT221D printer, and manage daily grow room operations.

## Features
- **Dashboard & Queue:** Real-time tracking of active trays, germination uncovering tasks, and harvest schedules.
- **Sow New Batch & UPC Generator:** Automatically links pre-populated crop varieties (Pea Shoots, Sunflower, Radish, Broccoli, Basil, Cilantro, etc.) with calculated blackout and grow-out timelines.
- **Thermal Label Printing:** Formats scannable Code128 barcodes for direct printing to the Clabel CT221D thermal printer.
- **Supabase Backend:** Connected securely via PostgreSQL schema and Row Level Security.

## Deployment on GitHub Pages
1. Push this repository (`index.html` and `README.md`) to your GitHub repository.
2. Go to your repository **Settings** -> **Pages**.
3. Under **Build and deployment**, select **Branch: main** (or `master`) and `/ (root)`, then click **Save**.
4. Access your live web app instantly from any phone or tablet in the grow room!
