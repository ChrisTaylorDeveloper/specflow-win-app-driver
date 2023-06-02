# SpecFlow WinAppDriver

A sample / boilerplate project.  Attempting to run the Windows Application Driver with SpecFlow and MSTest.

Genesis was https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-mstest

Development environment
```
docker run -it \
--volume $(pwd):/source \
--workdir /source \
mcr.microsoft.com/dotnet/sdk:6.0
```

Run tests
```
dotnet test
```
