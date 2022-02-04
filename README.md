<h4>

```kotlin
import io.v47.misc.DriverLicense
import io.v47.misc.Person
import io.v47.misc.Experience

val workExperience = Experience(
    languages = listOf("Kotlin", "Rust", "Go", "Python", "TypeScript", "JavaScript", "Regex"),
    runtimes = listOf("JVM", "Node.js"),
    libraries = listOf("Micronaut", "Quarkus", "Spring", "Vue", "React", "Angular", "AWS SDK"),
    databases = listOf("PostgreSQL", "Oracle", "MySQL", "Teradata"),
    tools = listOf("Docker", "AWS CDK", "IntelliJ IDEA", "Linux", "GitLab"),
    isEmployed = true
)

val personalExperience = Experience(
    languages = listOf("English", "German", "ActionScript 3"),
    libraries = listOf("Nuxt"),
    tools = listOf("GamePad", "Windows"),
    interests = listOf("Media Transcoding", "Flying", "Space Exploration", "Sci-Fi"),
    driverLicense = setOf(DriverLicense.B)
)

val person = Person(
    name = "Alex Katlein",
    home = "Vienna, Austria",
    age = 28,
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
