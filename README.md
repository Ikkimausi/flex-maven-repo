This repo can be included as a plugin repository:

<pluginRepository>
	<id>flex-maven-repo</id>
	<name>Flex Maven Repo on GitHub</name>
	<url>https://raw.github.com/Ikkimausi/flex-maven-repo/master</url>
	<releases>
		<enabled>true</enabled>
	</releases>
	<snapshots>
		<enabled>false</enabled>
	</snapshots>
</pluginRepository>

Or, a regular repository:

<repository>
	<id>flex-maven-repo</id>
	<url>https://raw.github.com/Ikkimausi/flex-maven-repo/master</url>
	<releases>
		<enabled>true</enabled>
	</releases>
	<snapshots>
		<enabled>false</enabled>
	</snapshots>
</repository>
