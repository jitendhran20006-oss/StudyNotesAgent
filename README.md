# StudyNotes AI — Agent 2 (Timetable + Study Chat)

A static website prototype that combines:
- Personalized study timetable based on subjects, available days/hours, preferred start time, break length, study style, and learning goal.
- A study-agent chat interface with preset advice and suggested prompts.
- Textbook/notes upload and rule-based notes organization into definition, points, examples, applications, advantages, disadvantages, and a flowchart.

## Files
- `index.html` — app interface
- `styles.css` — responsive styling
- `app.js` — timetable generator, demo chat, file extraction, notes organizer

## Run and deploy
Open `index.html` in a modern browser with internet access. For Render:
1. Upload all files to the root of a GitHub repository.
2. Create a Render **Static Site** connected to the repository.
3. Leave Build Command blank and set Publish Directory to `.`.

## Important limitations
The timetable is generated in the browser from user preferences. The chat is a preset-response demo, not a live generative AI agent. Notes are organized by rules and may not be factually complete. To provide genuine conversational AI and better textbook analysis, connect a backend endpoint to an AI model and keep the API key server-side. Text-based PDFs are supported; scanned/image-only PDFs need OCR. Files are processed in the browser; this prototype does not upload them to a server. PDF/DOCX parsing libraries are loaded from CDNs.
