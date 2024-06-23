# HelloWorldApp

This is a simple .NET Core application. The project demonstrates the structure of a basic .NET Core application along with a CI/CD pipeline using GitHub Actions.

## dotnet-core-ci.yml
Steps:
1.Checkout code: This step checks out the code from the repository.
2.Install .NET SDK: This step installs the specified version of the .NET SDK.
3.Set .NET SDK version: This step verifies the installed .NET SDK version.
4.Restore dependencies: This step restores the dependencies for the project.
5.Build: This step builds the project in Release configuration.
6.Test: This step runs the tests for the project without rebuilding.
7.Publish: This step publishes the project to the specified output directory.
8.Output message: This step outputs a message indicating the build and publish process completed successfully.
