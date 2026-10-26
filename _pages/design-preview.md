---
layout: single
permalink: /design-preview/
title: ""
author_profile: false
---

<style>
.vk-page {
  --vk-ink: #203344;
  --vk-muted: #627587;
  --vk-blue: #2675a8;
  --vk-line: #e2eaf0;
  --vk-soft: #f4f8fb;
  max-width: 1050px;
  margin: 0 auto;
  color: var(--vk-ink);
}

.vk-page * { box-sizing: border-box; }

.vk-page a {
  color: var(--vk-blue);
  text-decoration: none;
}

.vk-page a:hover { text-decoration: underline; }

.vk-hero {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 175px;
  align-items: center;
  gap: 3rem;
  padding: 2.5rem 0 1.5rem;
}

.vk-eyebrow {
  color: var(--vk-blue);
  font-size: .75rem;
  font-weight: 700;
  letter-spacing: .13em;
  text-transform: uppercase;
}

.vk-hero h1 {
  font-size: clamp(2.3rem, 5vw, 3.7rem);
  line-height: 1.12;
  margin: .65rem 0 1rem;
  color: var(--vk-ink);
}

.vk-lead {
  font-size: 1.15rem;
  line-height: 1.7;
  margin-bottom: .8rem;
}

.vk-description {
  color: var(--vk-muted);
  line-height: 1.8;
  font-size: .96rem;
}

.vk-photo {
  width: 175px;
  height: 210px;
  object-fit: cover;
  object-position: 31% 35%;
  border-radius: 16px;
  box-shadow: 0 10px 30px rgba(24, 52, 74, .09);
}

.vk-links {
  display: flex;
  flex-wrap: wrap;
  gap: .8rem;
  margin-top: 1.5rem;
}

.vk-link {
  display: inline-block;
  padding: .65rem 1rem;
  border: 1px solid var(--vk-line);
  border-radius: 9px;
  font-size: .85rem;
  font-weight: 600;
}

.vk-link.primary {
  background: var(--vk-blue);
  color: white;
  border-color: var(--vk-blue);
}

.vk-wave {
  height: 76px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 3px;
  overflow: hidden;
  margin: 1.5rem 0 3rem;
  opacity: .8;
}

.vk-wave span {
  width: 3px;
  height: var(--h);
  background: linear-gradient(#78bedc, #2675a8);
  border-radius: 5px;
  animation: vk-pulse 2.4s ease-in-out infinite alternate;
  animation-delay: var(--delay);
}

@keyframes vk-pulse {
  from { transform: scaleY(.35); opacity: .45; }
  to { transform: scaleY(1); opacity: 1; }
}

.vk-section { margin: 3rem 0; }

.vk-section h2 {
  font-size: 1.65rem;
  margin-bottom: .65rem;
  color: var(--vk-ink);
}

.vk-section-intro {
  color: var(--vk-muted);
  line-height: 1.75;
  max-width: 700px;
}

.vk-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
  margin-top: 1.5rem;
}

.vk-card {
  border: 1px solid var(--vk-line);
  border-radius: 15px;
  padding: 1.5rem;
  background: #fff;
  transition: transform .2s, box-shadow .2s;
}

.vk-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 28px rgba(24, 52, 74, .07);
}

.vk-card-icon {
  font-size: 1.5rem;
  margin-bottom: .9rem;
}

.vk-card h3 {
  font-size: 1.1rem;
  margin: 0 0 .6rem;
  color: var(--vk-ink);
}

.vk-card p {
  color: var(--vk-muted);
  font-size: .91rem;
  line-height: 1.7;
  margin: 0;
}

.vk-highlight {
  background: var(--vk-soft);
  border: 1px solid var(--vk-line);
  border-radius: 17px;
  padding: 2rem;
  margin-top: 1.5rem;
}

.vk-highlight p {
  line-height: 1.8;
  color: var(--vk-muted);
}

.vk-footer-note {
  border-top: 1px solid var(--vk-line);
  padding: 1.5rem 0;
  margin-top: 3rem;
  color: var(--vk-muted);
  font-size: .85rem;
}

@media (max-width: 650px) {
  .vk-hero {
    grid-template-columns: minmax(0, 1fr) 100px;
    gap: 1rem;
    padding-top: 1rem;
  }

  .vk-photo {
    width: 100px;
    height: 125px;
    border-radius: 12px;
  }

  .vk-hero h1 { font-size: 2rem; }
  .vk-lead { font-size: 1rem; }
  .vk-grid { grid-template-columns: 1fr; }
  .vk-highlight { padding: 1.3rem; }
}

@media (prefers-reduced-motion: reduce) {
  .vk-wave span { animation: none; }
  .vk-card { transition: none; }
}
</style>

<div class="vk-page">

  <section class="vk-hero">
    <div>
      <div class="vk-eyebrow">
        Phonetics · Speech Science · Language
      </div>

      <h1>Hi, I'm Valentin!</h1>

      <p class="vk-lead">
        Welcome to my little corner of the academic world.
      </p>

      <p class="vk-description">
        I am a researcher and university instructor at
        Saarland University. My work revolves around spoken
        language, speech fluency, and the intersection of
        speech technology and education.
      </p>

      <p class="vk-description">
        Here you can explore my research, teaching activities,
        academic background, and the topics that spark my curiosity.
      </p>

      <div class="vk-links">
        <a class="vk-link primary" href="#research">My research</a>
        <a class="vk-link" href="#teaching">My teaching</a>
      </div>
    </div>

    <div>
      <img
        class="vk-photo"
        src="{{ '/images/profile-2026.jpg' | relative_url }}"
        alt="Portrait of Valentin Kany"
      >
    </div>
  </section>

  <div class="vk-wave" id="vk-wave" aria-hidden="true"></div>

  <section class="vk-section" id="research">
    <div class="vk-eyebrow">What I work on</div>
    <h2>Research &amp; Interests</h2>

    <p class="vk-section-intro">
      I am fascinated by how spoken language works,
      how it develops, and how technology can help us
      better understand it.
    </p>

    <div class="vk-grid">
      <div class="vk-card">
        <div class="vk-card-icon">🎙️</div>
        <h3>Speech Fluency</h3>
        <p>
          Investigating fluency and disfluency in spoken
          language, with a particular interest in children's speech.
        </p>
      </div>

      <div class="vk-card">
        <div class="vk-card-icon">📊</div>
        <h3>Speech Technology</h3>
        <p>
          Exploring computational methods for analysing
          speech and assessing aspects of spoken language.
        </p>
      </div>

      <div class="vk-card">
        <div class="vk-card-icon">🗣️</div>
        <h3>Phonetics &amp; Variation</h3>
        <p>
          Understanding speech sounds, pronunciation,
          dialectal variation, and the diversity of spoken language.
        </p>
      </div>

      <div class="vk-card">
        <div class="vk-card-icon">💡</div>
        <h3>Language &amp; Education</h3>
        <p>
          Connecting linguistic research with educational
          applications and accessible technological tools.
        </p>
      </div>
    </div>
  </section>

  <section class="vk-section">
    <div class="vk-eyebrow">A closer look</div>
    <h2>The WUSCHEL Project</h2>

    <div class="vk-highlight">
      <p>
        A major focus of my research has been the assessment
        of speech fluency in preschool children.
        Within the WUSCHEL project, I investigate how
        fluency can be described, evaluated, and
        computationally assessed.
      </p>
      <p>
        This work brings together phonetics, language
        development, human judgments, and speech technology.
      </p>
    </div>
  </section>

  <section class="vk-section" id="teaching">
    <div class="vk-eyebrow">Sharing knowledge</div>
    <h2>Teaching</h2>

    <p class="vk-section-intro">
      Alongside my research, teaching has been an important
      part of my academic work. I enjoy exploring linguistic
      questions with students and making complex ideas accessible.
    </p>

    <div class="vk-grid">
      <div class="vk-card">
        <div class="vk-card-icon">🔤</div>
        <h3>Phonetics &amp; Phonology</h3>
        <p>
          Introducing students to speech sounds,
          their production, perception, and linguistic functions.
        </p>
      </div>

      <div class="vk-card">
        <div class="vk-card-icon">📈</div>
        <h3>Statistics with R</h3>
        <p>
          Working with students on statistical reasoning,
          data analysis, and practical applications in R.
        </p>
      </div>

      <div class="vk-card">
        <div class="vk-card-icon">🎧</div>
        <h3>Speech Science</h3>
        <p>
          Exploring interdisciplinary perspectives on
          spoken language and speech communication.
        </p>
      </div>

      <div class="vk-card">
        <div class="vk-card-icon">🎓</div>
        <h3>Research &amp; Academic Practice</h3>
        <p>
          Supporting students in engaging with
          research questions, methods, and scientific discussion.
        </p>
      </div>
    </div>
  </section>

  <section class="vk-section">
    <div class="vk-eyebrow">Beyond the publications</div>
    <h2>A little more about me</h2>

    <p class="vk-section-intro">
      Beyond individual research topics, I enjoy
      exploring new ideas, connecting different fields,
      and finding creative ways to approach problems.
      This website is also a place for the projects
      and interests that emerge along the way.
    </p>
  </section>

  <div class="vk-footer-note">
    Thanks for stopping by!
  </div>

</div>

<script>
(function () {
  const wave = document.getElementById("vk-wave");
  if (!wave || wave.children.length) return;

  const count = 85;

  for (let i = 0; i < count; i++) {
    const bar = document.createElement("span");
    const position = i / (count - 1);
    const envelope = Math.pow(Math.sin(Math.PI * position), 1.5);
    const modulation = Math.abs(
      Math.sin(i * 0.48) * Math.cos(i * 0.17)
    );

    const height = 5 + 58 * envelope * (0.2 + 0.8 * modulation);

    bar.style.setProperty("--h", height + "px");
    bar.style.setProperty("--delay", (-i * 0.035) + "s");

    wave.appendChild(bar);
  }
})();
</script>
