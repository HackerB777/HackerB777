
<!-- Profile Header -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=2500&pause=900&center=true&vCenter=true&width=800&lines=Hi%2C+I'm+A+Gowtham+%7C+HackerB777;Cyber+Security+Engineer;Offensive+%26+Defensive+Security+Enthusiast;Building+AI+powered+Cyber+Security+Tools" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=HackerB777&style=for-the-badge&label=PROFILE+VIEWS" alt="profile views" />
  <img src="https://img.shields.io/github/followers/HackerB777?style=for-the-badge&label=FOLLOWERS" alt="followers" />
  <img src="https://img.shields.io/github/stars/HackerB777?style=for-the-badge&label=STARS" alt="stars" />
</p>

<!-- Animated Sun/Moon Theme Toggle Demo (visual flair) -->
<p align="center">
  <div class="theme-toggle">
    <input type="checkbox" id="theme-switch" />
    <label for="theme-switch" class="toggle-track">
      <span class="sun">☀️</span>
      <span class="moon">🌙</span>
      <span class="toggle-ball"></span>
    </label>
  </div>
  <small><i>Offensive <-> Defensive Security Mode (just for fun)</i></small>
</p>

<style>
.theme-toggle {
  --size: 90px;
  position: relative;
  width: var(--size);
  height: calc(var(--size) / 2.2);
  margin: 20px auto;
}

#theme-switch { display: none; }

.toggle-track {
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, #f6d365, #fda085);
  border-radius: 999px;
  cursor: pointer;
  overflow: hidden;
  transition: background 0.6s ease;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}

.sun, .moon {
  position: absolute;
  font-size: 32px;
  top: 50%;
  transform: translateY(-50%);
  transition: all 0.7s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}

.sun { left: 12px; color: #fff; opacity: 1; }
.moon { right: 12px; color: #111; opacity: 0; }

.toggle-ball {
  position: absolute;
  width: calc(var(--size) / 2.4);
  height: calc(var(--size) / 2.4);
  background: #fff;
  border-radius: 50%;
  top: 5px;
  left: 5px;
  transition: all 0.7s cubic-bezier(0.68, -0.55, 0.265, 1.55);
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

#theme-switch:checked \~ .toggle-track {
  background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
}

#theme-switch:checked .sun { opacity: 0; transform: translateX(-40px) rotate(-90deg); }
#theme-switch:checked .moon { opacity: 1; transform: translateX(40px) rotate(360deg); }
#theme-switch:checked .toggle-ball { transform: translateX(calc(var(--size)/2 - 10px)); background: #ffd700; box-shadow: 0 0 20px #ffd700; }
</style>

---

## 👨‍💻 About Me

- 🛡️ Cyber Security Engineer from Namakkal, India  
- 🧪 Passionate about **offensive & defensive security, CTI, SIEM, and AI-driven security tooling**  
- 🧠 Currently building **automation tools for payload creation, threat detection, and security operations**  
- 🧬 Exploring **AI + Cyber Security** (LLM-powered CLIs, auto-recon, and smart payload generators)  
- 🌐 Portfolio: [my-portfolio-website-77.web.app](https://my-portfolio-website-77.web.app/)  
- 📫 Reach me on: [LinkedIn](https://www.linkedin.com/in/gowtham-a-489910284), [Instagram](https://www.instagram.com/mr_dart_77), [Facebook](https://www.facebook.com/mrdart77)

---

## 🛡️ Cyber Security Focus

<!-- Simple cyber-themed toggle (red/blue accent) -->
<p align="center">
  <label class="cyber-toggle">
    <input type="checkbox" checked />
    <span class="slider"></span>
  </label>
  <small>Ethical Hacking ↔ Blue Team Mode</small>
</p>

<style>
.cyber-toggle {
  position: relative;
  display: inline-block;
  width: 80px;
  height: 42px;
  margin: 15px;
}

.cyber-toggle input {
  opacity: 0;
  width: 0;
  height: 0;
}

.slider {
  position: absolute;
  cursor: pointer;
  top: 0; left: 0; right: 0; bottom: 0;
  background: #1e3a8a;
  border-radius: 42px;
  transition: .5s;
  box-shadow: inset 0 3px 8px rgba(0,0,0,0.4);
}

.slider:before {
  position: absolute;
  content: "";
  height: 34px;
  width: 34px;
  left: 4px;
  bottom: 4px;
  background: #fff;
  border-radius: 50%;
  transition: .5s;
  box-shadow: 0 3px 10px rgba(0,0,0,0.3);
}

input:checked + .slider {
  background: #dc2626;
}

input:checked + .slider:before {
  transform: translateX(38px);
  background: #fef08a;
}
</style>

- 🔍 **Phishing & Website Detection** – ML models to classify malicious vs legit sites  
- 📊 **SIEM & Log Analysis** – collecting, parsing, and correlating logs for threat hunting  
- 🌐 **Cyber Threat Intelligence (CTI)** – aggregating and visualizing threat data  
- 🧨 **Payload Research** – ethical research on payload generation and EDR evasion concepts  
- 🤖 **AI-Assisted Security** – integrating LLMs into security workflows and CLIs  

---

## ⚙️ Tech Stack & Tools

<p align="center">
  <!-- Languages -->
  <img src="https://skillicons.dev/icons?i=python,bash,cpp,java,js,ts" /><br/>
  <!-- Cyber / Infra -->
  <img src="https://skillicons.dev/icons?i=linux,docker,ubuntu" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tools-Wireshark-informational?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-informational?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Metasploit-informational?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Burp%20Suite-informational?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Splunk%2FELK-SIEM-informational?style=for-the-badge" />
</p>

---

## 🚀 Highlighted Projects

### 🧠 Phishing Website Detection (ML)
- 📂 Repo: [website-detection-using-ML](https://github.com/HackerB777/website-detection-using-ML)  
- 🧪 Uses **machine learning** to detect phishing websites based on URL and content features.  
- 🎯 Great for demonstrating **security + data science** skills.

### 🌐 Cyber Threat Intelligence Platform
- 📂 Repo: [Cyber-Threat-Intelligence-Platform-](https://github.com/HackerB777/Cyber-Threat-Intelligence-Platform-)  
- 🧠 Collects and processes threat intel data.  
- 📊 Helps security teams to **visualize, analyze, and act on threat feeds**.

### 📡 SIEM Lab
- 📂 Repo: [SIEM](https://github.com/HackerB777/SIEM)  
- 🎛️ Focused on building a **SIEM pipeline** using logs and alerts.  
- 🔎 Useful for **threat hunting, correlation rules, and blue-team practice**.

### 🐚 Cybert – Cyber Security Toolkit
- 📂 Repo: [Cybert](https://github.com/HackerB777/Cybert)  
- 💻 Shell-based tool collection for **automation, recon, and utilities**.  
- 🧩 Designed to be extended with more offensive/defensive modules.

---

## 📊 GitHub Analytics

<p align="center">
  <img alt="HackerB777 GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=HackerB777&show_icons=true&theme=radical&hide_border=true&count_private=true" />
</p>

<p align="center">
  <img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=HackerB777&theme=radical&hide_border=true" />
</p>

<p align="center">
  <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HackerB777&layout=compact&theme=radical&hide_border=true" />
</p>

<p align="center">
  <img alt="GitHub Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=HackerB777&theme=radical&hide_border=true&area=true" />
</p>

---

## 🎯 Current Goals

<!-- Another small sun/moon toggle near goals for consistency -->
<p align="center">
  <div class="theme-toggle small">
    <input type="checkbox" id="theme-small" />
    <label for="theme-small" class="toggle-track">
      <span class="sun">⚡</span>
      <span class="moon">🔒</span>
      <span class="toggle-ball"></span>
    </label>
  </div>
  <small>Offense → Defense Automation</small>
</p>

<style>
.theme-toggle.small {
  --size: 70px;
  margin: 10px auto;
}

.theme-toggle.small .toggle-track {
  background: linear-gradient(135deg, #60a5fa, #3b82f6);
}

.theme-toggle.small #theme-small:checked \~ .toggle-track {
  background: linear-gradient(135deg, #1e293b, #111827);
}

.theme-toggle.small .sun, .theme-toggle.small .moon { font-size: 24px; }
.theme-toggle.small .toggle-ball { width: calc(var(--size)/2.5); height: calc(var(--size)/2.5); }
</style>

- 🔁 Build a **full automation pipeline** for payload creation and testing in a lab environment  
- 🤖 Release an **AI-powered cyber security CLI** for recon, scanning, and reporting  
- 📚 Contribute to more **open-source security tools** and ML-based detection projects  

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://my-portfolio-website-77.web.app/">
    <img src="https://img.shields.io/badge/Portfolio-visit-informational?style=for-the-badge" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/gowtham-a-489910284">
    <img src="https://img.shields.io/badge/LinkedIn-Gowtham_A-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="https://www.instagram.com/mr_dart_77">
    <img src="https://img.shields.io/badge/Instagram-@mr_dart_77-critical?style=for-the-badge&logo=instagram" alt="Instagram" />
  </a>
  <a href="https://www.facebook.com/mrdart77">
    <img src="https://img.shields.io/badge/Facebook-mrdart77-blue?style=for-the-badge&logo=facebook" alt="Facebook" />
  </a>
</p>

---

<p align="center">
  <b>🔥 Keep hacking, keep learning, keep securing. 🔥</b>
</p>