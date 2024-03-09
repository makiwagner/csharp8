* Execute os comandos a seguir:
dotnet new web -o TodoApi
cd TodoApi
code -r ../TodoApi

* Confie no certificado de desenvolvimento HTTPS executando o seguinte comando:
dotnet dev-certs https --trust

* Execute o comando a seguir para iniciar o aplicativo no perfil https:
dotnet run --launch-profile https

* Adicionar pacotes do nuget
dotnet add package Microsoft.EntityFrameworkCore.InMemory
dotnet add package Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore

