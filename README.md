``` kotlin

val bchmsl = Developer.Builder(Developer.SOFTWARE)
    .firstName("Bachana")
    .lastName("Mosulishvili")
    .skills("Kotlin", "Android")
    .experience(
        Personal(years = (2..3)),
        Working(
            SpaceInternational(years = 1)
        )
    ).networks(Network.SOCIAL) {
        setOf(
            Facebook(name = "Bachana Mosulishvili"),
            Instagram(username = "bchmsl"),
            Threads(username = instagram.username),
            LinkedIn(username = "bchmsl")
        )
    }.networks(Network.CONTACT) {
        Email(email = "bachanamosulishvili@gmail.com")
    }.build().run {
        develop()
    }

```
