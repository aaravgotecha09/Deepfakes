# Deepfake Network Lab

Interactive model for the Computer Networks project "Future Security Networks: Deepfakes, Network Vulnerabilities, and Defense".
By Ashima Bhattacharjee (I010) and Aarav Gotecha (I019), NMIMS MPSTME, Mumbai.

Static site: one `index.html`, no build step, no dependencies, no external requests.

## Deploy on Vercel
Option A (no tools): unzip, go to vercel.com/new, drag the unzipped folder in, Deploy.
Option B (CLI): `npm i -g vercel`, then run `vercel --prod` inside this folder.
Framework preset: Other. Build command: none. Output directory: (leave blank / root).

## Run locally
Open index.html in a browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.
The Provenance tab uses Web Crypto, which needs https (Vercel) or localhost.

## Notes
Simplified simulations for teaching. Arup figures from CNN reporting; rupee values use an editable approximate rate. The Mumbai scenario is hypothetical.
