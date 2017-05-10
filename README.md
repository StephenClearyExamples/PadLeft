    dotnet restore
	dotnet build /p:ci=true /p:Configuration=Release
	dotnet pack -c Release --no-build
    nuget.exe push .\StephenClearyExamples.PadLeft.1.1.1.nupkg -Source https://www.nuget.org/api/v2/package