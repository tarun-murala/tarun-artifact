# tarun-artifact

Local Nexus Setup:
```
docker run -d -p 2500:8081 -v $PWD/nexus --name nexus sonatype/nexus3
```

Assuming you are running the local nexus repo in 2500

1. Create the Proxy Repo
2. Repurpose the maven-release and maven-snapshots (default shipped with nexus)

Follow the steps from the link:
https://help.sonatype.com/learning/repository-manager-3/first-time-installation-and-setup/lesson-2%3A-proxy-and-hosted-maven-repositories

Perform a release, Follow the steps from the link:
https://maven.apache.org/maven-release/maven-release-plugin/usage.html
