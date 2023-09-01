``` kotlin

val bchmsl = Developer.Builder()
        .firstName("Bachana")
	.lastName("Mosulishvili")
        .age(Time.THIS_YEAR - 2002)
        .skills(
            mainSkills = listOf("Kotlin", "Android"),
            designPatterns = Pattern.MVVM,
            architecturePatterns = Pattern.CLEAN,
            architectures = listOf("Monolithic", "Modular"),
            otherSkills = listOf(
                JetpackCompose::class,
                unitTest,
            )
        ).experience(
            Personal(time = (2021.09f..Time.NOW)),
            Working(
                SpaceInternational(time = (2023.04f..Time.NOW))
            )
        ).contact(
            Facebook(name = "Bachana Mosulishvili"),
            Instagram(username = "bchmsl"),
            Threads(username = instagram.username),
            LinkedIn(url = "https://www.linkedin.com/in/bchmsl/"),
            Medium(url = "https://bchmsl.medium.com/")
        ).email(email = "bachanamosulishvili@gmail.com")
        .build().run { develop() }
```
