# Conversor de Moedas em Java

Este projeto é um conversor de moedas que utiliza dados de taxas de câmbio em tempo real obtidos através da API ExchangeRate-API. Desenvolvido em Java, o aplicativo oferece uma interface interativa via terminal para o usuário realizar diversas conversões entre moedas.

---

## Funcionalidades

- Obtenção dinâmica das taxas de câmbio a partir da ExchangeRate-API.
- Conversão entre diferentes moedas, incluindo BRL, USD, ARS, CLP, entre outras.
- Menu textual para seleção de opções e inserção dos valores para conversão.
- Tratamento básico de erros para entradas inválidas e problemas na conexão com a API.

---

## Tecnologias e Ferramentas

- **Java 11** — para garantir compatibilidade e uso da API HttpClient.
- **Maven** — gerenciamento de dependências e execução do projeto.
- **Gson** — biblioteca para manipulação e parsing de JSON.
- **API ExchangeRate-API** — fonte das taxas de câmbio atualizadas.
- **Scanner** — captura da entrada do usuário via console.

---

## Como utilizar

### Requisitos

- Java 11 ou superior instalado.
- Maven instalado para gerenciar dependências e executar o projeto.

### Passos para execução

1. Navegue até a pasta raiz do projeto onde está o arquivo `pom.xml`.
2. Compile o projeto com:

   ```bash
   mvn compile

    Execute a aplicação com:

    mvn exec:java -Dexec.mainClass=br.com.conversor.Main

    Siga as instruções no menu exibido no console.

Estrutura do Projeto

conversor-moedas/
│
├── pom.xml
└── src/
    └── main/
        └── java/
            └── br/
                └── com/
                    └── conversor/
                        ├── Main.java
                        ├── ExchangeRateService.java
                        └── Conversor.java

Considerações finais

Este projeto foi desenvolvido para fornecer uma ferramenta simples e eficiente de conversão de moedas com base em dados atualizados da API ExchangeRate-API. Ele demonstra o uso de APIs REST, manipulação de JSON com Gson e interação básica com o usuário via terminal.
Autor

Desenvolvido por [Kaize Araujo].

Se desejar contribuir ou reportar problemas, fique à vontade para abrir uma issue no repositório.

Obrigado por utilizar o Conversor de Moedas!
