
1. Install gradle wrapper version 4.10.2 'all' distribution
   https://docs.gradle.org/current/userguide/gradle_wrapper.html
2. Configure gradle multi-project so app module compiles, with core as a dependent project
3. Make sure unit tests compile and run in core project
4. Use the application plugin in the app project to create an application distribution
   https://docs.gradle.org/current/userguide/application_plugin.html
5. In app build, add the app/LICENSE file into the application distribution
