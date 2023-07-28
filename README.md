# Serviço Certificado

O serviço certificado é uma aplicação que permite gerar certificados para alunos. Ele foi desenvolvido utilizando a plataforma .NET e é baseado no SDK Web da Microsoft.

## Requisitos

Certifique-se de ter os seguintes requisitos instalados em seu ambiente:

- [.NET SDK 7.0](https://dotnet.microsoft.com/download/dotnet/7.0)
- [itext7](https://www.nuget.org/packages/itext7) v8.0.0
- [itext7.bouncy-castle-adapter](https://www.nuget.org/packages/itext7.bouncy-castle-adapter) v8.0.0
- [Microsoft.AspNetCore.OpenApi](https://www.nuget.org/packages/Microsoft.AspNetCore.OpenApi) v7.0.0
- [Microsoft.EntityFrameworkCore](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore) v7.0.9
- [Microsoft.AspNetCore.Authentication.JwtBearer](https://www.nuget.org/packages/Microsoft.AspNetCore.Authentication.JwtBearer) v2.2.0
- [Microsoft.EntityFrameworkCore.Tools](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Tools) v7.0.9
- [Npgsql.EntityFrameworkCore.PostgreSQL](https://www.nuget.org/packages/Npgsql.EntityFrameworkCore.PostgreSQL) v7.0.4
- [Swashbuckle.AspNetCore](https://www.nuget.org/packages/Swashbuckle.AspNetCore) v6.4.0
- identityLibMinimal (arquivo DLL localizado em Libs\identityLibMinimal.dll)

## Funcionalidades Principais

O serviço certificado oferece as seguintes funcionalidades principais:

1. Geração de certificados para alunos: O serviço permite gerar certificados para alunos com base em dados específicos, proporcionando uma maneira fácil e rápida de emitir documentos oficiais.

## Configuração

Para configurar o serviço, certifique-se de ter todas as dependências listadas acima instaladas corretamente. Além disso, verifique se o arquivo de DLL do identityLibMinimal está localizado na pasta "Libs".

## Como Executar

1. Clone este repositório em sua máquina local.
2. Navegue até a pasta do projeto e execute o seguinte comando:

```bash
dotnet run
O serviço será iniciado e estará disponível em http://localhost:5000.

##Documentação da API
O serviço certificado utiliza o pacote Swashbuckle.AspNetCore para fornecer documentação interativa da API. Após executar o serviço, você pode acessar a documentação em http://localhost:5000/swagger.

##Contribuições
Contribuições são bem-vindas! Se você quiser contribuir para este projeto, sinta-se à vontade para criar um pull request. Vamos revisar e incorporar suas alterações.
