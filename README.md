<div align="center">

  <!-- Animated Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,12,15,20&height=220&section=header&text=Hey%20there,%20I'm%20Iman!&fontSize=42&fontAlignY=38&animation=twinkling" width="100%" />

  <!-- Vector Animated Interconnected Dark Purple Cubes -->
  <br/>
  <svg width="100%" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="cubeGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#7e22ce" stop-opacity="0.9" />
        <stop offset="100%" stop-color="#3b0764" stop-opacity="0.9" />
      </linearGradient>
      <linearGradient id="glowGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#a855f7" />
        <stop offset="100%" stop-color="#6b21a8" />
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Connecting Energy Beams -->
    <path d="M 220 90 L 400 70 L 580 100 Z" stroke="#a855f7" stroke-width="1.5" stroke-dasharray="6,6" fill="none" opacity="0.6">
      <animate attributeName="stroke-dashoffset" values="0;24" dur="3s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite" />
    </path>
    <path d="M 150 110 L 400 70 M 400 70 L 650 60" stroke="#c084fc" stroke-width="1" fill="none" opacity="0.4">
      <animate attributeName="opacity" values="0.1;0.7;0.1" dur="5s" repeatCount="indefinite" />
    </path>

    <!-- Cube 1 (Left - Orbiting) -->
    <g transform="translate(220, 90)">
      <animateTransform attributeName="transform" type="translate" values="220,90; 210,75; 230,100; 220,90" dur="6s" repeatCount="indefinite" />
      <!-- Isometric Cube Group -->
      <g filter="url(#glow)">
        <polygon points="0,-25 22,-12 0,0 -22,-12" fill="#c084fc" opacity="0.8"/>
        <polygon points="-22,-12 0,0 0,25 -22,13" fill="url(#cubeGrad)"/>
        <polygon points="0,0 22,-12 22,13 0,25" fill="#581c87"/>
      </g>
    </g>

    <!-- Cube 2 (Center Master Node - Floating & Pulsing) -->
    <g transform="translate(400, 70)">
      <animateTransform attributeName="transform" type="translate" values="400,70; 400,55; 400,80; 400,70" dur="5s" repeatCount="indefinite" />
      <g filter="url(#glow)">
        <polygon points="0,-35 30,-17 0,0 -30,-17" fill="#d8b4fe"/>
        <polygon points="-30,-17 0,0 0,35 -30,18" fill="url(#glowGrad)"/>
        <polygon points="0,0 30,-17 30,18 0,35" fill="#3b0764"/>
      </g>
    </g>

    <!-- Cube 3 (Right - Lurking & Connecting) -->
    <g transform="translate(580, 100)">
      <animateTransform attributeName="transform" type="translate" values="580,100; 595,110; 570,85; 580,100" dur="7s" repeatCount="indefinite" />
      <g filter="url(#glow)">
        <polygon points="0,-22 20,-11 0,0 -20,-11" fill="#a855f7" opacity="0.8"/>
        <polygon points="-20,-11 0,0 0,22 -20,11" fill="url(#cubeGrad)"/>
        <polygon points="0,0 20,-11 20,11 0,22" fill="#3b0764"/>
      </g>
    </g>

    <!-- Floating Connection Nodes -->
    <circle cx="220" cy="90" r="3" fill="#e9d5ff" filter="url(#glow)">
      <animate attributeName="r" values="2;5;2" dur="3s" repeatCount="indefinite" />
    </circle>
    <circle cx="400" cy="70" r="4" fill="#ffffff" filter="url(#glow)">
      <animate attributeName="r" values="3;6;3" dur="2.5s" repeatCount="indefinite" />
    </circle>
    <circle cx="580" cy="100" r="3" fill="#e9d5ff" filter="url(#glow)">
      <animate attributeName="r" values="2;5;2" dur="3.5s" repeatCount="indefinite" />
    </circle>
  </svg>

  <!-- Animated Typing Effect -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1000&color=A855F7&center=true&vCenter=true&width=650&lines=.NET+9+%26+Blazor+Web+Apps;Building+Local+AI+Agents+%26+Semantic+Kernel;ASP.NET+Core+%26+RAG+Architectures;Full-Stack+Web+%26+System+Integration" alt="Typing SVG" />
  </a>

  <br /><br />

  <!-- Tech Stack Badges -->
  <p align="center">
    <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white" />
    <img src="https://img.shields.io/badge/.NET_9-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
    <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
    <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/Semantic_Kernel-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
    <img src="https://img.shields.io/badge/SQL_Server-CC292B?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  </p>

</div>

---

### ⚡ About Me

```csharp
public class Developer
{
    public string Name { get; } = "Iman Bayat";
    public string Specialization { get; } = ".NET 9 & Blazor Web Applications";
    
    public string[] TechStack { get; } = 
    { 
        "Blazor WebAssembly / Server", 
        "Semantic Kernel & Ollama", 
        "RAG Architecture & Local LLMs", 
        "ASP.NET Core Web APIs", 
        "SQL Server & Entity Framework Core" 
    };
    
    public string CurrentFocus() 
    {
        return "Architecting reactive Blazor frontends backed by local AI agents.";
    }
}
