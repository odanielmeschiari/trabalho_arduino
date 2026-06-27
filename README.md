# Dado Personalizável
---
## SOFTWARE
O programa foi desenvolvido no Arduino IDE, utilizando a linguagem C++.

**Bibliotecas:** Utilizamos #keypad.h e #LiquidCrystal.h para controlar, respectivamente, o teclado matricial 4x3 e o display LCD 16x2;

**LCD:** Então, é configurado o display LCD, definindo os pinos da placa utilizados para sua comunicação;

**Teclado Matricial 4x3:** Após, definimos a matriz de teclas, os pinos das linhas e colunas e criamos o objeto que permite ler as teclas pressionadas;

**Variável:** Declaramos a variável "maximo", que armazena o valor máximo digitado pelo usuário;

**Void Setup():** Inicializa a comunicação serial, o gerador de números aleatórios, o LCD e exibe a mensagem inicial ("Digite Max:");

**Leitura do Teclado (Void Loop()):** Verifica continuamente se alguma tecla foi pressionada;

**Entrada de Números:** Monta o número digitado pelo usuário, armazenando-o em "maximo" e exibindo-o no monitor serial e no LCD;

**Limpa o valor '*':** Zera o valor digitado e informa ao usuário que a entrada foi apagada;

**Sorteio '#':** Verifica se o valor máximo é válido e, em caso positivo, sorteia um número entre 1 e esse valor, exibindo-o no LCD e no monitor serial. Esse excerto código utiliza a função random(). Além disso, para evitar que a sequência de números seja sempre a mesma, é utilizada a função randomSeed();

**Tratamento de erros:** Caso o usuário tente realizar o sorteio com um  valor inválido, é exibida uma mensagem de erro no LCD e no monitor serial.

## CIRCUITO
<div align="center">
  <img src="https://github.com/user-attachments/assets/e752d040-0018-4626-a359-fae986bd3ea9" width="600px" alt="Imagem do circuito no simulador Tinkercad">
  <br>
  <span style="font-size: 1px;"><em>(No circuito digital foi utilizado um teclado matricial 4x4 pois não há o teclado utilizado por nós: o 4x3. A lógica é idêntica e as ligações foram ajustadas)</em></span>
</div>

## IMAGENS DO PROJETO
<div align="center">
  <img width="900" height="1600" alt="Foto de Enzo" src="https://github.com/user-attachments/assets/a6afc0bc-6c84-4eb5-9d9b-535b385bfec6" />
</div>

## VÍDEO
O vídeo pode ser acessado pelo seguinte link: 

## INTEGRANTES:
Enzo Abreu Di Santo

Daniel Meschiari Silva

Davi Miguel Moreira de Resende

Matheus de Oliveira Reis Pereira
