# Maven-repo for sosandstrom

Two repos are available:
* releases - [https://raw.github.com/sosandstrom/maven-repo/master/releases](https://raw.github.com/sosandstrom/maven-repo/master/releases)
* snapshots - [https://raw.github.com/sosandstrom/maven-repo/master/snapshots](https://raw.github.com/sosandstrom/maven-repo/master/snapshots)

## Repositories

You can include sosandstrom's repositories in your project's pom.xml:
~~~
    <pluginRepositories>
        <pluginRepository>
            <id>sosandstrom-github-releases</id>
            <name>sosandstrom Maven releases repo at GitHub</name>
            <releases>
                <enabled>true</enabled>
            </releases>
            <snapshots>
                <enabled>false</enabled>
            </snapshots>
            <url>https://raw.github.com/sosandstrom/maven-repo/master/releases</url>
        </pluginRepository>
    </pluginRepositories>
    <repositories>
        <repository>
            <id>sosandstrom-github-releases</id>
            <name>sosandstrom Maven releases repo at GitHub</name>
            <releases>
                <enabled>true</enabled>
            </releases>
            <snapshots>
                <enabled>false</enabled>
            </snapshots>
            <url>https://raw.github.com/sosandstrom/maven-repo/master/releases</url>
        </repository>
    </repositories>
~~~


