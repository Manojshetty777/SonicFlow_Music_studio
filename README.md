🎵 SONICFLOW – Online Music Streaming & Download Platform

📥 Download Large File (250MB)
Due to GitHub’s file size limitations, the main project package has been uploaded to Google Drive.

👉 Download File: [ google drive link](https://drive.google.com/drive/folders/1qb_ZYeRbsjua8zt3Er4_Ahk5uUaeD1zk?usp=drive_link)

🎵 SONICFLOW – Online Music Streaming & Download Platform

📄 Project Overview
This repository contains the complete source code and project assets for SONICFLOW, an interactive music streaming and download platform.
Please download the external file to access the full project package.

📝 How to Use

Clone or download this repository

Download the external large file from the provided link

(If required) Place the downloaded file inside the project folder

Open home.html in your browser → It will load the SONICFLOW homepage

🎶 SONICFLOW – Music Streaming & Download Platform

SONICFLOW is a modern and responsive music streaming web application built using HTML, CSS, and JavaScript (ES6). It provides users with smooth music playback, popup-based song preview, personalized downloads, and secure client-side login — all without a backend.

🚀 Features
🎧 Music Playback

Popup audio player with album art, title, progress bar & controls

Smooth animations and responsive design

Browse by categories: Trending, New Releases, Popular Artists, Genres

🔐 User Authentication

Client-side registration & login using LocalStorage

Personalized session handling

Secure logout system

Welcomes each user by name

📥 Smart Download Management

Logged-in users can download songs instantly

Payment confirmation popup before download

Prevents duplicate downloads

Unique download list for every user

Delete songs from download history anytime

💾 LocalStorage-Based Data Handling

Stored values include:

users → Registered users array

logedinuser → Current session

downloadedSongs_$<username> → User-specific downloads

🛠️ Tech Stack
Technology	Purpose
HTML5	Structure & layout
CSS3	Styling, animations, responsive UI
JavaScript (ES6)	Logic, events, dynamic behavior
LocalStorage	Client-side persistence
📂 Project Structure
SONICFLOW/
│
├── home.html
├── downloads.html
├── login.html
├── style.css
├── audio.js
├── script.js         (authentication logic)
├── audio_tracks/     (songs & assets)
└── images/           (thumbnails & icons)

🧩 How It Works
1. User Flow

New users register → stored in LocalStorage

Returning users log in → session restored

Redirected to home.html

Can listen to or download songs

2. Download Flow

User taps Download

Payment confirmation popup appears

If confirmed → saved to downloadedSongs_$<username>

Visible inside downloads.html

3. Delete Flow

Delete any downloaded track

Removed instantly from:
✔ UI
✔ LocalStorage

LOGIN PAGE 
  
<img width="1910" height="927" alt="login page" src="https://github.com/user-attachments/assets/4c3d9972-5b11-4d93-8859-569c26a14cb2" />


HOME PAGE
<img width="1867" height="917" alt="home page" src="https://github.com/user-attachments/assets/44006a8a-c040-4dc2-9f7e-98413c1e14d6" />


POPUP SONG PLAYER
<img width="1875" height="917" alt="Song player page" src="https://github.com/user-attachments/assets/f5f1015d-0e66-46a4-bd6f-d70663a9feee" />









✨ Key Highlights

Attractive UI with animated popups

Completely backend-free (runs on any browser)

Modular JavaScript structure

Personalized download list for each user

Smooth user flow and responsive layout

📌 Future Enhancements

Playlists & favorites

Server-side authentication (Node.js / Django)

Cloud/DB storage for songs & users

Theme switcher (light/dark mode)

AI-based song recommendations

👨‍💻 Developer

SONICFLOW Development Team
Front-End & JavaScript Developer
