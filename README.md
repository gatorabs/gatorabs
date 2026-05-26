

```csharp
public class AboutMe : Developer
{
    public AboutMe()
    {
        Name = "Gabriel S. Estevão";
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

