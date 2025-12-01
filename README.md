<div align="center">

<h1>Cybersecurity, Storytelling and Frontend Experiments</h1>

<br />

<p align="center">
This profile collects small browser based experiments that connect <b>cybersecurity</b>, <b>interactive storytelling</b> and <b>frontend architecture</b>.  
The focus is on showing how the web observes visitors and how data can be visualized in real time.
</p>

<p align="center">
<a href="#showcase-experiments">
  <img src="https://img.shields.io/badge/Featured%20Projects-00f2ea?style=for-the-badge&logo=github&logoColor=black" alt="Featured Projects" />
</a>
<a href="#technical-philosophy">
  <img src="https://img.shields.io/badge/Tech%20Philosophy-ff0055?style=for-the-badge&logo=atom&logoColor=white" alt="Philosophy" />
</a>
</p>
</div>

<br />

<h2 id="showcase-experiments" align="center">🏆 Showcase Experiments</h2>

<p align="center">
<i>Each project is designed as an experiment that makes hidden web mechanics visible.</i>
</p>

<table width="100%">
<tr>
<td width="50%" valign="top">
<h3 align="center">🌐 More than IP?</h3>
<p align="center">
<b><i>Turns a single request into a picture of the visitor environment.</i></b>
</p>
<hr>
<p>
<b>Purpose</b>  
This project shows that an IP address is not just a number. By combining geolocation data with weather and time information, one ordinary page load can be turned into a simple physical profile of the visitor.
</p>
<p>
<b>How it works</b>  
The page runs only in the browser and calls the <code>ipwho.is</code> interface.  
The interface returns address, city, provider and coordinates for the current visitor. The coordinates are then passed to a weather interface to pull conditions for that place. No data is stored on a personal server and all requests are made directly from the visitor browser.
</p>
<p align="center">
<a href="https://jiachengma-26.github.io/ProjectPlayground/" target="_blank">
  <img src="https://img.shields.io/badge/Live%20Demo-00ADD8?style=for-the-badge&logo=google-earth&logoColor=white" alt="Live Demo" />
</a>
</p>
</td>

<td width="50%" valign="top">
<h3 align="center">🎣 FakeFishing</h3>
<p align="center">
<b><i>Shows how accurate but public data can be used in scare style pages.</i></b>
</p>
<hr>
<p>
<b>Purpose</b>  
This project is a training aid for social engineering awareness.  
It demonstrates how a visitor may trust a fake alert page simply because it shows real looking network details such as provider name or city.
</p>
<p>
<b>How it works</b>  
The page calls <code>ipwho.is</code> for each visitor and takes city, provider and ASN from the returned result.  
These values are inserted into an alert style layout that imitates a system warning.  
The goal is to show that the page can look personal and threatening while still using only open interfaces and without touching the visitor device.
</p>
<p align="center">
<a href="https://jiachengma-26.github.io/ProjectPlayground/" target="_blank">
  <img src="https://img.shields.io/badge/Live%20Simulation-FF2A2A?style=for-the-badge&logo=hack-the-box&logoColor=white" alt="Live Simulation" />
</a>
</p>
</td>
</tr>
</table>

<br />

<h2 align="center">📂 Other Investigations and Tools</h2>

Project

Description

Core Concept

DragyTech: Entropy's Arc

An interactive science fiction case that walks through an incident.

Uses React state to control scene flow and highlight security concepts step by step.

Simple Real Estate Analyzer

A browser based calculator for basic return on investment.

Shows how to keep financial interfaces focused on data and layout instead of decoration.

Personal Cyber Portfolio

A small personal site with three dimensional effects.

Experiments with Three js to present security projects in a more visual way.

<br />

<h2 align="center">🛠 Technology and Tools</h2>

<div align="center">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />

<br />

<img src="https://img.shields.io/badge/Open_Meteo_API-orange?style=for-the-badge" alt="Open Meteo API" />
<img src="https://img.shields.io/badge/IPwho.is_API-blue?style=for-the-badge" alt="IPwho.is API" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
</div>

<br />

<h2 id="technical-philosophy" align="center">🧠 Technical Philosophy</h2>

<p align="center">
These projects try to turn abstract network behavior and threat models into concrete visual experiences.  
The aim is to let visitors see what information a simple web request exposes, and how the same data can either support education or be used in misleading interfaces.
</p>

<br />

<hr />
