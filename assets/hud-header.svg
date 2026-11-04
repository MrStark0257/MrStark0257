<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 850 240" width="100%" height="240">
  <defs>
    <!-- Soft, Controlled Cyan Neon Glow (Not Overexposed) -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="1.8" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <filter id="subtle-glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="1" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <filter id="soft-text-shadow" x="-10%" y="-10%" width="120%" height="120%">
      <feDropShadow dx="0" dy="0" stdDeviation="2" flood-color="#00f2fe" flood-opacity="0.4" />
    </filter>

    <!-- Background Radial Gradient -->
    <radialGradient id="bgGradient" cx="50%" cy="50%" r="70%">
      <stop offset="0%" stop-color="#002238" stop-opacity="0.75" />
      <stop offset="60%" stop-color="#091420" stop-opacity="0.95" />
      <stop offset="100%" stop-color="#0d1117" stop-opacity="1" />
    </radialGradient>

    <!-- Cyan Divider Gradient -->
    <linearGradient id="cyanLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00f2fe" stop-opacity="0" />
      <stop offset="25%" stop-color="#00f2fe" stop-opacity="0.7" />
      <stop offset="50%" stop-color="#38bdf8" stop-opacity="0.9" />
      <stop offset="75%" stop-color="#00f2fe" stop-opacity="0.7" />
      <stop offset="100%" stop-color="#00f2fe" stop-opacity="0" />
    </linearGradient>

    <!-- Crisp Name Text Gradient -->
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" />
      <stop offset="60%" stop-color="#e0f7fe" />
      <stop offset="100%" stop-color="#38bdf8" />
    </linearGradient>
  </defs>

  <!-- Background Base -->
  <rect width="850" height="240" rx="12" fill="url(#bgGradient)" stroke="#004466" stroke-width="1.2" />

  <!-- Outer HUD Grid & Corner Accents -->
  <g stroke="#00f2fe" stroke-width="1.8" fill="none" opacity="0.7" filter="url(#subtle-glow)">
    <!-- Top-Left Bracket -->
    <path d="M 20 40 L 20 20 L 40 20" />
    <circle cx="20" cy="20" r="2.5" fill="#00f2fe" />
    <!-- Top-Right Bracket -->
    <path d="M 830 40 L 830 20 L 810 20" />
    <circle cx="830" cy="20" r="2.5" fill="#00f2fe" />
    <!-- Bottom-Left Bracket -->
    <path d="M 20 200 L 20 220 L 40 220" />
    <circle cx="20" cy="220" r="2.5" fill="#00f2fe" />
    <!-- Bottom-Right Bracket -->
    <path d="M 830 200 L 830 220 L 810 220" />
    <circle cx="830" cy="220" r="2.5" fill="#00f2fe" />
  </g>

  <!-- Telemetry Side Metadata (Left) -->
  <g fill="#38bdf8" font-family="'Segoe UI', Roboto, monospace" font-size="9" letter-spacing="1.5" opacity="0.7">
    <text x="35" y="45">SYS.DIAG // ACTIVE</text>
    <text x="35" y="62">HUD.REV // 4.2.0</text>
    <text x="35" y="79">NODE // AHMEDABAD</text>
    <rect x="35" y="90" width="45" height="1.2" fill="#00f2fe" opacity="0.3" />
    <text x="35" y="105">PWR: 100%</text>
  </g>

  <!-- Telemetry Side Metadata (Right) -->
  <g fill="#38bdf8" font-family="'Segoe UI', Roboto, monospace" font-size="9" letter-spacing="1.5" text-anchor="end" opacity="0.7">
    <text x="815" y="45">PROTOCOL // J.A.R.V.I.S.</text>
    <text x="815" y="62">SECURITY // LEVEL 7</text>
    <text x="815" y="79">CALLSIGN // MrStark0257</text>
    <rect x="770" y="90" width="45" height="1.2" fill="#00f2fe" opacity="0.3" />
    <text x="815" y="105">NET // SECURE</text>
  </g>

  <!-- Center Animated Arc Reactor Core -->
  <g transform="translate(425, 68)">
    <!-- Rotating Ring 1 (Clockwise) -->
    <circle cx="0" cy="0" r="38" fill="none" stroke="#00f2fe" stroke-width="1.2" stroke-dasharray="6, 5" opacity="0.5">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="20s" repeatCount="indefinite" />
    </circle>
    <!-- Rotating Segmented Ring 2 (Counter-Clockwise) -->
    <circle cx="0" cy="0" r="30" fill="none" stroke="#38bdf8" stroke-width="1.8" stroke-dasharray="16, 8" opacity="0.7">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="12s" repeatCount="indefinite" />
    </circle>
    <!-- Triangle Core Bracket -->
    <polygon points="0,-18 16,10 -16,10" fill="none" stroke="#00f2fe" stroke-width="1.6" filter="url(#subtle-glow)">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="8s" repeatCount="indefinite" />
    </polygon>
    <!-- Center Point with Controlled Pulse -->
    <circle cx="0" cy="0" r="6.5" fill="#00f2fe" filter="url(#subtle-glow)">
      <animate attributeName="r" values="5.5;7.5;5.5" dur="2.5s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.7;0.95;0.7" dur="2.5s" repeatCount="indefinite" />
    </circle>
    <circle cx="0" cy="0" r="2.5" fill="#ffffff" />
  </g>

  <!-- Divider Line Top -->
  <line x1="80" y1="125" x2="770" y2="125" stroke="url(#cyanLine)" stroke-width="1.2" opacity="0.7" />

  <!-- Main User Name (MEET PAVAGADHI) - Crisp, Clean & Controlled Glow -->
  <text x="425" y="162" text-anchor="middle" font-family="'Segoe UI', Roboto, 'Helvetica Neue', sans-serif" font-weight="800" font-size="32" letter-spacing="7" fill="url(#textGrad)" filter="url(#soft-text-shadow)">
    MEET PAVAGADHI
  </text>

  <!-- Role Subtitle - Crisp, Legible & Unblurred -->
  <text x="425" y="190" text-anchor="middle" font-family="'Segoe UI', Roboto, monospace" font-weight="600" font-size="12.5" letter-spacing="4" fill="#38bdf8" opacity="0.85">
    UI/UX ARCHITECT  •  FRONTEND DEVELOPER
  </text>

  <!-- Bottom Divider Accent -->
  <line x1="180" y1="208" x2="670" y2="208" stroke="url(#cyanLine)" stroke-width="1" opacity="0.5" />
  <circle cx="425" cy="208" r="2.5" fill="#00f2fe" opacity="0.8" />
</svg>
