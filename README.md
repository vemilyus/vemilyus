<h4>

```kotlin
import io.v47.misc.DriverLicense
import io.v47.misc.Person
import io.v47.misc.Experience

val workExperience = Experience(
    languages = listOf("Kotlin", "TypeScript", "Rust", "JavaScript", "Regex"),
    runtimes = listOf("JVM", "Node.js"),
    libraries = listOf("Micronaut", "Spring", "Vue", "React", "Angular", "AWS SDK"),
    databases = listOf("PostgreSQL", "Oracle", "MySQL", "Teradata"),
    tools = listOf("Docker", "AWS CDK", "IDEA", "Linux"),
    isEmployed = true
)

val personalExperience = Experience(
    languages = listOf("English", "German", "ActionScript 3", "Python"),
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
