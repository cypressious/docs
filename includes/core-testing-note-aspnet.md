>[!IMPORTANT]
>If you're _not_ using the **.NET Core 3.0 SDK**, you must add two additional package references,`Microsoft.AspNetCore.App` and `Microsoft.AspNetCore.Mvc.Testing`.
>
>```
>dotnet add package Microsoft.AspNetCore.App
>dotnet add package Microsoft.AspNetCore.Mvc.Testing
>```
>
>If you're using the **.NET Core 2.1 SDK** or earlier, also set the SDK type in the testing project file to the web SDK
>
>```xml
><Project Sdk="Microsoft.NET.Sdk.Web">
>```