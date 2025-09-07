# 📘 Atividade Prática – Inteligência Artificial  

Este documento apresenta as respostas referentes à atividade prática sobre o **Perceptron**, proposta na disciplina de Inteligência Artificial.  

---

## 📌 Perguntas e Respostas  

### 1. Conceito  
O **Perceptron** é um modelo de neurônio artificial criado por **Frank Rosenblatt**, em 1958.  
Ele recebe valores de entrada, multiplica-os por pesos, adiciona um valor de **bias** e, em seguida, aplica uma **função de ativação** que define a saída como `0` ou `1`.  

Sua importância histórica reside no fato de ter sido a **primeira rede neural artificial prática**, constituindo-se como um marco inicial para o desenvolvimento de técnicas mais avançadas em **Inteligência Artificial** e **Aprendizado de Máquina**.  

---

### 2. Funcionamento  
O Perceptron é considerado um **classificador linear**, pois estabelece uma **reta (ou hiperplano em dimensões superiores)** que separa os dados em duas classes distintas.  
Assim, seu funcionamento é adequado apenas para problemas em que os dados sejam **linearmente separáveis**.  

**Limitação:** este modelo não é capaz de resolver problemas **não lineares**, como o clássico exemplo do **XOR**, sendo necessária a utilização de arquiteturas mais complexas, como redes neurais multicamadas.  

---

### 3. Código (Etapas Principais)  
A análise do código fornecido permite identificar as seguintes etapas:  

1. **Cálculo da entrada do Perceptron**  
   Realiza a multiplicação das entradas pelos respectivos pesos e soma o valor do bias (`perceptron_input`).  

2. **Aplicação da função de ativação**  
   Utiliza a função degrau: se o valor calculado for maior ou igual a zero, retorna `1`; caso contrário, retorna `0` (`perceptron_output`).  

3. **Execução do exemplo**  
   No arquivo `main.py`, são atribuídos valores de entrada, pesos e bias, permitindo a verificação prática do funcionamento do modelo.  

---

### 4. Aplicação prática  
Um exemplo de aplicação do Perceptron é na **classificação de e-mails como spam ou não-spam**.  

- **Entradas:** características do e-mail (por exemplo, presença de determinadas palavras, tamanho da mensagem, entre outros atributos).  
- **Saída:** `1` para indicar spam e `0` para indicar não-spam.  

Esse tipo de tarefa pode ser aproximado por **regras lineares simples**, o que torna o Perceptron adequado como uma solução inicial ou como filtro preliminar, antes da utilização de métodos mais sofisticados.  