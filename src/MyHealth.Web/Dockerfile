FROM sriramdasbalaji/aspnetcore1.0:1.0.4
WORKDIR /app
EXPOSE 80
COPY obj/Docker/publish .  # Explicitly specify the source directory
ENTRYPOINT ["dotnet", "MyHealth.Web.dll"]

