# ![Logo](logo.png "Logo") Tandoor API Client

<!-- Short description about the project and intention -->

## Installation

## Usage

```groovy
repositories {
    mavenCentral()
    maven {
        url = uri("https://maven.pkg.github.com/OWNER/REPOSITORY")
        credentials {
            username = findProperty("gpr.user") ?: System.getenv("GITHUB_ACTOR")
            password = findProperty("gpr.key") ?: System.getenv("GITHUB_TOKEN")
        }
    }
}

dependencies {
    implementation "net.octosystems.tandoor:tandoor-client:0.1.0"
}
```

## Configuration

## Contribution

Consider contributing? Check [Contributing](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) beforehand.

## License

[GNU GPLv3](https://spdx.org/licenses/GPL-3.0-or-later.html)


