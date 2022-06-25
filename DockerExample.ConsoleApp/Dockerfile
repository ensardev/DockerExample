FROM mcr.microsoft.com/dotnet/runtime:6.0
WORKDIR /App
COPY bin/Release/net6.0/publish App/
ENTRYPOINT ["dotnet", "DockerExample.ConsoleApp.dll"]