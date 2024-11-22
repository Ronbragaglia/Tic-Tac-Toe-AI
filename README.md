Descrição do Projeto:

Este projeto implementa uma versão interativa do Jogo da Velha, onde um jogador humano compete contra uma inteligência artificial (IA). A IA utiliza o algoritmo Minimax para tomar decisões estratégicas e garantir um jogo equilibrado. O jogo é apresentado em uma interface gráfica usando ipywidgets.

Funcionalidades:
Interface Gráfica:

Utiliza ipywidgets para criar botões que representam as casas do tabuleiro.
Exibe o turno atual do jogador e o número de vitórias de cada jogador.
Mecânica do Jogo:

O jogador humano pode clicar em um botão para fazer sua jogada.
A IA responde automaticamente após a jogada do jogador.
Possui um botão de reiniciar o jogo.
Detecção de Vitória e Empate:

O jogo verifica se há um vencedor ou um empate após cada jogada.
O jogo é reiniciado automaticamente após uma vitória ou empate.
Contador de Vitórias:

Mantém um registro do número de vitórias de cada jogador.


Tecnologias Utilizadas:
ipywidgets: Para criar uma interface gráfica interativa.

NumPy: Para facilitar operações de matriz, embora não seja essencial neste caso específico.

random: Importado, mas não utilizado diretamente; pode ser removido.

Como o Código Funciona:
Classe TicTacToeAI:

A classe TicTacToeAI é responsável por gerenciar o estado do jogo, a interface e a lógica da IA.
O método __init__ inicializa o jogo e define o jogador atual como 'X'.
Reiniciar o Jogo:

O método reset_game reinicializa o tabuleiro, define o jogador atual e cria a interface.
Interface do Usuário:

O método create_ui constrói a interface com botões para o tabuleiro e rótulos para exibir informações do jogo.
Movimento do Jogador:

O método on_button_click é chamado quando um botão do tabuleiro é clicado. Ele atualiza o tabuleiro e verifica se houve vitória ou empate.
Movimento da IA:

A IA utiliza o método ai_move para fazer sua jogada. O movimento é escolhido com base no algoritmo Minimax, que avalia todos os possíveis movimentos e escolhe o melhor.
Minimax:

O método minimax implementa a lógica de decisão da IA, avaliando o tabuleiro e retornando um valor que representa a qualidade da jogada.
Verificações de Vitória e Empate:

Os métodos check_win e check_draw são responsáveis por verificar o estado do jogo após cada jogada.
Mensagens para o Usuário:

O método display_message exibe mensagens sobre o resultado do jogo e atualiza a interface.
Resultados:
O jogo permite que o jogador jogue contra uma IA que sempre busca a melhor jogada possível.
O contador de vitórias atualiza automaticamente com base nos resultados das partidas.
A interface é clara e interativa, proporcionando uma experiência amigável ao usuário.

Exemplo de Uso:
Basta instanciar a classe TicTacToeAI para iniciar o jogo. O jogo será exibido em uma interface interativa, e o usuário poderá jogar clicando nos botões correspondentes.

game = TicTacToeAI()

Observações Finais:
O projeto oferece uma boa introdução à programação de jogos simples em Python, combinando lógica de programação e interface gráfica.
A utilização do algoritmo Minimax representa uma aplicação prática de conceitos de inteligência artificial em jogos.

![image](https://github.com/user-attachments/assets/6c4ffb0e-7002-4bd0-b440-e0bb1eec3244)

![image](https://github.com/user-attachments/assets/eb4ea3ca-3774-43e9-862d-94e3e28072b5)

![image](https://github.com/user-attachments/assets/9e82173b-a169-4a27-8bbc-7675b82c42f2)

