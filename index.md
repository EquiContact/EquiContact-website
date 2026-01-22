---
layout: none
---

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>EquiContact</title>
  <link rel="stylesheet" href="assets/css/style.css" />
</head>

<body>
  <div class="container">

    <div class="hero">
      <div class="hero-left">
        <h1>EquiContact</h1>
        <p class="subtitle">Hierarchical SE(3) Vision-to-Force Equivariant Policy for Contact-Rich Tasks</p>

        <p class="authors">
          <b>Joohwan Seo</b>, Coauthor A, Coauthor B, …
        </p>
        <p class="affil">UC Berkeley • Horowitz Lab</p>

        <div class="badges">
          <a class="badge" href="[PDF]">Paper (PDF)</a>
          <a class="badge" href="[arXiv]">arXiv</a>
          <a class="badge" href="[supp]">Supplementary</a>
          <a class="badge" href="[code]">Code</a>
          <a class="badge" href="[data]">Data</a>
        </div>

        <div class="section">
          <h2>TL;DR</h2>
          <p>
            We present <b>EquiContact</b>, a hierarchical policy that is <b>SE(3)-equivariant</b> and outputs
            force/impedance-relevant actions for contact-rich manipulation. Our key contribution is
            <b>G-CompACT</b>: a geometry-consistent composition mechanism that improves robustness under
            large pose changes.
          </p>
        </div>

        <div class="section">
          <h2>Abstract</h2>
          <p>
            [Paste your abstract here.]
          </p>
        </div>
      </div>

      <div class="hero-right">
        <div class="video">
          <!-- Self-hosted teaser (recommended) -->
          <video controls playsinline poster="assets/imgs/teaser.jpg">
            <source src="assets/videos/teaser.mp4" type="video/mp4" />
          </video>
        </div>
        <p class="small" style="margin-top:10px;">
          Teaser video. (If you prefer YouTube/Vimeo, replace the &lt;video&gt; block with an iframe embed.)
        </p>
      </div>
    </div>

    <div class="section">
      <h2>Method</h2>

      <div class="grid">
        <div class="card">
          <h3>Equivariant perception → action</h3>
          <p class="small">
            Describe the vision backbone and how you form SE(3)-equivariant features (1–2 sentences).
          </p>
        </div>

        <div class="card">
          <h3><b>G-CompACT</b> (main contribution)</h3>
          <p class="small">
            Explain the group-consistent composition / conditioning and why it matters for extreme transformations.
          </p>
        </div>

        <div class="card">
          <h3>Pose estimator (replaceable)</h3>
          <p class="small">
            Mention Diff-EDF (or others) as a swappable module so the page emphasizes G-CompACT.
          </p>
        </div>
      </div>

      <div style="height:14px;"></div>

      <div class="figure">
        <img src="assets/imgs/pipeline.png" alt="Pipeline figure" />
      </div>
      <p class="small">
        Figure: Overview of EquiContact with emphasis on G-CompACT. (Replace with your final main figure.)
      </p>
    </div>

    <div class="section">
      <h2>Results (Videos)</h2>

      <div class="grid">
        <div class="card">
          <h3>Extreme transformation generalization</h3>
          <div class="video" style="margin-top:10px;">
            <video controls playsinline>
              <source src="assets/videos/exp1.mp4" type="video/mp4" />
            </video>
          </div>
          <p class="small" style="margin-top:10px;">
            One-liner describing the setup + what’s impressive.
          </p>
        </div>

        <div class="card">
          <h3>Task B (contact-rich)</h3>
          <div class="video" style="margin-top:10px;">
            <video controls playsinline>
              <source src="assets/videos/exp2.mp4" type="video/mp4" />
            </video>
          </div>
          <p class="small" style="margin-top:10px;">
            Compare against baseline / ablations succinctly.
          </p>
        </div>

        <div class="card">
          <h3>Ablation: w/o G-CompACT</h3>
          <div class="video" style="margin-top:10px;">
            <video controls playsinline>
              <source src="assets/videos/ablation_gcompact.mp4" type="video/mp4" />
            </video>
          </div>
          <p class="small" style="margin-top:10px;">
            Highlight failure modes (drift, wrong contact, instability, etc.).
          </p>
        </div>
      </div>

      <p class="small" style="margin-top:12px;">
        Tip: keep clips 10–30 seconds and show only 3–8 best ones.
      </p>
    </div>

    <div class="section">
      <h2>Citation</h2>
      <p class="small">If you find this useful, please cite:</p>
      <pre><code>@inproceedings{equicontact2026,
  title     = {EquiContact: Hierarchical SE(3) Vision-to-Force Equivariant Policy for Contact-Rich Tasks},
  author    = {Seo, Joohwan and ...},
  booktitle = {Robotics: Science and Systems (RSS)},
  year      = {2026}
}</code></pre>
    </div>

    <div class="section">
      <h2>Links</h2>
      <ul>
        <li><b>Paper:</b> <a href="[PDF]">PDF</a> • <a href="[arXiv]">arXiv</a> • <a href="[supp]">Supplementary</a></li>
        <li><b>Code:</b> <a href="[code]">GitHub repo</a></li>
        <li><b>Dataset:</b> <a href="[data]">Download</a></li>
        <li><b>Contact:</b> your-email [at] berkeley.edu</li>
      </ul>
    </div>

    <div class="footer">
      Last updated: 2026-01-15.
    </div>

  </div>
</body>
</html>
