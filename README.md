``` kotlin
val bchmsl = Developer.Builder()
    .firstName("Bachana")
    .lastName("Mosulishvili")
    .skills("Kotlin", "Android")
    .experience(
        Personal(years = (2..3)), Working(
            SpaceInternational(years = 1)
        )
    ).contact(
        Facebook(name = "Bachana Mosulishvili"),
        Instagram(username = "bchmsl"),
        Threads(username = instagram.username),
        LinkedIn(url = "https://www.linkedin.com/in/bchmsl/")
    ).email(email = "bachanamosulishvili@gmail.com")
    .build().run { develop() }
```
