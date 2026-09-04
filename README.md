# 🚀 Mini Guia de Estudos — APIs REST com ASP.NET Core

> Projeto desenvolvido como parte de um Desafio de Projeto da DIO, utilizando Inteligência Artificial como ferramenta de aprendizagem ativa por meio do NotebookLM.

## 📌 Sobre o projeto

Este projeto apresenta um **Caderno Temático sobre desenvolvimento de APIs REST utilizando ASP.NET Core**.

A proposta foi utilizar o **NotebookLM como ferramenta de apoio ao estudo**, realizando uma curadoria de fontes, elaboração de perguntas estratégicas, comparação de respostas e organização dos conhecimentos adquiridos em um guia de consulta rápida.

O projeto também foi estruturado para demonstrar não apenas o resultado final, mas o processo de aprendizagem e a utilização consciente da Inteligência Artificial.

---

# 🎯 Contexto e Objetivos

## Contexto

As APIs REST são amplamente utilizadas no desenvolvimento de sistemas modernos, permitindo que diferentes aplicações se comuniquem por meio de protocolos e padrões bem definidos.

O **ASP.NET Core**, plataforma da Microsoft para desenvolvimento de aplicações modernas com .NET, oferece recursos para criação de APIs robustas, escaláveis e multiplataforma.

Escolhi esse tema por sua importância no desenvolvimento Back-end e por estar diretamente relacionado ao desenvolvimento de aplicações utilizando **C# e .NET**.

## Objetivos

Os principais objetivos deste estudo foram:

* Compreender os fundamentos de APIs REST.
* Entender o funcionamento do protocolo HTTP.
* Aprender como estruturar uma Web API utilizando ASP.NET Core.
* Compreender Controllers, endpoints e rotas.
* Estudar o uso de DTOs.
* Entender o Entity Framework Core.
* Conhecer conceitos de Injeção de Dependência.
* Compreender autenticação utilizando JWT.
* Estudar boas práticas para desenvolvimento de APIs.
* Utilizar Inteligência Artificial como ferramenta de aprendizagem.
* Desenvolver uma metodologia de estudo baseada em perguntas, análise e validação das respostas.

---

# 🤖 Utilização do NotebookLM

O NotebookLM foi utilizado como uma ferramenta de **aprendizagem ativa**, e não apenas como um gerador de respostas.

O processo foi dividido em etapas:

```text
Curadoria das fontes
        ↓
Upload das fontes no NotebookLM
        ↓
Elaboração dos primeiros prompts
        ↓
Análise das respostas
        ↓
Identificação de lacunas
        ↓
Refinamento dos prompts
        ↓
Comparação e validação
        ↓
Consolidação do conhecimento
        ↓
Criação deste Mini Guia
```

A utilização do NotebookLM permitiu consultar as fontes selecionadas e formular perguntas direcionadas para facilitar a compreensão dos conceitos.

---

# 📚 Curadoria de Fontes

Foram selecionadas fontes abertas e preferencialmente oficiais ou tecnicamente reconhecidas.

## 1. Documentação oficial do ASP.NET Core

**Microsoft Learn — ASP.NET Core**

https://learn.microsoft.com/aspnet/core/

Principal fonte utilizada para compreender os fundamentos do ASP.NET Core, criação de aplicações Web e APIs.

---

## 2. Documentação oficial sobre APIs Web

**Microsoft Learn — Create web APIs with ASP.NET Core**

https://learn.microsoft.com/aspnet/core/web-api/

Fonte utilizada para estudar criação de APIs, controllers, routing, respostas HTTP e estrutura de Web APIs.

---

## 3. Documentação oficial do Entity Framework Core

**Microsoft Learn — Entity Framework Core**

https://learn.microsoft.com/ef/core/

Fonte utilizada para compreender o funcionamento do ORM Entity Framework Core, acesso a banco de dados, entidades e operações de persistência.

---

## 4. Documentação sobre autenticação e autorização

**Microsoft Learn — Authentication and authorization in ASP.NET Core**

https://learn.microsoft.com/aspnet/core/security/

Fonte utilizada para estudar conceitos relacionados à segurança de aplicações ASP.NET Core, autenticação e autorização.

---

## 5. HTTP — MDN Web Docs

**MDN Web Docs — HTTP**

https://developer.mozilla.org/docs/Web/HTTP

Fonte complementar utilizada para compreender os fundamentos do protocolo HTTP, métodos, códigos de status, requisições e respostas.

---

# 🧠 Engenharia de Prompts

Uma das etapas mais importantes do projeto foi perceber que **a qualidade da resposta da IA depende diretamente da qualidade da pergunta realizada**.

Por isso, foram utilizados diferentes níveis de prompts.

---

## Prompt 01 — Pergunta inicial

```text
Explique o que é ASP.NET Core e para que ele é utilizado.
```

### Objetivo

Obter uma visão inicial e geral sobre o assunto.

### Resultado esperado

Uma explicação introdutória sobre o ASP.NET Core e suas principais aplicações.

### Limitação encontrada

Uma pergunta muito ampla pode gerar uma resposta superficial e abordar muitos conceitos ao mesmo tempo.

---

# 🔎 Prompt 02 — Aprofundamento

```text
Com base nas fontes disponíveis neste notebook, explique o que é ASP.NET Core,
quais são suas principais características e como ele é utilizado para construir
APIs REST. Organize a resposta em tópicos e cite as fontes utilizadas.
```

### Melhoria

O segundo prompt apresenta:

* contexto;
* objetivo;
* formato esperado;
* restrição às fontes;
* necessidade de referências.

Isso torna a resposta mais direcionada.

---

# 🧩 Prompt 03 — Explicação para estudo

```text
Explique o funcionamento de uma API REST em ASP.NET Core como se estivesse
ensinando um estudante que já conhece C#, mas ainda está começando no
desenvolvimento de APIs.

Utilize exemplos conceituais e explique:
1. HTTP
2. Endpoint
3. Controller
4. Routing
5. GET
6. POST
7. PUT
8. DELETE
9. Status Codes
```

### Objetivo

Adaptar a explicação ao nível de conhecimento do estudante.

---

# 🛠️ Prompt 04 — Aprendizagem prática

```text
Com base nas fontes deste notebook, crie um roteiro de estudo para desenvolver
uma API REST simples utilizando ASP.NET Core.

O roteiro deve abordar:
- criação do projeto;
- estrutura da aplicação;
- controllers;
- endpoints;
- DTOs;
- Entity Framework Core;
- banco de dados;
- validação;
- tratamento de erros;
- autenticação;
- testes.

Organize do nível iniciante ao intermediário.
```

### Objetivo

Transformar o conteúdo teórico em uma sequência prática de aprendizagem.

---

# 🔬 Prompt 05 — Pensamento crítico

```text
Analise as informações apresentadas nas fontes e identifique possíveis
confusões que um estudante iniciante poderia ter ao aprender ASP.NET Core
e APIs REST.

Para cada possível confusão:
- explique o problema;
- apresente a diferença entre os conceitos;
- dê um exemplo;
- indique qual fonte sustenta a explicação.
```

### Objetivo

Utilizar a IA não apenas para obter respostas, mas para identificar possíveis dificuldades durante o aprendizado.

---

# 🩹 "Cicatrizes" do processo

Durante o processo de estudo, alguns problemas podem surgir ao utilizar IA como ferramenta de aprendizagem.

## Cicatriz 01 — Pergunta muito ampla

### Problema

Perguntas genéricas podem produzir respostas extensas, porém pouco aprofundadas.

### Solução

Dividir o assunto em perguntas menores e específicas.

---

## Cicatriz 02 — Excesso de conceitos em uma única pergunta

### Problema

Solicitar que vários conceitos sejam explicados simultaneamente pode fazer com que alguns sejam tratados de forma superficial.

### Solução

Separar os assuntos em etapas:

```text
HTTP
 ↓
REST
 ↓
ASP.NET Core
 ↓
Controllers
 ↓
Entity Framework Core
 ↓
Autenticação
```

---

## Cicatriz 03 — Respostas sem contexto

### Problema

Uma resposta tecnicamente correta pode não estar adequada ao nível de conhecimento do estudante.

### Solução

Informar no prompt:

* conhecimento prévio;
* objetivo;
* nível de dificuldade;
* formato desejado.

---

## Cicatriz 04 — Necessidade de validação

### Problema

Uma resposta gerada por IA não deve ser automaticamente considerada verdadeira.

### Solução

Comparar a resposta com as fontes utilizadas no NotebookLM, principalmente documentação oficial.

---

# 📖 MINI GUIA DE ESTUDO

# 1. O que é uma API?

API significa **Application Programming Interface**.

Uma API permite que diferentes sistemas ou componentes de software se comuniquem utilizando regras previamente definidas.

Por exemplo:

```text
Frontend
   ↓
HTTP Request
   ↓
API ASP.NET Core
   ↓
Banco de Dados
   ↓
API
   ↓
HTTP Response
   ↓
Frontend
```

---

# 2. O que é REST?

REST significa **Representational State Transfer**.

É um estilo arquitetural utilizado para projetar serviços que utilizam recursos acessíveis através de operações HTTP.

Uma API REST normalmente trabalha com recursos.

Exemplo:

```text
/api/usuarios
/api/produtos
/api/tarefas
```

---

# 3. Métodos HTTP

Os principais métodos utilizados em APIs REST são:

| Método | Função                 |
| ------ | ---------------------- |
| GET    | Consultar dados        |
| POST   | Criar um recurso       |
| PUT    | Atualizar um recurso   |
| PATCH  | Atualizar parcialmente |
| DELETE | Excluir um recurso     |

Exemplo:

```http
GET /api/tarefas
```

Consulta as tarefas.

```http
POST /api/tarefas
```

Cria uma nova tarefa.

```http
DELETE /api/tarefas/10
```

Remove a tarefa de ID 10.

---

# 4. Status Codes

Os códigos HTTP indicam o resultado de uma requisição.

### 2xx — Sucesso

```text
200 OK
201 Created
204 No Content
```

### 4xx — Erro do cliente

```text
400 Bad Request
401 Unauthorized
403 Forbidden
404 Not Found
```

### 5xx — Erro do servidor

```text
500 Internal Server Error
```

Conhecer os códigos HTTP é importante para construir APIs previsíveis e fáceis de consumir.

---

# 5. ASP.NET Core

O ASP.NET Core é uma plataforma para construção de aplicações Web utilizando .NET.

Uma aplicação pode ser estruturada utilizando componentes como:

```text
Controllers
Services
Models
DTOs
Repositories
Data
Middlewares
```

A divisão de responsabilidades ajuda a manter o código organizado e facilita manutenção e testes.

---

# 6. Controllers

Controllers recebem requisições HTTP e normalmente são responsáveis por definir os endpoints da API.

Exemplo conceitual:

```csharp
[ApiController]
[Route("api/[controller]")]
public class ProdutosController : ControllerBase
{
    [HttpGet]
    public IActionResult Get()
    {
        return Ok();
    }
}
```

Nesse exemplo, o controller disponibiliza um endpoint HTTP GET.

---

# 7. Routing

Routing determina qual código deve ser executado quando uma requisição chega à aplicação.

Exemplo:

```text
GET /api/produtos
```

pode ser direcionado para:

```csharp
[HttpGet]
public IActionResult Get()
```

Uma rota também pode receber parâmetros:

```text
GET /api/produtos/10
```

---

# 8. DTO

DTO significa **Data Transfer Object**.

É um objeto utilizado para transportar dados entre diferentes partes da aplicação.

Uma API pode utilizar DTOs para evitar expor diretamente suas entidades de banco de dados.

Exemplo:

```csharp
public class ProdutoDto
{
    public string Nome { get; set; }
    public decimal Preco { get; set; }
}
```

---

# 9. Entity Framework Core

O **Entity Framework Core** é um ORM para aplicações .NET.

ORM significa **Object-Relational Mapping**.

Ele permite trabalhar com dados relacionais utilizando objetos e classes do C#.

Fluxo simplificado:

```text
Classe C#
   ↓
Entity Framework Core
   ↓
SQL
   ↓
Banco de Dados
```

Entre seus recursos estão:

* entidades;
* DbContext;
* migrations;
* consultas;
* relacionamentos;
* operações CRUD.

---

# 10. Injeção de Dependência

A Injeção de Dependência é um padrão utilizado para fornecer dependências às classes em vez de criá-las diretamente dentro delas.

Exemplo conceitual:

```text
Controller
    ↓
Service
    ↓
Repository
    ↓
Database
```

Isso ajuda a reduzir o acoplamento e facilita testes e manutenção.

---

# 11. Autenticação e JWT

JWT significa **JSON Web Token**.

É um formato utilizado para transportar informações relacionadas à identidade e autorização entre sistemas.

Em uma aplicação autenticada, um fluxo simplificado pode ser:

```text
Usuário
   ↓
Login
   ↓
API
   ↓
Validação
   ↓
JWT
   ↓
Cliente
```

Nas próximas requisições, o token pode ser enviado para que a API identifique e autorize o usuário.

---

# 12. CRUD

CRUD representa as quatro operações básicas de persistência:

```text
C → Create
R → Read
U → Update
D → Delete
```

Em uma API:

```text
POST   → Create
GET    → Read
PUT    → Update
DELETE → Delete
```

---

# 13. Boas práticas

Algumas práticas importantes para APIs incluem:

* utilizar nomes de rotas consistentes;
* utilizar corretamente os métodos HTTP;
* retornar status codes apropriados;
* utilizar DTOs quando necessário;
* validar entradas;
* evitar expor informações sensíveis;
* separar responsabilidades;
* utilizar tratamento adequado de exceções;
* documentar a API;
* implementar autenticação e autorização quando necessário;
* manter as dependências atualizadas;
* escrever testes.

---

# 📚 Glossário

| Conceito             | Definição                                                 |
| -------------------- | --------------------------------------------------------- |
| API                  | Interface que permite comunicação entre sistemas          |
| REST                 | Estilo arquitetural para serviços distribuídos            |
| HTTP                 | Protocolo utilizado na comunicação Web                    |
| Endpoint             | Ponto de acesso de uma API                                |
| Controller           | Componente responsável por tratar requisições             |
| Route                | Caminho utilizado para acessar um recurso                 |
| DTO                  | Objeto utilizado para transferência de dados              |
| ORM                  | Tecnologia que relaciona objetos com dados relacionais    |
| Entity               | Representação de uma entidade da aplicação                |
| DbContext            | Principal classe de interação do EF Core com o banco      |
| Migration            | Mecanismo para evolução do modelo do banco                |
| CRUD                 | Create, Read, Update e Delete                             |
| JWT                  | JSON Web Token                                            |
| Middleware           | Componente que participa do processamento das requisições |
| Dependency Injection | Técnica para fornecer dependências às classes             |
| Status Code          | Código HTTP que representa o resultado da requisição      |
| JSON                 | Formato de dados muito utilizado em APIs                  |

---

# ♻️ Prompts Reutilizáveis

## Revisão rápida

```text
Com base nas fontes deste notebook, faça uma revisão sobre [CONCEITO].
Explique os pontos mais importantes em linguagem simples e termine com
5 perguntas para testar meu conhecimento.
```

## Explicação aprofundada

```text
Explique [CONCEITO] de forma aprofundada, considerando que já conheço C#
mas ainda estou desenvolvendo conhecimentos em ASP.NET Core.

Apresente:
- definição;
- funcionamento;
- exemplo;
- vantagens;
- limitações;
- erros comuns;
- boas práticas.
```

## Comparação

```text
Compare [CONCEITO A] e [CONCEITO B].

Mostre:
- diferenças;
- semelhanças;
- quando utilizar cada um;
- vantagens;
- desvantagens;
- exemplo prático.
```

## Exercícios

```text
Crie 10 exercícios sobre [CONCEITO], começando no nível iniciante e
aumentando gradualmente a dificuldade.

Não forneça as respostas inicialmente.
Depois que eu responder, corrija meus erros e explique os conceitos
que eu não compreendi.
```

## Simulação de entrevista

```text
Simule uma entrevista técnica para uma vaga de Desenvolvedor Backend .NET.

Faça uma pergunta por vez sobre:
- C#;
- ASP.NET Core;
- APIs REST;
- Entity Framework Core;
- SQL;
- autenticação;
- boas práticas.

Avalie minha resposta e explique como eu poderia melhorar.
```

## Identificação de lacunas

```text
Analise meu conhecimento sobre [CONCEITO] com base nas respostas que eu
fornecer.

Identifique:
1. conceitos que domino;
2. conceitos que compreendo parcialmente;
3. conceitos que preciso estudar novamente.

Depois crie um plano de revisão baseado nas minhas dificuldades.
```

---

# 📊 O que foi aprendido

Ao final do estudo, os principais conhecimentos consolidados foram:

* funcionamento básico de APIs REST;
* comunicação através do protocolo HTTP;
* utilização dos principais métodos HTTP;
* interpretação de status codes;
* estrutura de uma Web API em ASP.NET Core;
* utilização de Controllers e Routing;
* importância dos DTOs;
* funcionamento básico do Entity Framework Core;
* conceitos de CRUD;
* Injeção de Dependência;
* fundamentos de autenticação com JWT;
* importância da validação e tratamento de erros;
* utilização de IA como ferramenta complementar de aprendizagem.

---

# 💡 Reflexão sobre o uso da Inteligência Artificial

A utilização do NotebookLM mostrou que a Inteligência Artificial pode ser utilizada como uma ferramenta de estudo quando existe uma metodologia por trás das perguntas.

Em vez de simplesmente solicitar uma resposta pronta, o processo foi baseado em:

```text
Perguntar
   ↓
Analisar
   ↓
Questionar
   ↓
Comparar fontes
   ↓
Identificar lacunas
   ↓
Refinar perguntas
   ↓
Consolidar conhecimento
```

Uma das principais conclusões foi que a IA não substitui a necessidade de estudar e verificar informações. Ela pode acelerar a compreensão, organizar conteúdos e ajudar a identificar dúvidas, mas as respostas precisam ser analisadas criticamente e confrontadas com fontes confiáveis.

---

# 🚀 Conclusão

Este projeto permitiu consolidar conhecimentos fundamentais sobre o desenvolvimento de APIs REST utilizando ASP.NET Core e, ao mesmo tempo, experimentar uma metodologia de aprendizagem baseada em Inteligência Artificial.

A construção do Caderno Temático possibilitou transformar diferentes fontes de estudo em um material organizado, com conceitos, exemplos, glossário e prompts reutilizáveis.

Além do conhecimento técnico, o projeto também reforçou a importância de saber **formular boas perguntas, avaliar respostas geradas por IA e validar informações utilizando fontes confiáveis**.

---

# 🛠️ Tecnologias e Ferramentas

* C#
* .NET
* ASP.NET Core
* Entity Framework Core
* APIs REST
* HTTP
* JWT
* SQL
* NotebookLM
* Git
* GitHub

---

# 👨‍💻 Autor

**Ruan**

Estudante de Análise e Desenvolvimento de Sistemas, com foco em desenvolvimento Back-end e tecnologias do ecossistema .NET.

---

## 📌 Projeto desenvolvido para a DIO

Este repositório foi desenvolvido como parte de um **Desafio de Projeto da Digital Innovation One (DIO)**, com foco na utilização de Inteligência Artificial como ferramenta de aprendizagem ativa.

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!
