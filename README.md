<svg width="900" height="180" viewBox="0 0 900 180" xmlns="http://www.w3.org/2000/svg" overflow="hidden">
  <defs>
    <linearGradient id="lg" gradientUnits="userSpaceOnUse" x1="300" y1="100" x2="600" y2="100">
      <stop offset="0%"   stop-color="#0078D4" stop-opacity="0"/>
      <stop offset="50%"  stop-color="#0078D4" stop-opacity="1"/>
      <stop offset="100%" stop-color="#0078D4" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <style>
    @keyframes draw { from { stroke-dashoffset: 300; } to { stroke-dashoffset: 0; } }
    @keyframes up   { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: translateY(0); } }
    @keyframes fin  { from { opacity: 0; } to { opacity: 1; } }
    .nm { animation: up  1.4s cubic-bezier(0.22,1,0.36,1) 0.0s both; }
    .dl { stroke-dasharray: 300; stroke-dashoffset: 300; animation: draw 1.6s cubic-bezier(0.22,1,0.36,1) 0.8s forwards; }
    .rl { animation: up  1.2s cubic-bezier(0.22,1,0.36,1) 1.2s both; }
    .sk { animation: fin 1.4s ease-out 1.7s both; }
  </style>
  <rect width="900" height="180" fill="#000000"/>
  <text x="450" y="178" font-family="'Helvetica Neue',Helvetica,Arial,sans-serif" font-size="210" font-weight="100" fill="#0078D4" opacity="0.03" text-anchor="middle" dominant-baseline="auto" letter-spacing="14">RS</text>
  <text class="nm" x="450" y="84" font-family="-apple-system,'SF Pro Display','Helvetica Neue',Helvetica,Arial,sans-serif" font-size="56" font-weight="200" fill="#F5F5F7" text-anchor="middle" letter-spacing="10">RIPAL SUTHAR</text>
  <line class="dl" x1="300" y1="100" x2="600" y2="100" stroke="url(#lg)" stroke-width="1.2"/>
  <text class="rl" x="450" y="132" font-family="-apple-system,'SF Pro Text','Helvetica Neue',Helvetica,Arial,sans-serif" font-size="10.5" font-weight="400" fill="#86868B" text-anchor="middle" letter-spacing="9">DATA ENGINEER</text>
  <text class="sk" x="450" y="157" font-family="-apple-system,'SF Pro Text','Helvetica Neue',Helvetica,Arial,sans-serif" font-size="10" font-weight="300" fill="#3A3A3C" text-anchor="middle" letter-spacing="1.8">Databricks · Spark · Delta Lake · Cloud (AWS / Azure / GCP)</text>
  <line x1="0" y1="0"   x2="900" y2="0"   stroke="#1D1D1F" stroke-width="1"/>
  <line x1="0" y1="179" x2="900" y2="179" stroke="#1D1D1F" stroke-width="1"/>
</svg>
