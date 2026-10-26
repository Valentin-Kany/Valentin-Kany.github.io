---
layout: single
permalink: /design-preview/
title: ""
author_profile: false
---

<style>
.vk-home {
  --vk-blue: #2563eb;
  --vk-ink: #18253b;
  --vk-muted: #596779;
  --vk-border: #e2e8f0;
  font-family: inherit;
}

.vk-hero {
  padding: 3.5rem 2rem;
  border-radius: 22px;
  background: linear-gradient(125deg, #eff6ff, #ffffff 65%, #e0f2fe);
  position: relative;
  overflow: hidden;
}

.vk-eyebrow {
  color: var(--vk-blue);
  font-size: .8rem;
  font-weight: 700;
  letter-spacing: .12em;
  text-transform: uppercase;
}

.vk-hero h1 {
  color: var(--vk-ink);
  font-size: clamp(2.2rem, 5vw, 3.8rem);
  line-height: 1.12;
  margin: 1rem 0;
}

.vk-hero p {
  color: var(--vk-muted);
  font-size: 1.05rem;
  max-width: 38rem;
}

.vk-actions {
  display: flex;
  flex-wrap: wrap;
  gap: .75rem;
  margin-top: 1.5rem;
}

.vk-button {
  display: inline-block;
  padding: .8rem 1.2rem;
  border-radius: 10px;
  font-weight: 600;
  text-decoration: none !important;
}

.vk-primary {
  background: var(--vk-blue);
  color: white !important;
}

.vk-secondary {
  border: 1px solid #bfdbfe;
  color: var(--vk-ink) !important;
  background: white;
}

.vk-wave {
  display: flex;
  align-items: center;
  gap: 5px;
  height: 75px;
  margin-top: 2rem;
}

.vk-wave span {
  display: block;
  width: 5px;
  height: 16px;
  border-radius: 5px;
  background: #60a5fa;
  animation: vk-pulse 1.2s ease-in-out infinite alternate;
}

.vk-wave span:nth-child(3n) {
  animation-delay: -.4s;
}
.vk-wave span:nth-child(4n) {
  animation-delay: -.8s;
}
.vk-wave span:nth-child(5n) {
  animation-delay: -.2s;
}

@keyframes vk-pulse {
  from { height: 8px; opacity: .45; }
  to { height: 65px; opacity: 1; }
}

.vk-section {
  margin: 3rem 0;
}

.vk-section h2 {
  color: var(--vk-ink);
  font-size: 1.6rem;
  margin-bottom: 1.2rem;
}

.vk-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}

.vk-card {
  padding: 1.5rem;
  border: 1px solid var(--vk-border);
  border-radius: 16px;
  background: white;
  transition: transform .2s, box-shadow .2s;
}

.vk-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 30px rgba(20, 40, 70, .08);
}

.vk-card h3 {
  color: var(--vk-ink);
  margin: .5rem 0;
  font-size: 1.05rem;
}

.vk-card p {
  color: var(--vk-muted);
  font-size: .9rem;
  margin-bottom: 0;
}

@media (max-width: 650px) {
  .vk-hero { padding: 2rem 1.2rem; }
  .vk-grid { grid-template-columns: 1fr; }
}

@media (prefers-reduced-motion: reduce) {
  .vk-wave span { animation: none; }
  .vk-card { transition: none; }
}
</style>

<div class="vk-home">

  <section class="vk-hero">
    <div class="vk-eyebrow">Speech Science · Phonetics · Education</div>

    <h1>Hi, I'm Valentin! 👋</h1>

    <p>
      I am a researcher at Saarland University, exploring
      how we speak, how speech fluency develops, and how
      technology can support language assessment and education.
    </p>

    <div class="vk-actions">
      <a class="vk-button vk-primary" href="/publications/">
        Explore my research
      </a>
      <a class="vk-button vk-secondary" href="/teaching/">
        My teaching
      </a>
    </div>

    <div class="vk-wave" aria-hidden="true">
      <span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span>
      <span></span><span></span><span></span><span></span>
    </div>
  </section>

  <section class="vk-section">
    <h2>About my work</h2>

    <p>
      I work in the Phonetics group and the German as a
      foreign/second language group at Saarland University.
      As part of the
      <a href="https://www.uni-saarland.de/lehrstuhl/haberzettl/projekte/sprachliche-bildung-in-kita.html">
        WUSCHEL project
      </a>,
      I investigate approaches to assessing the language
      proficiency of preschool children.
    </p>
  </section>

  <section class="vk-section">
    <h2>Research interests</h2>

    <div class="vk-grid">

      <div class="vk-card">
        <div>🎙️</div>
        <h3>Speech Disfluencies</h3>
        <p>Understanding fluency and disfluency in spoken language.</p>
      </div>

      <div class="vk-card">
        <div>💻</div>
        <h3>Speech Technology</h3>
        <p>Exploring computational approaches to speech assessment.</p>
      </div>

      <div class="vk-card">
        <div>🗣️</div>
        <h3>Dialectal Variation</h3>
        <p>Investigating variation in spoken language.</p>
      </div>

      <div class="vk-card">
        <div>✨</div>
        <h3>Sound Symbolism</h3>
        <p>Exploring connections between speech sounds and meaning.</p>
      </div>

    </div>
  </section>

</div>
