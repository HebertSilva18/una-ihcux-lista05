Heurísticas de Nielsen Aplicadas no Código
1. Heurística 1 — Visibilidade do Status do Sistema
O sistema informa ao usuário o que está acontecendo em tempo real. As mensagens "Conectando ao Banco Central..." e "Calculando taxas..." com os pontos animados via Thread.Sleep simulam um feedback de progresso, evitando que o usuário fique sem resposta na tela.

2. Heurística 5 — Prevenção e Recuperação de Erros
O bloco catch captura qualquer entrada inválida (como letras no lugar de números) e exibe uma mensagem clara com fundo vermelho, indicando visualmente a gravidade do problema. A mensagem orienta o usuário sobre o formato correto: "Use apenas números e vírgula para decimais."

3. Heurística 8 — Estética e Design Minimalista
O resultado é exibido de forma limpa e destacada: fonte verde, separadores --- e apenas a informação essencial (VALOR CONVERTIDO). Nada de dados desnecessários poluindo a tela, só o que o usuário precisa ver.
