
# Relatório Aplicativo Prova

**Curso**
> Informática para a internet
> Dispositivos Móveis

**Alunos**
- Bruno Bandeira Marques
- Heitor de Lima Dias 
# 📚 Quiz de Ética e Cidadania

_____________

## Sobre o Projeto

O **Quiz de Ética e Cidadania** é um aplicativo educativo desenvolvido no **MIT App Inventor**, com o objetivo de testar e ampliar os conhecimentos dos usuários sobre ética, cidadania, direitos do consumidor e responsabilidade social.

O aplicativo apresenta questões de múltipla escolha, permitindo que o usuário coloque seus conhecimentos em prática de maneira simples e interativa.

## Objetivo

O principal objetivo do projeto é incentivar o aprendizado sobre temas importantes para a convivência em sociedade e para a formação de cidadãos conscientes.

O aplicativo busca:

- Desenvolver o conhecimento sobre ética e cidadania.
- Ensinar direitos e deveres dos consumidores.
- Incentivar atitudes responsáveis no ambiente profissional.
- Promover o respeito às diferenças e à inclusão.
- Estimular o consumo consciente.
- Utilizar a tecnologia como ferramenta educacional.

## Como Funciona

O aplicativo possui um banco com **30 questões cadastradas**, abordando diferentes assuntos relacionados à ética e à cidadania.

Ao iniciar uma prova, o sistema seleciona aleatoriamente **10 questões**, evitando repetições durante a mesma tentativa.
Cada questão apresenta quatro alternativas:

- **A)** Primeira alternativa.
- **B)** Segunda alternativa.
- **C)** Terceira alternativa.
- **D)** Quarta alternativa.

O usuário deve selecionar a alternativa que considera correta.
O aplicativo verifica a resposta escolhida e registra os acertos.
Ao finalizar as 10 questões, o sistema apresenta a quantidade total de respostas corretas.
O usuário também pode iniciar uma nova prova, recebendo outra seleção aleatória de perguntas.

### Tecnologias Utilizadas

- **MIT App Inventor:** desenvolvimento das telas e da lógica do aplicativo.
- **Programação em blocos:** criação dos procedimentos e condições.
- **TinyDB:** armazenamento local das informações.
- **Listas:** organização das questões e alternativas.
- **Android:** plataforma utilizada para executar o aplicativo.

## 🧩 Principais Procedimentos

### Sortear

O procedimento `Sortear` é responsável por selecionar as perguntas que serão utilizadas na prova.

Seu funcionamento consiste em:

1. Criar uma lista com os índices das 30 questões.
2. Sortear aleatoriamente um índice.
3. Adicionar a questão correspondente à lista da prova.
4. Remover o índice sorteado para evitar repetições.
5. Repetir o processo até selecionar 10 questões.

### MostrarQuestao

O procedimento `MostrarQuestao` apresenta as informações da questão atual na tela.

Ele é responsável por:

- Mostrar o número da questão.
- Exibir o enunciado.
- Apresentar as quatro alternativas.
- Atualizar os textos dos botões.
- Restaurar as cores dos botões.

### VerificarResposta

O procedimento `VerificarResposta` compara a alternativa selecionada pelo usuário com a resposta correta cadastrada.

Quando o usuário acerta, o sistema acrescenta um ponto à pontuação.

O procedimento também controla o avanço das questões e a finalização da prova.

## 🗂️ Organização das Perguntas

As perguntas são armazenadas em listas.

Cada questão possui:

- Um enunciado.
- Quatro alternativas.
- Um número que identifica a resposta correta.

As alternativas são representadas pelos números de 1 a 4, correspondendo às letras A, B, C e D.

Essa organização facilita a identificação das respostas e o funcionamento do sistema de correção.


## 📚 Material de Apoio

O aplicativo também conta com materiais educativos desenvolvidos para auxiliar os usuários nos estudos.

Esses materiais apresentam explicações sobre:

- Ética e impessoalidade.
- Direitos do consumidor.
- Inclusão e acessibilidade.
- Consumo consciente.

O objetivo é permitir que os alunos estudem os conteúdos antes de realizar a prova.

