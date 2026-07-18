<!-- HEADER BANNER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&section=header&text=Tejas%20Dhakate&fontSize=65&fontColor=ffffff&color=gradient&gradient=a855f7,6366f1" width="100%" alt="Tejas Dhakate Header Banner" />
</div>

<!-- SUBTITLE TYPING ANIMATION -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&size=24&duration=3000&pause=1000&color=A855F7&background=0F172A00&center=true&vCenter=true&width=600&lines=Computer+Engineering+Student;Full+Stack+Developer;AI+%26+Machine+Learning+Explorer;System+Architect" alt="Typing Animation" />
</div>

<!-- TOP CONTACT BADGES -->
<div align="center">
  <a href="mailto:tejasdhakate62@gmail.com">
    <img src="https://img.shields.io/badge/Email-tejasdhakate62%40gmail.com-1E1E2F?style=for-the-badge&logo=gmail&logoColor=A855F7" alt="Email Badge" />
  </a>
  <a href="https://linkedin.com/in/tejas-suresh-dhakate">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-1E1E2F?style=for-the-badge&logo=linkedin&logoColor=6366F1" alt="LinkedIn Badge" />
  </a>
  <a href="https://tejasdhakate62-dev.github.io">
    <img src="https://img.shields.io/badge/Portfolio-Interactive%203D-1E1E2F?style=for-the-badge&logo=react&logoColor=A855F7" alt="Portfolio Badge" />
  </a>
  <br/>
  <img src="https://img.shields.io/badge/Location-Wardha%2C%20MH%2C%20India-1E1E2F?style=for-the-badge&logo=googlemaps&logoColor=6366F1" alt="Location Badge" />
</div>

<br/>

---

### 🌌 About Me

Welcome to my digital workspace. I am a Computer Engineering student specializing in building high-performance, robust software architectures, database integrations, and intelligent machine learning microservices. Dedicated to translating complex mathematical algorithms and system requirements into clean, optimized production-ready environments.

---

### 🛠️ Core Tech Stack & Toolkit

<div align="center">
  <table>
    <tr>
      <td align="center" width="250"><b>Languages & Syntax</b></td>
      <td align="center" width="250"><b>Frameworks & Web Motion</b></td>
      <td align="center" width="250"><b>Databases & Systems</b></td>
    </tr>
    <tr>
      <td align="left" valign="top">
        • <img src="https://img.shields.io/badge/Java-1E1E2F?style=flat&logo=openjdk&logoColor=A855F7" alt="Java" /> Native Android / Core Logic<br/>
        • <img src="https://img.shields.io/badge/Python-1E1E2F?style=flat&logo=python&logoColor=6366F1" alt="Python" /> Data Processing / ML REST<br/>
        • <img src="https://img.shields.io/badge/JavaScript-1E1E2F?style=flat&logo=javascript&logoColor=A855F7" alt="JavaScript" /> Frontend / Interactive Loops<br/>
        • <img src="https://img.shields.io/badge/XML-1E1E2F?style=flat&logo=xml&logoColor=6366F1" alt="XML" /> Declarative UI Structures
      </td>
      <td align="left" valign="top">
        • <img src="https://img.shields.io/badge/Flask-1E1E2F?style=flat&logo=flask&logoColor=A855F7" alt="Flask" /> Microservices / REST API<br/>
        • <img src="https://img.shields.io/badge/Three.js-1E1E2F?style=flat&logo=threedotjs&logoColor=6366F1" alt="Three.js" /> WebGL 3D Rendering<br/>
        • <img src="https://img.shields.io/badge/GSAP-1E1E2F?style=flat&logo=greensock&logoColor=A855F7" alt="GSAP" /> ScrollTrigger Animations<br/>
        • <img src="https://img.shields.io/badge/Tailwind_CSS-1E1E2F?style=flat&logo=tailwindcss&logoColor=6366F1" alt="Tailwind" /> Utility-First Layouts
      </td>
      <td align="left" valign="top">
        • <img src="https://img.shields.io/badge/SQLite-1E1E2F?style=flat&logo=sqlite&logoColor=A855F7" alt="SQLite" /> Transaction-Safe Caches<br/>
        • <img src="https://img.shields.io/badge/Firebase_DB-1E1E2F?style=flat&logo=firebase&logoColor=6366F1" alt="Firebase" /> Realtime / Firestore / Cloud Storage<br/>
        • <img src="https://img.shields.io/badge/Linux-1E1E2F?style=flat&logo=linux&logoColor=A855F7" alt="Linux" /> Admin & Shell Scripting<br/>
        • <img src="https://img.shields.io/badge/Git-1E1E2F?style=flat&logo=git&logoColor=6366F1" alt="Git" /> Version Control / Git Workflows
      </td>
    </tr>
  </table>
</div>

---

### 💻 Key Project Spotlights

<details>
  <summary><b>🛡️ SecurScan AI™ — Fake Credit Card Generator & Detector Suite</b></summary>
  <br/>

  > A cyberpunk-themed validation and synthetic credential engine that matches physical device parameters, parses visual card textures, and caches client keys locally.

  #### 📊 Core Architectural Flow
  ```mermaid
  graph TD
      UI["3D Parallax UI / Camera Feed"] -->|"Video / Upload"| OCR["Tesseract.js WASM OCR"]
      OCR -->|"Extract Digit String"| VAL["Validation Router"]
      UI -->|"Manual Entry"| VAL
      VAL -->|"HTTP POST /validate"| BE["Flask API Backend"]
      BE -->|"Luhn Algorithm Check"| BE_RES["Network Identification & Validity"]
      BE_RES -->|"Response < 5ms"| UI
      GEN["Generator Engine"] -->|"Compute Check Digit"| UI
      UI -->|"Cache Credentials"| DB[("Local Storage Vault")]
  ```

  #### 🛠️ Technical Specifications
  | Parameter | Detail |
  | :--- | :--- |
  | **Backend Engine** | Python 3.x, Flask Micro-router |
  | **Optical Parsing** | Tesseract.js (Client-Side WASM execution) |
  | **UI Components** | Three.js (Dynamic Rotations), Container Query width metrics (`cqw`) |
  | **Performance Cap** | Luhn checksum execution & response under **5ms** |
  
  #### Key Accomplishments
  * **Dynamic Tilt Parallax:** Developed a canvas-rendering pipeline that translates real-time cursor coordinate offsets into smooth physical matrix rotations.
  * **Fluid Breakpoints:** Structured layout elements using CSS Container Queries to guarantee asset proportions and card aspect ratios stay uniform across all mobile screen widths.
  * **Offline Name Matrix:** Programmed a fallback pool containing **10,000+ unique name combinations** to prevent generation pipeline blocks during API timeouts.
</details>

<details>
  <summary><b>📉 PredictiveRiskAnalyzer — Machine Learning Risk Evaluation</b></summary>
  <br/>

  > An analytical classification pipeline optimized to evaluate systemic risk indices using scikit-learn models, deployed behind an interactive Flask UI.

  #### 📊 Core Architectural Flow
  ```mermaid
  graph TD
      DS["100k Row Dataset"] -->|"Model Training"| TM["train_model.py"]
      TM -->|"Serialize Model"| PKL["risk_model.pkl"]
      USER["User Input Data"] -->|"Submit Form"| FLASK["app.py Flask Backend"]
      PKL -->|"Load Weights"| FLASK
      FLASK -->|"Feature Matrix Parsing"| ML["Scikit-Learn Classifier"]
      ML -->|"Predictive Inference"| RES["Real-time Risk Level Assessment"]
      RES -->|"JSON / Render UI"| USER
  ```

  #### 🛠️ Technical Specifications
  | Parameter | Detail |
  | :--- | :--- |
  | **Core Language** | Python 3.x |
  | **Mathematical Model** | Scikit-learn Random Forest Classifier |
  | **Data Frame Handling** | Pandas, NumPy Matrice Operations |
  | **Analytical Yield** | Cut manual evaluation error rates by **30%** |

  #### Key Accomplishments
  * **Model Serialization:** Created automated scripts (`train_model.py`) to prepare and serialize high-dimension decision matrices using joblib.
  * **Dynamic Assessment:** Engineered a Flask API gateway to ingest multi-tier JSON matrices and return risk classification vectors in real-time.
</details>

<details>
  <summary><b>📱 Invoix App — Mobile Freelance Billing Platform</b></summary>
  <br/>

  > A production-tier native Android invoice tracking application featuring isolated VM states, query batching, and synchronized cloud storage.

  #### 📊 Core Architectural Flow
  ```mermaid
  graph TD
      APP["Invoix Android App"] -->|"XML Layout UI"| AUTH["Firebase Authentication"]
      APP -->|"State Isolation"| VM["ViewModel & Repository"]
      VM -->|"Query Batching"| DB["Firebase Firestore & Realtime DB"]
      VM -->|"Local Sync Cache"| LOC[("Offline Cache")]
      APP -->|"Logo Upload"| STR["Firebase Cloud Storage"]
  ```

  #### 🛠️ Technical Specifications
  | Parameter | Detail |
  | :--- | :--- |
  | **Native Language** | Java / Android SDK |
  | **Database Integration**| Firebase Firestore, Realtime DB, Firebase Storage |
  | **State Management** | isolated ViewModel State / Query Batching |
  | **Memory Footprint** | Reduced run-time heap from **120MB** to **<45MB** |

  #### Key Accomplishments
  * **Query Optimization:** Implemented strict query batching parameters that minimized Firebase read/write overhead by 40%.
  * **Robust Localization:** Designed a system preferences dashboard that overrides and synchronizes localized symbols (e.g. `₹`) across generated invoice tables.
  * **Appearance Overrides:** Programmed dynamic XML layouts to seamlessly sync with system light/dark settings.
</details>

<details>
  <summary><b>🥗 Diet Plan App — Local Nutrition Tracker</b></summary>
  <br/>

  > An offline-first mobile application featuring structural daily diet schedules, progress bars, and localized SQLite transaction integrity.

  #### 📊 Core Architectural Flow
  ```mermaid
  graph TD
      USER["User Input (Meals/Water)"] -->|"Update Stats"| UI["XML Layout UI"]
      UI -->|"Trigger Transaction"| DB[("Local SQLite Database")]
      DB -->|"Write Log State"| CACHE["Transaction-Safe Local Storage"]
      CACHE -->|"Sync / Update Progress"| UI
  ```

  #### 🛠️ Technical Specifications
  | Parameter | Detail |
  | :--- | :--- |
  | **Language & Engine** | Java, Android SDK (API 34+) |
  | **Local Storage** | SQLite Cache / ConstraintLayout UI |
  | **Architectural Model**| Offline-First Data Isolation |
  | **Data Reliability** | **Zero Data Loss** via ACID SQL transaction triggers |

  #### Key Accomplishments
  * **SQLite Transaction Integrity:** Configured strict transaction checkpoints to prevent partial writes and corrupt entries when the app lifecycle interrupts.
  * **Responsive Canvas Gauges:** Created customized progress indicators to visually project meal target completions dynamically.
</details>

---

### 📊 GitHub Activity & Analytics

<div align="center">
  <table border="0">
    <tr>
      <td align="center" valign="top">
        <img src="https://github-readme-stats.vercel.app/api?username=tejasdhakate62-dev&show_icons=true&theme=radical&bg_color=0f172a&title_color=a855f7&text_color=e2e8f0&icon_color=6366f1&border_color=334155&hide_border=false" alt="Tejas's GitHub Stats" />
      </td>
      <td align="center" valign="top">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=tejasdhakate62-dev&theme=dark&background=0f172a&fire=a855f7&ring=6366f1&currStreakNum=e2e8f0&sideNums=e2e8f0&sideLabels=e2e8f0&currStreakLabel=a855f7&border=334155&hide_border=false" alt="Tejas's GitHub Streak" />
      </td>
    </tr>
  </table>
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tejasdhakate62-dev&layout=compact&theme=radical&bg_color=0f172a&title_color=a855f7&text_color=e2e8f0&border_color=334155&hide_border=false" alt="Tejas's Top Languages" />
</div>

---

### 🎓 Academic Progression

> [!NOTE]
> Currently pursuing advanced computer engineering studies, aligning mathematical models with practical application architectures.

* **B.Tech in Computer Engineering** (2021 — 2026 Expected)
  *Rashtrasant Tukadoji Maharaj Nagpur University (RTMNU) | Nagpur, India*
* **Higher Secondary Certificate (HSC) — 74.00%** (2019 — 2021)
  *Vidya Vikas Arts, Commerce & Science College | Samudrapur, MH*
* **Secondary School Certificate (SSC) — 58.60%** (2017 — 2019)
  *Yeshwant Junior College & High School | Mandgaon, MH*

---

### 🏅 Verified Certifications

| Specialization / Course | Issuer | Core Modules |
| :--- | :--- | :--- |
| **Google AI Essentials Specialization** | Coursera | Introduction to AI, Maximize Productivity, Discover the Art of Prompting, Use AI Responsibly, Stay Ahead of the AI Curve |
| **Google Prompting Essentials Specialization** | Coursera | Pro Prompting, Everyday Prompt Design, AI Data Analysis, Creative AI Partner |

---

<!-- Sleek Centered Footer -->
<div align="center">
  <p>🌐 Built with precision and a commitment to high-performance software engineering.</p>
  <sub>© 2026 Tejas Dhakate. All rights reserved.</sub>
</div>
