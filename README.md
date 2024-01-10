# Analisando dados com python
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/tarcisioalvesleop/analise/blob/main/LICENSE) 

# Sobre o projeto

 Analisando dados com Python é uma aplicação para identificar as causas dos cancelamentos de serviços desenvolvida na Jornada Python pela [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).
A aplicação consiste em carregar a base de dados a ser analisado, corrigir os possíveis dados com chances de interferir na analise, analisado visualmente as causas do cancelamento através dos gráficos e
efetuado o tratamento para obtenção de evitar os cancelamentos e identificar possibilidades de fidelizar os clientes. 

## Resultados
Os resultados obtidos no projeto foram através das análises que demostram um cancelamento significativo nos termos relacionados a contratos mensal, clientes que ligaram reclamando a cima de 4 vezes e 
clientes que atrasaram o pagamento em mais de 20 dias. Após a identificação, foi tratado os causadores e o resultado de cancelamento que era de 57% reduziu para 18%.  


![normal](https://github.com/tarcisioalvesleop/analise/blob/main/assets/normal.png)   ![Tratado](https://github.com/tarcisioalvesleop/analise/blob/main/assets/tratada.png)

# Como executar o projeto

## Pré-requisitos
Antes de começar, você precisa ter instalado em sua máquina as seguintes ferramentas: [python](https://www.python.org/), [jupyter](https://jupyter.org/), [git](https://git-scm.com/) e um editor de para trabalhar com o código como [VS Code](https://code.visualstudio.com/).

``` bash
# Clone esse repositório numa pasta
$ git clone https://github.com/tarcisioalvesleop/analise.git

# Instale a biblioteca pandas através do terminal
pip install pandas numpy openpyxl

# Execute a aplicação clicando no Run ALL ou 
CTRL + ALT + ENTER   # Em cada parte do código.

```
