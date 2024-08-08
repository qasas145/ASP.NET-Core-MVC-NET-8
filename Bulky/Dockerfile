from mcr.microsoft.com/dotnet/sdk:7.0

WORKDIR /app

# COPY  .  ./
WORKDIR /app/BulkyWeb
# run dotnet restore


EXPOSE 5184


# CMD [ "dotnet" , "./output/BulkyBookWeb.dll"]
cmd ["dotnet", "watch", "run"]

