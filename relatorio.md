<<<<<<< HEAD
# Relatório de Pesquisa: Git, GitHub, Protocolos de Comunicação e Tecnologias Web

## 1. Git e GitHub

### O que é o Git?

[Git](https://git-scm.com/) é um sistema de controle de versão distribuído, criado por Linus Torvalds. Ele permite que desenvolvedores acompanhem mudanças no código-fonte, revertam alterações e colaborem em projetos de forma eficiente.

- **Função**: Controlar versões de arquivos e coordenar trabalho entre desenvolvedores.

### O que é o GitHub?

[GitHub](https://github.com/) é uma plataforma de hospedagem de código que utiliza o Git. Ele adiciona funcionalidades sociais como pull requests, issues, forks e ações automatizadas.

- **Função**: Hospedar repositórios Git e facilitar colaboração em projetos de software.

---

## 2. Protocolos de Rede e Comunicação

### HTTP (HyperText Transfer Protocol)
- **O que é**: Protocolo para transferência de dados da web.
- **Para que serve**: Comunicação entre cliente e servidor (por exemplo, navegador e site).
- **Porta padrão**: 80

### HTTPS (HTTP Secure)
- **O que é**: Versão segura do HTTP, com criptografia SSL/TLS.
- **Para que serve**: Garantir segurança e privacidade na comunicação web.
- **Porta padrão**: 443

### WebSockets
- **O que é**: Protocolo para comunicação bidirecional em tempo real.
- **Para que serve**: Aplicações que exigem atualizações em tempo real, como chats e jogos.
- **Porta padrão**: 80 (ws) e 443 (wss)

### FTP (File Transfer Protocol)
- **O que é**: Protocolo para transferência de arquivos.
- **Para que serve**: Enviar e receber arquivos entre cliente e servidor.
- **Porta padrão**: 21

### SSH (Secure Shell)
- **O que é**: Protocolo para acesso remoto seguro a sistemas.
- **Para que serve**: Acesso e controle remoto de servidores via linha de comando.
- **Porta padrão**: 22

### SSL (Secure Sockets Layer)
- **O que é**: Protocolo de criptografia para segurança na internet (substituído por TLS).
- **Para que serve**: Proteger comunicação entre clientes e servidores.
- **Porta padrão**: Varia conforme protocolo (ex: 443 com HTTPS)

---

## 3. Arquitetura Cliente-Servidor

A arquitetura **cliente-servidor** é um modelo de comunicação em que um dispositivo (cliente) solicita serviços ou recursos a outro (servidor).

- O cliente inicia requisições.
- O servidor responde com os dados ou ações solicitadas.

**Exemplo**: Quando você acessa um site, seu navegador (cliente) solicita o conteúdo ao servidor web, que responde com o HTML, CSS, imagens etc.

---

## 4. Funcionamento do DNS e Proxies

### DNS (Domain Name System)

- **O que faz**: Traduz nomes de domínio (ex: www.google.com) para endereços IP.
- **Funcionamento**: 
  1. O navegador envia uma requisição DNS.
  2. O servidor DNS responde com o IP correspondente.
  3. A conexão é estabelecida com esse IP.

[Mais sobre DNS](https://developer.mozilla.org/pt-BR/docs/Learn/Common_questions/What_is_DNS)

### Proxies

- **O que é**: Um servidor intermediário entre o cliente e o servidor final.
- **Função**:
  - Filtrar conteúdo
  - Melhorar desempenho (cache)
  - Adicionar segurança (ocultando IP real)

---

## 5. Diferenças entre HTTP e HTTPS

| Característica | HTTP | HTTPS |
|----------------|------|-------|
| Segurança      | Sem criptografia | Usa SSL/TLS para criptografia |
| Porta padrão   | 80   | 443   |
| Uso recomendado| Sites sem dados sensíveis | Sites com dados sensíveis, login, transações |

---

## 6. Códigos HTTP e Verbos de Requisição

### Categorias de Códigos HTTP

- **2xx – Sucesso**
  - `200 OK`: Requisição bem-sucedida
  - `201 Created`: Recurso criado
- **4xx – Erros do Cliente**
  - `400 Bad Request`: Requisição malformada
  - `404 Not Found`: Página não encontrada
- **5xx – Erros do Servidor**
  - `500 Internal Server Error`: Erro interno
  - `503 Service Unavailable`: Serviço indisponível

### Verbos de Requisição

- `GET`: Recupera dados
- `POST`: Envia dados para criação
- `PUT`: Atualiza recurso existente
- `DELETE`: Remove recurso
- `PATCH`: Atualiza parcialmente

---

## 7. Principais Tags do HTML

- `<html>`: Raiz do documento
- `<head>`: Cabeçalho da página
- `<title>`: Título exibido no navegador
- `<body>`: Conteúdo principal
- `<h1>` a `<h6>`: Títulos
- `<p>`: Parágrafo
- `<a>`: Link
- `<img>`: Imagem
- `<div>`: Divisão genérica
- `<span>`: Elemento em linha

[Referência: MDN HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)

---

## 8. Seletores do CSS

- `*`: Seleciona todos os elementos
- `tag`: Seleciona por nome da tag (ex: `p`, `div`)
- `.classe`: Seleciona por classe
- `#id`: Seleciona por ID
- `elemento elemento`: Seleciona descendentes
- `elemento > elemento`: Seleciona filhos diretos

[Referência: MDN CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

---

## 9. O que é uma WebView

**WebView** é um componente utilizado em aplicações mobile (Android, iOS) para exibir conteúdo web dentro de um aplicativo.

- **Uso comum**: Abrir páginas da web sem sair do app.
- **Exemplo**: Um app de e-commerce que exibe o site de pagamento via WebView.

---

## Referências

- [Git - Documentação oficial](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/)
- [MDN Web Docs](https://developer.mozilla.org/pt-BR/)
- [W3Schools](https://www.w3schools.com/)
=======
# Relatório de Pesquisa: Git, GitHub, Protocolos de Comunicação e Tecnologias Web

## 1. Git e GitHub

### O que é o Git?

[Git](https://git-scm.com/) é um sistema de controle de versão distribuído, criado por Linus Torvalds. Ele permite que desenvolvedores acompanhem mudanças no código-fonte, revertam alterações e colaborem em projetos de forma eficiente.

- **Função**: Controlar versões de arquivos e coordenar trabalho entre desenvolvedores.

### O que é o GitHub?

[GitHub](https://github.com/) é uma plataforma de hospedagem de código que utiliza o Git. Ele adiciona funcionalidades sociais como pull requests, issues, forks e ações automatizadas.

- **Função**: Hospedar repositórios Git e facilitar colaboração em projetos de software.

---

## 2. Protocolos de Rede e Comunicação

### HTTP (HyperText Transfer Protocol)
- **O que é**: Protocolo para transferência de dados da web.
- **Para que serve**: Comunicação entre cliente e servidor (por exemplo, navegador e site).
- **Porta padrão**: 80

### HTTPS (HTTP Secure)
- **O que é**: Versão segura do HTTP, com criptografia SSL/TLS.
- **Para que serve**: Garantir segurança e privacidade na comunicação web.
- **Porta padrão**: 443

### WebSockets
- **O que é**: Protocolo para comunicação bidirecional em tempo real.
- **Para que serve**: Aplicações que exigem atualizações em tempo real, como chats e jogos.
- **Porta padrão**: 80 (ws) e 443 (wss)

### FTP (File Transfer Protocol)
- **O que é**: Protocolo para transferência de arquivos.
- **Para que serve**: Enviar e receber arquivos entre cliente e servidor.
- **Porta padrão**: 21

### SSH (Secure Shell)
- **O que é**: Protocolo para acesso remoto seguro a sistemas.
- **Para que serve**: Acesso e controle remoto de servidores via linha de comando.
- **Porta padrão**: 22

### SSL (Secure Sockets Layer)
- **O que é**: Protocolo de criptografia para segurança na internet (substituído por TLS).
- **Para que serve**: Proteger comunicação entre clientes e servidores.
- **Porta padrão**: Varia conforme protocolo (ex: 443 com HTTPS)

---

## 3. Arquitetura Cliente-Servidor

A arquitetura **cliente-servidor** é um modelo de comunicação em que um dispositivo (cliente) solicita serviços ou recursos a outro (servidor).

- O cliente inicia requisições.
- O servidor responde com os dados ou ações solicitadas.

**Exemplo**: Quando você acessa um site, seu navegador (cliente) solicita o conteúdo ao servidor web, que responde com o HTML, CSS, imagens etc.

---

## 4. Funcionamento do DNS e Proxies

### DNS (Domain Name System)

- **O que faz**: Traduz nomes de domínio (ex: www.google.com) para endereços IP.
- **Funcionamento**: 
  1. O navegador envia uma requisição DNS.
  2. O servidor DNS responde com o IP correspondente.
  3. A conexão é estabelecida com esse IP.

[Mais sobre DNS](https://developer.mozilla.org/pt-BR/docs/Learn/Common_questions/What_is_DNS)

### Proxies

- **O que é**: Um servidor intermediário entre o cliente e o servidor final.
- **Função**:
  - Filtrar conteúdo
  - Melhorar desempenho (cache)
  - Adicionar segurança (ocultando IP real)

---

## 5. Diferenças entre HTTP e HTTPS

| Característica | HTTP | HTTPS |
|----------------|------|-------|
| Segurança      | Sem criptografia | Usa SSL/TLS para criptografia |
| Porta padrão   | 80   | 443   |
| Uso recomendado| Sites sem dados sensíveis | Sites com dados sensíveis, login, transações |

---

## 6. Códigos HTTP e Verbos de Requisição

### Categorias de Códigos HTTP

- **2xx – Sucesso**
  - `200 OK`: Requisição bem-sucedida
  - `201 Created`: Recurso criado
- **4xx – Erros do Cliente**
  - `400 Bad Request`: Requisição malformada
  - `404 Not Found`: Página não encontrada
- **5xx – Erros do Servidor**
  - `500 Internal Server Error`: Erro interno
  - `503 Service Unavailable`: Serviço indisponível

### Verbos de Requisição

- `GET`: Recupera dados
- `POST`: Envia dados para criação
- `PUT`: Atualiza recurso existente
- `DELETE`: Remove recurso
- `PATCH`: Atualiza parcialmente

---

## 7. Principais Tags do HTML

- `<html>`: Raiz do documento
- `<head>`: Cabeçalho da página
- `<title>`: Título exibido no navegador
- `<body>`: Conteúdo principal
- `<h1>` a `<h6>`: Títulos
- `<p>`: Parágrafo
- `<a>`: Link
- `<img>`: Imagem
- `<div>`: Divisão genérica
- `<span>`: Elemento em linha

[Referência: MDN HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)

---

## 8. Seletores do CSS

- `*`: Seleciona todos os elementos
- `tag`: Seleciona por nome da tag (ex: `p`, `div`)
- `.classe`: Seleciona por classe
- `#id`: Seleciona por ID
- `elemento elemento`: Seleciona descendentes
- `elemento > elemento`: Seleciona filhos diretos

[Referência: MDN CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

---

## 9. O que é uma WebView

**WebView** é um componente utilizado em aplicações mobile (Android, iOS) para exibir conteúdo web dentro de um aplicativo.

- **Uso comum**: Abrir páginas da web sem sair do app.
- **Exemplo**: Um app de e-commerce que exibe o site de pagamento via WebView.

---

## Referências

- [Git - Documentação oficial](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/)
- [MDN Web Docs](https://developer.mozilla.org/pt-BR/)
- [W3Schools](https://www.w3schools.com/)
>>>>>>> ac6f7bcd7887e3cf8400406c1826ae5670fe7eef
