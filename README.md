<svg width="800" height="240" viewBox="0 0 800 240" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="0" y2="240" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#1a1b26"/>
      <stop offset="100%" stop-color="#16161e"/>
    </linearGradient>
    <linearGradient id="border" x1="0" y1="0" x2="800" y2="240" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#bb9af7"/>
      <stop offset="50%" stop-color="#7dcfff"/>
      <stop offset="100%" stop-color="#bb9af7"/>
    </linearGradient>
    <filter id="glow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="5" result="b"/>
      <feMerge>
        <feMergeNode in="b"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <clipPath id="c1"><rect x="0" y="52" width="0" height="26"><animate id="a1" attributeName="width" from="0" to="760" begin="0.4s" dur="0.5s" fill="freeze"/></rect></clipPath>
    <clipPath id="c2"><rect x="0" y="82" width="0" height="26"><animate id="a2" attributeName="width" from="0" to="760" begin="a1.end+0.25s" dur="1.9s" fill="freeze"/></rect></clipPath>
    <clipPath id="c3"><rect x="0" y="112" width="0" height="26"><animate id="a3" attributeName="width" from="0" to="760" begin="a2.end+0.25s" dur="0.9s" fill="freeze"/></rect></clipPath>
    <clipPath id="c4"><rect x="0" y="142" width="0" height="26"><animate id="a4" attributeName="width" from="0" to="760" begin="a3.end+0.25s" dur="1.7s" fill="freeze"/></rect></clipPath>
    <clipPath id="c5"><rect x="0" y="172" width="0" height="26"><animate id="a5" attributeName="width" from="0" to="760" begin="a4.end+0.25s" dur="1.8s" fill="freeze"/></rect></clipPath>
    <clipPath id="c6"><rect x="0" y="202" width="0" height="26"><animate id="a6" attributeName="width" from="0" to="760" begin="a5.end+0.25s" dur="1.1s" fill="freeze"/></rect></clipPath>
  </defs>

  <rect x="1.5" y="1.5" width="797" height="237" rx="16" fill="none" stroke="url(#border)" stroke-width="1.5" opacity="0.55" filter="url(#glow)"/>
  <rect x="4" y="4" width="792" height="232" rx="14" fill="url(#bg)" stroke="#2a2b3d"/>
  <rect x="4" y="4" width="792" height="36" rx="14" fill="#16161e"/>
  <rect x="4" y="18" width="792" height="22" fill="#16161e"/>

  <circle cx="28" cy="22" r="6" fill="#f7768e"/>
  <circle cx="50" cy="22" r="6" fill="#e0af68"/>
  <circle cx="72" cy="22" r="6" fill="#9ece6a"/>
  <text x="400" y="27" text-anchor="middle" font-family="Menlo, Consolas, monospace" font-size="12" fill="#565f89">harkirat@dev-machine — zsh</text>

  <circle cx="754" cy="22" r="4" fill="#9ece6a">
    <animate attributeName="opacity" values="1;0.25;1" dur="1.6s" repeatCount="indefinite"/>
  </circle>

  <g font-family="Menlo, Consolas, 'Courier New', monospace" font-size="18">
    <text x="26" y="70" fill="#bb9af7" clip-path="url(#c1)">$ whoami</text>
    <text x="26" y="100" fill="#7dcfff" clip-path="url(#c2)">&gt; Harkirat Singh — BCA student, Rajasthan</text>
    <text x="26" y="130" fill="#bb9af7" clip-path="url(#c3)">$ status --check</text>
    <text x="26" y="160" fill="#7dcfff" clip-path="url(#c4)">&gt; [OK] building with the MERN stack</text>
    <text x="26" y="190" fill="#7dcfff" clip-path="url(#c5)">&gt; [OK] curiosity: AI x Web integration</text>
    <text x="26" y="220" fill="#bb9af7" clip-path="url(#c6)">$ ready_to_ship --now</text>
  </g>

  <rect x="258" y="202" width="11" height="26" fill="#bb9af7" opacity="0">
    <animate attributeName="opacity" values="1;0;1" dur="0.9s" begin="a6.end" repeatCount="indefinite"/>
  </rect>
</svg>
