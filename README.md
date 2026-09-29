<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Uppala Abhilash | Python Full Stack Developer</title>
  <style>
    :root {
      color-scheme: dark;
      --background: #0d1117;
      --panel: #161b22;
      --border: #30363d;
      --text: #e6edf3;
      --muted: #9da7b3;
      --accent: #58a6ff;
      --tag: #1f3a5a;
    }

   * { box-sizing: border-box; }
    body {
      margin: 0;
      padding: 40px 20px;
      background: var(--background);
      color: var(--text);
      font: 16px/1.6 system-ui, -apple-system, "Segoe UI", sans-serif;
    }

   main {
     width: min(900px, 100%);
      margin: 0 auto;
    }

   header, section {
     padding: 28px;
      margin-bottom: 20px;
      background: var(--panel);
      border: 1px solid var(--border);
      border-radius: 14px;
    }

   header { text-align: center; }

   h1 { margin: 0; font-size: clamp(2rem, 5vw, 3rem); }
    h2 { margin-top: 0; color: var(--accent); }
    h3 { margin-bottom: 4px; }
    p { margin-top: 8px; }
    .subtitle, .muted { color: var(--muted); }

   a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }

   .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      padding: 0;
      list-style: none;
    }

   .tags li {
      padding: 4px 10px;
      background: var(--tag);
      border: 1px solid #28496c;
      border-radius: 999px;
      font-size: 0.9rem;
    }

   .project {
      padding: 16px 0;
      border-top: 1px solid var(--border);
    }

   .project:first-of-type { border-top: 0; }
    footer { padding: 12px; text-align: center; color: var(--muted); }
    @media (max-width: 600px) {
      body { padding: 20px 12px; }
      header, section { padding: 20px; }
    }
  </style>
</head>
<body>
  <main>
    <header>
      <h1>Hi, I'm Uppala Abhilash 👋</h1>
      <p class="subtitle">Python Full Stack Developer · Computer Science Undergraduate</p>
      <p>
        I build web applications with Python and Django, and explore practical AI projects,
        from disease prediction workflows to voice and gesture controlled desktop tools.
      </p>
      <p>
        <a href="mailto:uppalaabhilash22@gmail.com">Email me</a>
      <!-- Add your actual GitHub and LinkedIn URLs here -->
      </p>
    </header>

   <section>
      <h2>About Me</h2>
      <ul>
        <li>B.Tech in Computer Science Engineering at Dhanalakshmi Srinivasan University (2022–2026)</li>
        <li>Interested in Python full stack development and applied AI</li>
        <li>Focused on problem solving, maintainable software, and user-friendly interfaces</li>
        <li>Languages: English and Telugu</li>
      </ul>
    </section>

   <section>
      <h2>Technical Skills</h2>
      <ul class="tags">
        <li>Python</li>
        <li>JavaScript</li>
        <li>Django</li>
        <li>FastAPI</li>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>Pandas</li>
        <li>Matplotlib</li>
        <li>Vosk</li>
        <li>OpenCV</li>
        <li>MediaPipe</li>
        <li>Tkinter</li>
        <li>pyttsx3</li>
      </ul>
    </section>

   <section>
      <h2>Featured Projects</h2>

   <article class="project">
        <h3>Disease Prediction System</h3>
        <p class="muted">Python · Django · JavaScript · HTML · CSS</p>
        <ul>
          <li>Built a Django application that accepts health-related inputs and presents prediction results with confidence scores.</li>
          <li>Implemented user authentication and profile management for secure access.</li>
          <li>Created interactive interfaces for submitting inputs and viewing results.</li>
        </ul>
      </article>

   <article class="project">
        <h3>AI Virtual Assistant for Desktop</h3>
        <p class="muted">Python · FastAPI · Vosk · pyttsx3 · MediaPipe · OpenCV · Pandas · Matplotlib · Tkinter</p>
        <ul>
          <li>Developed a desktop assistant with voice commands and online/offline speech recognition.</li>
          <li>Added gesture-based cursor control and voice-driven CSV analysis with spoken summaries and charts.</li>
          <li>Exposed assistant actions through FastAPI endpoints for external command triggering and analysis workflows.</li>
        </ul>
      </article>
    </section>

   <section>
      <h2>Experience</h2>
      <h3>Artificial Intelligence Trainee · SkillVertex</h3>
      <p class="muted">Remote · December 2023 – January 2024</p>
      <p>Completed a remote AI training program covering AI foundations, Python-based problem solving, and practical technology applications.</p>
    </section>

   <section>
      <h2>Education &amp; Certifications</h2>
      <ul>
        <li><strong>B.Tech, Computer Science Engineering</strong> — Dhanalakshmi Srinivasan University, 2022–2026</li>
        <li><strong>Intermediate</strong> — Narayana Junior College, 2020–2022</li>
        <li><strong>SSC</strong> — Himalaya High School, 2019–2020</li>
        <li><strong>Data Analysis with Python</strong> — IBM Cognitive Class</li>
        <li><strong>Data Science &amp; Analytics</strong> — HP LIFE, HP Foundation</li>
      </ul>
    </section>

   <footer>
      Contact: <a href="mailto:uppalaabhilash22@gmail.com">uppalaabhilash22@gmail.com</a>
    </footer>
  </main>
</body>
</html>
