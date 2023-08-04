``` kotlin

const val bchmsl = developer(Software) {
    about {
        name = "Bachana Mosulishvili"
        company = SpaceInternational
        company.role = ANDROID_DEVELOPER
        experience {
            working < 1
            personal 2..3
        }
    }
    skills("Kotlin", "Android")
    contact {
        github = this@bchmsl
        facebook = "Bachana Mosulishvili"
        instagram = @BCHMSL
        email = bachanaMosulishvili@Gmail
        linked.in("https://www.linkedin.com/in/bchmsl/")
    }
    init {
        develop()
    }
}

val bchmsl = Developer.Builder(ANDROID)
    .firstName("Bachana")
    .lastName("Mosulishvili")
    .skills("Kotlin", "Android")
    .experience(
        Personal(years = 3), Working(
            SpaceInternational(years = 1)
        )
    ).networks(SOCIAL) {
        listOf(
            Facebook(name = "Bachana Mosulishvili"),
            Instagram(username = "bchmsl").also {
                Threads().username = username
            },
            LinkedIn(username = "bchmsl"),
        )
    }.networks(CONTACT) {
        Email(email = "bachanamosulishvili@gmail.com")
    }.build().run {
        develop()
    }

```
