This is an example application of my blog post titled Getting Started with Gradle: Working with Dependencies (Not published yet)

You can package the application by running one of the following commands at command prompt:

    gradle assemble (runs only the tasks required to create the jar file)
    gradle build (runs the full build)

Both commands create a jar file called _working-with-dependencies.jar_ to the _build_ directory.
    
You can run the application by running the following command at command prompt:

    java -jar working-with-dependencies.jar