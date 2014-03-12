#Maven Repository

Add the releases and snapshot repositories to your Maven settings.xml or to your projects pom.xml.

    <repositories>
        ...
        <repository>
            <id>linch-releases</id>
            <name>Linch Releases Repository</name>
            <url>https://github.com/linchproject/mvn-repo/raw/master/releases</url>
        </repository>
        <repository>
            <id>linch-snapshots</id>
            <name>Linch Snapshots Repository</name>
            <url>https://github.com/linchproject/mvn-repo/raw/master/snapshots</url>
        </repository>
        ...
    </repositories>
