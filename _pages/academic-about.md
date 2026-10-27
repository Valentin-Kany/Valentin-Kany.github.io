---
layout: single
permalink: /about/
title: ""
author_profile: false
---

<style>
.vk-about {
  --ink: #253747;
  --muted: #617486;
  --accent: #2879a8;
  --line: #e3ebf0;
  --soft: #f5f9fc;
  max-width: 1050px;
  margin: 0 auto;
  color: var(--ink);
}
.vk-about * { box-sizing: border-box; }
.vk-about a { color: var(--accent); text-decoration: none; }
.vk-about a:hover { text-decoration: underline; }
.vka-header {
  padding: 2rem 0 2.5rem;
  border-bottom: 1px solid var(--line);
  margin-bottom: 2.5rem;
}
.vka-eyebrow {
  color: var(--accent);
  font-size: .74rem;
  font-weight: 700;
  letter-spacing: .12em;
  text-transform: uppercase;
  margin-bottom: .7rem;
}
.vka-header h1 {
  color: var(--ink);
  font-size: clamp(1.9rem, 3vw, 2.5rem);
  line-height: 1.2;
  margin: 0 0 1rem;
}
.vka-lead {
  color: var(--muted);
  font-size: 1rem;
  line-height: 1.8;
  max-width: 800px;
  margin: 0;
}
.vka-section-title {
  color: var(--ink);
  font-size: 1.4rem;
  margin: 0 0 1.7rem;
}
.vka-timeline { position: relative; margin: 0 0 3.5rem; }
.vka-timeline::before {
  content: "";
  position: absolute;
  left: 51px;
  top: 17px;
  bottom: 17px;
  width: 2px;
  background: var(--line);
}
.vka-item {
  position: relative;
  display: grid;
  grid-template-columns: 102px minmax(0, 1fr);
  gap: 1.3rem;
  padding: 0 0 1.6rem;
}
.vka-item:last-child { padding-bottom: 0; }
.vka-date {
  position: relative;
  z-index: 1;
  align-self: start;
  padding: .5rem .35rem;
  border: 1px solid var(--line);
  border-radius: 8px;
  background: var(--soft);
  color: var(--accent);
  font-size: .9rem;
  font-weight: 700;
  text-align: center;
}
.vka-content {
  padding: .1rem 0 1.4rem;
  border-bottom: 1px solid var(--line);
}
.vka-item:last-child .vka-content { border-bottom: none; }
.vka-content h3 {
  color: var(--ink);
  font-size: 1.07rem;
  line-height: 1.5;
  margin: 0 0 .3rem;
}
.vka-content p {
  color: var(--muted);
  font-size: .9rem;
  line-height: 1.7;
  margin: 0;
}
.vka-original { margin-top: .35rem !important; font-size: .83rem !important; }
.vka-footer {
  border-top: 1px solid var(--line);
  padding: 1.4rem 0;
  font-size: .85rem;
}
@media (max-width: 720px) {
  .vka-header { padding-top: 1rem; }
  .vka-timeline::before { left: 39px; }
  .vka-item { grid-template-columns: 78px minmax(0, 1fr); gap: .9rem; }
  .vka-date { font-size: .82rem; }
  .vka-content h3 { font-size: 1rem; }
}
</style>

<div class="vk-about">

  <header class="vka-header">
    <div class="vka-eyebrow">Speech · Technology · Education</div>
    <h1>About</h1>
    <p class="vka-lead">
      A brief overview of my educational and academic background.
    </p>
  </header>

  <section aria-labelledby="vka-background-heading">
    <h2 class="vka-section-title" id="vka-background-heading">
      Academic &amp; Professional Background
    </h2>

    <div class="vka-timeline">

      <div class="vka-item">
        <div class="vka-date">2016</div>
        <div class="vka-content">
          <h3>State-Certified Business IT Specialist</h3>
          <p class="vka-original">Staatlich geprüfter Wirtschaftsinformatiker</p>
          <p class="vka-original">Höhere Berufsfachschule für Wirtschaftsinformatik Saarbrücken</p>
        </div>
      </div>

      <div class="vka-item">
        <div class="vka-date">2019</div>
        <div class="vka-content">
          <h3>B.A. in Language Science</h3>
          <p>Saarland University</p>
        </div>
      </div>

      <div class="vka-item">
        <div class="vka-date">2021</div>
        <div class="vka-content">
          <h3>M.Sc. in Language Science and Technology</h3>
          <p>Saarland University</p>
        </div>
      </div>

      <div class="vka-item">
        <div class="vka-date">2026</div>
        <div class="vka-content">
          <h3>Doctoral Dissertation Submitted</h3>
          <p>Saarland University · September 2026</p>
        </div>
      </div>

    </div>
  </section>

  <footer class="vka-footer">
    <a href="{{ '/' | relative_url }}">← Back to homepage</a>
  </footer>

</div>
