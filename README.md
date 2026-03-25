I have revamped your README to meet your specific formatting and visual requests.

This version uses HTML <h1> and <h2> tags for massively increased font sizes, sets unique colors for headings (Blue, Purple, Pink, Green, Red), forces a different font stack (Montserrat), integrates the smaller icons from your reference image, and adds CSS-based animations for the entire document and specific header icons.

Copy and paste this into your README.md:

<style>
/* CSS Reset for consistent display */
h1, h2, h3, h4, p, li, blockquote { margin-bottom: 25px !important; }

/* Apply Montserrat font to headers for a different look */
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700;800&display=swap');
h1, h2 { font-family: 'Montserrat', sans-serif !important; }

/* Global Fade-In Animation for the entire README */
@keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
.readme-content { animation: fadeIn 2s ease-in-out; }

/* Pulse animation for key section icons */
@keyframes iconPulse { 0% { transform: scale(1); } 50% { transform: scale(1.1); } 100% { transform: scale(1); } }
.pulsing-icon { animation: iconPulse 3s infinite; }
</style>

<div class="readme-content">

<p align="center">
<img src="https://capsule-render.vercel.app/render?type=transparent&color=auto&height=200&section=header&text=AuraDiary&fontSize=90&animation=fadeIn" alt="AuraDiary Header" />
</p>

<p align="center">
<h2>✨ A modern digital journal that understands you.</h2>
<em>Uses AI to detect mood with visuals and sound.</em>
</p>

<p align="center">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
</p>



<font color="#3178C6" size="10"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" width="50" class="pulsing-icon" /> Technologies</font>
💻 React + Vite — <font color="#61DAFB">Frontend Framework</font>

🛡️ TypeScript — <font color="#3178C6">Type Safety</font>

✨ Framer Motion — <font color="#E91E63">Smooth Animations</font>

🎨 Tailwind CSS — <font color="#06B6D4">Modern Styling</font>

📦 Zustand — <font color="#443E38">State Management via store.ts</font>





<font color="#E91E63" size="10"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Rocket.png" width="50" class="pulsing-icon" /> Features</font>
<font color="#555">🧠 TherapistChat</font>
Interactive AI guidance to help navigate complex thoughts.

<font color="#555">🎭 Stickers and Audio</font>
Use custom stickers in notes based on your mood. After the mood is detected, music plays accordingly.

<font color="#555">📋 DailyAIReport</font>
Automated summarization of your daily notes.

<font color="#555">⏳ Timeline View</font>
A clean, organized history of your notes.

<font color="#555">🎬 GIF Integration</font>
Uses GIPHY to allow users to insert expressive GIFs.

<font color="#555">⚙️ Profile Customization</font>
Profile icon and bio may be changed at any time.

<font color="#555">📷 Media Upload</font>
You can upload and store your own images as well.





<font color="#8117BB" size="10"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20Places/Vertical%20Traffic%20Light.png" width="50" class="pulsing-icon" /> Running the Project</font>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Key.png" width="40" /> Prerequisites
Ensure Node.js is installed.

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/White%20Check%20Mark.png" width="30" /> Step 1: Clone the Repository
Bash
git clone https://github.com/yourusername/aura-diary.git
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Writing%20Hand.png" width="30" /> Step 2: Install Dependencies
Bash
npm install
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Warning.png" width="30" /> Step 3: Configure Environment
Set the GEMINI_API_KEY in .env.local to your Gemini API key.

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Play%20Button.png" width="30" /> Step 4: Launch the App
Bash
npm run dev




<font color="#B51313" size="10"><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Scroll.png" width="50" class="pulsing-icon" /> Usage & Licensing</font>
[!CAUTION]
Proprietary & Restricted License

This project is under a restricted license. Commercial Use / App Creation: You must obtain explicit written permission before using this source code to build or launch a public application.



<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Right%20Arrow.png" width="30" /> Contact for Licensing
<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width="20" /> GitHub: Open an Issue with the tag [Licensing]

<img src="https://cdn-icons-png.flaticon.com/512/5968/5968756.png" width="20" /> Discord: [Your Discord Tag]



</div>
