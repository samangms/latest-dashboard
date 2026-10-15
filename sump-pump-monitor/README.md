# Sump Pump Monitor

A single-page web app for monitoring 25 estate sump pumps. It follows a simple workflow:

- **Pump board:** status of all 25 pumps (running, fault, high water, offline), water level against the 80% alarm line, and flags for pumps whose monthly check is overdue.
- **Fault queue:** each fault moves through Detected, Alert approved, Contractor notified and Closed, with a 15-minute target for approving the alert.
- **Weekly summary:** the week's fault counts, alert timings, overdue checks and a Monday reminder text you can copy.

## Mock data

All pumps, locations and faults are made-up sample data. Nothing is connected to real pumps, and approvals do not send any email, WhatsApp or contractor message. Changes are saved in your own browser (localStorage) only, so they are not shared between people or devices. To reset the sample data, clear this site's data in your browser.

## Open it

Open `index.html` in a browser, or serve this folder with GitHub Pages.
