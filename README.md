# Consulta de Endereço por CEP - Java

Este projeto é uma aplicação Java simples que permite ao usuário digitar um CEP e retorna as informações de endereço correspondentes, utilizando uma API externa. O resultado é salvo localmente em um arquivo `.json`.

## 🚀 Funcionalidades

- Solicita um número de CEP ao usuário
- Consulta os dados do endereço usando uma API
- Exibe as informações no console
- Salva os dados em um arquivo `.json`
- Tratamento de exceções para falhas de rede ou entrada inválida

## 💻 Tecnologias utilizadas

- Java 17+ (ou compatível)
- Biblioteca padrão (`java.net`, `java.io`, `Scanner`, etc.)
- [JSON-java (org.json)](https://github.com/stleary/JSON-java) ou outra biblioteca JSON (dependendo da implementação)
- API de consulta de CEP (ex: ViaCEP)

## 📂 Estrutura do projeto

```bash
src/
├── Principal.java
├── ConsultaCep.java
├── Endereco.java
└── GeradorDeArquivo.java
