# HIKE SAFE — standalone web prototype

Prepared for elnurabdulla009-spec/hike-safe.

## Origin
The exported Expo web application is taken from https://github.com/waxyfx/hikesafepresentaition at commit b3816692ef103550da571500e520aaf507445b08, a team project. Original attribution is retained. This is not the original editable Expo source project.

## Changes
Standalone demo page; cream/forest palette; original exported app logic, worker and SQLite WASM preserved. Only asset base paths and five visual color values were changed in the app bundle. No backend or rescue delivery added.

## GitHub Pages
Upload the contents of this folder to a repository named `hike-safe`. In Settings → Pages select Deploy from a branch → main → /(root). The path is configured for /hike-safe/.

## Local preview
From this folder's parent run `python3 -m http.server 8080` and open http://localhost:8080/hike-safe/ . Do not open index.html with file://. The service worker prepares isolation for SQLite; one reload may occur.

## Demo
Create a hike in the app. Scenario controls enable after a hike is active. SOS, history, settings and finishing remain inside the original app. Reset starts a fresh temporary session. GPS is simulated and maps are schematic. No emergency service receives alerts. Browser QA is required before presenting.
