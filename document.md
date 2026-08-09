SecureIMEI — Stolen Phone Report & Verify Registry

A frontend web app that lets people report a stolen phone by its IMEI number and lets buyers verify a used phone's status before purchasing it — helping prevent stolen device resale.

🔗 Live Demo

View Live Site (update this link after enabling GitHub Pages)

📱 Features
Report Stolen — File a report with IMEI, brand, model, city, and date lost
Verify a Device — Check any IMEI instantly to see if it's been reported stolen
Live Stats — Real-time count of total reports, stolen devices, and cities covered
Recent Reports Table — Dynamically rendered list with masked IMEI for privacy
Form Validation — IMEI format checking (15–17 characters)
Persistent Storage — Data saved using browser localStorage, so it stays even after refresh
Responsive Design — Works on mobile, tablet, and desktop
Smooth Animations — Scroll reveals, scan effect on verification, toast notifications
🛠️ Built With
HTML5
CSS3 (Custom properties, Grid, Flexbox, animations)
Vanilla JavaScript (DOM manipulation, localStorage API, form validation)
Google Fonts — Space Grotesk, IBM Plex Sans, JetBrains Mono

No frameworks, no backend — pure client-side implementation.

🚀 How to Run Locally
Clone this repository
   git clone https://github.com/Atchaya6/secureimei-registry.git
Open index.html directly in any browser — no build step or server required.
💡 How It Works
Report — User fills a form with device details. Data is saved as a JSON object in localStorage.
Verify — User enters an IMEI. The app searches all stored reports for a match.
If a match is found → shows a red "Stolen" alert with the reported details.
If no match is found → shows a green "Clear" confirmation.
📌 Future Improvements
Connect to a real backend (Node.js + MongoDB) so reports are shared across all users, not just one browser
Add user authentication for report ownership
Add email/SMS notification when a stolen device is found
Map integration to show where devices were reported stolen
👩‍💻 Author

Atchaya G Electrical & Electronics Engineering Graduate | Embedded Systems • IoT • Software Development LinkedIn · GitHub

Content

PDF

PDF

PDF
