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
<img width="1365" height="629" alt="Captura de tela 2026-03-29 173412" src="https://github.com/user-attachments/assets/a5b80f9e-adb4-428b-a5f4-780ad2f8b4f8" />
<img width="1362" height="629" alt="Captura de tela 2026-03-29 173304" src="https://github.com/user-attachments/assets/ca5d14e5-ea37-4ee6-8e0b-208ce9625117" />



---

## 🧩 Print das telas dos Blocos
<img width="1359" height="602" alt="Captura de tela 2026-03-29 170623" src="https://github.com/user-attachments/assets/6b69e5dd-350c-40f7-9fc3-d2dd8fe048d2" />
<img width="1102" height="516" alt="Captura de tela 2026-03-29 170525" src="https://github.com/user-attachments/assets/27483b09-2a0a-42b8-bee1-b3dbe5958d16" />
<img width="971" height="507" alt="Captura de tela 2026-03-29 170455" src="https://github.com/user-attachments/assets/cdd62bfa-4541-4a1c-8869-29507fb00244" />
<img width="952" height="501" alt="Captura de tela 2026-03-29 170431" src="https://github.com/user-attachments/assets/2f639c19-d63e-4436-959d-aae9a4dce4cf" />
<img width="1036" height="501" alt="Captura de tela 2026-03-29 170414" src="https://github.com/user-attachments/assets/3790e7d7-00df-49d7-82ab-eb2648544798" />
<img width="897" height="447" alt="Captura de tela 2026-03-29 170345" src="https://github.com/user-attachments/assets/bab6900a-74b3-4f2f-9d55-9523af0029c8" />






---
