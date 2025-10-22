<svg xmlns="http://www.w3.org/2000/svg" width="1280" height="320" viewBox="0 0 1280 320" role="img" aria-label="Stylized onion illustration">
  <defs>
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0" stop-color="#7b2ff7"/>
      <stop offset="1" stop-color="#2ec6ff"/>
    </linearGradient>
    <filter id="s" x="-50%" y="-50%" width="200%" height="200%">
      <feDropShadow dx="0" dy="8" stdDeviation="18" flood-color="#000000" flood-opacity="0.18"/>
    </filter>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" fill="#0f1724"/>

  <!-- onion shadow -->
  <ellipse cx="640" cy="230" rx="200" ry="28" fill="#000" opacity="0.25"/>

  <!-- onion main shape -->
  <g filter="url(#s)" transform="translate(640,130)">
    <path d="M0,-110 C70,-110 120,-60 120,-10 C120,60 0,110 0,110 C0,110 -120,60 -120,-10 C-120,-60 -70,-110 0,-110 Z"
          fill="url(#g1)"/>
    <!-- inner layers -->
    <path d="M0,-90 C55,-90 95,-50 95,-10 C95,45 0,90 0,90 C0,90 -95,45 -95,-10 C-95,-50 -55,-90 0,-90 Z"
          fill="#ffffff" opacity="0.06"/>
    <path d="M0,-70 C40,-70 70,-40 70,-10 C70,30 0,70 0,70 C0,70 -70,30 -70,-10 C-70,-40 -40,-70 0,-70 Z"
          fill="#ffffff" opacity="0.03"/>
    <!-- onion highlight -->
    <ellipse cx="-45" cy="-70" rx="22" ry="10" fill="#ffffff" opacity="0.16" transform="rotate(-20)"/>
    <!-- stem -->
    <rect x="-6" y="-132" width="12" height="28" rx="5" fill="#1f2937"/>
    <path d="M0,-140 C8,-142 12,-150 20,-152" stroke="#32d3c9" stroke-width="4" stroke-linecap="round" fill="none"/>
  </g>

  <!-- caption area (optional) -->
  <g transform="translate(40,40)">
    <text x="0" y="0" fill="#bcd4ff" font-family="Segoe UI, Roboto, Arial" font-size="26" font-weight="600">Tor-friendly header (onion illustration)</text>
    <text x="0" y="30" fill="#94a3b8" font-family="Segoe UI, Roboto, Arial" font-size="14">Original SVG — free to use in your README</text>
  </g>
</svg>

<svg xmlns="http://www.w3.org/2000/svg" width="1280" height="320" viewBox="0 0 1280 320" role="img" aria-label="Flat programmer illustration">
  <defs>
    <linearGradient id="bg" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0" stop-color="#041b2d"/>
      <stop offset="1" stop-color="#072b3b"/>
    </linearGradient>
    <linearGradient id="monitorGrad" x1="0" x2="1">
      <stop offset="0" stop-color="#0ea5e9"/>
      <stop offset="1" stop-color="#7c3aed"/>
    </linearGradient>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" fill="url(#bg)"/>

  <!-- desk -->
  <rect x="160" y="220" width="960" height="18" rx="4" fill="#0b1220" opacity="0.9"/>
  <rect x="260" y="238" width="760" height="10" rx="4" fill="#0b1220" opacity="0.8"/>

  <!-- monitor -->
  <g transform="translate(360,40)">
    <rect x="0" y="0" width="420" height="220" rx="12" fill="#0a1420" stroke="#0f1724" stroke-width="2"/>
    <rect x="14" y="18" width="392" height="152" rx="8" fill="url(#monitorGrad)"/>
    <!-- code lines -->
    <g fill="#071628" opacity="0.9">
      <rect x="30" y="36" width="320" height="12" rx="6" fill="#ffffff" opacity="0.12"/>
      <rect x="30" y="58" width="240" height="12" rx="6" fill="#ffffff" opacity="0.08"/>
      <rect x="30" y="80" width="360" height="12" rx="6" fill="#ffffff" opacity="0.1"/>
      <rect x="30" y="102" width="160" height="12" rx="6" fill="#ffffff" opacity="0.07"/>
    </g>
    <!-- monitor stand -->
    <rect x="180" y="176" width="60" height="12" rx="4" fill="#0b1220"/>
    <rect x="200" y="188" width="20" height="24" rx="4" fill="#0b1220"/>
  </g>

  <!-- person -->
  <g transform="translate(220,72)">
    <!-- head -->
    <circle cx="80" cy="64" r="36" fill="#ffd8b5"/>
    <!-- hair -->
    <path d="M44,64 C50,40 110,42 120,64 C85,48 60,54 44,64 Z" fill="#1f2937"/>
    <!-- body -->
    <rect x="32" y="96" width="96" height="68" rx="12" fill="#153243"/>
    <!-- arms -->
    <rect x="10" y="98" width="26" height="16" rx="8" fill="#153243" transform="rotate(-12 23 106)"/>
    <rect x="130" y="98" width="26" height="16" rx="8" fill="#153243" transform="rotate(12 143 106)"/>
    <!-- laptop / keyboard in front -->
    <rect x="128" y="170" width="420" height="12" rx="6" fill="#081221"/>
  </g>

  <!-- small caption -->
  <g transform="translate(820,40)">
    <text x="0" y="0" fill="#cfeafe" font-family="Segoe UI, Roboto, Arial" font-size="24" font-weight="600">Developer at work</text>
    <text x="0" y="28" fill="#94a3b8" font-family="Segoe UI, Roboto, Arial" font-size="13">Original flat SVG, safe for README use</text>
  </g>
</svg>

# Threat-Hunt-Report-Family-Member-Compromise-Leads-to-Unauthorized-TOR-Usage
Detection of Unauthorized TOR Browser Installation and Use on Workstation: win11vmbruce
