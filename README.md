
---
# Caleb Kibet
### IT Consultant   |   [Portfolio](https://ogc16.github.io/gitprofile/)
[LinkedIn](https://www.linkedin.com/in/caleb-kibet-834020362) | [ngenokibetcaleb@gmail.com](mailto:ngenokibetcaleb@gmail.com) | [+254 703 871 410](tel:+254703871410)

---

## Profile
Performance-focused IT Consultant with a strong foundation in Software Engineering specializing in developing secure, scalable digital products. <br>
Expert at bridging complex backend architectures with frictionless, user-centric web and mobile interfaces using TypeScript(React and Next.js) and Flutter.

---
## Skills
### Technical Skills
- **Frontend Ecosystem**: React, Next.js, React Native, Vite, Flutter, Kotlin (Native Android)
- **Backend & Cloud**: Node.js, Supabase, PostgreSQL, REST/GraphQL APIs, async, local
- **Architecture & Tooling**: UML Modeling (PlantUML), Git/GitHub, Expo, Xcode, IntelliJ IDEA
- **Network tools**: Wireshark, OSINT, Burp Suite, Splunk, Nmap

### Soft Skills
- Keen attention to Detail
- Timely - Deadline arriving in sprints(Project organized into deliverables).
- Quick learning and adaptation to changes/updates.
- Collaborative approach.

---

## Education
- **Bachelor of Science in Information Technology (BScIT)** -JKUAT,Kenya <br>
  *Focus: Object-Oriented Analysis and Design*  <br>
  Coursework: UML modeling, conceptual design, Data Structures & Algorithms (DSA), and software architecture.

- *Junior Cybersecurity Analyst Certificate* - CISCO
- *Cybersecurity Certificate* - Google

---

## Projects

<details>
<summary><b>Parcel Delivery App (ParcelFlow)</b> — <a href="https://parcelapp.expo.app/">Demo</a></summary>
<br>
<b>Situation:</b> High market demand for streamlined, transparent parcel logistics and delivery tracking.<br>
<b>Task:</b> Engineer a cross-platform mobile application supporting interactive, real-time location tracking.<br>
<b>Action:</b> Built a responsive UI using Flutter; integrated map APIs and location services for precise spatial routing.<br>
<b>Result:</b> Reduced package routing errors by 15% and optimized driver navigation accuracy.<br>
</details>

<details>
<summary><b>News Aggregator (AggregatorX)</b> — <a href="https://aggregatorx1.netlify.app/">Demo</a></summary>
<br>
<b>Situation:</b> Users required a single, fast dashboard to aggregate cross-domain tech, crypto, and sports content.<br>
<b>Task:</b> Develop a full-stack aggregator platform with low network latency and custom personalized feeds.<br>
<b>Action:</b> Programmed a React+Vite frontend and a Node.js scraping architecture (Cheerio). Configured Supabase for user auth, data caching, and bookmark storage.<br>
<b>Result:</b> Processed 1,000+ daily articles efficiently while maintaining rapid, sub-100ms API response times.<br>
</details>

<details>
<summary><b>Food & E-Commerce Mobile App (ePay)</b> — <a href="https://epay.expo.app/">Demo</a></summary>
<br>
<b>Situation:</b> High cart-abandonment rates in traditional retail apps caused by complicated checkout experiences.<br>
<b>Task:</b> Build a performance-optimized e-commerce and ordering client interface using React Native.<br>
<b>Action:</b> Architected a state-managed cart pipeline with secure, transactional payment integration checkpoints.<br>
<b>Result:</b> Streamlined checkout mechanics, reducing end-to-end customer purchase times by ~30%.<br>
</details>

<details>
<summary><b>House Design (The Pavilion House)</b> — <a href="https://ogc16.github.io/house/">Demo</a></summary>
<br>
<b>Situation:</b> Architectural blueprints need readable, highly accessible web-based visualizations for remote clients.<br>
<b>Task:</b> Convert a 2,200 sq ft residential spatial layout into an interactive web-rendered environment.<br>
<b>Action:</b> Programmed an optimized web client displaying interactive 3D orthographic and plan-view spatial modules- three.js.<br>
<b>Result:</b> Delivered a high-fidelity digital proposal that eliminated technical blueprint confusion during stakeholder review.<br>
</details>

<details>
<summary><b>File Manipulation Tools</b> — <a href="https://ogc16.github.io/data_manipulation_tool/">Demo</a></summary>
<br>
<b>Situation:</b> Office teams frequently struggle with local data processing due to slow server-side transformation tools.<br>
<b>Task:</b> Construct an all-in-one local data utility suite handling large file conversions and data visualization.<br>
<b>Action:</b> Programmed clean file pipelines for Excel/PDF-to-CSV transformation, chart rendering, ZIP archival operations, and client-side encryption algorithms.<br>
<b>Result:</b> Saved users significant administrative processing overhead by executing all operations safely in the browser client.<br>
</details>

<details>
<summary><b>Image Editor & CWS Asset Resizer</b> — <a href="https://ogc16.github.io/ChromeExtensionTool/">Demo</a></summary>
<br>
<b>Situation:</b> Product developers spend excessive time manually formatting graphic banners for standard application marketplace requirements.<br>
<b>Task:</b> Automate dynamic multi-ratio graphical resizing and background canvas generation.<br>
<b>Action:</b> Implemented explicit canvas scaling engines inside a client-side layout tool supporting crop, contain, and ZIP exports.<br>
<b>Result:</b> Standardized platform compliance and cut extension store listing preparation times by roughly 40%.<br>
</details>

<details>
<summary><b>Vulnerability Scanner (ShieldUp)</b> — <a href="https://chromewebstore.google.com/detail/mlgjidmlbpmcphkaainofhkgjelmffnn">Chrome Web Store Extension</a></summary>
<br>
<b>Situation:</b> Developers inadvertently ship misconfigured HTTP headers, creating immediate cross-site scripting vulnerabilities.<br>
<b>Task:</b> Build a non-intrusive network traffic analysis layer directly embedded inside the browser context.<br>
<b>Action:</b> Engineered an asynchronous background engine monitoring incoming host response headers, cookie state flags, and data anomalies.<br>
<b>Result:</b> Deployed a lightweight 2.18MiB utility providing real-time security hardening insights without injecting processing overhead.<br>
</details>

---

<div style="width: 80%; max-width: 600px; margin: 20px auto;">
  <canvas id="projectChart"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  const ctx = document.getElementById('projectChart').getContext('2d');
  const projectChart = new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: ['JavaScript/TypeScript', 'Python', 'Flutter', 'Swift', 'C++', 'Go','Others'],
      datasets: [{
        data: [35, 20, 20, 10, 10, 3, 2],
        backgroundColor: [
          '#3178c6', // JavaScript/TypeScript
          '#116191', // Python
          '#2482e3', // Flutter
          '#bf2a0d', // Swift
          '#de83bb', // C++
          '#1297b5', // Go
          '#e3c712'  // Others
        ],
        borderColor: '#ffffff',
        borderWidth: 2
      }]
    },
    options: {
      responsive: true,
      plugins: {
        legend: {
          position: 'bottom',
          labels: { padding: 20, font: { size: 14 } }
        },
        title: {
          display: true,
          text: 'Projects Distribution by Language',
          font: { size: 16 }
        }
      }
    }
  });
</script>

---

## Focus
**Technical leadership** — Architecting resilient full-stack systems with optimized mobile applications and performance-focused interfaces.  
**User-centered engineering** — Bridging complex backends with intuitive frontends to deliver production-ready solutions.  
**Innovation & impact** — Leading technical strategy for digital products while championing code quality, security, and agile execution.

<p align="right">
  <a href="/Resume">🔺 Back to Top</a>
</p>
<p align="center">
  <small>© 2026 Ngeno Kibet Caleb.</small>
</p>
