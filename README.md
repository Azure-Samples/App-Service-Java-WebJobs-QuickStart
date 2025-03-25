# App Service Java WebJobs QuickStart

Write your first Java WebJob for App Service. This is a simple Java program that outputs some basic statistics about the machine that is currently running.

### Instructions

To deploy to App Service WebJobs, we need an executable jar file and the run.sh file. Starting with the jar file, running `mvn package` produces an executable jar file in project/target/webjob-artifact-1.0.0.jar. Then, the jar and the run.sh file must be zipped together to be run by the App Service platform as a WebJob. Running `zip webjob.zip run.sh webjob-artifact-1.0.0.jar` will produce a zip file that can then be uploaded and run on App Service.
