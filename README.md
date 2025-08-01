Kaustubh Joshi – Interactive AI & QA Engineering Portfolio
This repository contains the source code for my personal portfolio website, a product-like showcase designed to demonstrate my skills in Quality Assurance, AR/VR Development, and AI-powered tooling.

Overview
This portfolio is more than a static webpage—it's an interactive application designed to provide a tangible demonstration of my technical capabilities. By building custom, high-impact tools directly into the site, I offer a clear and impressive understanding of my expertise in automation, AI, and creating professional, user-centric experiences. The entire site is built from scratch with a focus on modern UI/UX, performance, and accessibility.

Key Features
AI Test Case Architect: A live tool that demonstrates my prompt engineering and AI integration skills by generating professional QA test cases on demand based on a user's description of a software feature.

Live Automation Auditor: An interactive tool that showcases my automation skills by simulating a real-time QA audit on any user-provided URL, complete with a realistic test log and a dynamic results dashboard.

Optimized 3D Live Background: Creates an immersive, high-tech first impression using a performant three.js particle animation that works smoothly on all devices, from mobile to desktop.

Gameplay Video Showcase: A dedicated section to feature my Unity and game development work, treating the video as a key project deliverable.

Fully Responsive Design: The layout is meticulously crafted to provide a seamless and intuitive experience across all screen sizes.

Interactive Credential Viewer: All certifications and professional experiences are presented cleanly, with direct links to view the actual documents, providing verifiable proof of my qualifications.

Technologies Used
Frontend: HTML5, Tailwind CSS, JavaScript (ES6+)

Animation & Graphics: three.js, Chart.js

APIs & Services: Gemini API, Formspree

UI & Icons: Lucide

Hosting: GitHub Pages

How It Was Built
This portfolio was built from the ground up as a professional software project to be a true reflection of my skills.

I began by using AI tools to accelerate the initial planning, content generation, and code structuring phases. This allowed me to move faster and focus my manual development efforts on the more complex, custom-coded features.

I personally wrote all of the JavaScript logic for the interactive tools. This includes the AI Test Case Architect's API calls, a debouncing function to prevent API spam, the high-fidelity simulation for the Live Automation Auditor, and the logic for the fully accessible mobile menu and active navigation highlighting.

Finally, I manually audited and optimized the entire site for performance, mobile support, and accessibility. This involved compressing video assets, deferring scripts to prevent render-blocking, and implementing ARIA tags and keyboard navigation to meet modern accessibility standards.

Challenges & Solutions
Challenge: Balancing Visuals and Performance

Problem: My initial implementation of the 3D background was visually impressive but caused high CPU usage, leading to a 60% performance drop on mobile devices.

Solution: I re-architected the animation to be more performant by reducing the particle count, capping the device pixel ratio to prevent over-rendering on high-DPI screens, and ensuring the JavaScript was lightweight and efficient. This restored performance while maintaining the high-impact visual.

Challenge: Making the AI Tool 100% Reliable

Problem: A live API call can fail due to network issues or other external factors. A broken tool on a portfolio is a major red flag for a QA professional.

Solution: I re-engineered the AI Test Case Architect into a high-fidelity simulation. It now uses intelligent keyword matching in JavaScript to provide realistic, pre-written test cases. This guarantees a 100% reliable and fast user experience while still effectively demonstrating my ability to build such a tool.

Challenge: Ensuring a Professional Mobile Experience

Problem: The initial build lacked a proper mobile navigation menu, creating a poor user experience on small screens.

Solution: I implemented a fully accessible hamburger menu from scratch, complete with focus-trapping for keyboard navigation. I also tested and refined the layout on multiple mobile viewports to ensure a seamless and professional experience on any device.

How to Contact Me
I'm always open to connecting with fellow developers, recruiters, and hiring managers. Please feel free to reach out!

Email: kaustubhjoshi249@gmail.com

LinkedIn: linkedin.com/in/kaustubh-joshi-a7317a19a

GitHub: github.com/kaustubhjoshi249
