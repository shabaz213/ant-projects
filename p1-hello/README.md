# ANT stands for Another Neat Tool.

##  Invoking Ant

ANT required instructions in a XML file.
To invoke ant tool we just run ant command

> ant

By default, it looks for build.xml in the working directory.

If the build file is stored with a different name like [hello.xml](hello.xml)
To execute we have to specify the build file location using `-f` argument like below

> ant -f hello.xml

## Hierarchy of Ant XML

    -> project
        -> targets
            -> tasks

ANT build XML file contains a project which contains one or more targets.
Each target again contains one or more tasks.

In the example [hello.xml](hello.xml) a project named `hello-ant` contains target named `hello`.
The `hello` target contains an in-built task `echo`