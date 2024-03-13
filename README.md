# .NET Sonatype SCA Results 


Note: bom.xml maps transitive dependencies. 

### Resources
- https://www.nuget.org/packages/CycloneDX/
- https://github.com/CycloneDX/cyclonedx-dotnet



dotnet restore
dotnet tool install --global CycloneDX
dotnet CycloneDX SonatypeSCA\SonatypeSCA.csproj -o SonatypeSCA\
