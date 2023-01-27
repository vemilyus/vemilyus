<h4>

```kotlin
import io.v47.misc.DriverLicense
import io.v47.misc.Person
import io.v47.misc.Experience

val workExperience = Experience(
    languages = listOf("Rust", "Kotlin", "Go", "Python", "TypeScript", "JavaScript", "Regex"),
    runtimes = listOf("JVM", "Node.js"),
    platforms = listOf("Linux", "Android"),
    libraries = listOf("Tokio", "AWS SDK", "Quarkus", "Micronaut", "Spring Boot", "Vue", "React", "Angular"),
    databases = listOf("PostgreSQL", "DynamoDB", "Redis", "Oracle", "MySQL", "Teradata"),
    tools = listOf("Docker", "AWS CDK", "IntelliJ IDEA", "Linux", "GitLab", "GitHub", "macOS"),
    happyCustomers = listOf("Otto GmbH & Co KG", "FIATWISE Software AG", "Joyn GmbH", "Raiffeisen Bank International A.G."),
    isEmployed = true
)

val personalExperience = Experience(
    languages = listOf("English", "German", "ActionScript 3"),
    libraries = listOf("Nuxt"),
    tools = listOf("Proxmox", "openmediavault", "LXC", "SaltStack", "GamePad", "Windows"),
    interests = listOf("Homelabs", "Media Transcoding", "Flying", "Space Exploration", "Sci-Fi", "Craft Beer"),
    driverLicense = setOf(DriverLicense.B)
)

val person = Person(
    name = "Alex Katlein",
    home = "Vienna, Austria",
    age = 30,
    experience = workExperience + personalExperience
)
```

</h4>

<!--
**vemilyus/vemilyus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
