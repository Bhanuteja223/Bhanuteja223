<svg width="100%" viewBox="0 0 1180 610" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Developer profile card">
  <defs>
    <clipPath id="cardClip_d">
      <rect x="0" y="0" width="1180" height="610" rx="32" ry="32"/>
    </clipPath>
    <clipPath id="leftClip_d">
      <rect x="0" y="0" width="416" height="562" rx="24" ry="24"/>
    </clipPath>
    <clipPath id="rightClip_d">
      <rect x="0" y="0" width="696" height="562" rx="24" ry="24"/>
    </clipPath>

    <linearGradient id="accentGrad_d" x1="0" y1="0" x2="1" y2="0" gradientTransform="translate(0,0)">
      <animateTransform attributeName="gradientTransform" type="translate" values="-0.6 0;0.6 0;-0.6 0" dur="7s" repeatCount="indefinite"/>
      <stop offset="0%" stop-color="#7C3AED"/>
      <stop offset="50%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#10B981"/>
    </linearGradient>

    <linearGradient id="borderGrad_d" x1="0" y1="0" x2="1" y2="1">
      <animateTransform attributeName="gradientTransform" type="rotate" values="0 0.5 0.5;360 0.5 0.5" dur="9s" repeatCount="indefinite"/>
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.9"/>
      <stop offset="35%" stop-color="#22D3EE" stop-opacity="0.15"/>
      <stop offset="65%" stop-color="#10B981" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0.9"/>
    </linearGradient>

    <radialGradient id="glowTL_d" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#3B82F6" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#3B82F6" stop-opacity="0"/>
      <animate attributeName="cx" values="30%;40%;30%" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="25%;35%;25%" dur="14s" repeatCount="indefinite"/>
    </radialGradient>

    <radialGradient id="glowBR_d" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
      <animate attributeName="cx" values="70%;60%;70%" dur="13s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="75%;65%;75%" dur="11s" repeatCount="indefinite"/>
    </radialGradient>

    <radialGradient id="glowMid_d" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#10B981" stop-opacity="0.28"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
      <animate attributeName="cx" values="55%;48%;55%" dur="16s" repeatCount="indefinite"/>
    </radialGradient>

    <linearGradient id="scanGrad_d" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#ffffff" stop-opacity="0.05"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>

    <linearGradient id="reflectGrad_d" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#ffffff" stop-opacity="0.10"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>

    <filter id="bgBlur_d" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="55"/>
    </filter>

    <filter id="textGlow_d" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="1.4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <filter id="pillGlow_d" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="2.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <filter id="cardShadow_d" x="-30%" y="-30%" width="160%" height="160%">
      <feDropShadow dx="0" dy="18" stdDeviation="26" flood-color="#000000" flood-opacity="0.35"/>
    </filter>

    <filter id="noiseFilter_d" x="0" y="0" width="100%" height="100%">
      <feTurbulence type="fractalNoise" baseFrequency="0.85" numOctaves="2" stitchTiles="stitch" result="n">
        <animate attributeName="baseFrequency" values="0.85;0.9;0.85" dur="9s" repeatCount="indefinite"/>
      </feTurbulence>
      <feColorMatrix in="n" type="matrix" values="0 0 0 0 1  0 0 0 0 1  0 0 0 0 1  0 0 0 0.025 0"/>
    </filter>

    <mask id="cardMask_d">
      <rect x="0" y="0" width="1180" height="610" rx="32" ry="32" fill="#ffffff"/>
    </mask>
  </defs>

  <g clip-path="url(#cardClip_d)">
    <!-- BACKGROUND -->
    <rect x="0" y="0" width="1180" height="610" fill="#030712"/>
    <g filter="url(#bgBlur_d)">
      <rect x="-200" y="-200" width="700" height="700" fill="url(#glowTL_d)"/>
      <rect x="680" y="110" width="700" height="700" fill="url(#glowBR_d)"/>
      <rect x="140" y="-80" width="900" height="780" fill="url(#glowMid_d)"/>
    </g>

    <!-- scanline sweep -->
    <rect x="0" y="0" width="1180" height="610" fill="url(#scanGrad_d)" opacity="0.6">
      <animateTransform attributeName="transform" type="translate" values="0,-610;0,610" dur="6s" repeatCount="indefinite"/>
    </rect>

    <!-- noise overlay -->
    <rect x="0" y="0" width="1180" height="610" filter="url(#noiseFilter_d)"/>

    <!-- particles -->
    <g>
      <circle r="1.6" fill="#22D3EE" opacity="0.55">
        <animateMotion path="M100,500 C 300,420 500,560 700,460 S 1000,380 1100,470" dur="18s" repeatCount="indefinite" rotate="0"/>
        <animate attributeName="opacity" values="0.15;0.7;0.15" dur="3.0s" repeatCount="indefinite"/>
      </circle>

      <circle r="2.2" fill="#22D3EE" opacity="0.55">
        <animateMotion path="M60,150 C 250,220 420,90 640,180 S 950,240 1120,140" dur="21s" repeatCount="indefinite" rotate="0"/>
        <animate attributeName="opacity" values="0.15;0.7;0.15" dur="3.4s" repeatCount="indefinite"/>
      </circle>

      <circle r="2.8" fill="#22D3EE" opacity="0.55">
        <animateMotion path="M180,560 C 380,500 560,590 780,520 S 1020,470 1140,540" dur="24s" repeatCount="indefinite" rotate="0"/>
        <animate attributeName="opacity" values="0.15;0.7;0.15" dur="3.8s" repeatCount="indefinite"/>
      </circle>

      <circle r="1.6" fill="#22D3EE" opacity="0.55">
        <animateMotion path="M40,320 C 220,260 430,360 620,300 S 900,260 1150,330" dur="27s" repeatCount="indefinite" rotate="0"/>
        <animate attributeName="opacity" values="0.15;0.7;0.15" dur="4.2s" repeatCount="indefinite"/>
      </circle>

      <circle r="2.2" fill="#22D3EE" opacity="0.55">
        <animateMotion path="M140,60 C 320,120 500,40 690,100 S 980,150 1130,70" dur="30s" repeatCount="indefinite" rotate="0"/>
        <animate attributeName="opacity" values="0.15;0.7;0.15" dur="4.6s" repeatCount="indefinite"/>
      </circle>

      <circle r="2.8" fill="#22D3EE" opacity="0.55">
        <animateMotion path="M90,440 C 260,380 460,470 650,410 S 940,350 1120,420" dur="33s" repeatCount="indefinite" rotate="0"/>
        <animate attributeName="opacity" values="0.15;0.7;0.15" dur="5.0s" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- MAIN GLASS CARD -->
    <g filter="url(#cardShadow_d)">
      <rect x="24" y="24" width="1132" height="562" rx="28" fill="#0F172A" fill-opacity="0.55" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>
    </g>
    <rect x="24.5" y="24.5" width="1131" height="561" rx="27.5" fill="none" stroke="url(#borderGrad_d)" stroke-width="1.2"/>

    <!-- glass reflection sweep across whole card -->
    <g clip-path="url(#cardClip_d)">
      <rect x="-400" y="0" width="260" height="610" fill="url(#reflectGrad_d)" transform="skewX(-18)">
        <animateTransform attributeName="transform" type="translate" values="-100,0; 1500,0" dur="7s" begin="1s" repeatCount="indefinite" additive="sum"/>
      </rect>
    </g>

    <!-- ============ LEFT PANEL ============ -->
    <g transform="translate(40,40)">
      <rect x="0" y="0" width="416" height="562" rx="24" fill="#111c34" fill-opacity="0.55" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>
      <g clip-path="url(#leftClip_d)">
        <!-- terminal header -->
        <circle cx="26" cy="26" r="6" fill="#EF4444"/>
        <circle cx="46" cy="26" r="6" fill="#F59E0B"/>
        <circle cx="66" cy="26" r="6" fill="#10B981"/>
        <text x="90" y="31" font-family="'SFMono-Regular',monospace" font-size="12.5" fill="#94A3B8">portrait.ascii</text>
        <line x1="0" y1="48" x2="416" y2="48" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        <!-- ascii portrait -->
        <g>
          
      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="0.60s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="90" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣶⣶⣦⣄</text>
      </g>

      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="0.95s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="122" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⠀⠀⣠⣾⠟⠉⠉⠙⠻⣷⣄</text>
      </g>

      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="1.30s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="154" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⠀⣼⠟⠀⠀⠀⠀⠀⠀⠈⢿⣧</text>
      </g>

      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="1.65s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="186" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⣸⡏⠀⠀⢀⣤⣤⣄⠀⠀⠘⣿</text>
      </g>

      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="2.00s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="218" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⣿⡇⠀⠀⠘⠿⠿⠟⠀⠀⠀⣿</text>
      </g>

      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="2.35s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="250" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⢿⣧⠀⠀⠀⠀⠀⠀⠀⠀⣰⡿</text>
      </g>

      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="2.70s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="282" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⠈⢿⣦⡀⠀⠀⠀⠀⢀⣴⡿</text>
      </g>

      <g opacity="0">
        <animate attributeName="opacity" attributeType="XML" begin="3.05s" dur="0.6s" fill="freeze" values="0;1"/>
        <text x="70" y="314" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" letter-spacing="1" fill="url(#accentGrad_d)" filter="url(#textGlow_d)">⠀⠀⠀⠀⠀⠀⠙⠿⣶⣤⣴⣾⠿⠋</text>
      </g>
        </g>

        <!-- blinking cursor under ascii -->
        <rect x="70" y="372" width="10" height="18" fill="#22D3EE">
          <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
        </rect>

        <!-- scanline sweep local -->
        <rect x="0" y="0" width="416" height="562" fill="url(#scanGrad_d)" opacity="0.4">
          <animateTransform attributeName="transform" type="translate" values="0,-562;0,562" dur="5s" repeatCount="indefinite"/>
        </rect>

        <!-- floating whole panel content -->
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="6s" repeatCount="indefinite" additive="sum"/>
      </g>
      <rect x="0.5" y="0.5" width="415" height="561" rx="23.5" fill="none" stroke="url(#borderGrad_d)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.3;0.8;0.3" dur="4s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- ============ RIGHT PANEL ============ -->
    <g transform="translate(464,40)">
      <rect x="0" y="0" width="696" height="562" rx="24" fill="#111c34" fill-opacity="0.5" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>
      <g clip-path="url(#rightClip_d)">

        <!-- header -->
        <circle cx="26" cy="26" r="6" fill="#EF4444"/>
        <circle cx="46" cy="26" r="6" fill="#F59E0B"/>
        <circle cx="66" cy="26" r="6" fill="#10B981"/>
        <text x="90" y="31" font-family="'SFMono-Regular',monospace" font-size="12.5" fill="#94A3B8">bhanuteja@portfolio ~ %</text>
        <line x1="0" y1="48" x2="696" y2="48" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        <!-- greeting -->
        <g opacity="0" transform="translate(24,90)">
          <animate attributeName="opacity" begin="0.3s" dur="0.6s" fill="freeze" values="0;1"/>
          <text x="0" y="0" font-family="Inter,'Segoe UI',sans-serif" font-size="27" font-weight="700" fill="#F8FAFC">Hi <tspan>&#128075;</tspan> I'm Bhanuteja Thouti</text>
        </g>

        <!-- typing line -->
        <g transform="translate(24,124)">
          <text x="0" y="0" font-family="'SFMono-Regular',monospace" font-size="14" fill="#94A3B8">&gt;</text>
          <g transform="translate(18,-19)">
            
      <g>
        <clipPath id="typeClip_d0">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="0.00s" dur="15.00s" repeatCount="indefinite"
              keyTimes="0;0.62;0.72;0.8;1" values="0;187;187;0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#typeClip_d0)">
          <text x="0" y="24" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" font-weight="600" fill="url(#accentGrad_d)">Frontend Engineer</text>
        </g>
      </g>

      <g>
        <clipPath id="typeClip_d1">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="3.00s" dur="15.00s" repeatCount="indefinite"
              keyTimes="0;0.62;0.72;0.8;1" values="0;220;220;0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#typeClip_d1)">
          <text x="0" y="24" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" font-weight="600" fill="url(#accentGrad_d)">Full Stack Developer</text>
        </g>
      </g>

      <g>
        <clipPath id="typeClip_d2">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="6.00s" dur="15.00s" repeatCount="indefinite"
              keyTimes="0;0.62;0.72;0.8;1" values="0;253;253;0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#typeClip_d2)">
          <text x="0" y="24" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" font-weight="600" fill="url(#accentGrad_d)">Open Source Contributor</text>
        </g>
      </g>

      <g>
        <clipPath id="typeClip_d3">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="9.00s" dur="15.00s" repeatCount="indefinite"
              keyTimes="0;0.62;0.72;0.8;1" values="0;121;121;0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#typeClip_d3)">
          <text x="0" y="24" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" font-weight="600" fill="url(#accentGrad_d)">UI Engineer</text>
        </g>
      </g>

      <g>
        <clipPath id="typeClip_d4">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="12.00s" dur="15.00s" repeatCount="indefinite"
              keyTimes="0;0.62;0.72;0.8;1" values="0;143;143;0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#typeClip_d4)">
          <text x="0" y="24" font-family="'SFMono-Regular','Consolas',monospace" font-size="20" font-weight="600" fill="url(#accentGrad_d)">AI Enthusiast</text>
        </g>
      </g>
            <rect x="0" y="4" width="2.5" height="22" fill="#22D3EE">
              <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/>
            </rect>
          </g>
        </g>

        <line x1="24" y1="168" x2="672" y2="168" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        <!-- info rows -->
        <g transform="translate(24,196)">
          
      <g transform="translate(0,0)" opacity="0">
        <animate attributeName="opacity" begin="2.20s" dur="0.5s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="2.20s" dur="0.5s" fill="freeze" values="0,14;0,0"/>
        <text x="0" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" letter-spacing="0.5" fill="#94A3B8">LOCATION</text>
        <text x="150" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="13.5" fill="#F8FAFC">Hyderabad, India</text>
      </g>

      <g transform="translate(0,34)" opacity="0">
        <animate attributeName="opacity" begin="2.42s" dur="0.5s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="2.42s" dur="0.5s" fill="freeze" values="0,14;0,0"/>
        <text x="0" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" letter-spacing="0.5" fill="#94A3B8">EDUCATION</text>
        <text x="150" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="13.5" fill="#F8FAFC">B.Tech EEE</text>
      </g>

      <g transform="translate(0,68)" opacity="0">
        <animate attributeName="opacity" begin="2.64s" dur="0.5s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="2.64s" dur="0.5s" fill="freeze" values="0,14;0,0"/>
        <text x="0" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" letter-spacing="0.5" fill="#94A3B8">CURRENT FOCUS</text>
        <text x="150" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="13.5" fill="#F8FAFC">Building scalable recruitment platforms</text>
      </g>

      <g transform="translate(0,102)" opacity="0">
        <animate attributeName="opacity" begin="2.86s" dur="0.5s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="2.86s" dur="0.5s" fill="freeze" values="0,14;0,0"/>
        <text x="0" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" letter-spacing="0.5" fill="#94A3B8">PORTFOLIO</text>
        <text x="150" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="13.5" fill="#F8FAFC">bhanuteja-rho.vercel.app</text>
      </g>

      <g transform="translate(0,136)" opacity="0">
        <animate attributeName="opacity" begin="3.08s" dur="0.5s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="3.08s" dur="0.5s" fill="freeze" values="0,14;0,0"/>
        <text x="0" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" letter-spacing="0.5" fill="#94A3B8">EMAIL</text>
        <text x="150" y="14" font-family="Inter,'Segoe UI',sans-serif" font-size="13.5" fill="#F8FAFC">bhanutejathouti@gmail.com</text>
      </g>
        </g>

        <line x1="24" y1="380" x2="672" y2="380" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        <!-- skills -->
        <g transform="translate(24,400)">
          <text x="0" y="-10" font-family="Inter,sans-serif" font-size="12.5" font-weight="600" fill="#94A3B8">SKILLS</text>
          <g transform="translate(0,8)">
            
      <g transform="translate(0,0)" opacity="0">
        <animate attributeName="opacity" begin="3.40s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="3.40s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="75" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.00s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="37.5" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">React</text>
      </g>

      <g transform="translate(85,0)" opacity="0">
        <animate attributeName="opacity" begin="3.49s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="3.49s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="93" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.09s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="46.5" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Next.js</text>
      </g>

      <g transform="translate(188,0)" opacity="0">
        <animate attributeName="opacity" begin="3.58s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="3.58s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="93" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.18s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="46.5" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Node.js</text>
      </g>

      <g transform="translate(291,0)" opacity="0">
        <animate attributeName="opacity" begin="3.67s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="3.67s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="120" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.27s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="60.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">TypeScript</text>
      </g>

      <g transform="translate(421,0)" opacity="0">
        <animate attributeName="opacity" begin="3.76s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="3.76s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="102" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.36s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="51.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Tailwind</text>
      </g>

      <g transform="translate(533,0)" opacity="0">
        <animate attributeName="opacity" begin="3.85s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="3.85s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="84" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.45s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="42.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Python</text>
      </g>

      <g transform="translate(0,42)" opacity="0">
        <animate attributeName="opacity" begin="3.94s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="3.94s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="84" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.54s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="42.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Docker</text>
      </g>

      <g transform="translate(94,42)" opacity="0">
        <animate attributeName="opacity" begin="4.03s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="4.03s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="120" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.63s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="60.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">PostgreSQL</text>
      </g>

      <g transform="translate(224,42)" opacity="0">
        <animate attributeName="opacity" begin="4.12s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="4.12s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="64" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.72s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="32.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">AWS</text>
      </g>

      <g transform="translate(298,42)" opacity="0">
        <animate attributeName="opacity" begin="4.21s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="4.21s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="64" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.81s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="32.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Git</text>
      </g>

      <g transform="translate(372,42)" opacity="0">
        <animate attributeName="opacity" begin="4.30s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="4.30s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="75" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.90s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="37.5" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Figma</text>
      </g>

      <g transform="translate(457,42)" opacity="0">
        <animate attributeName="opacity" begin="4.39s" dur="0.4s" fill="freeze" values="0;1"/>
        <animateTransform attributeName="transform" type="scale" additive="sum" begin="4.39s" dur="0.4s" fill="freeze" values="0.85,0.85;1,1" calcMode="spline" keySplines="0.2 0.8 0.2 1"/>
        <rect width="102" height="30" rx="15" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="4.99s" dur="2.6s" repeatCount="indefinite" values="0.45;1;0.45"/>
        </rect>
        <text x="51.0" y="20" text-anchor="middle" font-family="Inter,'Segoe UI',sans-serif" font-size="12.5" font-weight="600" fill="#F8FAFC">Supabase</text>
      </g>
          </g>
        </g>

        <!-- socials -->
        <g transform="translate(24,504)">
          
      <g transform="translate(22,22)">
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="4.60s" dur="3.2s" repeatCount="indefinite" values="0,0;0,-5;0,0" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
        <circle r="20" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1.4" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="0.0s" dur="2.4s" repeatCount="indefinite" values="0.5;1;0.5"/>
        </circle>
        <text x="0" y="5" text-anchor="middle" font-family="'SFMono-Regular',monospace" font-size="13" font-weight="700" fill="#F8FAFC">&lt;/&gt;</text>
      </g>

      <g transform="translate(84,22)">
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="5.10s" dur="3.5s" repeatCount="indefinite" values="0,0;0,-5;0,0" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
        <circle r="20" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1.4" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="0.4s" dur="2.4s" repeatCount="indefinite" values="0.5;1;0.5"/>
        </circle>
        <text x="0" y="5" text-anchor="middle" font-family="'SFMono-Regular',monospace" font-size="13" font-weight="700" fill="#F8FAFC">in</text>
      </g>

      <g transform="translate(146,22)">
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="5.60s" dur="3.8s" repeatCount="indefinite" values="0,0;0,-5;0,0" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
        <circle r="20" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1.4" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="0.8s" dur="2.4s" repeatCount="indefinite" values="0.5;1;0.5"/>
        </circle>
        <text x="0" y="5" text-anchor="middle" font-family="'SFMono-Regular',monospace" font-size="13" font-weight="700" fill="#F8FAFC">X</text>
      </g>

      <g transform="translate(208,22)">
        <animateTransform attributeName="transform" type="translate" additive="sum" begin="6.10s" dur="4.1s" repeatCount="indefinite" values="0,0;0,-5;0,0" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
        <circle r="20" fill="#111c34" stroke="url(#accentGrad_d)" stroke-width="1.4" filter="url(#pillGlow_d)">
          <animate attributeName="stroke-opacity" begin="1.2s" dur="2.4s" repeatCount="indefinite" values="0.5;1;0.5"/>
        </circle>
        <text x="0" y="5" text-anchor="middle" font-family="'SFMono-Regular',monospace" font-size="13" font-weight="700" fill="#F8FAFC">⊕</text>
      </g>
        </g>
      </g>
      <rect x="0.5" y="0.5" width="695" height="561" rx="23.5" fill="none" stroke="url(#borderGrad_d)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.3;0.8;0.3" dur="4.5s" repeatCount="indefinite"/>
      </rect>
    </g>
  </g>
</svg>
