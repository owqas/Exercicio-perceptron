O Perceptron é um modelo de neurônio artificial criado por Frank Rosenblatt em 1958.
Ele recebe entradas numéricas, multiplica por pesos, soma um valor de bias e passa o resultado por uma função de ativação que decide a saída (0 ou 1).
Sua importância histórica está no fato de ser a primeira rede neural artificial prática, servindo de base para o desenvolvimento de técnicas mais avançadas em Inteligência Artificial e Aprendizado de Máquina.



O Perceptron é um classificador linear, ou seja, ele traça uma reta (ou hiperplano em dimensões maiores) que separa os dados em duas classes diferentes.
Isso significa que ele só funciona bem quando os dados são linearmente separáveis.





No código fornecido, as etapas principais foram:
	1.	Cálculo da entrada do perceptron
Multiplicação das entradas pelos pesos e soma com o bias (perceptron_input).
	2.	Função de ativação
Aplicação da função degrau: se o valor for maior ou igual a 0, retorna 1; caso contrário, retorna 0 (perceptron_output).
	3.	Execução do exemplo
No main.py, foram passados valores de entrada, pesos e bias para verificar o funcionamento do perceptron.







Um exemplo simples onde o Perceptron pode ser útil é na classificação de e-mails como spam ou não-spam.
	•	Entradas: características do e-mail (ex.: presença de certas palavras, tamanho da mensagem).
	•	Saída: 1 para spam, 0 para não-spam.

Como é uma tarefa que muitas vezes pode ser aproximada por regras lineares simples, o perceptron é suficiente para um primeiro filtro, antes de aplicar técnicas mais sofisticadas.
