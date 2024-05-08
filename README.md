# Imersão Inteligência Artificial 2ª Edição

> Alura + Google

[Guia de mergulho da imersão IA: Notion](https://grupoalura.notion.site/Imers-o-IA-Guia-de-Mergulho-41ae5fadd8fd47899167a115e96244d9)

## Links geral

[Google Gemini](https://gemini.google.com/)

[Google AI Studio](https://aistudio.google.com/app/prompts/new_chat/?utm_source=website&utm_medium=referral&utm_campaign=Alura&utm_content=)

[Google API Key](https://aistudio.google.com/app/apikey/?utm_source=website&utm_medium=referral&utm_campaign=Alura&utm_content=)

## Aula 1: Mergulhando no Gemini, a IA do Google

Nesta aula, vamos começar o nosso mergulho conhecendo o Gemini, a IA do Google, e ver como ele consegue criar tabelas, escrever poemas, gerar códigos e muito mais. Além disso, vamos conhecer também o Google AI Studio.

Nesta aula, você vai:

- Conhecer o Gemini, a IA do Google;

- Entender o que é a Inteligência Artificial generativa;

- Gerar tabelas, poemas, códigos pelo Gemini;

- Conhecer o Google AI Studio;

- Analisar imagens com o Gemini e o Google AI Studio.

### Prompts utilizados Google Gemini

1. O que é Inteligência Artificial?

2. Crie um texto para a minha agência de viagens que quer levar pessoas pro Japão. Essas pessoas trabalham com tecnologia. Crie esse texto em estilo de poema, como se fosse um anúncio, com fins de marketing.

3. Gere uma tabela com 3 colunas. Na coluna 1, terá o nome de 5 países da Europa, 5 países da África e 5 países da Ásia. Na coluna 2, o respectivo continente. Na coluna 3, a respectiva capital.

4. Tenho 5 avaliações de hotéis. Quero que você analise o sentimento de cada uma delas, e dê uma nota de 1 a 5, sendo que a nota 5 é o sentimento mais positivo e a 1 é o sentimento mais negativo. [Anexe cada avaliação a partir dessa planilha](/files/aula-01/Avaliações%20de%20hotéis.xlsx)

5. Tenho 5 avaliações de hotéis. Quero que você analise o sentimento de cada uma delas, e dê uma nota de 1 a 5, sendo que a nota 5 é o sentimento mais positivo e a 1 é o sentimento mais negativo. Gere seu resultado em formato JSON, contendo o resumo da avaliação, o nome do hotel e a nota.

6. Eu quero cinco ideias interessantes pra vídeos curtos que serão postados no Instagram Stories sobre programação Front-end.

7. Volte para o prompt da tabela de países e peça: “Com base na tabela criada, gere uma query SQL que irá retornar a capital dos países da Ásia.”

8. Crie o código HTML, CSS e JavaScript para uma agência de viagens especializada em brasileiros que viajam para o Japão. Dê destaques para tópicos relacionados a samurais, ninjas e tecnologia. Crie os códigos em arquivos separados.

9. Transcreva esta imagem [Anexe a imagem carta de natal](/files/aula-01/Carta%20de%20Natal.png)

### Prompts utilizados Google AI Studio

1. Descreva esta imagem [Inserir esta imagem antes](/files/aula-01/Imagem%20Paulo.jpeg)

2. Traduza para o português

3. Pode identificar o modelo da caminhonete?

obs: pular linha SHIFT+ENTER

### Resultado dos prompts

- [Resultados dos prompts da aula](/resultados-aula-01.md)

### Links da aula

- [Base de dados do Kaggle de avaliações sobre hotéis](https://www.kaggle.com/code/thehustler2003/naive-sentiment-classification/input)

- [CodePen](https://codepen.io/pen/)

### Desafios desta aula

- Use o Gemini ou o Google AI Studio para algo do seu dia a dia no trabalho, visando a automação de alguns processos já realizados por você;

- Pegue o seu [histórico do Google Chrome](https://chromewebstore.google.com/detail/quick-chrome-history-expo/hdfpifhfphhgjipcnfnolgalplokmmge) por meio dessa extensão e peça para o Gemini tirar conclusões de como você tem usado o seu tempo, criando um resumo do que você mais acessa, quantidade de uso e tipo de site;

- Faça parte da comunidade gratuita de desenvolvedores e de usuários da Google Cloud Innovators, acesse a plataforma aqui!

## Aula 2: Melhores técnicas em Engenharia de Prompt

Nesta aula, iremos conhecer as melhores técnicas e práticas de engenharia de prompt por meio do Google AI Studio!

Nesta aula, você vai:

- Aprender as melhores técnicas de como realizar um prompt;

- Conhecer o conceito de zero-shot prompting;

- Aprender a técnica de few-shot prompting;

- Conhecer a técnica Few-shot Chain-of-Thought prompting.

### Prompts da aula

1. Crie uma campanha de viagem para o Japão.

2. Aja como um agente de marketing. Crie uma campanha de viagem para o Japão focada em brasileiros que se interessam pela cultura de artes marciais e samurais. Liste os principais pontos turísticos que os viajantes irão visitar no Japão, que tenham relação com esses temas. Seja específico no dia a dia, com um itinerário de 5 dias.

3. Gostaria que você incluísse a cidade de Yokohama.

4. Escreva um código que calcule a sequência de Fibonacci.

5. Escreva uma função TypeScript para calcular com eficiência a sequência de Fibonacci. Crie comentários no código para explicar o que cada parte faz e por que foi escrita dessa forma.

6. Onde poderia rodar esse código para ver o resultado?

#### Conceito de Zero-shot prompting:

7. “Um diretor de cinema já dirigiu 16 filmes. Metade dos filmes que ele dirigiu são de ação, e metade dos filmes de ação têm a participação do Nicolas Cage, e na metade deles o Nicolas Cage tem bigode. Quantos filmes de ação com a participação do Nicolas Cage com bigode ele dirigiu?”

#### Conceito de Few-shot prompting:

8. “Pergunta: João tem 10 bolas. Metade delas são azuis e metade são vermelhas. Quantas bolas vermelhas o João tem?

Resposta: A resposta é 5.

Pergunta: Um diretor de cinema já dirigiu 16 filmes. Metade dos filmes que ele dirigiu são de ação, e metade dos filmes de ação têm a participação do Nicolas Cage, e na metade deles o Nicolas Cage tem bigode. Quantos filmes de ação com a participação do Nicolas Cage com bigode ele dirigiu?

Resposta:”

#### Conceito de Few-shot Chain-of-Thought prompting:

9. Few-shot “puro”:

“Inglês: Hello, how are you?
Português: Olá, como vai?

Inglês: I am learning to speak Portuguese.
Português: Eu estou aprendendo a falar português.

Inglês: The weather is very nice today.
Português:”

10. Few-shot Chain-of-Thought:

“Aja como um professor de português do Brasil. Vou te passar uma lista de palavras-chave e também exercícios que foram criados com base nessas palavras. Na sequência, vou te passar uma nova lista de palavras-chave, e você vai escolher algumas das mais relevantes e criar exercícios em português brasileiro (informal).

LISTA DE PALAVRAS COM TRADUÇÃO

legal - cool
desde - since
trabalhar - to work

EXERCÍCIOS

1 - Traduza: “Since then, I can’t work anymore.”
2 - Complete: “Ele é um cara muito ------.” (He's a very cool guy.)

LISTA DE PALAVRAS COM TRADUÇÃO

lembrar - to remember
resumir - to sum up

EXERCÍCIOS"

11. “Pergunta: Tenho uma lista de valores. O meu resultado final será 30% da soma de valores. Porém, nem todos os valores serão somados, apenas aqueles acima de R$40.000,00. Para a lista abaixo, conte quantos valores existem e me diga qual é o meu resultado final?

R$10.000,00
R$20.000,00
R$50.000,00
R$60.000,00

Resposta: Nessa lista existem 4 valores. Há 2 valores acima de R$40.000,00, que são R$50.000,00 e R$60.000,00. A soma desses valores é R$110.000,00. O resultado final é 30% da soma desses valores, portanto, 30% de R$110.000,00, que resulta em R$33.000,00.

Pergunta: Tenho uma lista de valores. O meu resultado final será 30% da soma de valores. Porém, nem todos os valores serão somados, apenas aqueles acima de R$40.000,00. Para a lista abaixo, conte quantos valores existem e me diga qual é o meu resultado final?

[Colar aqui os 10 valores da nossa lista real do Google Sheets](/files/aula-02/Soma%20de%20colunas.xlsx)

Resposta:”

### Resultado dos prompts

- [Resultados dos prompts da aula](/resultados-aula-02.md)

### Links da aula

- [Guia de design de prompts do Google](https://ai.google.dev/gemini-api/docs/prompting-strategies?hl=pt-br)

### Desafios desta aula

- Use a técnica de Few-shot Chain-of-Thought para um problema da sua vida real;

- Escolha 10 textos do seu site de notícias preferido. Apresente para o Google AI Studio o padrão dos títulos e das suas respectivas notícias e quando chegar no décimo primeiro texto, apresente somente a notícia e peça para ele gerar um título. Veja se existe alguma técnica ou padrão;

- Faça parte da comunidade gratuita de desenvolvedores e de usuários da Google Cloud Innovators, acesse a plataforma [aqui](https://cloud.google.com/innovators?hl=pt-br)!
