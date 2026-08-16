<div align="center">

  <!-- Minimalist Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=11,15,30&height=180&section=header&text=IMAN%20BAYAT&fontSize=50&fontAlign=50&fontAlignY=45&desc=.NET%20%26%20AI%20Software%20Architect&descSize=18&descAlign=50&descAlignY=68&animation=twinkling" width="100%" />

  <br />

  <!-- Dynamic Typing Subtitle -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=818CF8&center=true&vCenter=true&width=600&lines=Building+Reactive+Blazor+Web+Apps;Integrating+Semantic+Kernel+%26+Local+LLMs;Architecting+.NET+9+Backend+Systems" alt="Typing SVG" />
  </a>

</div>

<br/>

### 🛠️ Tech Stack & Ecosystem

<table align="center" width="100%">
  <tr>
    <td width="33%" valign="top" align="center">
      <h4>Core & Backend</h4>
      <img src="https://img.shields.io/badge/C%23_13-239120?style=flat-square&logo=csharp&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/.NET_9-512BD4?style=flat-square&logo=dotnet&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Blazor_WASM-512BD4?style=flat-square&logo=blazor&logoColor=white"/>
    </td>
    <td width="33%" valign="top" align="center">
      <h4>AI & Intelligence</h4>
      <img src="https://img.shields.io/badge/Semantic_Kernel-0078D4?style=flat-square&logo=microsoft&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/RAG_Pipelines-4F46E5?style=flat-square&logo=openai&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Local_LLM_Agents-0D9488?style=flat-square&logo=cpu&logoColor=white"/>
    </td>
    <td width="33%" valign="top" align="center">
      <h4>Data & DevOps</h4>
      <img src="https://img.shields.io/badge/SQL_Server-CC292B?style=flat-square&logo=microsoft-sql-server&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
    </td>
  </tr>
</table>

---

### 💻 Developer Profile

```csharp
namespace Profile.Overview;

public record Developer
{
    public string Name { get; init; } = "Iman Bayat";
    public string Role { get; init; } = "Software Developer";
    public string PrimaryFocus { get; init; } = ".NET 9, Blazor Web Apps & Semantic Kernel Integration";

    public string[] Expertise { get; init; } = 
    [
        "High-performance C# / .NET backend services",
        "Reactive single-page web frontends using Blazor",
        "Local RAG systems and autonomous AI agent workflows",
        "Relational database design and EF Core ORM optimization"
    ];

    public string GetStatus() => "Building modern full-stack web and AI solutions.";
}
