🎵 SONICFLOW – Online Music Streaming & Download Platform

📥 Download Large File (250MB)
Due to GitHub’s file size limitations, the main project package has been uploaded to Google Drive.

👉 Download File: [ google drive link](https://drive.google.com/file/d/1SLpJ11CCKX5ICAGgLUTMz5248tz2Cpxk/view?usp=drive_link)

📄 Project Overview

This repository contains the complete SONICFLOW source code and project resources.
To access the full package, download the external file above.

📝 How to Use

Clone or download this repository

Download the large file from Google Drive

Place the downloaded file inside the project folder (if required)

Open home.html in your browser — this will take you to the SONICFLOW homepage

🎶 SONICFLOW – Stream. Discover. Download.

SONICFLOW is a fully interactive online music streaming platform designed for a smooth user experience.
It features real-time music playback, dynamic popups, personalized downloads, and a clean UI — all built using HTML, CSS, and JavaScript.

🚀 Features
🎧 Music Playback

Popup-style music player with album art & playback controls

Smooth animations + responsive design

Browse by: Trending, New Releases, Artists, Genres

🔐 User Authentication

Client-side Registration & Login (LocalStorage)

Session persistence

Personalized welcome UI

Secure Logout

📥 Song Download Management

Logged-in users can download songs instantly

Payment confirmation before each download

Prevents duplicate downloads

Each user gets a personal download list

Delete individual downloaded songs

💾 Client-Side Storage (LocalStorage)

Stored keys:

users — list of registered users

logedinuser — current session

downloadedSongs_$<username> — unique download list per user

🛠️ Tech Stack
Technology	Purpose
HTML5	Structure & Layout
CSS3	Styling, Animations, UI
JavaScript (ES6)	Core Logic
LocalStorage	Data Persistence
📂 Project Structure
SONICFLOW/
│
├── home.html
├── downloads.html
├── login.html
├── style.css
├── audio.js
├── script.js
├── audio_tracks/   ← songs & media files
└── images/         ← thumbnails & icons

🧩 How SONICFLOW Works
1️⃣ User Flow

New users register → data saved to LocalStorage

Logged-in users are redirected to home.html

Users stream and download songs

2️⃣ Download Flow

User clicks Download

Payment confirmation appears

If confirmed:

Song stored under downloadedSongs_$username

Shown in downloads.html

3️⃣ Delete Flow

Users can delete downloaded songs

Immediately removed from:

UI

LocalStorage

✨ Key Highlights

Clean, modern, animated UI

Complete music experience — streaming + downloads

No backend needed

Fully client-side database using LocalStorage

User-specific download history

Modular JavaScript for easy expansion

📌 Future Enhancements

(You can add these if you plan updates)

Playlist creation

Cloud-based user authentication (Django / Node.js)

Server-side song library

AI-based music recommendations

Dark mode / theme system

👨‍💻 Developer

SonicFlow Team
Full-Stack Developer | JavaScript Enthusiast
