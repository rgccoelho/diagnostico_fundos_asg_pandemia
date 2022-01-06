# diagnostico_fundos_asg_pandemia
Diagnóstico de Fundos ASG na pandemia

#### Aluna: [Roberta Gonçalves Coelho](https://github.com/rgccoelho)

#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler)
#### Co-orientador: [Pedro Marco Achanccaray Diaz](https://github.com/pedro9589)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

https://github.com/rgccoelho/diagnostico_fundos_asg_pandemia
---

### Resumo

Foi publicada uma matéria na ["exame.invest"](https://invest.exame.com/me/os-fundos-de-acoes-que-mais-ganharam-investidores-durante-a-pandemia) que abordava a evolução da quantidade de cotistas nos fundos de investimento em ações durante a pandemia. A matéria também chamou atenção para o crescimento de fundos temáticos, como é o caso de fundos ASG. Desta forma, originou-se a ideia da realização de uma análise dignóstica do comportamento dos fundos com a temática ASG durante a pandemia de Covid-19 no Brasil no período de março/2020 a junho/2021.

### Abstract

An article was published in "exame.invest" (https://invest.exame.com/me/os-fundos-de-acoes-que-mais-ganharam-investidores-durante-a-pandemia) that addressed the evolution number of shareholders in equity investment funds during the pandemic. The article also drew attention to the growth of thematic funds, such as ESG funds. This gave rise to the idea of ​​carrying out a diagnostic analysis of the behavior of funds with the ESG theme during the Covid-19 pandemic in Brazil from March/2020 to June/2021.

### 1. Introdução

A partir da leitura da materia, foi definida a Pergunta de Negócio (Como foi o comportamento dos fundos ASG na pandemia?) e avaliadas as demais etapas do processo de BI, desde a Definição de Requisitos até o Storytelling.

### 2. Modelagem

Com o mapeamento dos dados necessários e análise das fontes confiáveis, a fonte escolhida foi a [Quantum Axis](http://www.quantumaxis.com.br).

<img align="center" height="250" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/QuantumAxis.PNG?raw=true" />

Todo processo de ETL foi realizado no PDI - Pentaho Data Integration que é o componente da suíte Pentaho usado para criar processos de extração, transformação e carga (do inglês Extraction, Transformation and Loading, ETL).

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/PDI%20ret%20vol.PNG?raw=true" />

Assim, o Power BI foi escolhido pra entrega da Análise Diagnóstica.

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/Introdu%C3%A7%C3%A3o.PNG?raw=true" />

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/Grandes%20Nrs%20032020.PNG?raw=true" />

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/Grandes%20Nrs%20122020.PNG?raw=true" />

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/Grandes%20Nrs%20062021.PNG?raw=true" />

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/Comparador%20carteiras%20032020.PNG?raw=true" />

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/Comparador%20carteiras%20122020.PNG?raw=true" />

<img align="center" height="400" width="800" src="https://github.com/rgccoelho/Imagens/blob/main/Comparador%20carteiras%20122020.PNG?raw=true" />

### 3. Resultados

Com os dados disponibilizados no dashboard puderam ser apurados várias conclusões dependendo da variável avaliada já que trata-se de uma análise multi. Mas apenas com esses dados quantitativos não há como concluir que tipo de indutor foi responsável por cada movimento em cada variável, quantidade de cotista, captação líquida e etc. Demonstrou-se com números os momentos de maior movimento mas não os motivos. Motivos estes a serem apurados com as informações qualitativas as quais não temos acesso. 

### 4. Conclusões

O diagnóstico dos fundos ASG na pandemia possibilitou verificarmos o crescimento de PL, número de cotistas e número de fundos com essa temática na indústria de fundos de investuimentos. Também viabilizou a comparação da composição dos ativos entre fundos desta temática.

---

Matrícula: 183.477.012

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*

