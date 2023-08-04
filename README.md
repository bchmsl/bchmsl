``` kotlin

val bchmsl = developer(Software) {
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

```
