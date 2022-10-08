# Wallids - .Net  - .Net core | Integration API

Developed with .Net Core 3.1.
Used in .Net 6 project.

Integrate into Startup.cs for .Net core 3.1,
Integrate into Program.cs for .Net 5 and 6

***Package Install***:
**[Nuget](https://www.nuget.org/packages/WallidsIntegration "Nuget")** 

**Monitoring & Manipulation (IPS) Model**:
```
app.Wallids(new WallidsSettings()
{
	SecretKey = "SECRET_KEY"
});
```

**Monitoring Model**:
```
app.Wallids(new WallidsSettings()
{
	SecretKey = "YOUR_SECRET_KEY",
	UseMonitoring =  True
});
```
