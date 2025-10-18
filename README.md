<div id="readme-top"></div>

<h1 align="center">ReqRes API – Complete Testing Suite</h1>
<p align="center">
  <img src="images/postman.png" alt="Collection Banner" width="100%" />
</p>
<p class="lead" align="center">
  A complete automated test suite for the public ReqRes API, designed to validate CRUD operations, response integrity, and system resilience.
  Built entirely in Postman with reusable scripts, assertions, and environments to simulate real-world API testing scenarios.
</p>

<hr />

<h2 id="about">About The Project</h2>

<p>
  The <strong>ReqRes API – Complete Testing Suite</strong> is a professional-quality Postman collection created to demonstrate advanced skills in API testing and automation.
  It validates the functionality, reliability, and performance of the ReqRes API through structured test cases, including CRUD operations, response time checks, and idempotency validation.
  Designed as a portfolio-ready testing suite, it reflects best practices in automated API testing and reporting using <strong>Postman</strong> and <strong>Newman</strong>.
</p>

<div class="badge-container">
  <h3>Built With</h3>
  <a class="badge" href="https://www.postman.com/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman Badge" />
  </a>
  <a class="badge" href="https://www.javascript.com/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge" />
  </a>
  <a class="badge" href="https://www.npmjs.com/package/newman" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Newman-000000?style=for-the-badge&logo=npm&logoColor=white" alt="Newman Badge" />
  </a>
  <a class="badge" href="https://nodejs.org/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js Badge" />
  </a>
</div>

<h2 id="requirements">Requirements</h2>
<p>Make sure you have the following installed:</p>
<pre><code>
Postman (latest version)
Node.js >= 18
npm
Newman CLI (for automated runs)
</code></pre>

<h2 id="installation">Installation</h2>
<ol>
  <li>Clone or download this repository:
    <pre><code>git clone https://github.com/PortillaXpert/ReqRes-API-Testing-Suite.git</code></pre>
  </li>
  <li>Import the collection into Postman:
    <pre><code>File → Import → 01_-_ReqRes_API_Testing.postman_collection.json</code></pre>
  </li>
  <li>(Optional) Import the environment:
    <pre><code>File → Import → ReqRes_Production.postman_environment.json</code></pre>
  </li>
</ol>

<h2 id="usage">Usage</h2>
<p>To execute the collection locally using <strong>Newman</strong>:</p>
<pre><code>
newman run 01_-_ReqRes_API_Testing.postman_collection.json -e ReqRes_Production.postman_environment.json
</code></pre>

<p>This will run all automated tests, including:</p>
<ul>
  <li>Response status validation (2xx, 4xx, 5xx)</li>
  <li>Data integrity checks</li>
  <li>Performance and response time assertions</li>
  <li>Idempotency verification for DELETE operations</li>
  <li>Security header presence checks</li>
</ul>

<h2 id="features">Features</h2>
<ul>
  <li>Comprehensive CRUD operation coverage</li>
  <li>Automatic validation of status codes and response bodies</li>
  <li>Dynamic environment variables and chained requests</li>
  <li>Performance assertions for acceptable response times</li>
  <li>Post-request validations ensuring data consistency</li>
  <li>Ready-to-execute via Newman CLI for CI/CD pipelines</li>
</ul>

<h2 id="collection-structure">Collection Structure</h2>
<ul>
  <li><strong>Users:</strong> Tests for user creation, retrieval, update, and deletion</li>
  <li><strong>Global Tests:</strong> Shared pre-request and post-request scripts</li>
  <li><strong>Assertions:</strong> Performance, JSON schema, and security validations</li>
</ul>

<h2 id="contributing">Contributing</h2>
<p>Contributions are welcome! Here's how to start:</p>
<ol>
  <li>Fork the repository</li>
  <li>Create a new branch:
    <pre><code>git checkout -b feature/feature-name</code></pre>
  </li>
  <li>Commit your changes:
    <pre><code>git commit -m "Add your feature"</code></pre>
  </li>
  <li>Push the branch:
    <pre><code>git push origin feature/feature-name</code></pre>
  </li>
  <li>Open a Pull Request</li>
</ol>

<h2 id="license">License</h2>
<p>This project is licensed under the MIT License. See <code>LICENSE</code> for more information.</p>

<h2 id="contact">Contact</h2>
<p>
  Created by <a href="https://github.com/PortillaXpert" target="_blank">Juan Pablo Rivera Portilla</a><br/>
  Email: <a href="mailto:jrivera082002@gmail.com">jrivera082002@gmail.com</a>
</p>

<div class="right-link">
  (<a href="#readme-top">Back to top</a>)
</div>
