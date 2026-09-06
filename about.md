---
layout: default
title: Project
---
<div class="page">
  <header class="page-header">
    <h1>About the project</h1>
    <p>An attempt at a 20&nbsp;GHz vector network analyzer.</p>
  </header>

  <div class="page-body">

    <h2>The idea</h2>
    <p>
      A vector network analyzer is an instrument that measures how much of a microwave signal is
      reflected from a device (return loss / S11) and how much passes through it (insertion loss / S21),
      including the phase relationships. Commercial units covering tens of gigahertz cost a small fortune.
      This project is an attempt to build a usable VNA that reaches up to 20&nbsp;GHz on a reasonable hobby budget,
      and to document every step so others can build on the work.
    </p>

    <h2>Current status</h2>
    <p>
      The project is at an early stage and there is no finished product yet — this is part of the journey.
      Hardware is being designed and breadboard prototypes tested, one block at a time:
    </p>
    <ul>
      <li>Signal source and broadband generation up to 20&nbsp;GHz</li>
      <li>Directional couplers / bridges for reflection measurements</li>
      <li>Down-conversion and sampling architecture</li>
      <li>Calibration routines (SOLT-style) and user software</li>
    </ul>

    <h2>What will be published here</h2>
    <ul>
      <li><strong>Progress updates</strong> — short posts describing what was done, tested and learned</li>
      <li><strong>Photos</strong> — build pictures from the workbench</li>
      <li><strong>Measurement data</strong> — S-parameter plots together with the raw <strong>CSV files</strong>,
        so anyone can re-plot or analyse the numbers themselves</li>
      <li><strong>Build notes</strong> — documentation of design decisions and experiments as they happen</li>
    </ul>

    <h2 id="updates">Updates policy</h2>
    <p>
      This website is maintained alongside the project and <strong>will be updated</strong> as progress happens.
      If nothing has changed for a while, it simply means the bench work is taking longer than the writing.
      New measurements and files will appear in the <a href="{{ '/blog' | relative_url }}">Updates</a> section.
    </p>

    <h2>Source</h2>
    <p>
      The repository for this site lives on GitHub:
      <a href="https://github.com/patryksi11/20ghz-vna-blog" target="_blank" rel="noopener">patryksi11/20ghz-vna-blog</a>.
    </p>

    <h2>Contact</h2>
    <p>
      Comment on the Reddit thread, or reach out via the <a href="{{ '/contact' | relative_url }}">Contact</a> page —
      questions, ideas and criticism are welcome.
    </p>
  </div>
</div>