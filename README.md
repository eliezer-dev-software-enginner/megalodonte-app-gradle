# Megalodonte App Using Gradle

This project is a base project for developing Megalodonte/JavaFX applications, which already includes HotReload configured by default.

It also includes Gradle scripts for generating native desktop applications for Windows (.exe and .msi) and Linux (.deb).

## Features

- Java 25
- JavaFX 17
- Integrated HotReload for rapid development

## Megalodonte Dependencies

```
megalodonte:megalodonte-base:1.0.0-beta
megalodonte:megalodonte-components:1.0.0-beta
megalodonte:megalodonte-reactivity:1.0.0-beta
megalodonte:megalodonte-router:1.0.0-beta
megalodonte:megalodonte-theme:1.0.0-beta
```

## Get Started

1. Download the project [clicking here](https://github.com/eliezer-dev-software-enginner/megalodonte-app-gradle/releases/download/app/megalodonte-startup.zip)
2. Extract the zip and open the **`megalodonte-app-gradle`** folder in your favorite IDE
3. Go to **Gradle > Tasks > megalodonte** and run **`compileMegalodonteDeps`** to publish all dependencies locally
4. Then just run the project with **`./gradlew run`** or via your IDE's run button

## Credits

Developed by [Eliezer Software Engineer](https://github.com/eliezer-software-enginner)