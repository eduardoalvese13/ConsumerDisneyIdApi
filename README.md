# ConsumerDisneyIdApi

Aplicação console em **C# (.NET 10)** que consome a [Disney API](https://disneyapi.dev/) para buscar informações de um personagem Disney pelo seu ID.

## Descrição

O programa realiza uma requisição HTTP GET ao endpoint `https://api.disneyapi.dev/character/423` e exibe no console o **nome** e a **URL da imagem** do personagem retornado (Big Bad Wolf).

## Tecnologias Utilizadas

- C# / .NET 10
- `System.Net.Http` (HttpClient)
- `System.Text.Json` (serialização/deserialização JSON)

## Como Executar

1. Certifique-se de ter o [.NET 10 SDK](https://dotnet.microsoft.com/download) instalado.
2. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/ConsumerDisneyIdApi.git
   ```
3. Acesse a pasta do projeto:
   ```bash
   cd ConsumerDisneyIdApi
   ```
4. Execute a aplicação:
   ```bash
   dotnet run
   ```

## Exemplo de Saída

```
Nome:
Big Bad Wolf
Imagem:
https://static.wikia.nocookie.net/disney/images/3/3c/Bigbadwolf.png
```

## Estrutura do Projeto

| Arquivo | Descrição |
|---|---|
| `Program.cs` | Ponto de entrada da aplicação; realiza a chamada HTTP e exibe os dados |
| `BigBadWolf.cs` | Modelo de dados do personagem Disney |
| `ConsumerDisneyIdApi.csproj` | Arquivo de projeto .NET |

---

**Aluno:** Eduardo Alves e Santos
**RA:** 124114208
**Unidade Curricular:** UDWMJ
**Instituição:** UniBH — Engenharia de Software
**Período:** 6º Período