## Ford-Fulkerson-GrALoG-Plugin
-----

For those who already use GrALoG and have a number of your own plugins installed, 
the individual files relevant to this plugin are available in the above 
"Ford-Fulkerson GrALoG Plugin" folder. 
Please refer to the "Build" section below for instructions on how to introduce
these files to your GrALoG workspace.

For those new to GrALoG, a precompiled "gralog-fx.jar" file is available for download.
To install, download the "build" folder, and place it into the root of the GrALoG directory; 
gralog-master\

Navigate then to the gralog-fx.jar file in gralog-master\build\dist\

This can be run by double clicking it after downloading.

PLEASE NOTE:
Java version JRE 11 is needed to run GrALoG.
This is available for download <a href="https://adoptium.net/installation" target="_blank">HERE</a>

If you are having trouble running GrALoG, ensure that you are running the correct version of GrALoG using
`java --version`

If you are on Linux and are struggling to run GrALoG, try running
`java -jar gralog-fx.jar`


All alterations to pre-existing GrALoG files are annotated with the phrase "MAXFLOW".


## Your Build
-----
Files MaxFlow.java, MaxFlowFunctions.java and plugin.xml are all pre-organised and contained within
the folder labelled gralog-max-flow. 
This folder, in addition to the settings.gradle and build.gradle files, are to be inserted into the
root of the GrALoG directory: 
gralog-master\


config.xml should replace the previous GrALoG file, located 
gralog-master\gralog-fx\src\main\java\gralog\gralogfx\


EdgeRenderer.java should overwrite the previous GrALoG file, located 
gralog-master\gralog-core\src\main\java\gralog\rendering\


MainWindow.java should overwrite its previous version, located 
gralog-master\gralog-fx\src\main\java\gralog\gralogfx\

MaxFlowLegendPanel.java should be introduced into the same location wherein PluginControlPanel.java should overwrite its previous version, at
gralog-master\gralog-fx\src\main\java\gralog\gralogfx\panels\

