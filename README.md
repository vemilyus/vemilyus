<h4>

```kotlin
import io.v47.misc.DriverLicense
import io.v47.misc.Person
import io.v47.misc.Experience
import io.v47.misc.Customer

val workExperience = Experience(
    specializations = listOf("Software Architecture", "Software Transformation", "Product Engineering"),
    languages = listOf("Rust", "Kotlin", "Go", "Python", "TypeScript", "JavaScript", "Regex"),
    runtimes = listOf("JVM", "Node.js"),
    platforms = listOf("Linux", "Android"),
    libraries = listOf("Tokio", "AWS SDK", "Quarkus", "Micronaut", "Spring Boot", "Vue", "React", "Angular"),
    databases = listOf("PostgreSQL", "DynamoDB", "Redis", "Oracle", "MySQL", "Teradata"),
    tools = listOf("Docker", "AWS CDK", "IntelliJ IDEA", "Linux", "GitLab", "GitHub", "macOS"),
    happyCustomers = listOf(
        Customer("SPAR Business Services GmbH", "Salzburg", "Austria"),
        Customer("Raiffeisen-IMPULS-Leasing Gesellschaft m.b.H.", "Linz", "Austria"),
        Customer("Umweltbundesamt GmbH", "Vienna", "Austria"),
        Customer("Erste Digital GmbH", "Vienna", "Austria"),
        Customer("ACREDIA Versicherung AG", "Vienna", "Austria"),
        Customer("MSE Personal Service AG", "Eschen", "Liechtenstein"),
        Customer("Otto GmbH & Co KG", "Hamburg", "Germany"),
        Customer("FIATWISE Software AG", "Vienna", "Austria"),
        Customer("Joyn GmbH", "Munich", "Germany"),
        Customer("Raiffeisen Bank International A.G.", "Vienna", "Austria")
    ),
    isFreelancing = true
)

val personalExperience = Experience(
    languages = listOf("English", "German", "ActionScript 3"),
    libraries = listOf("Nuxt"),
    tools = listOf("Proxmox", "openmediavault", "LXC", "SaltStack", "GamePad", "Windows", "ffmpeg"),
    interests = listOf("Homelabs", "Media Transcoding", "Flying", "Space Exploration", "Sci-Fi", "Craft Beer"),
    driverLicense = setOf(DriverLicense.B)
)

val person = Person(
    name = "Alex Katlein",
    home = "Vienna, Austria",
    age = 31,
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
