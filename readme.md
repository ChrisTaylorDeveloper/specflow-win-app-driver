# SpecFlow WinAppDriver

A sample / boilerplate project.  Attempting to run the Windows Application Driver with SpecFlow and MSTest.

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
