# Sanjay Kanth Portfolio

Run `npm install`, create `.env` from `.env.example`, set `GOOGLE_APPS_SCRIPT_URL`, then run `npm start`. Open `http://localhost:3000`.

Both enquiry forms submit to the same `/api/enquiries` endpoint and the same Google Apps Script deployment, so both are written to the same `Enquiries` worksheet.

Google Apps Script: create/rename the worksheet tab to `Enquiries`, paste `google-apps-script.gs`, deploy as Web app, Execute as Me, access Anyone, and copy the `/exec` URL to `.env`.

## Latest visual update
- The second skills section now uses a layered flow-field/parallax treatment with animated paths and responsive motion.
- The lower enquiry section includes the supplied portfolio video at `assets/video/sanjay-kanth-portfolio-video.mp4`.
- The lower section includes the “OUR CLIENTS. OUR PROMISE.” commitment panel.
- Both enquiry forms still submit through `/api/enquiries` to the same Google Apps Script and the same `Portfolio` worksheet; there is no budget field.
