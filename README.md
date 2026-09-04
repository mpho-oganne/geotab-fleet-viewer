# Geotab Fleet Viewer

Single-page viewer for the MyGeotab JSON-RPC API (https://developers.geotab.com/myGeotab/introduction/).

Open `index.html` (or the GitHub Pages site), sign in with a MyGeotab database, username and password, and browse devices, users, zones, trips, exceptions, faults and more. Calls go directly from the browser to `https://<server>/apiv1`; only the session token is kept, in `sessionStorage`.

No database? Register a free test one at https://my.geotab.com/registration.html
