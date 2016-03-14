Svelto Eclipse plugin
=====================

Svelto is an lightweight monitoring tool for Eclipse. It constantly checks the UI thread
and automatically saves a thread dump when the UI thread is unresponsive for a (configurable)
period of time.

You can configure the amount of time before saving a thread dump, and the directory where to
save this file. The file is never erased, so you may want to delete it from time to time.

# Installation

Point Eclipse to the following update site:

    http://download.scala-ide.org/plugins/svelto/releases/2.11.x/site

# Build

Run maven like this:

    mvn -P scala-2.11.x -Dscala.version=2.11.8 clean install

# Hack

Eclipse project files are provided, so you can directly use `Import Existing projects inside Eclipse`.
