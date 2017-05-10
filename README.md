    dotnet pack -c Release --include-symbols
    nuget.exe push .\StephenClearyExamples.PadLeft.1.0.0.nupkg -Source https://www.nuget.org/api/v2/package