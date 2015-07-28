# ASPNET5UnitTestSample
Unit Test template sample for ASP.NET 5. This was built with ASP.NET 5 Beta5 and works with Beta6 as well.
To run from command line do:
- Open the developer command prompt and set a version of .NET Version Manager (DNVM)
- dnvm use 1.0.0-beta6
- navigate to your project directory
- dnu restore
- dnx . test

To run from VS:
- You can launch the project with the test command

To run from Test Explorer:
- Install this package: xunit.runner.visualstudio version:2.1.0-beta3-build1069
- Goto Test Explorer and run all your tests

