# 🎮 Candy Crush YOLO - Instruções de Execução

Este sistema automatiza jogadas no jogo **Candy Crush** com base em visão computacional. Abaixo estão os requisitos e passos necessários para garantir o seu funcionamento adequado.

---

## 🖥️ Requisitos

- **Resolução do ecrã:** `1920x1080`  
  ⚠️ O sistema foi desenvolvido e testado com esta resolução. Outras resoluções podem comprometer a deteção.

- **Acesso ao jogo:**   [https://yaegames.com/candy-crush/#](https://yaegames.com/candy-crush/#)

- **Modo de visualização:**  
  O jogo deve estar em **ecrã inteiro (fullscreen)** para que a região do tabuleiro seja corretamente capturada.

- **Nível mínimo do jogo:**  
  ⚠️ A partir do **nível 2**, o tabuleiro é do tipo 8x8 (formato esperado pelo sistema).

---

## 🛠️ Recomendado

- Usar **dois monitores**:
  - Um exclusivo para o jogo em fullscreen
  - Outro para executar o código Python (Jupyter/Colab)

- **❗ Não mexer no rato** durante a execução, pois o sistema controla o movimento e cliques automaticamente.

---

## 🚀 Como executar

1. **Abrir** o ficheiro `yolo.ipynb` no Jupyter Notebook ou Google Colab.
2. **Executar todos os blocos** para carregar modelos e funções.
3. **Iniciar o jogo automático** executando o **bloco do loop principal**, responsável pela:
   - Captura do ecrã
   - Deteção com YOLO
   - Análise de jogadas
   - Movimentação automática do rato

---

Siga estes passos para jogar Candy Crush automaticamente com inteligência artificial! 🍬🤖