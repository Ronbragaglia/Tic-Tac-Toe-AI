# 🎮 Tic-Tac-Toe AI: Jogo da Velha com Inteligência Artificial

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![ipywidgets](https://img.shields.io/badge/ipywidgets-Interactive%20UI-blue?style=for-the-badge)](https://ipywidgets.readthedocs.io/)
[![Algorithm](https://img.shields.io/badge/Algorithm-Minimax-6366f1?style=for-the-badge)](https://en.wikipedia.org/wiki/Minimax)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

> Jogo da Velha interativo onde você enfrenta uma IA imbatível: implementada com o algoritmo **Minimax**, que avalia cada jogada possível e sempre escolhe a ótima.

---

## ✨ Funcionalidades

- 🤖 **IA com Minimax**: nunca perde, sempre joga a melhor jogada possível
- 🖥️ **Interface gráfica interativa** com ipywidgets (botões clicáveis no Jupyter)
- 📊 **Contador de vitórias**: placar atualizado automaticamente
- 🔄 **Botão de reiniciar**: nova partida sem recarregar o notebook
- ⚡ Detecção automática de vitória, derrota e empate

---

## 📸 Screenshots

![Tabuleiro em jogo](https://github.com/user-attachments/assets/6c4ffb0e-7002-4bd0-b440-e0bb1eec3244)

![Vitória](https://github.com/user-attachments/assets/eb4ea3ca-3774-43e9-862d-94e3e28072b5)

![Empate](https://github.com/user-attachments/assets/9e82173b-a169-4a27-8bbc-7675b82c42f2)

---

## 🧠 Como o Minimax Funciona

```
Estado atual do tabuleiro
        ↓
  IA avalia TODOS os movimentos possíveis
        ↓
  Para cada movimento → avalia recursivamente
        ↓
  Maximiza pontuação da IA (X)
  Minimiza pontuação do humano (O)
        ↓
  Escolhe o movimento com maior pontuação
```

A IA com Minimax é **matematicamente ótima**: é impossível vencê-la, só empatar.

---

## 🛠️ Tech Stack

| Componente | Tecnologia |
|-----------|-----------|
| Interface | ipywidgets |
| Lógica / IA | Python puro + Minimax |
| Ambiente | Jupyter Notebook |
| Aux | NumPy |

---

## 🚀 Como Usar

### 1. Clone o repositório
```bash
git clone https://github.com/Ronbragaglia/Tic-Tac-Toe-AI.git
cd Tic-Tac-Toe-AI
```

### 2. Instale as dependências
```bash
pip install ipywidgets numpy jupyter
```

### 3. Abra o notebook
```bash
jupyter notebook
```

### 4. Inicie o jogo
No notebook, execute a célula com:
```python
game = TicTacToeAI()
```

Clique nos botões do tabuleiro e tente vencer a IA! 🎯

---

## 📁 Estrutura

```
Tic-Tac-Toe-AI/
├── tic_tac_toe_ai.ipynb   # Notebook principal com o jogo
└── README.md
```

---

## 🤝 Contribuições

Pull requests são bem-vindos! Sugestões: adicionar alpha-beta pruning, dificuldade ajustável ou interface web.

---

<div align="center">
  <sub>Feito com 🎮 por <a href="https://github.com/Ronbragaglia">Rone Bragaglia</a> · ML Engineer & Fundador <a href="https://cobrancaauto.com.br">CobrançaAuto</a></sub>
</div>
