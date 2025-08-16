# 🤖 Bot de Automação com PyAutoGUI – Python
Este projeto é um bot em Python que utiliza a biblioteca PyAutoGUI para automatizar cliques de acordo com a cor de pixels na tela.
Ele funciona como uma forma de robô de interação automática, podendo ser aplicado em jogos, testes de interface ou automações de tarefas repetitivas.

🚀 Tecnologias utilizadas
Python 3

PyAutoGUI (automação de mouse, teclado e captura de tela)

Time (controle de execução e delays)

🎮 Funcionalidades
✔ Monitora a cor de um pixel em uma posição fixa da tela.
✔ Captura em tempo real a posição e cor do mouse.
✔ Executa cliques automáticos quando a cor monitorada muda.
✔ Exibe mensagens no console para acompanhamento do processo.

🏗 Estrutura do código
pyautogui.pixel(x, y) → captura a cor RGB de um pixel específico.

pyautogui.position() → retorna a posição atual do mouse.

pyautogui.click(x, y) → executa clique automático.

while True → mantém o bot em execução contínua.

📊 Exemplo de uso
O script monitora a cor no pixel (246, 335).

Se a cor desse pixel for diferente da cor na posição atual do mouse → executa um clique em (312, 348).

Caso contrário, imprime "algo de errado".

💡 Aprendizados
Como automatizar interações com mouse e tela em Python.

Uso de cores RGB para detecção de mudanças visuais.

Construção de bots simples para jogos ou testes de software.
