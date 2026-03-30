# 📝 Estrutura do Relatório

Utilize o seguinte modelo para organizar o relatório.

---

## Instituição
Etec Vasco Antonio Vnechiarutti

## Curso
Informática para a internet 

## Turma
2 ano D

## Autores
Bruno Bandeira
Daniel Santiago
Enzo Trindade
Heitor de Lima DIas

---

# 📱 Projeto

## Título
Forca EtecVav

---

## Descrição

- objetivo do aplicativo
O objetivo do applicativo autoral é divertir o usuário com um jogo tipo "forca" personalizado com alguns cursos da EtecVav, o usuário prescisa acertar a palvra dentre as opções das  regras, mas sem ultrapassar a quantidade limite de erros, ao ganhar ou perder tocará uma música tema.

o sistema seleciona uma palavra aleatória de uma lista previamente definida. Essa palavra é armazenada internamente como a “palavra correta”, que o jogador precisa descobrir. Para evitar repetição, essa palavra é removida da lista original, garantindo que cada rodada seja diferente até que todas as palavras acabem.

Depois de escolher a palavra, o aplicativo cria a representação visual dela para o jogador. Em vez de mostrar a palavra diretamente, ele constrói uma nova lista composta apenas por traços (“”), com a mesma quantidade de letras da palavra escolhida. Essa lista é o que aparece na tela, simulando os espaços que o jogador precisa preencher. Por exemplo, se a palavra for “CASA”, o jogador verá “ _ _ _”. Essa separação entre a palavra real e o que é exibido é essencial, pois permite que o sistema controle o que o jogador pode ou não ver.

A interação principal do jogo acontece quando o jogador pressiona um botão de letra. Cada botão representa uma letra do alfabeto, e ao ser clicado, o sistema identifica qual letra foi escolhida e envia essa informação para um procedimento que verifica se ela está presente na palavra. Além disso, o botão pressionado é desativado para evitar que o jogador escolha a mesma letra novamente, o que ajuda a manter a lógica do jogo organizada.

O jogo da forca funciona começando com a escolha de uma palavra aleatória de uma lista, que é guardada internamente enquanto o jogador vê apenas traços representando cada letra. Ao clicar em uma letra, o sistema verifica se ela existe na palavra e, se existir, revela nas posições corretas; caso contrário, conta como erro e avança a imagem da forca. O jogo continua até o jogador acertar todas as letras, vencendo a rodada, ou atingir o limite de erros, perdendo. Ao final, o sistema exibe o resultado e reinicia automaticamente com uma nova palavra.

Os conceitos da Apostila ultilzados foram os loops que aparecem quando o app percorre a palavra inteira para verificar se a letra clicada existe nela. Isso permite analisar cada posição da palavra. As condições (if/else) são usadas para tomar decisões, como verificar se a letra está correta, se o jogador ganhou ou perdeu, e qual ação deve acontecer em cada caso., a criação e a ultilização de listas e variáveis Além disso, usamos componentes visuais, como botões (para as letras), rótulos (para mostrar a palavra e mensagens) e imagem (para a forca).

Foram utilizados os diversos recursos visuais, botões, foram usados audios, e diversos "if" e "else", assim coomo as diversas legendas, imagens e listas.

Um avanço é o uso de múltiplas listas com funções diferentes. Que separa uma lista com todas as palavras, outra com a palavra escolhida e outra com o que aparece na tela. Isso deixa o jogo mais organizado. Outro ponto mais avançado é o sorteio e controle de palavras sem repetição. Em vez de usar sempre a mesma palavra, seu app escolhe aleatoriamente e ainda remove da lista depois de usada. Usamos também procedimentos personalizados, como o de reiniciar o jogo e o de verificar letras. Também tem a verificação completa da palavra com loop, que percorre todas as letras para encontrar correspondências. Um app básico muitas vezes só verifica uma vez ou não trata letras repetidas, enquanto o seu já resolve isso corretamente.
  

---

## 🖥 Print das telas do Design


---

## 🧩 Print das telas dos Blocos

Inserir imagens da **programação em blocos** do aplicativo.

---
