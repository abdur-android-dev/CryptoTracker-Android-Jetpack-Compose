<h1>🪙 CryptoTracker — Modern Android Architecture App</h1>

<p>
  A <strong>clean-architecture Android app</strong> built to explore and display cryptocurrency data —
  including live coin lists, detailed stats, and <strong>custom Canvas chart</strong> visualizations —
  following modern Android best practices.
</p>

<p>
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-1.9+-orange" />
  <img alt="Compose" src="https://img.shields.io/badge/Jetpack%20Compose-UI-blue" />
  <img alt="Architecture" src="https://img.shields.io/badge/Architecture-MVI%20%7C%20Clean-success" />
  <img alt="License" src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

<hr />

<h2>📸 Screenshots</h2>
<div style="display:flex;flex-wrap:wrap;gap:12px;align-items:flex-start;">
  <img src="screenshots/1.png" width="250"  />
  <img src="screenshots/2.png" width="250"  />
  <img src="screenshots/3.png" width="250"/>
  <img src="screenshots/4.png" width="250"  />
</div>

<hr />

<!-- Features -->
<h2>🚀 Features</h2>

<h3>🧩 Clean Architecture with MVI pattern</h3>
<p>Organized codebase with separation of concerns — easy to test, maintain, and scale.</p>

<h3>💉 Koin Dependency Injection</h3>
<p>Lightweight DI for managing app dependencies with minimal boilerplate.</p>

<h3>🌐 Ktor Client for REST API calls</h3>
<p>Efficient, coroutine-friendly HTTP client to fetch crypto data.</p>

<h3>🎨 Canvas Chart Drawing</h3>
<p>Custom charting using the <code>Canvas</code> API (no third-party chart libs).</p>

<h3>🧭 Adapter Navigation</h3>
<p>Smooth navigation with clear UI state handling.</p>

<h3>📱 Responsive UI</h3>
<p>Layouts adapt beautifully to different screen sizes and orientations.</p>

<h3>🔐 Secure API Key Handling</h3>
<p>Environment-safe API key management following best practices.</p>

<h3>🌓 Dynamic Theming (Light &amp; Dark Mode)</h3>
<p>Automatic support for system-wide themes, delivering a consistent and visually adaptive experience.</p>

<hr />

<h2>🧠 What I Learned</h2>
<p>Built alongside the
  <a href="https://pl-coding.com/best-practice-guide/" target="_blank" rel="noopener noreferrer">
    Modern Android Architecture course
  </a>.
</p>
<ul>
  <li>Designing <strong>modular, scalable</strong> clean architecture.</li>
  <li>Integrating <strong>Koin</strong> for dependency injection.</li>
  <li>Performing network calls with <strong>Ktor</strong> and robust response handling.</li>
  <li>Implementing <strong>MVI</strong> for predictable, testable state management.</li>
  <li>Drawing <strong>dynamic charts</strong> using Canvas + Compose.</li>
  <li>Building a <strong>responsive UI</strong> for phones and tablets.</li>
  <li>Applying <strong>secure packaging &amp; key management</strong> for production apps.</li>
</ul>

<hr />

<!-- Tech stack -->
<h2>🏗️ Tech Stack</h2>
<table>
  <tr><td><strong>Language</strong></td><td>Kotlin</td></tr>
  <tr><td><strong>Architecture</strong></td><td>Clean Architecture (MVI)</td></tr>
  <tr><td><strong>DI</strong></td><td>Koin</td></tr>
  <tr><td><strong>Networking</strong></td><td>Ktor</td></tr>
  <tr><td><strong>UI</strong></td><td>Jetpack Compose, Canvas</td></tr>
  <tr><td><strong>Navigation</strong></td><td>Adapter Navigation / Jetpack Navigation</td></tr>
  <tr><td><strong>Async</strong></td><td>Kotlin Coroutines, Flow</td></tr>
  <tr><td><strong>Design</strong></td><td>Material 3, Light/Dark themes</td></tr>
  <tr><td><strong>Build</strong></td><td>Gradle (KTS)</td></tr>
</table>

<hr />

<h2>⚙️ Setup &amp; Run</h2>
<ol>
  <li>Clone the repo:
    <pre><code>git clone https://github.com/abdur-android-dev/CryptoTracker-Android-Jetpack-Compose.git</code></pre>
  </li>
  <li>Open in <strong>Android Studio</strong>.</li>
  <li>Add your API key to a secure place (create new file. <code>key.properties</code>):
    <pre><code># key.properties
API_KEY="your_api_key_here"</code></pre>
    <em>Read it at build/runtime via BuildConfig or Gradle encrypted vars (do not commit keys).</em>
  </li>
  <li>Run the app 🚀</li>
</ol>

<hr />

<!-- Acknowledgements -->
<h2>🙌 Acknowledgements</h2>
<ul>
  <li>
    <a href="https://pl-coding.com/best-practice-guide/" target="_blank" rel="noopener noreferrer">
      PL-Coding — Master Modern Android Architecture
    </a>
  </li>
  <li>
    <a href="https://pro.coincap.io/api-docs" target="_blank" rel="noopener noreferrer">
      Coincap API
    </a>
  </li>
</ul>

<hr />

<!-- License -->
<h2>🧾 License</h2>
<p>Released under the <strong>MIT License</strong>. You are free to use, modify, and distribute this project with attribution.</p>

<!-- Contact -->
<h2>📬 Connect</h2>
<p>
  <a href="https://www.linkedin.com/in/abdurrehman-android-dev/">LinkedIn</a> ·
  <a href="mailto:abdurrehmankhan75@gmail.com">Email</a>
</p>
