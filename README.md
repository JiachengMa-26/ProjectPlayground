<div align="center">

<!-- Header Image -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=00f2ea&height=280&section=header&text=Creative%20Developer%20%26%20Security%20Researcher&fontSize=40&fontAlign=50&fontAlignY=35&desc=Visualizing%20Data%20%7C%20Simulating%20Threats%20%7C%20Building%20Tools&descSize=20&descAlign=50&descAlignY=55&animation=twinkling" alt="Header Background" width="100%"/>

<br />

<!-- Intro Text -->

<p align="center">
I explore the intersection of <b>Cybersecurity</b>, <b>Interactive Storytelling</b>, and <b>Frontend Architecture</b>.




My goal is to demystify how the web tracks us and how data can be visualized in real-time.
</p>

<!-- Personal Info Highlight -->

<h3 align="center">Hi, I am Jiacheng Ma (JiachengMa 26).</h3>
<p align="center">
📫 Contact: <a href="mailto:JM6080@columbia.edu">JM6080@columbia.edu</a>
</p>

<!-- Navigation Badges -->

<p align="center">
<a href="#-showcase-experiments">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Featured_Projects-00f2ea%3Fstyle%3Dfor-the-badge%26logo%3Dgithub%26logoColor%3Dblack" alt="Featured Projects">
</a>
<a href="#-technical-philosophy">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Tech_Philosophy-ff0055%3Fstyle%3Dfor-the-badge%26logo%3Datom%26logoColor%3Dwhite" alt="Philosophy">
</a>
</p>
</div>

<br />

<!-- 🏆 PRIORITY SHOWCASE SECTION -->

<h2 align="center">🏆 Showcase Experiments</h2>

<p align="center">
<i>These projects are not just tools; they are educational experiments designed to reveal the hidden mechanics of the web.</i>
</p>

<table width="100%">
<tr>
<td width="50%" valign="top">
<h3 align="center">🌐 More than IP? 



<sub>(Highly Recommended)</sub></h3>
<p align="center">
<b><i>Real-time visualization of digital footprints mapped to physical context.</i></b>
</p>
<hr>
<p>
<b>🕵️‍♂️ Why I created this:</b>




We often treat IP addresses as abstract numbers. I wanted to break that illusion. "More than IP" exists to show that a simple network connection reveals your <b>physical reality</b>—your local weather, your time of day, and your ISP—turning abstract data into a tangible profile.
</p>
<p>
<b>⚙️ How it works (The Mechanics):</b>




This tool runs completely on the client side using the <code>ipwho.is</code> API.







It does not need a backend because all calls are <b>browser-initiated requests</b>. When you open the page, your browser calls the API directly. Since the request originates from <i>your</i> machine, the API automatically detects the source IP and returns geolocation JSON. I then chain this coordinate data into a weather API, which builds a snapshot of the user environment without storing any data on my own server.
</p>
<p align="center">
<a href="#">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Live_Demo-00ADD8%3Fstyle%3Dfor-the-badge%26logo%3Dgoogle-earth%26logoColor%3Dwhite" alt="Live Demo" />
</a>
</p>
</td>
<td width="50%" valign="top">
<h3 align="center">🎣 FakeFishing 



<sub>(Recommended)</sub></h3>
<p align="center">
<b><i>A scareware simulation that demonstrates fear-driven manipulation.</i></b>
</p>
<hr>
<p>
<b>🕵️‍♂️ Why I created this:</b>




Cybersecurity training is often dry. I built FakeFishing to make the experience of a <b>social engineering attack</b> more visceral. It shows how attackers bypass rational thinking by triggering fear—displaying the user location and ISP on a "system critical" alert screen to force a click.
</p>
<p>
<b>⚙️ How it works (The Mechanics):</b>




The psychological effect comes from <b>dynamic content injection</b> via <code>ipwho.is</code>.







Instead of a static fake alert, this page fetches visitor metadata in real-time such as City, ISP, and ASN. It injects these accurate details into a generic virus warning template, creating a verification loop in the user's mind: <i>"It shows my ISP so it must be real."</i> This illustrates how public API data can support psychological pressure without any real compromise of the system.
</p>
<p align="center">
<a href="#">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Live_Simulation-FF2A2A%3Fstyle%3Dfor-the-badge%26logo%3Dhack-the-box%26logoColor%3Dwhite" alt="Live Simulation" />
</a>
</p>
</td>
</tr>
</table>

<br />

<!-- 📂 OTHER PROJECTS -->

<h2 align="center">📂 Other Investigations and Tools</h2>

Project

Description

Core Concept

DragyTech: Entropy's Arc

An interactive sci-fi narrative case study.

Storytelling with Code: Using React state management to control narrative flow and immersion.

Simple Real Estate Analyzer

A minimalist financial tool for ROI calculation.

Financial Minimalism: Focusing on clear data processing and a clean interface without distraction.

Personal Cyber Portfolio

A 3D-enhanced personal website.

Creative Frontend: Utilizing Three.js for immersive web experiences.

<br />

<!-- 🛠 TECH STACK -->

<h2 align="center">🛠 Technology and Tools</h2>

<div align="center">
<!-- Languages -->
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Tailwind_CSS-38B2AC%3Fstyle%3Dfor-the-badge%26logo%3Dtailwind-css%26logoColor%3Dwhite" alt="Tailwind CSS" />

<br />

<!-- APIs & Tools -->

<img src="https://www.google.com/search?q=https://img.shields.io/badge/Open_Meteo_API-orange%3Fstyle%3Dfor-the-badge" alt="Open Meteo API" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/IPwho.is_API-blue%3Fstyle%3Dfor-the-badge" alt="IPwho.is API" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
</div>

<br />

<!-- 📊 STATS -->

<h2 align="center">📊 Activity Graph</h2>

<div align="center">
<a href="https://github.com/JiachengMa-26">
<img src="https://github-readme-stats.vercel.app/api?username=JiachengMa-26&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=00f2ea&icon_color=ff0055" height="180" alt="stats graph" />
</a>
<a href="https://github.com/JiachengMa-26">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JiachengMa-26&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=00f2ea" height="180" alt="languages graph" />
</a>
</div>

<br />

<div align="center">
<img src="https://raw.githubusercontent.com/gist/c0260216654e80b2a818c57508499934/raw/f656208a38520443cf847596066928e18471c993/github_footer_separator.svg" alt="separator" />
</div>
