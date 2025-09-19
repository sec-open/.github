<p align="center">
  <img src="https://avatars.githubusercontent.com/u/172953072?s=200&v=4" alt="sec-open logo" width="120"/>
</p>

<h1 align="center">🔐 sec-open</h1>
<p align="center">
  Open Source organization focused on <b>software supply chain security</b>.
</p>

---

## 🌍 About Us
`sec-open` is a community-driven initiative creating **free and open-source tools** to improve the security of software development pipelines.  

We focus on:
- 📦 **SBOMs** (Software Bill of Materials) generation  
- 🛡 **Vulnerability scanning** for code and containers  
- 📊 **Security reporting** (PDF/HTML/Markdown/Slack)  
- 🔗 **CI/CD integrations** for GitHub Actions  

---

## 🚀 Projects

### 🔎 [vuln-diff-action](https://github.com/sec-open/vuln-diff-action)
Compare vulnerabilities between two refs (branches, tags, commits) using **Syft + Grype**.  
- Generates SBOMs automatically  
- Detects new, removed, unchanged vulnerabilities  
- Outputs Markdown tables, JSON, PDF reports  
- Integrates with Pull Requests (comments, checks)  
- Optional Slack notifications  

---

## 🛣 Roadmap
- **v1.x** → Branch and PR vulnerability diff (✅ released)  
- **v2.x** →  
  - Enhanced reporting (PDF/HTML, charts, trends)  
  - Docker image scanning (single image + diff)  
  - SARIF output for GitHub Code Scanning  
  - PR annotations with Checks API  

---

## 📚 Resources
- [Syft](https://github.com/anchore/syft) → SBOM generation  
- [Grype](https://github.com/anchore/grype) → Vulnerability scanning  
- [CycloneDX](https://cyclonedx.org/) → SBOM standard  

---

## 👫 Community
We believe in **open collaboration**. Contributions, ideas, and bug reports are welcome!  

How to get involved:
- ⭐ Star our repositories to support the project  
- 🐛 Open issues if you find bugs or security problems  
- 🤝 Submit pull requests with fixes or improvements  
- 💬 Join discussions to shape the roadmap  

---

## 📄 License
All projects under `sec-open` are released under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).  

---

<p align="center">
  <sub>Securing the open-source supply chain, one project at a time ⚡</sub>
</p>
