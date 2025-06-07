🎶 The Weeknd Video Experience
A visually captivating, interactive webpage showcasing two iconic videos by The Weeknd—"The Remedy" and "Wordplay". Featuring a futuristic neon aesthetic, glowing effects, particle animations, and a custom cursor, this project immerses users in a sleek, responsive music-themed experience.

✨ Features
🎥 HTML5 Video Playback
Local .mp4 videos with native controls (The-Remedy.mp4, Wordplay.mp4).

🌌 Dynamic Visuals

Particle star background

Neon-glow, pulsating header

Hover-scale video containers with glowing shadows

🎵 Custom Cursor
Music note cursor trails the mouse.

🪐 Parallax Scrolling
Adds depth to the description section.

📱 Fully Responsive
Optimized for desktop, tablet, and mobile (breakpoints at 768px and 480px).

🔮 Futuristic Aesthetic
Orbitron font + neon color scheme (red, yellow, dark blue) inspired by The Weeknd.

📁 Project Structure
pgsql
Copy
Edit
BlindingLightsWebpage/
├── mp4/
│   ├── The-Remedy.mp4
│   └── Wordplay.mp4
├── index.html
├── README.md
🚀 Setup Guide
Clone the Repo

bash
Copy
Edit
git clone https://github.com/markjptolentino/BlindingLightsWebpage.git
cd BlindingLightsWebpage
Open in Visual Studio

File > Open > Project/Solution

Select index.html as Start Page

Set video files to Copy if newer

Run Locally

Press F5 to launch

Ensure videos play and animations respond

🌐 Deploy to GitHub Pages
Push Code

bash
Copy
Edit
git add .
git commit -m "Initial commit"
git push origin main
Enable GitHub Pages
Settings > Pages > Source: main branch > root (/)

View Live
Visit: https://your-username.github.io/BlindingLightsWebpage/

🛠️ Troubleshooting
Video not playing?

Check correct paths: mp4/The-Remedy.mp4

Ensure .mp4 is H.264 encoded

Use HandBrake if needed

File too large?
Use Git LFS:

bash
Copy
Edit
git lfs install
git lfs track "*.mp4"
git add .gitattributes mp4/*.mp4
git commit -m "Add MP4s via Git LFS"
git push origin main
GitHub auth issues?
Use a Personal Access Token

📚 Resources
Git LFS Docs

HandBrake Video Compression

GitHub Pages Guide

📄 License
MIT License – free to use, remix, and share.

🙏 Acknowledgments
Inspired by The Weeknd’s signature style, this project fuses music, motion, and modern web design into an unforgettable experience.
