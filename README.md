# 📘 Atividade Prática – Inteligência Artificial  

Este arquivo contém as respostas da atividade prática sobre o **Perceptron**, desenvolvida na disciplina de Inteligência Artificial.  

---

## 📌 Perguntas e Respostas  

### 1. Conceito  
O **Perceptron** é um modelo de neurônio artificial criado por **Frank Rosenblatt** em 1958.  
Ele funciona recebendo valores de entrada, multiplicando cada um por um peso, somando tudo com um **bias** e depois passando esse resultado por uma **função de ativação**, que decide se a saída será `0` ou `1`.  

Ele é importante porque foi a **primeira rede neural artificial prática** da história, e abriu caminho para o desenvolvimento das redes neurais modernas e de várias técnicas que usamos hoje em Inteligência Artificial.  

---

### 2. Funcionamento  
O Perceptron é considerado um **classificador linear**. Isso quer dizer que ele consegue traçar uma **reta** (ou um plano, quando temos mais dimensões) para separar os dados em duas classes diferentes.  

O ponto fraco é que ele só funciona bem quando os dados são **linearmente separáveis**.  
Quando o problema não é linear, como no caso do **XOR**, o Perceptron sozinho não dá conta e é preciso usar redes neurais mais complexas, com várias camadas.  

---

### 3. Código (Etapas Principais)  
O código que foi disponibilizado mostra o funcionamento básico do Perceptron. Ele passa por três etapas:  

1. **Cálculo da entrada**  
   Multiplica os valores de entrada pelos pesos e soma o resultado com o bias (`perceptron_input`).  

2. **Função de ativação**  
   Aplica a função degrau: se o valor da soma for maior ou igual a zero, retorna `1`; caso contrário, retorna `0` (`perceptron_output`).  

3. **Execução do exemplo**  
   No `main.py`, são usados valores de exemplo (entradas, pesos e bias) para mostrar como o perceptron funciona na prática.  

---

### 4. Aplicação prática  
Um exemplo simples onde o Perceptron pode ser aplicado é na **classificação de e-mails como spam ou não-spam**.  

- **Entradas:** características do e-mail, como certas palavras que aparecem na mensagem ou o tamanho do texto.  
- **Saída:** `1` para indicar spam e `0` para indicar não-spam.  

Esse tipo de modelo é útil porque pode funcionar como um **primeiro filtro** simples e rápido, antes de aplicar modelos mais avançados de detecção de spam.  