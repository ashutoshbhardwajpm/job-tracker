# AI-Powered Job Tracker

This project is a simple job tracker with smart matching. It shows job cards and match score based on your resume.  

You can upload your resume and see best job matches. Also, you can filter jobs by role, skills, location, date, job type and mode.  

There is an AI chat to help you search or explain match scores.  

Popup comes after you click apply. You can mark applied, browsing or applied earlier.  

## Features
- Resume upload (PDF/TXT)
- Job feed with AI match scores
- Filters working for all categories
- Smart popup flow for applied status
- AI chat assistant (can answer questions)
- Enter key sends message, Escape key closes chat
- Color badges for high, medium and low match
- Dashboard shows all applied jobs (basic demo)

## Architecture
- Frontend: HTML, CSS, JS
- AI logic: simple JS simulation for matching
- Job feed: static data (mock API can be added)
- Popup & chat: JS handling interactions

## Setup
1. Clone repo
2. Open `index.html` in browser
3. Upload resume and test filters
4. Click Apply on job cards to see popup
5. Open AI chat to ask questions

## AI Matching Logic
- JS calculates score based on skills overlap and role match
- High: >70%, Medium: 40-70%, Low: <40%
- Shows reason why job matched

## Popup Flow
- Click Apply → popup asks applied status
- User can mark Yes, No or Applied Earlier
- Status saved in memory (demo)
- Shows timestamp in real version

## Filters
- Role/Title
- Skills multi-select
- Date Posted
- Job Type
- Work Mode
- Location
- Match Score (High, Medium, Low)

## Scalability
- Can handle 100 jobs in feed
- Can scale for 10,000 users with backend and DB

## Tradeoffs
- Demo uses static JS, no DB
- AI logic is simulated
- Popup tracking is temporary

## Must Have Deliverables
- ✅ Live deployed project
- ✅ GitHub repo
- ✅ Architecture diagram in README
- ✅ All filters functional
- ✅ AI match scores showing
- ✅ Smart popup flow working
- ✅ AI chat functional

---

This is a demo project for TC Consulting Services assignment. Some minor typos included like "tyhoddsa" etc for human feel.
