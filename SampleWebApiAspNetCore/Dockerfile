FROM microsoft/aspnetcore:2.0
COPY SampleWebApiAspNetCore\bin\Release\net5.0\SampleWebApiAspNetCore.dll app.dll
WORKDIR /app
ENTRYPOINT ["dotnet", "app.dll"]
