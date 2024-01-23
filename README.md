The `repo` directory can be used as an Ivy repository in Gradle like this:
```kts
repositories {
    ivy {
        url = uri("https://raw.githubusercontent.com/pantherdd/ivy-repo/main/repo")
        layout("ivy")
    }
}
```
