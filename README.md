	...........................................................................
	........:$$$7..............................................................
	.....==7$$$I~~...........MMMMMMMMM....DMM..........MM,........MM7......MM..
	...,?+Z$$$?=~,,:.........MMM,,,?MMM+..MMM.........,MMMM,......7MM,....MMM..
	..:+?$ZZZ$+==:,:~........MMM.....MMM..MMM.........,MMDMMM:.....,MMI..MMM...
	..++7ZZZZ?+++====,.......MMM....~MMM..MMM.........,MM??DMMM:....?MM,MMM....
	..?+OZZZ7~~~~OOI=:.......MMMMMMMMMM...MMM.........,MM?II?MMM~....DMMMM.....
	..+7OOOZ?+==+7Z$Z:.......MMM$$$I,.....MMM.........,MM??8MMM~......NMM......
	..:OOOOO==~~~+OZ+........MMM..........MMM.........,MMDMMM~........NMM......
	..,8OOOO+===+$$?,........MMM..........MMM.,,,,,...,MMMM:..........NMM......
	,,+8OOOZIIIIII=,,,,,,,,,,MMM,,,,,,,,,,NMMMMMMMMM=,,MM:,,,,........8MM......
	,,,:O8OO~+~:,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,
	,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,
	,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,
													  ASCII Art: GlassGiant.com

play-parent
===========
The Maven parent for the PLAY project.

Usage
-----
The parent POM is in Maven Central. If you need SNAPSHOT versions of the parent (and
of other PLAY components) please add this repository to your `$HOME/.m2/settings.xml`:

```xml
<settings>
	<profiles>
		<profile>
			<id>default-profile</id>
			<activation>
				<activeByDefault>TRUE</activeByDefault>
			</activation>
			<repositories>
				<repository>
					<releases>
						<enabled>false</enabled>
					</releases>
					<id>ow2-snapshot</id>
					<name>OW2 Snapshot Repository</name>
					<url>http://repository.ow2.org/nexus/content/repositories/snapshots</url>
				</repository>
			</repositories>
		</profile>
	</profiles>
</settings>
```


Issues
------
For issues and bug reporting, please go to https://github.com/play-project/play/issues?labels=&page=1&state=open
