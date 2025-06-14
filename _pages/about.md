---
permalink: /
layout: default
author_profile: true
---

<h1 id="about-me" class="page__title">About Me</h1>

<p>
Junior year Computer Science student specializing in backend development. 6 months of backend experience (Java Spring Boot) from an internship at Fawry. Designed systems including a microservice-based e-commerce platform, version control system, and text editor. Open-source contributor to Checkstyle. Two-time ACPC finalist with passion for algorithms, problem-solving, and coaching in competitive programming.
</p>

<h2 id="experience">Experience</h2>
<ul>
  <li>
    <strong>Software Engineer Intern @ Fawry</strong> (Nov 2024 -- Apr 2025)
    <br><em>Fawry -- Egyptian digital transformation and fintech platform. <a href="https://github.com/Fawry-Intern">GitHub Repository</a></em>
    <ul>
      <li>Built <b>e-commerce platform</b> comprising <b>8+ microservice APIs</b> in collaboration with 5-member team.</li>
      <li>Utilized Spring Boot and PostgreSQL to ensure ACID compliance and high availability.</li>
      <li>Designed API Gateway with <b>JWT authentication</b>, rate limiting, and <b>Java Security</b> in User API.</li>
      <li>Implemented <b>Kafka-based</b> event-driven architecture to enable real-time communication between microservices.</li>
      <li>Applied <b>Saga pattern</b> to manage <b>distributed transactions</b> with reliable rollback and consistency across services.</li>
      <li>Developed <b>Angular</b> admin dashboard to manage stores, products, and customer interface for browsing checkout.</li>
      <li>Integrated Bank API for transactions, account creation, and payments, with seamless Angular front-end.</li>
      <li>Used <b>Docker Compose</b> for microservice orchestration and Eureka for service discovery and horizontal scaling of APIs.</li>
    </ul>
  </li>
</ul>

<h2 id="education">Education</h2>
<ul>
  <li>
    <strong>B.S. in Computer Science and Engineering</strong> (Oct 2021 -- April 2026)
    <br><em>Faculty of Electronic Engineering, Menoufia University (<b>GPA</b>: 3.3/4.0), Egypt</em>
    <ul>
      <li><strong>Relevant Coursework</strong>: Data Structures &amp; Algorithms, Logic Design &amp; Digital Systems, Object-Oriented Programming, Database Management, Networking, Software Engineering.</li>
    </ul>
  </li>
</ul>

<h2 id="open-source-contributions">Open-Source Contributions</h2>
<ul>
  <li>
    <strong>Checkstyle Contributor</strong> (Mar 2024 - Present)
    <br><em>Static code analysis tool for enforcing Java coding standards with over 8k stars on <a href="https://github.com/checkstyle/checkstyle">GitHub</a></em>
    <ul>
      <li>Active contributor to Checkstyle, with over <b>+10 merged</b> pull requests and <b>3+ bugs</b> reported. <a href="https://github.com/checkstyle/checkstyle/pulls?q=author%3AAbdelrhmansersawy"><b>All PRs</b></a></li>
      <li>Designed and implemented <b>new header validation check</b> for file headers against multiple regex-based definitions. <a href="https://github.com/checkstyle/checkstyle/pull/16625"><b>PR</b></a></li>
      <li>Enhanced doc integrity via JUnit test parsing XDoc to validate  <code>index.xml</code> categories. <a href="https://github.com/checkstyle/checkstyle/pull/17132"><b>PR</b></a></li>
      <li>Resolved PIT test suppression for JavadocTagInfo, ensuring accurate test coverage. <a href="https://github.com/checkstyle/checkstyle/pull/16770"><b>PR</b></a></li>
      <li>killed mutations for CheckstyleAntTask: processFiles() and processFile() methods, ensuring robust test coverage. <a href="https://github.com/checkstyle/checkstyle/pull/16763"><b>PR</b></a></li>
      <li>Refactored test utilities, including SarifLoggerTest.java, to use verifyWithInlineConfigParserAndLogger. <a href="https://github.com/checkstyle/checkstyle/pull/16698"><b>PR</b></a></li>
    </ul>
  </li>
</ul>

<h2 id="projects">Projects</h2>
<ul>
  <li>
    <strong>Gitlet</strong> | <em>Version Control System</em> - <a href="https://github.com/Abdelrhmansersawy/gitlet">GitHub Repository</a>
    <ul>
      <li>Developed Java-based <b>version control system</b> emulating Git's 3-stage architecture (working, staging, remote); supports core operations (add, commit, log, checkout, branch, merge) and utilizes <b>Builder pattern</b> for object creation.</li>
      <li>Support <b>parallel development workflows</b> using robust branching, merging, and conflict resolution to enable collaborative code management.</li>
      <li>Ensured <b>version tracking</b> and repository integrity using SHA-1 hashing, serialization, and File I/O.</li>
    </ul>
  </li>
  <li>
    <strong>Text Editor</strong> | <em>Advanced GUI Plaintext Editor</em> - <a href="https://github.com/Abdelrhmansersawy/TextEditor">GitHub Repository</a>
    <ul>
      <li>Built efficient GUI plaintext editor in Java Swing, leveraging <b>Rope (Treap)</b> data structure for O(log n) text operations.</li>
      <li>Incorporated <b>undo/redo functionality via Command Design Pattern</b> and stack-based history.</li>
      <li>Achieved fast find/replace operations by <b>integrating Knuth-Morris-Pratt</b> (KMP) algorithm for O(n + m) searching.</li>
      <li>Implemented <b>real-time spell-checking</b> system utilizing a Trie and <b>dynamic programming</b> (edit distance).</li>
    </ul>
  </li>
  <li>
    <strong>NexusChat</strong> | <em>Multi-Peer TCP/IP Messaging System</em> - <a href="https://github.com/Abdelrhmansersawy/Network-programming/tree/main/multi-peer-chat">GitHub Repository</a>
    <ul>
      <li>Developed <b>multi-peer TCP/IP</b> chat system using socket library for <b>real-time client-server messaging</b>.</li>
      <li>Managed concurrent client connections using <b>threading module,</b> enabling non-blocking message broadcasting.</li>
      <li>Support client application featuring dynamic port connection, message transmission, and asynchronous reception.</li>
      <li>Enhanced system stability via resilience, including graceful disconnection, port checks, and status reporting.</li>
    </ul>
  </li>
  <li>
    <strong>Minesweeper AI</strong> | <em>AI-powered Minesweeper Game</em> - <a href="https://github.com/Abdelrhmansersawy/minesweeper">GitHub Repository</a>
    <ul>
      <li>Developed <b>AI agent</b> for Minesweeper, using <b>propositional logic</b> for state analysis and cell inference (safe/mine).</li>
      <li>Designed <b>Pygame-based GUI</b>, enabling dynamic visualization of AI gameplay and progress tracking.</li>
      <li>Implemented <b>knowledge inference engine</b>, deducing new safe/mine cells from logical sentences and game information.</li>
      <li>Optimized AI move selection by prioritizing provably safe cells and using calculated random choices as fallback.</li>
    </ul>
  </li>
</ul>

<h2 id="technical-skills">Technical Skills</h2>
<ul>
  <li><strong>Programming Languages</strong>: Java, C++, Python, Typescript, SQL.</li>
  <li><strong>Technologies</strong>: Spring boot, RESTful APIs, Agular, Junit, Mockito.</li>
  <li><strong>Tools</strong>: Docker, Git, Linux, Postman.</li>
  <li><strong>Core Concepts</strong>: Data Structures, Algorithms, OOP, Database Systems, SOLID Principles, Design Patterns.</li>
</ul>

<h2 id="achievements">Achievements</h2>
<ul>
  <li>Ranked <b>25th</b> at the <b>Africa &amp; Arab Collegiate Programming Championship (ACPC)</b> 2024 out of 100+ teams.</li>
  <li>Ranked <b>22nd</b> at the <b>Africa &amp; Arab Collegiate Programming Championship (ACPC)</b> 2023 out of 100+ teams.</li>
  <li>Ranked <b>26th globally</b>, 8th in Middle East and 3rd in Egypt in <b>IEEExtreme 17.0</b> out of +7000 teams.</li>
  <li>Achieved <b>Candidate Master</b> (CM) rating on Codeforces (top 5% of users) (<a href="https://codeforces.com/profile/Sersawy">username: Sersawy</a>).</li>
  <li>Secured <b>1st place</b> at Menofia University Collegiate Programming Contest 2023, out of +100 teams.</li>
  <li>Problem Setter and Judge at TCPC and QCPC 2024.</li>
</ul>

<h2 id="leadership">Leadership</h2>
<ul>
  <li>
    <strong>Development Team Leader</strong> - ACM ICPC Menofia Community (Aug 2023 -- Aug 2024)
    <ul>
      <li>Developed and executed training programs for competitive programming, <b>mentoring 200+ trainees</b> in algorithms and data structures while designing structured learning paths and contests to enhance their performance.</li>
      <li>Oversaw problem setting and testing processes to ensure <b>high-quality, contest-ready problems</b> aligned with training goals and competitive standards.</li>
    </ul>
  </li>
</ul>