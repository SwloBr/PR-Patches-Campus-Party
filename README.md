# Oficina Git & GitHub PR

## Como participar do PR 

### 1. Faça um Fork deste repositório
Para você fazer um fork deste repositorio, basta clicar no botão Fork no canto superior direito da tela.

### 2. Clone o seu repositório

Para clonar o seu repositório, basta clicar no botão verde Code e copiar o link HTTPS ou SSH.
e rodar o comando abaixo no seu terminal

```
git clone <link-copiado>
```

### 3. Deixe sua mensagem

O que você achou da Oficina? (Max 280 char)

Substitua `<SEU-USUARIO>` pelo seu usuário do GitHub neste guia. 

Crie um arquivo markdown dentro da pasta `_messages` seguindo esse exemplo: `<YOUR-USERNAME>.md`. 

Ex. `_messages/SwloBr.md`

Fique atento, que `<SEU-USUARIO>` é Case Sensitive (respeita maiúsculas e minúsculas). Por exemplo, se o seu nome de usuário é `SwloBr`, usar outras variações como `swlobr` ou `SwloBR` irá gerar um erro ao submeter o Pull Request. Tenha certeza que você está usando o seu nome de usuário corretamente tanto no nome da pasta quanto no nome do arquivo.
  
🚨 Não use caracteres especiais no template acima.
    
```
---
user: Sua github user
time: 2022-11-11 11:00:00
quote: Sua frase aqui.
---
```

### 4. Faça o commit e push

```
git add _messages/<SEU-USUARIO>.md
git commit -m "Add message"
git push origin main
```

### 5. Envie seu Pull Request

Vá para a página do seu repositório no GitHub e clique no botão "Compare & pull request". Depois clique em "Create pull request". Adicione um título e uma descrição significativa para o seu Pull Request. Por fim, clique no botão "Create pull request".

### 6. Parabéns! Você fez um Pull Request

Agora converse com os organizadores da Oficina para aceitar seu Pull Request.


![SwloBr](https://avatars.githubusercontent.com/SwloBr?s=64)
![Joao-Victor-RVG](https://avatars.githubusercontent.com/Joao-Victor-RVG?s=64)

## Veja a resposta de sua pergunta 👀
Quando seu pull request for aprovado, você vera sua mensagem website. 


## Principais erros
### Não fazer o PR na pasta _ messages
Em algus casos, seu navegador pode traduzir o nome da pasta messages e colocar mensagens. NÃO faça o commit na pasta mensagens, corrija de volta para messages

## Não seguir exatamente o formato abaixo
O Formato do time é ANO-MES-DIA 
Exemplo:
time: 2022-06-16 11:00:00 é Dia 16 de Junho de 2022

```
---
user: Sua github user @
time: 2023-10-19 15:20:00
quote: Sua frase aqui.
---
```
