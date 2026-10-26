---
layout: single
permalink: /design-preview/
title: ""
author_profile: false
---

<style>
.vk-home {
  --ink: #253747;
  --muted: #617486;
  --accent: #2879a8;
  --line: #e3ebf0;
  --soft: #f5f9fc;

  max-width: 1050px;
  margin: 0 auto;
  color: var(--ink);
}

.vk-home * {
  box-sizing: border-box;
}

.vk-home a {
  text-decoration: none;
  color: var(--accent);
}

.vk-home a:hover {
  text-decoration: underline;
}

/* INTRODUCTION */

.vk-hero {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 165px;
  gap: 2.5rem;
  align-items: center;
  padding: 2.5rem 0 1rem;
}

.vk-eyebrow {
  color: var(--accent);
  font-size: .74rem;
  font-weight: 700;
  letter-spacing: .12em;
  text-transform: uppercase;
}

.vk-hero h1 {
  font-size: clamp(1.7rem, 3vw, 2.35rem);
  line-height: 1.15;
  margin: .6rem 0 1rem;
  color: var(--ink);
}

.vk-intro {
  font-size: 1.05rem;
  line-height: 1.8;
  margin: 0 0 1rem;
}

.vk-secondary {
  font-size: .95rem;
  line-height: 1.8;
  color: var(--muted);
  margin: 0 0 1rem;
}

.vk-portrait {
  width: 165px;
  height: 195px;
  object-fit: cover;
  object-position: 31% 35%;
  border-radius: 15px;
  box-shadow: 0 8px 26px rgba(30, 60, 80, .09);
}

/* AUDIO WAVE */

.vk-wave {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 3px;
  height: 58px;
  overflow: hidden;
  margin: 1.5rem 0 2.8rem;
  opacity: .7;
}

.vk-wave span {
  display: block;
  flex: 0 0 2.5px;
  height: var(--height);
  background: linear-gradient(#83bfdc, #2879a8);
  border-radius: 4px;
  animation: vk-breathe 2.8s ease-in-out infinite alternate;
  animation-delay: var(--delay);
}

@keyframes vk-breathe {
  from {
    transform: scaleY(.4);
    opacity: .5;
  }

  to {
    transform: scaleY(1);
    opacity: 1;
  }
}

/* SECTION LINKS */

.vk-section-label {
  font-size: .75rem;
  font-weight: 700;
  letter-spacing: .13em;
  text-transform: uppercase;
  color: var(--muted);
  margin-bottom: 1.2rem;
}

.vk-cards {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}

.vk-card {
  display: flex;
  flex-direction: column;
  border: 1px solid var(--line);
  border-radius: 15px;
  padding: 1.5rem;
  background: #fff;
  min-height: 205px;
  transition: transform .2s ease, box-shadow .2s ease;
}

.vk-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 28px rgba(30, 60, 80, .08);
  text-decoration: none;
}

.vk-card-icon {
  font-size: 1.5rem;
  margin-bottom: 1rem;
}

.vk-card h2 {
  font-size: 1.15rem;
  color: var(--ink);
  margin: 0 0 .6rem;
}

.vk-card p {
  color: var(--muted);
  font-size: .88rem;
  line-height: 1.65;
  margin: 0 0 1.1rem;
}

.vk-card-more {
  margin-top: auto;
  font-size: .82rem;
  font-weight: 700;
  color: var(--accent);
}

/* FOOTER */

.vk-end {
  margin-top: 3rem;
  padding: 1.3rem 0;
  border-top: 1px solid var(--line);
  font-size: .85rem;
  color: var(--muted);
}

/* RESPONSIVE */

@media (max-width: 720px) {
  .vk-cards {
    grid-template-columns: 1fr;
  }

  .vk-card {
    min-height: auto;
  }
}

@media (max-width: 540px) {
  .vk-hero {
    grid-template-columns: minmax(0, 1fr) 95px;
    gap: 1rem;
    padding-top: 1rem;
  }

  .vk-portrait {
    width: 95px;
    height: 120px;
    border-radius: 11px;
  }

  .vk-hero h1 {
    font-size: 1.65rem;
  }

  .vk-intro {
    font-size: .95rem;
  }

  .vk-wave {
    margin-bottom: 2rem;
  }
}

@media (prefers-reduced-motion: reduce) {
  .vk-wave span {
    animation: none;
  }

  .vk-card {
    transition: none;
  }
}
</style>

<div class="vk-home">

  <!-- INTRODUCTION -->

  <section class="vk-hero">
    <div>

      <div class="vk-eyebrow">
        Speech · Technology · Education
      </div>

      <h1>Hi, I'm Valentin!</h1>

      <p class="vk-intro">
        I am a research associate and PhD student in the
        <a
          href="https://www.coli.uni-saarland.de/groups/FK/speech_science/index.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          Speech Science group
        </a>
        and the group for
        <a
          href="https://www.uni-saarland.de/lehrstuhl/haberzettl.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          German as a foreign/second language
        </a>
        at Saarland University.
      </p>

      <p class="vk-secondary">
        My research focuses on speech fluency in preschool children,
        particularly its analysis and automatic assessment as part
        of the
        <a
          href="https://www.uni-saarland.de/lehrstuhl/haberzettl/projekte/sprachliche-bildung-in-kita.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          WUSCHEL project
        </a>.
        My broader interests include speech and language
        technologies in education, dialectal variation,
        and sound symbolism.
      </p>

      <p class="vk-secondary">
        On this website, you can find information about
        my research projects, publications, talks,
        and teaching activities.
      </p>

    </div>

    <div>
      <img
        class="vk-portrait"
        src="{{ '/images/profile-2026.jpg' | relative_url }}"
        alt="Portrait of Valentin Kany"
      >
    </div>

  </section>

  <!-- ANIMATED SPEECH WAVE -->

  <div
    class="vk-wave"
    id="vk-wave"
    aria-hidden="true">
  </div>

  <!-- MAIN AREAS -->

  <section>

    <div class="vk-section-label">
      Explore my work
    </div>

    <div class="vk-cards">

      <!-- RESEARCH -->

      <a class="vk-card" href="{{ '/research/' | relative_url }}">

        <div class="vk-card-icon">🎙️</div>

        <h2>Research &amp; Projects</h2>

        <p>
          An overview of my research interests,
          projects, and the questions behind my work.
        </p>

        <span class="vk-card-more">
          Explore research →
        </span>

      </a>

      <!-- TEACHING -->

      <a class="vk-card" href="{{ '/teaching/' | relative_url }}">

        <div class="vk-card-icon">🎓</div>

        <h2>Teaching</h2>

        <p>
          An overview of the courses I have taught
          and my experience in university teaching.
        </p>

        <span class="vk-card-more">
          Explore teaching →
        </span>

      </a>

      <!-- PUBLICATIONS -->

      <a class="vk-card" href="{{ '/publications/' | relative_url }}">

        <div class="vk-card-icon">📚</div>

        <h2>Publications &amp; Talks</h2>

        <p>
          A collection of my scientific publications,
          conference contributions, and presentations.
        </p>

        <span class="vk-card-more">
          View publications →
        </span>

      </a>

    </div>

  </section>

  <!-- FOOTER -->

  <div class="vk-end">
    Thanks for stopping by!
  </div>

</div>

<script>
(function () {
  const wave = document.getElementById("vk-wave");

  if (!wave || wave.children.length) {
    return;
  }

  const count = 85;

  for (let i = 0; i < count; i++) {
    const bar = document.createElement("span");
    const position = i / (count - 1);

    const envelope = Math.pow(
      Math.sin(Math.PI * position),
      1.5
    );

    const modulation = Math.abs(
      Math.sin(i * 0.48) *
      Math.cos(i * 0.17)
    );

    const height =
      4 + 45 * envelope * (0.2 + 0.8 * modulation);

    bar.style.setProperty(
      "--height",
      height + "px"
    );

    bar.style.setProperty(
      "--delay",
      (-i * 0.035) + "s"
    );

    wave.appendChild(bar);
  }
})();
</script>
