👋 Hello, I'm Utkarsh Bhariya

<style>
  :root {
    --bg: #0a0a0f;
    --bg-subtle: #12121a;
    --fg: #f5f0e8;
    --muted: #8a8a9a;
    --accent: #3b82f6;
    --accent-soft: rgba(59, 130, 246, 0.15);
    --border: #2a2a3a;
    --white: #ffffff;
  }

  * {
    box-sizing: border-box;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    background: var(--bg);
    color: var(--fg);
    margin: 0;
    padding: 0;
  }

  .prose {
    max-width: 100%;
    padding: 2rem;
  }

  h1 {
    font-size: clamp(2.5rem, 12vw, 8rem);
    font-weight: 900;
    letter-spacing: -0.03em;
    margin: 0 0 1rem 0;
    line-height: 1.05;
  }

  h2 {
    font-size: clamp(1.5rem, 6vw, 2.5rem);
    font-weight: 700;
    letter-spacing: -0.01em;
    margin: 3rem 0 1.5rem 0;
    color: var(--accent);
    border-bottom: 1px solid var(--border);
    padding-bottom: 0.5rem;
  }

  h3 {
    font-size: 1rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    color: var(--muted);
    margin: 2rem 0 1rem 0;
  }

  .nav-links a {
    font-size: 0.875rem;
    color: var(--muted);
    text-decoration: none;
    margin-right: 1.5rem;
    transition: color 0.2s;
  }

  .nav-links a:hover {
    color: var(--accent);
  }

  .nav-links .separator {
    color: var(--muted);
    margin: 0 0.5rem;
  }

  .section {
    margin: 4rem 0;
  }

  .divider {
    height: 1px;
    background: var(--border);
    margin: 2rem 0;
  }

  .skill-category {
    margin-bottom: 2rem;
  }

  .skill-category h4 {
    font-size: 0.75rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--muted);
    margin-bottom: 1rem;
  }

  .skill-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }

  .skill-tag {
    font-size: 0.8rem;
    background: var(--accent-soft);
    color: var(--accent);
    padding: 0.4rem 0.8rem;
    border-radius: 4px;
    border: 1px solid var(--accent);
    white-space: nowrap;
  }

  .focus-item {
    display: inline-block;
    font-size: 0.875rem;
    color: var(--fg);
    background: var(--accent-soft);
    padding: 0.5rem 1rem;
    border-radius: 4px;
    margin-right: 0.5rem;
    margin-bottom: 0.5rem;
    border: 1px solid var(--accent);
  }

  .principle {
    margin: 0.5rem 0;
    padding-left: 1rem;
    border-left: 3px solid var(--accent);
    color: var(--muted);
    font-size: 0.875rem;
    line-height: 1.6;
  }

  .timeline-item {
    padding: 1rem 0;
    border-bottom: 1px solid var(--border);
    display: flex;
    justify-content: space-between;
  }

  .timeline-item:last-child {
    border-bottom: none;
  }

  .timeline-label {
    font-size: 0.75rem;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .timeline-period {
    font-size: 0.875rem;
    color: var(--accent);
  }

  .connect-links a {
    font-size: 1rem;
    color: var(--muted);
    text-decoration: none;
    margin-right: 2rem;
    transition: color 0.2s;
  }

  .connect-links a:hover {
    color: var(--accent);
  }

  .connect-links svg {
    width: 1rem;
    height: 1rem;
    margin-right: 0.5rem;
    vertical-align: middle;
  }

  .lang-dist {
    display: flex;
    gap: 1rem;
    margin-top: 1rem;
  }

  .lang-item {
    flex: 1;
    height: 8px;
    border-radius: 4px;
    background: var(--bg-subtle);
  }

  .lang-label {
    font-size: 0.65rem;
    color: var(--muted);
    text-align: center;
    margin-top: 0.5rem;
  }

  .activity-stats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 1rem;
    margin-top: 2rem;
  }

  .stat {
    text-align: center;
    padding: 1rem;
    background: var(--bg-subtle);
    border-radius: 8px;
  }

  .stat-value {
    font-size: 2rem;
    font-weight: 700;
    color: var(--accent);
    margin-bottom: 0.25rem;
  }

  .stat-label {
    font-size: 0.7rem;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .profile-card {
    background: var(--bg-subtle);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 1.5rem;
    margin: 1rem 0;
  }
</style>

<div style="max-width: 800px; margin: 0 auto; padding: 2rem 3rem;">

  <!-- NAVIGATION -->
  <nav class="nav-links" style="margin-bottom: 3rem; padding-bottom: 1rem; border-bottom: 1px solid var(--border); display: flex; justify-content: center; gap: 1rem;">
    <a>ABOUT</a>
    <span class="separator">·</span>
    <a>SKILLS</a>
    <span class="separator">·</span>
    <a>STACK</a>
    <span class="separator">·</span>
    <a>EXPERIENCE</a>
    <span class="separator">·</span>
    <a>ACTIVITY</a>
    <span class="separator">·</span>
    <a>CONNECT</a>
  </nav>

  <!-- HERO SECTION -->
  <header style="text-align: center; margin-bottom: 4rem; padding-bottom: 2rem; border-bottom: 1px solid var(--border); margin-top: -2rem; position: relative; z-index: 10;">
    <h1 style="color: var(--fg); line-height: 1.1;">UTKARSH BHARIYA</h1>
    <p style="color: var(--muted); font-size: 1.25rem; margin: 0.5rem 0 2rem 0; max-width: 600px; margin-left: auto; margin-right: auto;">Software Developer · AI Engineer · Full-Stack Developer</p>
    <p style="color: var(--fg); font-size: 1rem; max-width: 600px; margin: 0 auto 2rem auto; line-height: 1.6;">Building intelligent software at the intersection of AI, backend engineering, and product development.</p>
  </header>

  <!-- ABOUT SECTION -->
  <section class="section" id="about">
    <span style="font-size: 3rem; font-weight: 900; color: var(--muted); opacity: 0.4; line-height: 1;">01</span> &nbsp;— ABOUT
    <h2>ABOUT</h2>
    <p style="color: var(--muted); font-size: 1.05rem; line-height: 1.8; max-width: 600px;">
      Computer Science Engineering student focused on software development, with interest in AI and backend engineering. Comfortable building full-stack applications and turning ideas into working products. Continuously improving engineering fundamentals and building practical software solutions.
    </p>
  </section>

  <div class="divider"></div>

  <span style="font-size: 3rem; font-weight: 900; color: var(--muted); opacity: 0.4; line-height: 1;">02</span> — SKILLS

  <!-- SKILLS SECTION -->
  <section class="section" id="skills">
    <h2>SKILLS</h2>

    <div class="skill-category">
      <h4>LANGUAGES</h4>
      <div class="skill-tags">
        <span class="skill-tag">Python</span>
        <span class="skill-tag">Java</span>
        <span class="skill-tag">JavaScript</span>
        <span class="skill-tag">SQL</span>
      </div>
    </div>

    <div class="skill-category">
      <h4>BACKEND</h4>
      <div class="skill-tags">
        <span class="skill-tag">FastAPI</span>
        <span class="skill-tag">Node.js</span>
        <span class="skill-tag">Express.js</span>
        <span class="skill-tag">Spring Boot</span>
        <span class="skill-tag">REST APIs</span>
      </div>
    </div>

    <div class="skill-category">
      <h4>FRONTEND</h4>
      <div class="skill-tags">
        <span class="skill-tag">React</span>
        <span class="skill-tag">HTML</span>
        <span class="skill-tag">CSS</span>
        <span class="skill-tag">Tailwind CSS</span>
      </div>
    </div>

    <div class="skill-category">
      <h4>AI / ML</h4>
      <div class="skill-tags">
        <span class="skill-tag">LLMs</span>
        <span class="skill-tag">RAG</span>
        <span class="skill-tag">AI Agents</span>
        <span class="skill-tag">Prompt Engineering</span>
        <span class="skill-tag">AI APIs</span>
      </div>
    </div>

    <div class="skill-category">
      <h4>DATABASES</h4>
      <div class="skill-tags">
        <span class="skill-tag">PostgreSQL</span>
        <span class="skill-tag">MongoDB</span>
        <span class="skill-tag">MySQL</span>
      </div>
    </div>

    <div class="skill-category">
      <h4>ENGINEERING</h4>
      <div class="skill-tags">
        <span class="skill-tag">Git</span>
        <span class="skill-tag">GitHub</span>
        <span class="skill-tag">Docker</span>
        <span class="skill-tag">Authentication</span>
        <span class="skill-tag">API Design</span>
        <span class="skill-tag">Database Design</span>
      </div>
    </div>

    <div class="skill-category">
      <h4>CORE CS</h4>
      <div class="skill-tags">
        <span class="skill-tag">Data Structures & Algorithms</span>
        <span class="skill-tag">OOP</span>
        <span class="skill-tag">DBMS</span>
        <span class="skill-tag">Operating Systems</span>
        <span class="skill-tag">Computer Networks</span>
        <span class="skill-tag">System Design</span>
      </div>
    </div>
  </section>

  <div class="divider"></div>

  <!-- ENGINEERING MINDSET SECTION -->
  <section class="section" id="mindset">
    <h2>HOW I APPROACH ENGINEERING</h2>
    <div style="color: var(--muted); font-size: 0.9rem; line-height: 1.8;">
      <span class="principle">Understand the problem before choosing technology</span>
      <span class="principle">Prefer simple architectures before unnecessary complexity</span>
      <span class="principle">Build systems hands-on rather than relying on abstractions blindly</span>
      <span class="principle">Focus on maintainability and real-world usability</span>
      <span class="principle">Learn through implementation</span>
      <span class="principle">Continuously improve engineering fundamentals</span>
    </div>
  </section>

  <div class="divider"></div>

  <span style="font-size: 3rem; font-weight: 900; color: var(--muted); opacity: 0.4; line-height: 1;">03</span> — FOCUS

  <!-- CURRENT FOCUS SECTION -->
  <section class="section" id="focus">
    <h2>CURRENTLY EXPLORING</h2>
    <div style="display: flex; flex-wrap: wrap; gap: 0.5rem;">
      <span class="focus-item">AI Engineering</span>
      <span class="focus-item">RAG Systems</span>
      <span class="focus-item">AI Agents</span>
      <span class="focus-item">Backend Architecture</span>
      <span class="focus-item">API Design</span>
      <span class="focus-item">System Design</span>
      <span class="focus-item">Production Deployment</span>
    </div>
  </section>

  <div class="divider"></div>

  <span style="font-size: 3rem; font-weight: 900; color: var(--muted); opacity: 0.4; line-height: 1;">04</span> — ACTIVITY

  <!-- GITHUB ACTIVITY SECTION -->
  <section class="section" id="activity">
    <h2>ACTIVITY</h2>

    <div style="color: var(--muted); font-size: 0.9rem; margin-bottom: 2rem;">
      <strong>Consistent engineering activity</strong> · building and improving regularly
    </div>

    <div class="activity-stats">
      <div class="stat">
        <div class="stat-value">•••••••</div>
        <div class="stat-label">Days</div>
      </div>
      <div class="stat">
        <div class="stat-value">••••••••••</div>
        <div class="stat-label">Repos</div>
      </div>
      <div class="stat">
        <div class="stat-value">••••••</div>
        <div class="stat-label">Contributions</div>
      </div>
    </div>

    <div class="lang-dist">
      <div class="lang-item" style="width: 45%; background: #1f77b4;"></div>
      <span class="lang-label">Python</span>
      <div class="lang-item" style="width: 30%; background: #ff7f0e;"></div>
      <span class="lang-label">JavaScript</span>
      <div class="lang-item" style="width: 20%; background: #2ca02c;"></div>
      <span class="lang-label">Java</span>
      <div class="lang-item" style="width: 15%; background: #d62728;"></div>
      <span class="lang-label">C++</span>
    </div>
  </section>

  <div class="divider"></div>

  <!-- EXPERIENCE/JOURNEY SECTION -->
  <section class="section" id="experience">
    <h2>EXPERIENCE</h2>

    <div style="display: flex; flex-direction: column; gap: 1.5rem;">
      <div class="timeline-item">
        <span>
          <div class="timeline-label">2024</div>
          <div class="timeline-period">Frontend Development</div>
        </span>
      </div>
      <div class="timeline-item">
        <span>
          <div class="timeline-label">2025</div>
          <div class="timeline-period">Full-Stack & Backend Engineering</div>
        </span>
      </div>
      <div class="timeline-item">
        <span>
          <div class="timeline-label">2025</div>
          <div class="timeline-period">AI Application Development</div>
        </span>
      </div>
      <div class="timeline-item">
        <span>
          <div class="timeline-label">2026</div>
          <div class="timeline-period">AI Engineering & System Design</div>
        </span>
      </div>
    </div>
  </section>

  <div class="divider"></div>

  <!-- CONNECT SECTION -->
  <section class="section" id="connect">
    <h2>LET'S CONNECT</h2>

    <div class="connect-links" style="display: flex; gap: 2rem; margin-top: 1.5rem; flex-wrap: wrap;">
      <a href="https://linkedin.com/in/utkarshbhariya" style="display: flex; align-items: center;">
        <svg viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.082-1.852-3.082-1.853 0-2.136 1.408-2.136 2.936v5.766H5.666v-5.569c0-1.328.026-3.083 1.852-3.083 1.853 0 2.136 1.405 2.136 2.936v5.767H1.83c-1.387 0-1.817.706-1.817 1.632v5.569h1.878v-5.205c0-.586.28-1.088.813-1.088.522 0 .812.35.812.936v.066h10.027v5.569c0 1.114.33 2.316.963 2.804.628.485.827 1.26.827 2.295v.057c0 1.032-.367 1.976-.98 2.688h2.917v5.57h-2.918c-.637 1.317-1.818 2.333-3.218 2.333-.788 0-1.381-.219-1.875-.52-.5-.307-1.037-.52-1.81-.52-1.386 0-2.162-.997-2.162-2.895v-5.628h8.688v5.628c0 1.787.66 3.452 1.858 4.389.972.766 2.06.99 3.277.99 2.055 0 2.56-.73 2.56-1.892v-5.569h1.88v-4.957c0-1.164-.505-2.025-1.505-2.025-1.121 0-1.506.955-1.817 2.158h-.064zM3.88 15.628h16.24c.578 0 1.047-.22 1.397-.63.354-.41.531-.881.531-1.433v-4.81h-16.24v4.81c0 .552.208 1.023.531 1.433.35.41.818.63 1.397.63zm1.52-6.113h9.024v2.87h-9.024V9.516z"/></svg>
        LinkedIn
      </a>
      <a href="https://github.com/utkarshbhariya" style="display: flex; align-items: center;">
        <svg viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-1.321-1.805-1.661-2.655-1.661-3.957 0-1.31.475-2.696 1.661-3.224-3.532-.305-7.079-1.344-7.079-6.879 0-2.116.695-3.56 1.805-5.056 0 0 1.239-.669 2.635-.884.435.107.878.197 1.342.207-3.226.188-5.778 1.08-5.778 4.834 0 4.833 3.182 6.765 6.782 10.194-1.083-.071-2.004-.426-2.635-.884-.364-.197-.79-.463-1.342-.207.958.518 2.32.883 3.734 1.295-.676.18-1.383-.197-1.383-.603v-2.234c-.001-.317-.005-.633-.005-.942 0-1.006.363-1.623.993-2.31h3.047c.522.09.878.251 1.156.363.278.112.522.18.772.18s.494-.068.772-.18c.277-.112.522-.251.727-.38.566-.328 1.03-1.01.993-2.31h3.046c-.008.309-.004.609.013.88.018.418.106.905.29 1.337h.057c.768-1.577 1.205-2.666 1.205-3.968 0-2.815-2.318-5.133-5.168-5.133-1.015 0-1.97.16-2.873.588l3.521 3.857.99-2.387zM3.674 6.693l.67.87 4.993-.837 1.515 4.63-4.993.837-.67-.87L3.674 6.693zM7.077 11.5l.568 1.48 3.245-.866-.967-3.05 3.712.866-.568-1.48L7.077 11.5zM12 2.588l2.837 1.19.958-2.387-2.837-1.19-.958 2.387zm5.173 9.088-.568 1.48 3.245-.866.967 3.05-3.245.866-.568 1.48-3.712-.866-3.245-.866-.967-3.05L12 2.588l-2.837 1.19-.958 2.387 2.837 1.19.958-2.387zM15.38 13.117l-.568 1.48-3.245.866.967 3.05-3.712-.866.568-1.48 3.245-.866-1.515-4.63 4.993.837.67.87L15.38 13.117z"/></svg>
        GitHub
      </a>
      <a href="https://utkarshbhariya.vercel.app" style="display: flex; align-items: center;">
        <svg viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 7l10 5 10-5M2 7l-10 5V7z"/></svg>
        Portfolio
      </a>
      <a href="mailto:utkarshbhariya@example.com" style="display: flex; align-items: center;">
        <svg viewBox="0 0 24 24"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2zM4 18h16v-2H4v2zm0-4h16v-2H4v2zm0-4v-2h16v2H4v2z"/></svg>
        Email
      </a>
    </div>
  </section>

</div>