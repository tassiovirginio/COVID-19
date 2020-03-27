# COVID-19
Dados e plots sobre as informações do Corona Virus levantadas pelo Peixe Babel.

## Brasil (Confirmados e Mortes) 
O arquivo ```data/casos-br-total.csv``` até o momento trás o número total de casos suspeitos, confirmados e mortes no Brasil. Suas informações foram compiladas no script ```COVID-19_Brasil.ipynb```. Como foi interrompido o reporte de casos suspeitos, traremos aqui apenas os casos confirmados, mortes e as projeçoes.

![Casos Confirmados no Brasil](/imagens/Confirmados-Total.png)

![Número de Mortes no Brasil](/imagens/Numero-Mortes-Brazil.png)

## Mundo (Casos Confirmados)
O notebook ```COVID-19_Mundial.ipynb``` compila as informações do mundo inteiro, divididas por região. As informações foram retiradas do repositório: https://github.com/CSSEGISandData/COVID-19 <br>
O resultado do notebook mundial é um gif animado com o avanço dos casos **confirmados** ao redor do mundo.

![Casos confirmados ao redor do mundo](/imagens/mundial-covid19.gif)

#### Situação Mundial
<img style="width: 49%;" src="/imagens/log.png" />
<img style="width: 49%;" src="/imagens/abs.png" />

## China

O notebook ```COVID-19_China.ipynb``` produz o gráfico apresentado na <a target=”_blank” href="https://www.youtube.com/watch?v=7jHgS4yxS0A">live do Átila Iamarino</a>, doutor em virologia. 
> Note que as medidas preventivas da China que pararam o país, tiveram início em 23/01/2020. Ainda assim, depois dessa data, foram registrados dezenas de milhares de casos, principalmente daqueles que já haviam sido infectados antes do lockdown.

![Casos por dia, China](/imagens/data-covid19-china.gif)

![Casos por dia, China](/imagens/china-pordia.png)


## Comparação dos dados entre Itália, USA, KS e Brasil

Casos confirmados na Itália, USA, KS e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.

![Casos confirmados na Itália, USA, KS e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.](/imagens/curva_brasil_italia_US_KS.png)

![Casos confirmados na Itália, USA, KS e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.](/imagens/curva_brasil_italia_US_KS_day_confirm.png)

Taxas de crescimento da Itália.

![Taxas de crescimento da Itália](/imagens/crescimento-italia.png)

Casos confirmados no Brasil e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.

![Casos confirmados no Brasil e projeção baseado na média de crescimento de 10 dias. Em azul os casos confirmados, em vermelho a projeção.](/imagens/covid-brasil-projecao.png)

Taxas de crescimento do Brasil.

![Taxas de crescimento do Brasil](/imagens/crescimento-brasil.png)

Comparação entre as taxas de crescimento da Itália (em azul) e do Brasil (em vermelho).

![Comparação entre as taxas de crescimento da Itália (em azul) e do Brasil (em vermelho)](/imagens/crescimento-comparativo.png)

Os dados foram retirados do Ministério da Saúde do Brasil e do https://www.worldometers.info/coronavirus/
