# BlazorWasmSuperHeroApi
Projeto acadêmico em C# e Blazor WebAssembly, baseado no roteiro de consumo da SuperHero API.

## Executar
Instale o SDK .NET 10 e execute `dotnet restore` e `dotnet run` na pasta do projeto. Abra o endereço exibido no terminal. Gere seu token em https://superheroapi.com/ e informe-o na tela. Pesquise por Batman, por exemplo.

O token não é armazenado no repositório. Como o projeto é WebAssembly, ele fica acessível ao próprio navegador durante a consulta. A API precisa permitir requisições CORS. A URL usada segue a correção da aula (`https://www.superheroapi.com/api.php`).
