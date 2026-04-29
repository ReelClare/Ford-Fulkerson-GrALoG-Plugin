## Ford-Fulkerson-GrALoG-Plugin

---

### Installation Existing Users

For those who already use GrALoG and have a number of your own plugins installed,
the easiest path is to add the new plugin folder and upgrade various existing GrALoG Files:

#### Plugin Folder

Copy the Installation-Existing-Users/gralog-max-flow folder to your GrALoG root folder, the folder should contain gradlew and gradlew.bat files.

#### Upgrade Existing GrALoG files

1. Copy Installation-Existing/settings.gradle and Installation-Existing-Users/build.gradle files to GrALoG root folder, (yourRootname)
2. Copy Installation-Existing/config.xml to (yourRootname)\gralog-fx\src\main\java\gralog\gralogfx\
3. Copy Installation-Existing/EdgeRenderer.java to (yourRootname)\gralog-core\src\main\java\gralog\rendering\
4. Copy Installation-Existing/MainWindow.java to (yourRootname)\gralog-fx\src\main\java\gralog\gralogfx\
5. Copy Installation-Existing/MaxFlowLegendPanel.java to (yourRootname)\gralog-fx\src\main\java\gralog\gralogfx\ (this is a new file)
6. Copy Installation-Existing/PluginControlPanel.java to (yourRootname)\gralog-fx\src\main\java\gralog\gralogfx\panels\

### Installation for New Users

For those new to GrALoG, a precompiled "gralog-fx.jar" file is available for Linux, Windows and MacOS.

You do not need to install GrALoG, simply copy the contents of the appropriate distribution folder for your OS, Installation-New/dist-{OS} to a suitable folder.

1. Copy contents of Installation-New/dist-{OS} folder into a suitable location
2. Navigate to the gralog-fx.jar file

This can be run by double clicking.

PLEASE NOTE:
Java version JRE 11 is needed to run GrALoG.
This is available for download <a href="https://jdk.java.net/java-se-ri/11-MR3" target="_blank">HERE</a>

If you are having trouble running GrALoG, ensure that you are running version 11 of Java using `java --version`

If you are on Linux and are struggling to run GrALoG, try running
`java -jar gralog-fx.jar`

All alterations to pre-existing GrALoG files are annotated with the phrase "MAXFLOW".

GrALoG software available <a href="https://github.com/gralog/gralog" target="_blank">HERE</a>.
