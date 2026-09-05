<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=512BD4&center=true&vCenter=true&repeat=true&width=550&height=50&lines=Hi%2C+I'm+Sourav+Chandrakant+Kore+%F0%9F%91%8B;Full+Stack+.NET+%2B+Angular+Developer;Microservices+%26+Distributed+Systems;AI-Assisted+Software+Engineer" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://linkedin.com/in/souravkore"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:souravkore@gmail.com"><img src="https://img.shields.io/badge/Email-souravkore%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://komarev.com/ghpvc/?username=souravkore&color=blueviolet&style=for-the-badge"><img src="https://komarev.com/ghpvc/?username=souravkore&color=blueviolet&style=for-the-badge" alt="Profile Views" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,25&height=120&section=header"/>
</p>

```csharp
using System;
using System.Collections.Generic;

namespace SouravKore.Profile
{
    public sealed class Engineer
    {
        public string Name { get; } = "Sourav Chandrakant Kore";
        public string Title { get; } = "Full Stack Developer";
        public int ExperienceYears { get; } = 5;
        public string Location { get; } = "Pune, Maharashtra, India";

        public IReadOnlyList<string> BackendStack { get; } = new[]
        {
            "C#", ".NET Core 6/8", "ASP.NET Web API", "Entity Framework Core", "Microservices"
        };

        public IReadOnlyList<string> FrontendStack { get; } = new[]
        {
            "Angular", "AngularJS", "TypeScript", "JavaScript"
        };

        public IReadOnlyList<string> Databases { get; } = new[]
        {
            "SQL Server", "Oracle (PL/SQL)", "MySQL"
        };

        public IReadOnlyList<string> AiTools { get; } = new[]
        {
            "GitHub Copilot", "ChatGPT", "Claude", "Google Gemini"
        };

        public void ExecuteDailyWorkflow()
        {
            ScaleMicroservices();
            TuneSqlExecutionPlans();
            AutomateWithGenerativeAI();
        }

        private void ScaleMicroservices() => Console.WriteLine("Engineering resilient distributed systems.");
        private void TuneSqlExecutionPlans() => Console.WriteLine("Optimizing query performance and throughput.");
        private void AutomateWithGenerativeAI() => Console.WriteLine("Accelerating tests, APIs, and refactoring with AI.");
    }
}
```
