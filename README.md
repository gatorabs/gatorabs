

```csharp
public class AboutMe : Developer
{
    public AboutMe()
    {
        Name = "Gabriel J. S. Estevão";
        Area = "Software Engineer";
        Location = "São Paulo";
    }
}

public class Skills : Developer
{
    public List<string> Languages { get; set; }
    public List<string> Frameworks { get; set; }
    public List<string> Architecture { get; set; }
    public List<string> Cloud { get; set; }
    public List<string> DevOps { get; set; }
    public List<string> Databases { get; set; }
    public List<string> Observability { get; set; }
    public List<string> Messaging { get; set; }

    public Skills()
    {
        Languages = new List<string> { "C#", "Python", "C/C++", "JavaScript" };
        Frameworks = new List<string> { "ASP.NET", ".NET, Flask" };

        Architecture = new List<string> { "Microservices", "Clean Architecture", "Domain-Driven Design" };
        Cloud = new List<string> { "Azure" };
        DevOps = new List<string> { "CI/CD Pipelines" };
        Databases = new List<string> { "SQL", "NoSQL" };
        Observability = new List<string> { "Dynatrace" };
        Messaging = new List<string> { "Kafka", "RabbitMQ" };
    }
}
}
```

---

