## GitHub Packages

### Add the following keys to your local.properties

| *Key* | *Description* |
|-------|---------------|
|gpr.user|Your GitHub Personal Access Token username|
|gpr.key|Your GitHub Personal Access Token password|
|github.organization|The GitHub organization to which you want to publish such as `readdle` or `heliumfoot`|

### Set The Version
Update this line in build.gradle
```
version = '1.4.0'
```

### Publish with Gradle
```
./gradlew publishMavenJavaPublicationToGitHubPackagesRepository
```


