<div align="center">
  <svg width="1200" height="520" viewBox="0 0 1200 520" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cyber profile art">
    <defs>
      <linearGradient id="bg" x1="0" x2="1">
        <stop offset="0%" stop-color="#050816"/>
        <stop offset="45%" stop-color="#0d1328"/>
        <stop offset="100%" stop-color="#090d1a"/>
      </linearGradient>
      <radialGradient id="glow1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#67e8ff" stop-opacity="1"/>
        <stop offset="35%" stop-color="#5a7cff" stop-opacity=".6"/>
        <stop offset="70%" stop-color="#b55bff" stop-opacity=".2"/>
        <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
      </radialGradient>
      <radialGradient id="glow2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#ff7de8" stop-opacity=".9"/>
        <stop offset="45%" stop-color="#b55bff" stop-opacity=".4"/>
        <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
      </radialGradient>
      <linearGradient id="line" x1="0" x2="1">
        <stop offset="0%" stop-color="#67e8ff"/>
        <stop offset="50%" stop-color="#9a7bff"/>
        <stop offset="100%" stop-color="#ff7de8"/>
      </linearGradient>
      <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="8" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <filter id="heavyGlow" x="-70%" y="-70%" width="240%" height="240%">
        <feGaussianBlur stdDeviation="16" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <style>
        .slow-spin { animation: spin 18s linear infinite; transform-origin: 600px 250px; }
        .fast-spin { animation: spin 9s linear infinite reverse; transform-origin: 600px 250px; }
        .pulse { animation: pulse 3s ease-in-out infinite alternate; }
        .float1 { animation: float1 5s ease-in-out infinite alternate; }
        .float2 { animation: float2 6s ease-in-out infinite alternate; }
        .shimmer { animation: shimmer 4s ease-in-out infinite; }
        @keyframes spin { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
        @keyframes pulse { 0% { opacity:.6; transform: scale(.92); } 100% { opacity:1; transform: scale(1.08); } }
        @keyframes float1 { 0% { transform: translateY(0px); } 100% { transform: translateY(-16px); } }
        @keyframes float2 { 0% { transform: translateY(0px); } 100% { transform: translateY(18px); } }
        @keyframes shimmer { 0% { opacity:.45; } 50% { opacity:1; } 100% { opacity:.45; } }
      </style>
    </defs>

    <rect width="1200" height="520" fill="url(#bg)"/>
    <g opacity=".9">
      <circle cx="200" cy="90" r="180" fill="url(#glow1)" class="pulse"/>
      <circle cx="980" cy="120" r="200" fill="url(#glow2)" class="pulse"/>
    </g>

    <g class="slow-spin">
      <circle cx="600" cy="250" r="180" fill="none" stroke="rgba(103,232,255,.28)" stroke-width="1.4"/>
      <circle cx="600" cy="250" r="230" fill="none" stroke="rgba(181,91,255,.18)" stroke-width="1.2"/>
      <circle cx="600" cy="250" r="280" fill="none" stroke="rgba(255,125,232,.12)" stroke-width="1.1"/>

      <g opacity=".8">
        <circle cx="600" cy="70" r="9" fill="#67e8ff" filter="url(#softGlow)"/>
        <circle cx="758" cy="180" r="7" fill="#b55bff" filter="url(#softGlow)"/>
        <circle cx="440" cy="186" r="7" fill="#ff7de8" filter="url(#softGlow)"/>
        <circle cx="818" cy="332" r="8" fill="#67e8ff" filter="url(#softGlow)"/>
        <circle cx="388" cy="330" r="8" fill="#b55bff" filter="url(#softGlow)"/>
      </g>
    </g>

    <g class="fast-spin">
      <ellipse cx="600" cy="250" rx="118" ry="216" fill="none" stroke="rgba(255,255,255,.12)" stroke-width="1"/>
      <ellipse cx="600" cy="250" rx="178" ry="286" fill="none" stroke="rgba(103,232,255,.14)" stroke-width="1"/>
    </g>

    <g filter="url(#heavyGlow)">
      <rect x="390" y="110" width="420" height="280" rx="34" fill="rgba(14,20,36,.78)" stroke="rgba(255,255,255,.08)" transform="rotate(-14 600 250)" class="float1"/>
      <rect x="432" y="151" width="332" height="195" rx="26" fill="rgba(17,25,43,.82)" stroke="rgba(103,232,255,.2)" transform="rotate(-14 600 250)"/>
      <path d="M470 265 L560 232 L624 272 L700 200 L760 250" fill="none" stroke="url(#line)" stroke-width="4" stroke-linecap="round" stroke-linejoin="round" transform="rotate(-14 600 250)"/>
      <circle cx="468" cy="260" r="9" fill="#67e8ff" transform="rotate(-14 600 250)"/>
      <circle cx="625" cy="274" r="9" fill="#b55bff" transform="rotate(-14 600 250)"/>
      <circle cx="760" cy="250" r="9" fill="#ff7de8" transform="rotate(-14 600 250)"/>
    </g>

    <g class="float2">
      <rect x="825" y="160" width="140" height="120" rx="24" fill="rgba(12,18,30,.76)" stroke="rgba(255,255,255,.08)" transform="rotate(12 895 220)"/>
      <rect x="214" y="190" width="118" height="110" rx="22" fill="rgba(12,18,30,.76)" stroke="rgba(255,255,255,.08)" transform="rotate(-16 273 245)"/>
      <circle cx="271" cy="245" r="34" fill="rgba(103,232,255,.14)" stroke="rgba(103,232,255,.32)"/>
      <circle cx="895" cy="220" r="30" fill="rgba(181,91,255,.14)" stroke="rgba(181,91,255,.32)"/>
    </g>

    <g opacity=".9">
      <path d="M320 390 L420 390" stroke="rgba(103,232,255,.7)" stroke-width="2" stroke-linecap="round"/>
      <path d="M780 390 L880 390" stroke="rgba(255,125,232,.7)" stroke-width="2" stroke-linecap="round"/>
      <path d="M600 380 L600 460" stroke="rgba(181,91,255,.8)" stroke-width="2" stroke-linecap="round"/>
    </g>

    <g class="shimmer">
      <rect x="462" y="90" width="270" height="18" rx="9" fill="rgba(255,255,255,.06)"/>
      <rect x="470" y="95" width="180" height="8" rx="4" fill="url(#line)"/>
    </g>

    <g opacity=".9">
      <circle cx="600" cy="250" r="120" fill="none" stroke="rgba(255,255,255,.06)" stroke-width="2"/>
      <circle cx="600" cy="250" r="156" fill="none" stroke="rgba(255,255,255,.04)" stroke-width="1.2"/>
    </g>
  </svg>
</div>
