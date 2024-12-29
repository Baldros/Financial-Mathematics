# Calulo de Juros:

## Juros Simples:

$$J = C\times i \times t$$

* $J$ é o Juros;
* $i$ é a taxa, no mesmo intervalo de tempo do tempo;
* $t$ tempo.

## Juros Compostos:

$$\begin{align*}  M &= C\times(1+r/n)^t \\
&= C\times(1+i)^t \end{align*}$$

Onde,

* $M$ é o Montante;
* $C$ é o Capital Principal;
* $r$ é a taxa;
* $n$ é o periodo;
* $t$ tempo.

Note que $\frac{r}{n} = i$.

# _Payback_:
**_Payback_** é um indicador financeiro que mede o tempo necessário para recuperar o dinheiro investido em um projeto ou aplicação. A palavra vem do inglês e significa "retorno". Ele é um dos principais parâmetros utilizados por investidores e empreendedores para avaliar a viabilidade de um novo projeto, sendo calculado com base nos fluxos de caixa gerados pelo investimento, considerando a expectativa de lucro ao longo do tempo. 

Algumas vantagens do **_Payback_**:
* Mostra o tempo que um investimento levará para trazer retorno;
* O cálculo é fácil, principalmente no caso do **_Payback_** simples;
* Permite entender a viabilidade de um negócio ou projeto, auxiliando na tomada de decisão.
  
Existem diferentes tipos de **_Payback_**, como o **_Payback_** simples e o **_Payback_** descontado. O **_Payback_** descontado é calculado a partir do fluxo de caixa, mas acrescenta-se uma taxa de desconto que corrige os valores pelo período. 

# Valor Presente Líquido:

Medida que avalia a volabilidade financeira de um projeto ou investimento, descontado todo os fluxos de caixa futuros esperados ao valor presente. Podemos formular matematicamente o calculo como,

$$\begin{align*} \text{VPL}&=\text{VPE}-\text{VPS}\\&=\sum_{i=0}^n\frac{\text{Cf}_t}{(1+r)^t}\end{align*}$$

onde,
* $\text{VPE}$ **Valor Presente das Entradas**, o que entra, normalizado pelo Juros, ou seja, trazido para "valores presentes";
* $\text{VPS}$ **Valor Presente das Saídas**, o que saíu, normalizado pelo Juros, ou seja, trazido para "valores presentes";
* $\text{Cf}_t$ são os **fluxos de caixa**, entrada e saída de dinheiro;
* $r$ é a **taxa**, geralmente é a **Taxa Mínima de Atratividade (TMA)**.

## Taxa Mínima Atrativa:

O **TMA** é um indicador que representa o **valor mínimo que um investimento deve render para ser considerado viável economicamente**. A **TMA** também pode ser usada para indicar a taxa máxima que um tomador de empréstimo está disposto a aceitar.

## Critério de Avaliação:

O critério de validação é simples, se $\text{VPL}\gt 0$, projeto aprovado. Caso contrário, não se aprova. Para a **Cesgranrio**, se nada for mencionado, o **VPL** deve ser priorizado!

# Taxa Interna de Retorno:

A **Taxa de Retorno Interno (TIR)**, ou **_Internal Rate of Return_ (IRR)**, é uma métrica que analisa o retorno financeiro de um projeto, comparando o fluxo de caixa antecipado com o valor investido. A ideia geral é trabalhar com a calculo do $\text{VPL}=0$ usando a **TIR**.

## Criétiro de Avaliação:

A **TIR** e a **TMA** são indicadores que devem ser comparados entre si para avaliar a viabilidade de um investimento:
* Quando a $\text{TIR} \gt \text{TMA}$, o projeto é considerado **viável**.
* Quando a $\text{TIR} = \text{TMA}$, a decisão de realizar o projeto fica a cargo do investidor.
* Quando a $\text{TIR} \lt \text{TMA}$, o investimento é considerado **inviável**. 

