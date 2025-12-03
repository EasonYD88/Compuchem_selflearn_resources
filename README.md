# Compuchem_selflearn_resources

<svg width="900" height="1100" xmlns="http://www.w3.org/2000/svg">

  <!-- Background -->
  <rect x="0" y="0" width="900" height="1100" fill="#f7f8fc"/>

  <!-- Title -->
  <text x="450" y="60" text-anchor="middle"
        font-size="30" font-weight="bold"
        fill="#26334f">
    Computational Chemistry
  </text>
  <text x="450" y="95" text-anchor="middle"
        font-size="22"
        fill="#4b5d80">
    Methods and Applications Overview
  </text>

  <!-- Methods section box -->
  <rect x="80" y="120" width="740" height="360" rx="30"
        fill="url(#gradMethods)" stroke="#3d7ea6" stroke-width="2"/>

  <!-- Methods header -->
  <text x="450" y="165" text-anchor="middle"
        font-size="24" font-weight="bold"
        fill="#1b3b5c">
    Core Methods / Theories
  </text>

  <!-- Methods bullets (two columns,紧凑填满方框) -->
  <!-- Left column -->
  <text x="120" y="210" font-size="18" fill="#0b2738">
    • Quantum chemistry (ab initio)
  </text>
  <text x="120" y="240" font-size="18" fill="#0b2738">
    • Density Functional Theory (DFT)
  </text>
  <text x="120" y="270" font-size="18" fill="#0b2738">
    • Semiempirical methods
  </text>
  <text x="120" y="300" font-size="18" fill="#0b2738">
    • Molecular mechanics (MM)
  </text>
  <text x="120" y="330" font-size="18" fill="#0b2738">
    • Molecular dynamics (MD)
  </text>
  <text x="120" y="360" font-size="18" fill="#0b2738">
    • Monte Carlo (MC)
  </text>
  <text x="120" y="390" font-size="18" fill="#0b2738">
    • Enhanced sampling / free energy
  </text>

  <!-- Right column -->
  <text x="480" y="210" font-size="18" fill="#0b2738">
    • QM/MM hybrid methods
  </text>
  <text x="480" y="240" font-size="18" fill="#0b2738">
    • Composite quantum chemistry
  </text>
  <text x="480" y="270" font-size="18" fill="#0b2738">
    • Machine-learning force fields
  </text>
  <text x="480" y="300" font-size="18" fill="#0b2738">
    • ML-accelerated electronic structure
  </text>
  <text x="480" y="330" font-size="18" fill="#0b2738">
    • Cheminformatics / QSAR / QSPR
  </text>
  <text x="480" y="360" font-size="18" fill="#0b2738">
    • Statistical mechanics &amp; models
  </text>
  <text x="480" y="390" font-size="18" fill="#0b2738">
    • Coarse-grained &amp; multiscale models
  </text>

  <!-- Downward connector arrow -->
  <line x1="450" y1="500" x2="450" y2="530"
        stroke="#555" stroke-width="3"
        marker-end="url(#arrowDown)"/>

  <!-- Applications section box -->
  <rect x="80" y="560" width="740" height="360" rx="30"
        fill="url(#gradApps)" stroke="#7a4ba8" stroke-width="2"/>

  <!-- Applications header -->
  <text x="450" y="605" text-anchor="middle"
        font-size="24" font-weight="bold"
        fill="#351c4c">
    Applications / Research Areas
  </text>

  <!-- Applications bullets (two columns,紧凑填满方框) -->

  <!-- Left column -->
  <text x="120" y="650" font-size="18" fill="#241233">
    • Drug design &amp; discovery
  </text>
  <text x="120" y="680" font-size="18" fill="#241233">
    • Protein–ligand binding &amp; docking
  </text>
  <text x="120" y="710" font-size="18" fill="#241233">
    • Enzyme catalysis mechanisms
  </text>
  <text x="120" y="740" font-size="18" fill="#241233">
    • Biomolecular simulations
  </text>
  <text x="120" y="770" font-size="18" fill="#241233">
    • Crystallography &amp; crystal engineering
  </text>
  <text x="120" y="800" font-size="18" fill="#241233">
    • Reaction pathways &amp; kinetics
  </text>

  <!-- Right column -->
  <text x="480" y="650" font-size="18" fill="#241233">
    • Materials &amp; solid-state chemistry
  </text>
  <text x="480" y="680" font-size="18" fill="#241233">
    • Catalysis &amp; surface chemistry
  </text>
  <text x="480" y="710" font-size="18" fill="#241233">
    • Nanomaterials &amp; polymers
  </text>
  <text x="480" y="740" font-size="18" fill="#241233">
    • Battery &amp; energy materials
  </text>
  <text x="480" y="770" font-size="18" fill="#241233">
    • Environmental &amp; atmospheric chemistry
  </text>
  <text x="480" y="800" font-size="18" fill="#241233">
    • High-throughput virtual screening
  </text>
  <text x="480" y="830" font-size="18" fill="#241233">
    • Data-driven &amp; AI-assisted discovery
  </text>

  <!-- Gradients and arrow marker definitions -->
  <defs>
    <!-- Methods gradient: teal-ish -->
    <linearGradient id="gradMethods" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#d7f1ff"/>
      <stop offset="100%" stop-color="#c1e4f5"/>
    </linearGradient>

    <!-- Applications gradient: light violet -->
    <linearGradient id="gradApps" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#f2e7ff"/>
      <stop offset="100%" stop-color="#e4d4ff"/>
    </linearGradient>

    <!-- Down arrow marker -->
    <marker id="arrowDown" markerWidth="10" markerHeight="10"
            refX="5" refY="5" orient="auto">
      <polygon points="0,0 10,5 0,10" fill="#555"/>
    </marker>
  </defs>

</svg>
