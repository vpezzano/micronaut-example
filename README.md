# micronaut-example
Example of building a microservice with Micronaut.
First, the Micronauto CLI has to be installed. Then, we can use the command:
mn --help
to get help. The project skeleton can be created with the command:
mn create-app micronaut-example.
This will generate a Gradle project. To create a Maven project, run:
mn create-app micronaut-example --build maven.
After moving inside the project folder, the controller can be created via the command:
mn create-controller HelloController.