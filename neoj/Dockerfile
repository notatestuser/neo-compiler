FROM microsoft/dotnet:1.1.2-sdk

WORKDIR /dotnetapp
COPY . .

RUN dotnet restore
#RUN dotnet publish -c Release -o out

ENTRYPOINT ["dotnet", "run", "-c", "Release"]
