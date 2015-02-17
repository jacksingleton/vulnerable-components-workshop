# Java version

If you get an error that looks like this:

    org/eclipse/jetty/maven/plugin/JettyRunMojo : Unsupported major.minor version 51.0

You might need to install Java 7, and/or set your JAVA_HOME environment variable.

If you are on a Mac, try `export JAVA_HOME=$(/usr/libexec/java_home -v1.7)`, then run `mvn` again.

If this works, you can add the line to your `~/.profile` to use Java7 by default from now on.

    echo 'export JAVA_HOME=$(/usr/libexec/java_home -v1.7)' >> ~/.profile
