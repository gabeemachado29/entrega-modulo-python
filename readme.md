## Python Explicação do Código Python

O arquivo principal (`calculadora.py`) é uma aplicação de linha de comando que opera dentro de um laço de repetição contínuo. O funcionamento detalhado é:

1.  **Laço Principal (`while True`):** O código mantém a calculadora ativa indefinidamente, permitindo realizar vários cálculos em sequência sem precisar reiniciar o programa.
2.  **Entrada e Validação de Dados:**
    * O script solicita dois números ao usuário.
    * Utiliza um bloco `try-except` para converter as entradas em números decimais (`float`). Se o usuário digitar um texto não numérico, o programa captura o `ValueError`, exibe um alerta e reinicia o ciclo imediatamente.
3.  **Operações Matemáticas:**
    * Exibe um menu com 4 opções: Soma, Subtração, Multiplicação e Divisão.
    * Utiliza uma estrutura condicional (`if/elif/else`) para identificar a escolha.
    * **Tratamento de Divisão:** Na opção 4, o código verifica se o segundo número é zero antes de calcular, prevenindo erros de execução (divisão por zero).
4.  **Controle de Fluxo:** Ao final da operação, o script pergunta "Deseja realizar outra operação? (s/n)". Se a resposta for qualquer coisa diferente de 's', o comando `break` encerra o laço e finaliza o programa.