``` kotlin

// Hello. My name is Bachana and this is my profile.
val bchmsl = developer(Software) {
    about {
        name = "Bachana Mosulishvili"
        company = SpaceInternational()
        company.role = ANDROID_DEVELOPER
        experience {
            working < 1
            personal 2..3
        }
    }
    skills("Kotlin", "Android")
    contact {
        social {
            facebook = "Bachana Mosulishvili"
            instagram = @BCHMSL
            linked.in("https://www.linkedin.com/in/bchmsl/")
        }.also {
            github = this@bchmsl
            email = bachanaMosulishvili@Gmail
        }
    }
    // Let's get started...
    init {
        develop()
    }
}

```
