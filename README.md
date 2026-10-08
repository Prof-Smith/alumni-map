# Saint Leo Alumni Impact Map prototype

Open `index.html` in a browser. Internet access is required for the map tiles, Leaflet library, and web fonts.

## Consent workflow represented
- Alumni can opt in directly.
- An administrator can populate a record after written email authorization is received.
- The authorization path records authorizing email, date, record ID, permitted fields, and evidence note.
- Every submission remains pending until reviewed; nothing publishes automatically.
- Public profiles use city-level coordinates and omit personal contact details.

## Production recommendation
Use Microsoft Forms for intake, SharePoint Lists for the profile and consent ledger, Power Automate for verification/approval, and a separately hosted front end for the map. Store an immutable reference to the authorization email rather than copying unnecessary email content into the public dataset.

All names and records in this prototype are fictional demonstration data.

Deployment refresh.
