FROM microsoft/dotnet:2.2-aspnetcore-runtime
COPY dist /app
WORKDIR /app
EXPOSE 80
EXPOSE 443
ENTRYPOINT ["dotnet","F19ITONK.ASPNETCore.MicroService.SecondFrontEnd.dll"]