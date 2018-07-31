FROM  microsoft/dotnet:2.0-sdk
WORKDIR /app

COPY . ./
RUN dotnet publish -o /publish

ENTRYPOINT ["dotnet", "DotNetCoreTestApp.dll"]
