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


# Threat-Hunt-Report-Family-Member-Compromise-Leads-to-Unauthorized-TOR-Usage
Detection of Unauthorized TOR Browser Installation and Use on Workstation: win11vmbruce
