FROM microsoft/aspnetcore:2.0
COPY SampleWebApiAspNetCore/bin/Release/net5.0/ app/
WORKDIR /app
ENTRYPOINT ["dotnet", "SampleWebApiAspNetCore.dll"]
