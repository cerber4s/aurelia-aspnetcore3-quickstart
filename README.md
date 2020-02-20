# [Aurelia](https://aurelia.io) and [ASP.NET Core 3.1](https://dotnet.microsoft.com/) project

## Prerequisites

- node (8.11.2)
- npm (6.13.1)
- aurelia-cli (1.2.3)
- vs2019

## Commands

Install `aurelia-cli`.

```batch
npm i aurelia-cli -g
```

Create the application.

```batch
au new aurelia-app -u -s http2,dotnet-core,typescript,vscode,scaffold-navigation
```

Install dependencies.

```batch
cd aurelia-app
npm i
```

Run the app (in 2 different command windows).

Command window 1:

```batch
dotnet run
```

Command window 2:

```batch
npm start
```

## References and Links

- [Obsoleting Microsoft.AspNetCore.SpaServices and Microsoft.AspNetCore.NodeServices](https://github.com/dotnet/aspnetcore/issues/12890)
- [Goodbye SpaServices, it was fun while it lasted](https://blogs.taiga.nl/martijn/2019/10/11/goodbye-spaservices-it-was-fun-while-it-lasted/) - Martijn Boland