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

Em 2021, a Associação Brasileira das Entidades dos Mercados Financeiro e de Capitais - [ANBIMA](https://www.anbima.com.br/pt_br/pagina-inicial.htm) promoveu uma pesquisa com instituições do mercado de capitais brasileiro sobre sustentabilidade. Segundo a ANBIMA, "_O tema não é novo, mas a adoção dos critérios ESG (ambientais, sociais e de governança) nos processos de decisões de investimento tem crescido diante de efeitos cada vez mais visíveis de mudanças climáticas, tragédias ambientais e problemas sociais_". <p>
A pandemia do Covid-19 reforçou ainda mais a relevância de implementação de boas práticas ASG (sigla em português para os três aspectos observados: ambiental, social e governança corporativa). Diante do crescimento da indústria de fundos de investimento e, também, dos fundos temáticos,onde estão incluídos os fundos que observam os aspectos ASG, originou-se a ideia da realização de uma análise diagnóstica do comportamento destes fundos temáticos ASG durante a pandemia de Covid-19 no Brasil no período de março/2020 a junho/2021.

### Abstract

In 2021, the Brazilian Association of Financial and Capital Market Entities - [ANBIMA](https://www.anbima.com.br/pt_br/pagina-inicial.htm) promoted a survey of Brazilian capital market institutions on sustainability. According to ANBIMA, "_The topic is not new, but the adoption of ESG (environmental, social and governance) criteria in investment decision processes has grown in light of the increasingly visible effects of climate change, environmental tragedies and social problems_" . <p>
The Covid-19 pandemic further reinforced the relevance of implementing good ESG practices (acronym for the three aspects observed: environmental, social and corporate governance). Given the growth of the investment fund industry and also of thematic funds, which include funds that observe the ESG aspects, the idea of carrying out a diagnostic analysis of the behavior of these ESG thematic funds during the Covid-19 pandemic in Brazil from March/2020 to June/2021. 

### 1. Introdução

A partir da observação do crescimento da indústria de fundos e da relevância dos aspectos ASG, foi definida a seguinte Pergunta de Negócio:<p>
Houve crescimento dos fundos ASG na pandemia?<p>
O objetivo é atender demanda da área de análise da empresa gestora de fundos de investimento (_asset_) onde trabalho.

### 2. Modelagem

Apesar de contar com a possibilidade de captura de dados confiáveis de fonte aberta, como a CVM, a opção de utilização por uma plataforma paga e já contratada pela empresa foi determinante pela gama de soluções disponibilizadas, incluindo dados em série, características dos fundos, classificação ANBIMA, composição das carteiras, entre outros. Desta forma, a fonte utilizada foi a [Quantum Axis](http://www.quantumaxis.com.br).

<img align="center" height="250" width="800" src="https://user-images.githubusercontent.com/95982482/148579761-bde1e4e2-5d64-4ca9-b236-30034b4cda10.png" />

A maior parte do processo de ETL (do inglês Extraction, Transformation and Loading) foi realizado no Excel, visto a disponibilização pela Quantum Axis dos dados em série. Entretanto, houve necessidade de lançar mão do PDI - Pentaho Data Integration que é o componente da suíte Pentaho usado para criar processos de extração, transformação e carga (ETL), unicamente para "pivotar" (o mesmo que "transpor" no Excel) as variáveis de retorno x volatilidade, pois a Quantum Axis não fornece esses dados em formato de série.

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148579973-854e8bd0-9231-4074-8b94-60e990eac49a.png" />

Para entrega da Análise Diagnóstica, foi escolhido o Power BI por ser a ferramenta já amplamente utilizada pela empresa e já familiarizada pelos funcionários.

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148580330-8b5a28b7-c382-48e4-b2bb-dabf895e42d3.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148580476-56726752-4e10-41b5-85d6-17b53caeacd4.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148580622-50a5470b-0122-4a45-b11c-125d3098b783.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148580763-6d89d7ba-4ea3-4b04-920c-220dbbf21bde.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148580902-a238ef10-ae25-4475-9259-26fde873318c.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148581018-be265d18-19be-4a98-98aa-ace7ebf69b85.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148581114-a10238e3-171b-47e6-8f75-e0d060a75655.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95982482/148581263-532c62a8-ae50-4bd6-9f62-a2900cdb7496.png" />

### 3. Resultados

Com os dados disponibilizados no dashboard puderam ser demonstrados vários números, como o crescimento do PL dos fundos, o crescimento do número de fundos ASG disponibilizados na indústria de fundos, o crescimento do número de cotistas, a composição das carteiras dos fundos e a comparação com as carteiras de outros fundos, a comparação entre o retorno e a volatilidade dos fundos.

### 4. Conclusões

O diagnóstico dos fundos ASG na pandemia possibilitou responder a Pergunta de Negócio: houve crescimento dos fundos ASG no período da pandemia, tanto em número de cotistas, quanto em número de fundos disponibilizados, quanto em Patrimônio Líquido (PL). Observou-se que esse tema está presente no marcado de capitais e que as gestoras estão buscando estratégias para incorporar o compromisso com as questões ASG.

---

Matrícula: 183.477.012

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*

