We use `depends` attribute on target to execute the tasks mentioned first.
In the example [build.xml](build.xml) task `world` depends on `hello` task.
This will be useful in the later parts where we would want to compile the classes before creating a jar.