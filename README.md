﻿# MicroservicesArchitecture
1) Created the solution/project and references:

dotnet new sln -n MicroservicesArchitecture

dotnet new classlib -n UserService.Domain
dotnet new classlib -n UserService.Application
dotnet new webapi -n UserService.API
dotnet new classlib -n UserService.Infrastructure

mkdir UserService

dotnet sln add UserService/UserService.Domain/UserService.Domain.csproj
dotnet sln add UserService/UserService.Application/UserService.Application.csproj
dotnet sln add UserService/UserService.API/UserService.API.csproj
dotnet sln add UserService/UserService.Infrastructure/UserService.Infrastructure.csproj

dotnet new classlib -n UserService/OrderService.Domain
dotnet new classlib -n UserService/OrderService.Application
dotnet new webapi -n UserService/OrderService.API
dotnet new classlib -n UserService/OrderService.Infrastructure

dotnet sln add UserService/OrderService.Domain/OrderService.Domain.csproj
dotnet sln add UserService/OrderService.Application/OrderService.Application.csproj
dotnet sln add UserService/OrderService.API/OrderService.API.csproj
dotnet sln add UserService/OrderService.Infrastructure/OrderService.Infrastructure.csproj

mkdir OrderService 

dotnet new classlib -n OrderService/OrderService.Domain
dotnet new classlib -n OrderService/OrderService.Application
dotnet new webapi -n OrderService/OrderService.API
dotnet new classlib -n OrderService/OrderService.Infrastructure

dotnet sln add OrderService/OrderService.Domain/OrderService.Domain.csproj
dotnet sln add OrderService/OrderService.Application/OrderService.Application.csproj
dotnet sln add OrderService/OrderService.API/OrderService.API.csproj
dotnet sln add OrderService/OrderService.Infrastructure/OrderService.Infrastructure.csproj

mkdir ProductService

dotnet new classlib -n ProductService/ProductService.Domain
dotnet new classlib -n ProductService/ProductService.Application
dotnet new webapi -n ProductService/ProductService.API
dotnet new classlib -n ProductService/ProductService.Infrastructure

dotnet sln add ProductService/ProductService.Domain/ProductService.Domain.csproj
dotnet sln add ProductService/ProductService.Application/ProductService.Application.csproj
dotnet sln add ProductService/ProductService.API/ProductService.API.csproj
dotnet sln add ProductService/ProductService.Infrastructure/ProductService.Infrastructure.csproj



