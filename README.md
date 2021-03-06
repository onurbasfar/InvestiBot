# InvestiBot

Bot [Telegram](https://telegram.org/) que fornece informações relevantes para investidores.
- Taxa selic atual.
- Taxa selic acumulada nos últimos 30 dias.
- Rendimento poupança nos últimos 30 dias.
- Rendimento poupança nos últimos 12 meses.

### Setup
- Crie um [Telegram bot](https://core.telegram.org/bots).
- Insira a token do seu bot no arquivo `application.properties`
```text
// src/main/resources/application.properties

telegram-bot.token={seuTelegramToken}
...
```
### Run
Execute na raiz do projeto a task `bootRun` do gradle.

- Windows
  `gradlew bootRun`
- Linux / Mac
  `./gradlew bootRun`

### Tela Inicial 
![Tela Inicial](/images/telaInicial.png)


### Comandos válidos
- `/start`
- `Taxa selic hoje`
- `Taxa selic acumulada nos últimos 30 dias`
- `Rendimento da poupanca nos últimos 30 dias`
- `Rendimento da poupança acumulado nos últimos 12 meses`

### JavaDoc
- Disponível [aqui](https://onurbasfar.github.io/InvestiBot/doc/) ou no diretorio /doc do projeto.
