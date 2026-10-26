---
layout: single
permalink: /research-preview/
title: ""
author_profile: false
---

<style>
.vk-research {
  --ink: #253747;
  --muted: #617486;
  --accent: #2879a8;
  --line: #e3ebf0;
  --soft: #f5f9fc;

  max-width: 1050px;
  margin: 0 auto;
  color: var(--ink);
}

.vk-research * {
  box-sizing: border-box;
}

.vk-research a {
  color: var(--accent);
  text-decoration: none;
}

.vk-research a:hover {
  text-decoration: underline;
}

/* PAGE HEADER */

.vkr-header {
  padding: 2rem 0 2.5rem;
  border-bottom: 1px solid var(--line);
  margin-bottom: 2.5rem;
}

.vkr-eyebrow {
  color: var(--accent);
  font-size: .74rem;
  font-weight: 700;
  letter-spacing: .12em;
  text-transform: uppercase;
  margin-bottom: .7rem;
}

.vkr-header h1 {
  color: var(--ink);
  font-size: clamp(1.9rem, 3vw, 2.5rem);
  line-height: 1.2;
  margin: 0 0 1rem;
}

.vkr-lead {
  color: var(--muted);
  font-size: 1rem;
  line-height: 1.8;
  max-width: 800px;
  margin: 0;
}

/* SECTIONS */

.vkr-section {
  margin-bottom: 3.2rem;
}

.vkr-section-title {
  font-size: 1.4rem;
  color: var(--ink);
  margin: 0 0 1.2rem;
}

.vkr-section-intro {
  color: var(--muted);
  font-size: .95rem;
  line-height: 1.8;
  margin: 0 0 1.4rem;
}

/* PROJECT CARDS */

.vkr-card {
  border: 1px solid var(--line);
  border-radius: 16px;
  padding: 1.8rem;
  background: #fff;
}

.vkr-featured {
  background: var(--soft);
  border-color: #d9e7f0;
}

.vkr-card-label {
  color: var(--accent);
  font-size: .72rem;
  font-weight: 700;
  letter-spacing: .1em;
  text-transform: uppercase;
  margin-bottom: .7rem;
}

.vkr-card h3 {
  color: var(--ink);
  font-size: 1.2rem;
  line-height: 1.4;
  margin: 0 0 1rem;
}

.vkr-card p {
  color: var(--muted);
  font-size: .92rem;
  line-height: 1.8;
  margin: 0 0 1rem;
}

.vkr-card p:last-child {
  margin-bottom: 0;
}

.vkr-meta {
  display: inline-block;
  color: var(--muted);
  font-size: .8rem;
  margin: 0 0 1.2rem;
}

.vkr-link {
  display: inline-block;
  font-size: .85rem;
  font-weight: 700;
  margin-top: .3rem;
}

/* CONNECTION BETWEEN PHD AND WUSCHEL */

.vkr-connection {
  display: flex;
  align-items: center;
  gap: .8rem;
  padding: 1.2rem 1.8rem;
  color: var(--muted);
  font-size: .84rem;
  line-height: 1.6;
}

.vkr-connection-icon {
  color: var(--accent);
  font-size: 1.4rem;
}

/* SOUND SYMBOLISM GRID */

.vkr-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}

.vkr-grid .vkr-card {
  height: 100%;
}

/* FOOTER */

.vkr-end {
  border-top: 1px solid var(--line);
  padding: 1.4rem 0;
  color: var(--muted);
  font-size: .85rem;
}

/* MOBILE */

@media (max-width: 720px) {
  .vkr-grid {
    grid-template-columns: 1fr;
  }

  .vkr-card {
    padding: 1.3rem;
  }

  .vkr-header {
    padding-top: 1rem;
  }

  .vkr-connection {
    padding: 1rem;
  }
}
</style>

<div class="vk-research">

  <!-- HEADER -->

  <header class="vkr-header">

    <div class="vkr-eyebrow">
      Speech · Technology · Education
    </div>

    <h1>Research &amp; Projects</h1>

    <p class="vkr-lead">
      My research interests lie in the fields of speech science
      and speech and language technology.
      Much of my recent work has focused on speech fluency
      in preschool children, combining phonetic analysis,
      human judgments, and computational methods.
    </p>

  </header>

  <!-- DOCTORAL RESEARCH -->

  <section class="vkr-section">

    <h2 class="vkr-section-title">
      Doctoral Research
    </h2>

    <div class="vkr-card vkr-featured">

      <div class="vkr-card-label">
        PhD Dissertation
      </div>

      <h3>
        Automatic Assessment of Speech Fluency
        in Preschool Children
      </h3>

      <div class="vkr-meta">
        Doctoral dissertation submitted in September 2026
      </div>

      <p>
        My doctoral research investigates how speech fluency
        in preschool children can be assessed using
        computational methods.
      </p>

      <p>
        The work combines analyses of children's speech
        with human fluency judgments and automatic approaches
        to disfluency detection and fluency assessment.
        It examines how these different sources of information
        can be used to develop and evaluate computational
        methods for assessing children's speech fluency.
      </p>

      <p>
        This research was conducted in the context of
        the WUSCHEL project at Saarland University.
      </p>

    </div>

    <div class="vkr-connection">
      <span class="vkr-connection-icon">↳</span>
      <span>
        My doctoral research forms part of the broader
        WUSCHEL research project.
      </span>
    </div>

    <!-- WUSCHEL -->

    <div class="vkr-card">

      <div class="vkr-card-label">
        Research Project
      </div>

      <h3>
        WUSCHEL – Language Assessment in
        Early Childhood Education
      </h3>

      <p>
        WUSCHEL is a research project concerned with
        the semi-automatic assessment of language
        proficiency in preschool children.
      </p>

      <p>
        As part of the project, I have worked on the
        analysis and assessment of speech fluency,
        investigating how properties of children's
        spoken language can be evaluated using both
        human judgments and computational methods.
      </p>

      <a
        class="vkr-link"
        href="https://wuschel-app.de/"
        target="_blank"
        rel="noopener noreferrer"
      >
        WUSCHEL website →
      </a>

    </div>

  </section>

  <!-- SOUND SYMBOLISM -->

  <section class="vkr-section">

    <h2 class="vkr-section-title">
      Sound Symbolism
    </h2>

    <p class="vkr-section-intro">
      Another area of my research interests is sound
      symbolism: the relationship between speech sounds
      and the meanings or associations they evoke.
      I explored this topic in two research projects
      during my studies.
    </p>

    <div class="vkr-grid">

      <!-- MASTER'S THESIS -->

      <div class="vkr-card">

        <div class="vkr-card-label">
          Master's Thesis · 2021
        </div>

        <h3>
          A Computational Model to Replicate
          Human Sound Symbolic Associations
        </h3>

        <p>
          In my master's thesis, I developed a
          computational approach to generating
          artificial words based on the visual
          characteristics of geometric shapes.
        </p>

        <p>
          The model combines automatic shape
          recognition with a word-generation
          algorithm informed by sound-symbolic
          associations. Its output was evaluated
          through experimental studies.
        </p>

      </div>

      <!-- POKEMON STUDY -->

      <div class="vkr-card">

        <div class="vkr-card-label">
          Laboratory Phonology · Course Paper
        </div>

        <h3>
          Sound Symbolism in Pokémon Names
        </h3>

        <p>
          In an experimental study, I investigated
          how German speakers associate speech
          sounds with the size and weight of Pokémon.
        </p>

        <p>
          Participants selected between artificially
          constructed names for different Pokémon.
          The results showed systematic preferences
          for particular consonants and vowels
          depending on the creatures' size.
        </p>

      </div>

    </div>

  </section>

  <!-- OTHER INTERESTS -->

  <section class="vkr-section">

    <h2 class="vkr-section-title">
      Further Research Interests
    </h2>

    <p class="vkr-section-intro">
      Beyond these projects, I am also interested in
      dialectal variation, particularly regional
      varieties of German.
    </p>

  </section>

  <!-- FOOTER -->

  <div class="vkr-end">
    <a href="{{ '/design-preview/' | relative_url }}">
      ← Back to homepage preview
    </a>
  </div>

</div>
