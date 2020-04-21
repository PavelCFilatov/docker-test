FROM mcr.microsoft.com/dotnet/core/aspnet:3.1 AS aspnetcore
WORKDIR /app
COPY * ./
ENTRYPOINT ["dotnet", "GrpcServer.dll"]
