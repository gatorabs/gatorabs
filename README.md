

```csharp
public class AboutMe : Developer
{
    public AboutMe()
    {
        Name = "Gabriel Spioni";
        Area = "BackEnd Software Engineer";
        Location = "São Paulo";
    }
}

public class Skills : Developer
{
    public List<string> Languages { get; set; }
    public List<string> Frameworks { get; set; }

    public Skills()
    {
        Languages = new List<string> { "C#", "Python", "C/C++", "JS", "Dart" };
        Frameworks = new List<string> { "ASP.Net Core", ".Net Core" };
    }
}
```

---


[![gatorabs](https://github-readme-stats.vercel.app/api/top-langs/?username=gatorabs&hide=html&layout=compact&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

