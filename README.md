VN Infra Reyality (Pro Local Edition) 🚀

VN Infra Reyality is a next-generation, serverless AI Recruitment Portal designed for privacy and speed. It runs entirely in your browser, using Local Intelligence to manage job applications, analyze resumes, and conduct AI interviews without needing a backend database.

✨ Key Features

🧠 AI-Powered Recruitment

Resume Match Checker: Upload a PDF resume and paste a JD to get an instant match score (0-100%), summary, and missing skills analysis.

Auto-JD Generator: Type a job title (e.g., "React Developer") and let AI write the full job description for you.

Smart Email Drafter: Generate professional emails for "Shortlisted" or "Rejected" candidates with one click.

Voice Interviewer: The AI acts as an interviewer, generating tough technical questions based on the candidate's specific weak points and speaking them out loud.

🔒 Privacy-First Architecture (Local Mode)

No Database Required: All data (candidates, scores, statuses) is stored securely in your browser's LocalStorage.

PDF Storage: Resume files are saved locally using IndexedDB, so you can download them anytime, even offline.

Your Data, Your Device: Data never leaves your computer (except the text sent to the AI API for processing).

🛠️ Pro Dashboard Tools

Kanban Board: Drag-and-drop style view to manage candidates (Pending -> Shortlisted -> Rejected).

Analytics Charts: Visual breakdown of application statuses.

Quick Actions: Shortlist or reject candidates directly from the list view.

Export Data: Download your entire candidate database as a CSV file for Excel.

🚀 How to Run

This is a Single-File Application. It requires no installation, no npm install, and no server.

Download: Save the index.html file to your computer.

Run: Double-click index.html to open it in any modern web browser (Chrome, Edge, Firefox).

Done: The app is ready to use!

For Hosting (Optional)

To share it with a team (note: data will not sync between devices), you can drag and drop the file onto:

Netlify Drop

GitHub Pages

Vercel

⚙️ Setting Up AI (Free)

To enable the AI features, you need an API Key. The app supports multiple providers:

Open the App.

Click the Settings (⚙️) icon in the top navigation bar.

Choose your provider:

Google Gemini (Recommended): Best free tier. Get Key Here.

Groq: Insanely fast, uses Llama 3. Get Key Here.

OpenAI: Requires a paid account/credits. Get Key Here.

Paste your key and click "Save & Test".

If the connection is successful, you are ready to go!

Note: If you don't have a key, you can click "Enable Demo Mode" in Settings to try the UI with simulated data.

📂 Project Structure

index.html: Contains ALL code (HTML, CSS, JavaScript).

vn.jpg (Optional): Place an image file named vn.jpg in the same folder to display your custom logo.

⚠️ Important Note on Data

Because this is the Local Edition:

Data Persistence: Your data lives in your browser's cache. Clearing your browser history/cache will delete your recruitment data.

No Sync: Data added on your laptop will not appear on your phone. Each device has its own separate database.

Backup: Use the "Export CSV" button regularly to back up your candidate list.

👨‍💻 Tech Stack

Frontend: HTML5, CSS3 (Custom styling), JavaScript (ES6+)

Libraries:

PDF.js (for parsing resumes)

Chart.js (for analytics)

Database: Browser LocalStorage & IndexedDB

AI Integration: Fetch API (REST)

Built for VN Infra Reyality Recruitment Team.
