AI il Thaalikett 🎯
Basic Details
Team Name: Bolt
Team Members
Team Lead: Sreedhu R Nair

Member 2: K P Kiran Kumar

Project Description
AI il Thaalikett is a proudly useless web app built for TinkerHub’s Useless Projects hackathon that simulates a South Indian wedding right inside your browser using HTML5 Canvas and vanilla JavaScript. You upload photos of the couple, pick a wedding vibe, and hit a button to watch the groom's arm magically stretch across the screen to tie the Thaali with full audio and confetti effects.

The Problem (that doesn't exist)
Real weddings cost a fortune, take months of planning, require dressing up, and force you to deal with loud relatives. Plus, your distant relatives always manage to blink or miss the exact second of the knot-tying on blurry video streams, leaving society in dire need of an automated, highly inaccurate digital wedding simulator.

The Solution (that nobody asked for)
We completely threw out human effort, emotional presence, and common sense by letting you map your faces onto pixel-art avatars and tie the knot an infinite number of times while blasting a soundboard packed with looping audio and digital confetti.

Technical Details
Technologies/Components Used
For Software:

HTML5, CSS3, JavaScript (ES6+)

HTML5 Canvas API

Web Audio API, FileReader API

VS Code, Git

For Hardware:

N/A (Pure software nonsense)

Implementation
For Software:

Installation
Bash
git clone https://github.com/your-username/ai-il-thaalikett.git
cd ai-il-thaalikett
Run
Open index.html in any web browser or use VS Code's Live Server extension.

Project Documentation
For Software:

Screenshots (Add at least 3)
("D:\AI Kalyanam\Screenshot 2026-09-03 162043.png","D:\AI Kalyanam\Screenshot 2026-09-03 162132.png","D:\AI Kalyanam\Screenshot 2026-09-03 162204.png","D:\AI Kalyanam\Screenshot 2026-09-03 162221.png","D:\AI Kalyanam\Screenshot 2026-09-03 162249.png","D:\AI Kalyanam\Screenshot 2026-09-03 162308.png")
Diagrams

How it all works under the hood: user inputs change the state, canvas redraws frame-by-frame, and the soundboard handles audio.
```
[ User Uploads Photos & Selects Tradition ]
                     │
                     ▼
         [ JavaScript State Update ]
                     │
                     ▼
       [ HTML5 Canvas Render Loop ]
       ├── Background Stage Loaded
       ├── Groom & Bride Avatars Drawn
       └── Animation Triggered (Arm Stretch & Confetti)
                     │
                     ▼
         [ Web Audio Soundboard ]
         (BGM & Effects Played/Looped)

```
Team Contributions
Sreedhu R Nair: Built core JavaScript state management, hacked together the canvas rendering loop, and figured out the arm-stretching and confetti math.

K P Kiran Kumar: Designed the sleek dark-mode UI, wired up the Web Audio soundboard with volume sliders and looping toggles, and organized project assets.

Made with ❤️ at TinkerHub Useless Projects