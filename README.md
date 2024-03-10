# Análise de Sentimentos com Language Studio no Azure AI-DIO

## Projeto DIO- Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Passo a passo do projeto de Análise de Sentimentos com Language Studio no Azure AI da DIO.

Links importantes:

[Recurso de fala de IA do Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)

[Analisar texto com o Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html#create-a-language-resource)



## Teste 1: Recurso de fala de IA do Azure

Abri o studio de fala da Azure [Speech Studio](https://speech.microsoft.com/portal) e fiz o login

![Img](/imagens/01.png)

Cliquei no simbolo de configurações e em seguida "criar novo recurso"

![Img](/imagens/02.png)

![Img](/imagens/03.png)

Ao criar voltei para a página inicial, rolei a página até achar "Conversão de fala em texto" e selecionei a primeira opção.

![Img](/imagens/04.png)
![Img](/imagens/05.png)

Em seguida escolhi um arquivo de audio
e já apareceu o texto do que foi dito junto com o código em JSON

![Img](/imagens/06.png)

[Clique aqui para ver o código](/inputs/TesteFala.json)

Logo abaixo apareceu próximas etapas
![Img](/imagens/07.png)


## Teste 2: Analisar texto com o Language Studio
No [portal do Azure](https://portal.azure.com/#create/hub)
cliquei em criar recurso

![image](/imagens/08.png)

Em categorias cliquei em "Inteligência Artificial + Machine Learning" e procurei por "serviço de linguagem"

![image](/imagens/09.png)

Cliquei em criar

![image](/imagens/10.png)

Com todas as features selecionadas cliquem em criei o recurso

![image](/imagens/11.png)

Esperei a validação e cliquei em criar para aguardar a finalização.

deploy finalizado

![image](/imagens/12.png)

verifiquei se estava ativo

![image](/imagens/13.png)

Com tudo ok, abri o [Language Studio](https://language.cognitive.azure.com/?azure-portal=true) e fiz o login

![image](/imagens/14.png)

Preenchi o que precisava e cliquei em "done"

![image](/imagens/15.png)

Selecionei "classificação de texto" e "analisar sentimentos e opniões"

![image](/imagens/16.png)

idioma selecionado, colei o texto da documentação

![image](/imagens/17.png)

mais abaixo marquei a caixinha e cliquei para examinar

![image](/imagens/18.png)

E esse foi o resultado:

![image](/imagens/19.png)
![image](/imagens/20.png)
![image](/imagens/21.png)

[Clique aqui para ver o código](/inputs/TesteLanguage.json)

