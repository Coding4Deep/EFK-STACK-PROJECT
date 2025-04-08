<div align="center">
  <h1 style="font-size: 3em; color: #4c8eda;">EFK Stack + NGINX Logging</h1>
  <p style="font-size: 1.2em; color: #555;">
    <strong>Elasticsearch</strong> • <strong>Fluentd</strong> • <strong>Kibana</strong> • <strong>NGINX</strong><br>
    Centralized logging system using Docker Compose
  </p>
</div>

---

<h2 style="color: #4c8eda;">📘 Project Summary</h2>
<p>
  This project sets up a fully containerized EFK (Elasticsearch, Fluentd, Kibana) logging stack along with an NGINX web server. NGINX logs are streamed in real-time to Fluentd, which forwards them to Elasticsearch. Kibana provides a visual interface to analyze and monitor logs.
</p>

---

<h2 style="color: #4c8eda;">🧩 Key Highlights</h2>
<ul>
  <li><strong>📦 Containerized Setup:</strong> All services are managed via Docker Compose.</li>
  <li><strong>🔁 Fluentd Log Driver:</strong> NGINX logs are forwarded directly using Fluentd as a log driver.</li>
  <li><strong>📊 Kibana Dashboards:</strong> Visualize web server logs, status codes, and traffic.</li>
  <li><strong>🧠 Elasticsearch Indexing:</strong> Log data is indexed and queryable instantly.</li>
</ul>

---

<h2 style="color: #4c8eda;">🧱 Tech Stack</h2>
<table>
  <tr><td><strong>Web Server</strong></td><td>NGINX (latest)</td></tr>
  <tr><td><strong>Log Forwarder</strong></td><td>Fluentd v1.16</td></tr>
  <tr><td><strong>Log Storage</strong></td><td>Elasticsearch 7.17</td></tr>
  <tr><td><strong>Visualization</strong></td><td>Kibana 7.17</td></tr>
  <tr><td><strong>Container Orchestration</strong></td><td>Docker Compose</td></tr>
</table>

---

<h2 style="color: #4c8eda;">🚀 Deployment Steps</h2>
<ol>
  <li>Clone the repository to your local machine.</li>
  <li>Use Docker Compose to build and launch all services.</li>
  <li>Access Kibana to visualize real-time NGINX access logs.</li>
</ol>

---

<h2 style="color: #4c8eda;">📍 Why This Project Matters</h2>
<p>
  Centralized logging is crucial in any production-grade infrastructure. This EFK setup demonstrates log aggregation, storage, and visualization using open-source tools. It reflects real-world DevOps skills like container orchestration, monitoring, log parsing, and stack integration.
</p>

---

<h2 style="color: #4c8eda;">🎯 Ideal For</h2>
<ul>
  <li>💼 Portfolio Showcase</li>
  <li>🛠️ DevOps Practice & Interview Preparation</li>
  <li>📊 Monitoring & Logging Fundamentals</li>
</ul>

---

<h2 style="color: #4c8eda;">📄 Resume Description (Copy this)</h2>
<!-- <blockquote>
  <em>
    Built and deployed a centralized logging system using EFK Stack and Docker Compose. Integrated NGINX web server with Fluentd logging driver for real-time log aggregation and visualization in Kibana. Demonstrated containerized orchestration and monitoring with zero manual log access.
  </em>
</blockquote> -->

---

<div align="center">
  <sub style="color: #888;">© 2025 • Designed with ❤️ by Deepak Sagar</sub>
</div>
