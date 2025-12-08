<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Your Name | Cybersecurity Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #0a0a0a;
            color: #d4d4d4;
        }

        header {
            padding: 3rem 2rem;
            text-align: center;
            background: linear-gradient(135deg, #0f0f0f, #001100);
            border-bottom: 2px solid #00ff88;
        }

        h1 {
            font-size: 3rem;
            color: #00ff88;
        }

        nav {
            margin-top: 1rem;
        }

        nav a {
            margin: 0 1rem;
            color: #00ff88;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 3rem 2rem;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: #00ff88;
            margin-bottom: 0.5rem;
        }

        .project-card {
            border: 1px solid #00ff88;
            padding: 1rem;
            margin-top: 1rem;
            border-radius: 8px;
            background: #111;
        }

        .project-card h3 {
            margin: 0;
            color: #00ff88;
        }

        .btn {
            display: inline-block;
            margin-top: 1rem;
            padding: 0.6rem 1rem;
            background: #00ff88;
            color: #000;
            font-weight: bold;
            text-decoration: none;
            border-radius: 6px;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #888;
            margin-top: 3rem;
        }

        .contact a {
            color: #00ff88;
            text-decoration: none;
        }
    </style>
</head>

<body>
    <header>
        <h1>Your Name</h1>
        <p>Cybersecurity Student | Penetration Tester | CTF Competitor</p>

        <nav>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#writeups">Write-Ups</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="skills">
        <h2>Skills</h2>
        <p>Here are some of my core cybersecurity skills:</p>
        <ul>
            <li>Penetration Testing (Web, Network, AppSec)</li>
            <li>CTFs: Web Exploitation, Forensics, Crypto, Reversing</li>
            <li>Python, Bash, PowerShell</li>
            <li>Burp Suite, Nmap, Wireshark, Metasploit</li>
            <li>Threat Modeling & Risk Analysis</li>
            <li>Secure Coding & Code Review</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>

        <div class="project-card">
            <h3>Automated HIPAA Risk Analysis Tool</h3>
            <p>
                A Python-based system that automates risk scoring of healthcare devices 
                and generates compliance-ready reports.
            </p>
            <a class="btn" href="#" target="_blank">View Project</a>
        </div>

        <div class="project-card">
            <h3>Penetration Testing: 'Arm Book'</h3>
            <p>
                Documented exploitation of XSS, SQL Injection, and CSRF vulnerabilities 
                in a web application.
            </p>
            <a class="btn" href="#" target="_blank">Read Report</a>
        </div>

        <div class="project-card">
            <h3>WheelLift Roblox Security System</h3>
            <p>
                Engineered secure server-client communication and exploited/mitigated 
                possible RCE vectors within game logic.
            </p>
            <a class="btn" href="#" target="_blank">View Code</a>
        </div>
    </section>

    <section id="writeups">
        <h2>Write-Ups</h2>

        <div class="project-card">
            <h3>NCL Competition Write-Up</h3>
            <p>Summary of OSINT, forensics, and cryptography challenges solved.</p>
            <a class="btn" href="#" target="_blank">Read Write-Up</a>
        </div>

        <div class="project-card">
            <h3>PicoCTF Challenges</h3>
            <p>Step-by-step solutions for web exploitation and binary analysis problems.</p>
            <a class="btn" href="#" target="_blank">Read Write-Up</a>
        </div>

        <div class="project-card">
            <h3>US Cyber Challenge</h3>
            <p>Reverse engineering and exploit dev notes from USCC workshops.</p>
            <a class="btn" href="#" target="_blank">Read Write-Up</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p class="contact">
            Email: <a href="mailto:your@email.com">your@email.com</a>
            <br>
            GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a>
            <br>
            LinkedIn: <a href="#" target="_blank">Your LinkedIn</a>
        </p>
    </section>

    <footer>
        © 2025 Your Name — Cybersecurity Portfolio
    </footer>
</body>
</html>
