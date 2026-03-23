<h2>URL Shortener Service - Scalable Backend Architecture</h2>

<p>This repository contains a high-performance <strong>URL Shortener</strong> service built with <strong>Java</strong> and <strong>Spring Boot</strong>. The application provides an efficient way to transform long, cumbersome URLs into compact, manageable links while ensuring fast redirection and reliable data persistence.</p>

<h3>Features</h3>
<ul>
  <li><strong>URL Compression:</strong> Generates unique, shortened identifiers for any valid long URL.</li>
  <li><strong>High-Speed Redirection:</strong> Optimized backend logic to ensure minimal latency when redirecting from a short link to the original destination.</li>
  <li><strong>Data Integrity:</strong> Implements robust mapping and storage mechanisms to prevent collisions and ensure link permanence.</li>
  <li><strong>RESTful API Design:</strong> Provides standardized endpoints for creating, retrieving, and managing shortened URLs.</li>
  <li><strong>Scalable Infrastructure:</strong> Designed using modular Spring Boot components, making it ready for containerization and cloud deployment.</li>
</ul>

<h3>Tech Stack</h3>
<ul>
  <li><strong>Language:</strong> Java</li>
  <li><strong>Framework:</strong> Spring Boot</li>
  <li><strong>Web Support:</strong> Jakarta Servlet API, JSTL (JavaServer Pages Standard Tag Library)</li>
  <li><strong>Build Tool:</strong> Maven</li>
</ul>


<h3>Implementation Overview</h3>

<h4>Core Logic</h4>
<p>The system utilizes a specialized hashing and encoding algorithm to convert long URLs into unique base-encoded strings. This ensures that every generated short link is both human-readable and mathematically unique within the system namespace.</p>

<h4>Dependency Management</h4>
<p>The project leverages <strong>Jakarta Servlet</strong> and <strong>JSTL</strong> for seamless web-tier processing, ensuring compatibility with modern Java Enterprise standards and efficient server-side rendering where applicable.</p>


<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Java JDK 17 or higher</li>
  <li>Maven 3.6+</li>
</ul>

<h3>Installation & Setup</h3>
<ol>
  <li><strong>Clone the repository:</strong>
    <pre><code>git clone https://github.com/leelendrareddygogula/URLShortener.git</code></pre>
  </li>
  <li><strong>Navigate to the project folder:</strong>
    <pre><code>cd URLShortener</code></pre>
  </li>
  <li><strong>Build the application:</strong>
    <pre><code>mvn clean install</code></pre>
  </li>
  <li><strong>Run the project:</strong>
    <pre><code>mvn spring-boot:run</code></pre>
  </li>
</ol>
