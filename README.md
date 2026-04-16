## Ford-Fulkerson-GrALoG-Plugin
-----

For those who already use GrALoG and have a number of your own plugins installed, 
the individual files relevant to this plugin are available in the above 
"Ford-Fulkerson GrALoG Plugin" folder. 
Please refer to the "Build" section below for instructions on how to introduce
these files to your GrALoG workspace.

For those new to GrALoG, a precompiled "gralog-fx.jar" file is available for download.
This can be run by double clicking it after downloading.

PLEASE NOTE:
Java version JRE 11 is needed to run GrALoG.
This is available for download <a href="https://adoptium.net/installation" target="_blank">HERE</a>

If you are having trouble running GrALoG, ensure that you are running the correct version of GrALoG using
`java --version`

If you are on Linux and are struggling to run GrALoG, try running
`java -jar gralog-fx.jar`

## Build
-----
Files MaxFlow.java, MaxFlowFunctions.java and plugin.xml are all pre-organised and contained within
the folder labelled gralog-max-flow. 
This folder, in addition to the settings.gradle and build.gradle files, are to be inserted into the
root of the GrALoG directory: 
Gralog\


config.xml should replace the previous GrALoG file, located 
Gralog\gralog-fx\src\main\java\gralog\gralogfx\


EdgeRenderer.java should overwrite the previous GrALoG file, located 
Gralog\gralog-core\src\main\java\gralog\rendering\


MainWindow.java should overwrite its previous version, located 
Gralog\gralog-fx\src\main\java\gralog\gralogfx\

MaxFlowLegendPanel.java should be introduced into the same location wherein PluginControlPanel.java should overwrite its previous version, at
Gralog\gralog-fx\src\main\java\gralog\gralogfx\panels\

