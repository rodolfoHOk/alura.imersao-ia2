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

## Aula 3: Explorando os parâmetros do Google AI Studio

Nesta aula, vamos ver mais sobre o Google AI Studio e explorar seus parâmetros e configurações até o suporte do modelo multimodal que o Gemini nos dá, iniciando a automação desse modelo com as APIs.

Nesta aula, você vai:

- Conhecer os 3 tipos de prompts do Google AI Studio: chat prompts, freeform prompts e structured prompts;
- Explorar os parâmetros do Google AI Studio;
- Conhecer mais sobre os tokens e PLN;
- Iniciar o contato com Python pelo Google Colab.

### Prompts da aula

- System Instruction: Você é um assistente muito sarcástico e que usa muitas gírias, message: Crie um e-mail convidando um amigo para ir em uma viagem pro Japão.

- Escreva um tuíte curto sobre o Japão.

- Escreva um texto sobre o Japão.

- Encontre a palavra ou expressão fora de contexto desse áudio.

- Transcreva o áudio inteiro. [Faça você o seu próprio áudio como desafio e realize esse prompt!]

- Analise o vídeo e me diga de que ele trata. [Inserir vídeo do Gemini](https://www.youtube.com/watch?v=UIZAiXYceBI&ab_channel=Google)

- Encontre o minuto e segundo do vídeo quando isso aparece. [Imagem usada no prompt]

- Sou uma agência de viagens. Quero que você gere um itinerário de viagens com base no que foi mostrado nesse vídeo.
  [Inserir vídeo do Fabrício](https://www.youtube.com/watch?v=dWO-9SyD7yc)

- Descreva o que há nesse arquivo PDF. [Inserir PDF com o guia de Nara e Kyoto](https://drive.google.com/file/d/1vByLRS3AED7NxrkgLTl2Haay53lylopr/view?usp=sharing)

- Relacione o que foi mostrado no vídeo com o que está contido neste arquivo PDF. Qual a intersecção? Defina especificamente. [Volte para o chat da viagem do Fabrício, adicione o guia de Nara e Kyoto]

### Resultado dos prompts

- [Resultados dos prompts da aula](/resultados-aula-03.md)

### Código fonte da aula

- [Código fonte](/files/aula-03/alura_imersao_ia2_aula3.py)

### Links da aula

- [Galeria de prompts do Google AI Studio](https://ai.google.dev/examples?hl=pt-br)

- [Google Colab](http://colab.research.google.com/)

- [Vlog do Fabrício Carraro no Japão](https://www.youtube.com/watch?v=dWO-9SyD7yc)

### Desafios desta aula

- Criar seu próprio áudio e realizar um prompt para análise pelo Google AI Studio;

- Pesquise como colocar a imagem do Google AI Studio dentro do código de Pyhton no Google Colab;

- Pegue os códigos que não contenham imagens do AI Studio e exporte para o Google Colab.

## Aula 4: Criando seu próprio chatbot com a Gemini API no Google Colab

Nesta aula, vamos criar um chatbot com a Gemini API pelo Google Colab e descobrir como funciona a premiação de melhores projetos!

Nesta aula, você vai:

- Aprender a criar o seu próprio chatbot;
- Saber como funciona a competição de projetos dessa Imersão.

### Código fonte da aula

- [Código fonte](/files/aula-04/alura_imersao_ia2_aula4.py)

### Links da aula

- [Guia de início rápido na API Gemini](https://ai.google.dev/gemini-api/docs/quickstart?hl=pt-br)

- Formulário de submissão do seu projeto [aqui](https://forms.gle/xtn8UvC8spvoWEr57)!

- [IA Conference Brasil 2024](https://iaconferencebrasil.com.br/)

### Desafios desta aula

#### Deseja ir além? Envie seu projeto e concorra a prêmios:

Para entender como a premiação vai funcionar, assista ao [tutorial](https://youtu.be/bLK66y0CcR8) e leia os passos abaixo. Não se esqueça de conferir o regulamento da premiação.

1. Desenvolva um Projeto Relacionado à Aula 4 e/ou Aula 5 da Imersão IA 2ª Edição

   O projeto deve estar relacionado ao conteúdo da Aula 4 e/ou Aula 5 da Imersão IA 2ª edição, organizada pela Alura em parceria com o Google.

2. Uso Obrigatório da API Key do Google

   É obrigatório o uso da API Key do Google ([acesse aqui](https://aistudio.google.com/app/apikey/?utm_source=website&utm_medium=referral&utm_campaign=Alura&utm_content=) para obter sua chave).

3. Publicação do Projeto no GitHub

   O projeto deve ser publicado no GitHub. Se precisar de ajuda para subir seu projeto, confira o tutorial [aqui](https://www.youtube.com/watch?v=9IiWoiBhWiA).

4. Submissão do Projeto

   A submissão do projeto deve ser feita através [deste formulário](https://forms.gle/xtn8UvC8spvoWEr57) entre os dias 09/05 e 11/05, até as 23h59.

5. Publicação e Votação no Discord

   O projeto será publicado no Servidor do Discord da Imersão IA 2024 para votação pela comunidade até 11/05, às 23h59.

   A votação acontece no canal "#Votação". Dê estrelas no projeto que você mais gostou e conecte-se com outras pessoas para incentivá-las a votar no seu projeto.

6. Avaliação pela Banca da Alura

   Uma banca da Alura irá avaliar os 30 projetos mais votados para eleger os 10 primeiros colocados com base nos seguintes critérios:

   - Utilidade do projeto.
   - Criatividade.
   - Eficácia.
   - Apresentação.
   - Ordem de envio.

7. Anúncio dos Vencedores

   O ranking final será divulgado na [live de encerramento](https://youtube.com/live/0x_WCLhen7Q) no YouTube no dia 13/05 às 18h30. Também será divulgado por e-mail para os vencedores e no [Guia de mergulho](https://grupoalura.notion.site/Imers-o-IA-Guia-de-Mergulho-41ae5fadd8fd47899167a115e96244d9).

Para saber mais, confira o regulamento da premiação [aqui](https://docs.google.com/document/d/1lTk8UlujtcL4g87CWgyCItCZOLHOLYZ3/edit?usp=sharing&ouid=107556453766758279419&rtpof=true&sd=true)!
