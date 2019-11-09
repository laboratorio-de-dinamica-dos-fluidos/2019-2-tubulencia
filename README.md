# 2019.2 Efeito Magnus

**Índice**
1. [Informações gerais](#id1)
1. [Introdução](#id2)
2. [Objetivos](#id4)
1. [Requisitos de solução](#id5)
3. [Escopo do experimento](#id6)
4. [Avaliação de viabilidade](#id7)
5. [Procedimentos experimentais](#id8)
6. [Referências](#id9)
<div id='id1' />

<h1>Informações gerais </h1>

**Nome dos integrantes**: Jhéssica Luz, Antonio Carlos Ribeiro Viana Junior, Francisca Raiane Gomes Pessoa.  
**GitHub dos integrantes**: jhessicaluz, antoniocrviana, RaianePessoa.  
**Tema**: Efeito Magnus.  
**Responsável pela criação do repositório**: Jhéssica Luz

<h1>Introdução </h1>

A análise e a compreensão do escoamento ao redor de corpos sólidos é de suma importância para o avanço da tecnologia, em várias áreas de estudo. Compreender a dinâmica do escoamento e sua interação com esses corpos é muito importante para avaliação do sistema por onde o fluido escoa e para determinação de parâmetros, como a sustentação e o arrasto gerado por estes corpos (Bimbato, 2012). 

O Efeito Magnus trata-se de um fenômeno hidrodinâmico descoberto pelo químico físico alemão Heinrich Gustav Magnus, onde um corpo girando em um fluido cria uma camada limite de ar ao redor dele mesmo. A camada limite induz um movimento circular generalizado do fluido. O Efeito Magnus é um caso isolado do princípio de Bernoulli, que estabelece que quando a velocidade é maior, a pressão do fluido é menor, e quando a velocidade é menor, a pressão do fluido é maior. Esse gradiente de fluido de pressão resulta em uma força líquida no corpo e consequentemente a rotação na direção perpendicular ao vetor velocidade.  

Para entender este princípio é necessário conhecer o comportamento dos fluidos em seu escoamento em torno dos objetos. Se um cilindro é introduzido num campo de escoamento inicialmente uniforme, as linhas de correte em torno do cilindro contornam o objeto. A velocidade do fluido é nula nos extremos de seu diâmetro horizontal e máxima nos extremos de seu diâmetro vertical, passando por valores intermediários para diâmetros que tenham outra orientação. Além disso, as velocidades da parede sólida e do escoamento  potencial possuem o mesmo sentido, enquanto que no escoamento principal e na parede movimentam-se em sentidos contrários (Carvalho,2003).

<p align="center">
  <img width="350" height="350" [Imagem 1] src="https://i.imgur.com/HskYTNb.png">
</p>

**Figura 1:** Esquema de um cilindro em rotação(Carvalho,2003).

Quando um fluido escoa em torno de um corpo sólido, surge sobre o corpo uma força. A projeção desta força na direção normal ao escoamento é chamada de sustentação (<a href="https://www.codecogs.com/eqnedit.php?latex=F_{l}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?F_{l}" title="F_{l}" /></a>); em contrapartida, a componente paralela à corrente livre é denominada arrasto (<a href="https://www.codecogs.com/eqnedit.php?latex=F_{d}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?F_{d}" title="F_{d}" /></a>). 

<p align="center">
  <img width="300" height="300" [Imagem 2] src="https://media.springernature.com/original/springer-static/image/art%3A10.1007%2Fs10494-017-9859-1/MediaObjects/10494_2017_9859_Fig1_HTML.gif">
</p>

**Figura 2:** Distribuição de forças em um corpo imerso em campo de escoamento.


No caso do emprego de cilindros rotativos, outros parâmetros também são analisados, como o número de Reynolds e a rotação específica, dados por: 

<a href="https://www.codecogs.com/eqnedit.php?latex=R_{e}=\frac{\rho&space;Ud}{\mu&space;}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?R_{e}=\frac{\rho&space;Ud}{\mu&space;}" title="R_{e}=\frac{\rho Ud}{\mu }" /></a>

**Equação 1:** Número de Reymolds.

<a href="https://www.codecogs.com/eqnedit.php?latex=\alpha=\frac{\omega&space;d}{2&space;U}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\alpha=\frac{\omega&space;d}{2&space;U}" title="\alpha=\frac{\omega d}{2 U}" /></a>

**Equação 2:** Rotação específica.


nas quais ρ é a massa específica do fluido, μ a viscosidade, U é a velocidade, d é o diâmetro do corpo e w éa velocidade angular do cilindro.

<p align="center">
  <img width="450" height="300" [Imagem 2] src="https://i.imgur.com/55QiiYn.png">
</p>

**Figura 3:** Escoamento de fluido em torno de um cilindro em rotação.

 Na figura 3, pode ser observado  que  as  linhas  de  corrente  estão  mais  próximas  na  parte  superior  do  cilindro. Como citado neste relatório, nessa  região  a  velocidade  do  escoamento  é  maior,  e  de  acordo  com  o  teorema  de  Bernoulli (1738): “em  toda  corrente  de  água  ou  de ar a pressão será grande quando a velocidade for pequena e, ao contrário, a pressão será pequena quando a velocidade for grande”. Dessa forma, é  explicado  o  Efeito  Magnus,  pois  como  a  pressão  na  parte  de  cima  do cilindro  é  menor  em  relação  à  parte  de  baixo  (e  consequentemente  à  pressão  atmosférica),  o objeto tende  a desviar  sua trajetória  também  para cima (BOFF et al,  2012).

Por meio desta teoria e dos estudos sobre o escoamento, foi constatado que um cilindro em rotação, imerso em um escoamento, é capaz de gerar altos coeficientes de sustentação. Entretanto, como todo corpo rombudo, apresenta altos coeficientes de arrasto.

<h1>Objetivos </h1>

 O propósito  desse projeto é demonstrar experimentalmente que o efeito Magnus gera uma força de sustentação em um Rc plane, observado na figura 1. O efeito será validado experimentalmente em túnel de vento utilizando uma adaptação da parte estrutural do dispositivo (o componente rotativo do RC plane) e desconsiderando o efeito do motor. Além da comprovação da força de sustentação, será também comprovado o arrasto gerado; para isso, será utilizado molas e pesos em pontos estratégicos da estrutura, que irão oscilar e deformar com o aumento da velocidade do fluxo de ar.  

<p align="center">
  <img width="300" height="400" [Imagem 1] src="https://static.wixstatic.com/media/42044d_7721dc274180459180a3ccff567550f4~mv2.jpg/v1/fill/w_593,h_1024,al_c,q_85/42044d_7721dc274180459180a3ccff567550f4~mv2.webp">
</p>

**Figura 4:** Rc plane.

<h1>Requisitos de solução </h1>

Para a concepção do projeto, é necessário construir uma estrutura do RC Plane que seja adequada para o teste em túnel de vento. Portanto, os requisitos englobam:

* Análise das características do túnel de vento (dimensões e velocidade); 
* Será utilizado uma base para o experimento com compensado de madeira, para que o protótipo não se desloque ao longo do túnel de vento;
* Será utilizado uma estrutura de impressão 3D, para sustentar a parte rotativa do experimento;
* Serão utilizados rolamentos e parafusos;
* A parte rotativa do experimento será constituída de madeira balsa;
* Será utilizada duas molas para validar a existência das forças de sustentação e de arrasto.





<h1>Escopo do experimento </h1> 

<p>
  Para concepção de tal projeto, será necessário primeiramente realizar um dimensionamento do túnel de vento, tendo em vista que será onde o experimento ocorrerá. Em segundo momento, será feito um desenho preliminar do protótipo, para posteriormente realizar um CAD 3D no software CATIA V5R21, este CAD ajudará na construção do protótipo que será feito com madeira balsa e impressão 3D. Finalizada a construção, se iniciarão os experimentos em túnel de vento para comprovar o efeito magnus. 
<br />
 
<h1>Avaliação de viabilidade </h1>  

Para o sucesso do experimento, algumas questões são levadas em conta, como as características do túnel de vento (Ventilator Ag Stäfa) e os componentes materiais. O local no túnel de vento onde o equipamento de teste será posicionado possui 71cm de altura por 80cm de largura; o mesmo possui velocidade máxima de 5 m/s. A princípio, a estrutura de teste possui altura de 17cm e largura máxima de 40cm, sendo viável o experimento no equipamento disposto no Laboratório de Termofluidos. Além disso, por serem peças pequenas, alguns componentes da estrutura de teste podem ser feitas em impressão 3D e madeira balsa, sem a necessidade do uso de solda, por exemplo. Assim, observa-se que o experimento possui também um custo mínimo, sendo viável e eficaz em sua proposta.

<h1>Procedimentos experimentais</h1>
 O tempo para execução dos procedimentos citados no escopo leva em conta desde a determinação das dimensões do protótipo à análise dos resultados, seguida pela escrita final do relatório. O cronograma (disposto abaixo) que relaciona as tarefas e datas foi construído de acordo com as datas de entrega de cada etapa, determinadas pelo professor.

![Figura 1- Rc Plane](https://i.imgur.com/1KWVMYN.png)

**Diagrama 1:** Cronograma.

Com relação a divisão de atividades, que pode ser observada na tabela abaixo. Foi determinada com base nas habilidades e disposição de cada membro para realiza-lás de acordo com o cronograma. 


| Divisão de atividades |                  |
|-----------------------|------------------|
| Introdução            | Raiane, Antonio  |
| Objetivo              | Jhéssica         |
| Requisitos de solução | Jhéssica         |
| Estimativa do tempo:  | Antonio          |
| Confecção do CAD      | Raiane           |
| Avaliação de custo    | Antonio          |
| Construção            | Jhéssica         |
| Análise de resultados | Todos os membros |

**Tabela 1:** Divisão de atividades.

Além disso, foi feita uma pesquisa detalhada dos preços dos materias que seriam utilizados na concepção do experimento. O grupo não teve gasto finaceiro com a madeira balsa e a placa de compensado, pois um membro do grupo já possui tais materiais e disponibilizou para uso. O orçamento final pode ser observado na tabela abaixo.

| Orçamento             |                  |
|-----------------------|------------------|
| Cola TEKBOND          | R$ 19,90         |
| Estilete              | R$ 17,40         |
| Elástico de borracha  | R$ 2,00          |
| Palito de churrasco   | R$ 5,00          |
| Parafusos             | R$ 1,47          |
| Placa de compensado   | R$ 18,00         |
| Placa de madeira balsa| R$ 19,40         |
| Impressão 3D          | R$ 15,00         |
| **Total:**            | R$ 117,57        |

**Tabela 2:** Orçamento.

Na figura 2, observa-se o CAD do experimento que foi desenvolvido no Software Catia V5-R19, elemento este que ajudará na etapa de construção e desenvolvimento do projeto. 

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/a8672JO.jpg">
</p>

**Figura 5:** CAD preliminar.

Na etapa de construção do experimento, o primeiro procedimento realizado foi a impressão das peças em uma impressora 3D, as quais podem ser observadas nas figuras abaixo. O material utilizado para a impressão foi um filamento de PLA.

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/8vPWESf.jpg">
</p>

**Figura 6:** Impressão 3D

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/CvCWOgj.jpg">
</p>

**Figura 7:** Suporte. 

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/wy9xwc4.jpg">
</p>

**Figura 8:** Parte giratória. 

Para a construção da peça rotativa, observada na figura 8, foi utilizada madeira balsa. O dimensionamento seguiu uma proporção entre a largura dos retângulos (5cm) e os raios das circunferências (2.5cm), que foram medidas baseadas nas dimensões do túnel de vento. A peça por completo é vazada e unida por um eixo (palito de churrasco). Para a construção desta peça, foram utilizadas ferramentas básicas, estilete e cola TEKBOND.

Por problemas no dimensionamento das peças no software Catia V5-R19, a construção não foi concluída no prazo estipulado de acordo com o cronograma, uma vez que algumas peças precisaram ser remodeladas e impressas novamente. Além disso, o grupo teve problema em encontrar as molas adequadas para o experimento. Portanto, optou-se por substituir as molas por elásticos, tendo em vista que umas das propostas do experimento é apenas mostrar a existência das forças de sutentação e arrasto devido a deformação do elástico. A estrutura final que foi implementada no túnel de vento pode ser visualizada na figura 9.

<p align="center">
  <img width="400" height="400" [Imgur] src="https://i.imgur.com/dRqoccl.jpg">
</p>

**Figura 9:** Estrutura final do experimento.

Outro problema encontro pelo grupo, foi a instabilidade da estrutura do experimento. Portanto, optou-se como solução medir o peso da estrutura e equilibrar com um outro peso exatamente igual (figura 10). Outra solução adotada, foi adicionar elasticos na parte contrária a parte rotativa, para a estrutura se manter em um certo equilibriu durante o ensaio em túnel de vento (Figura 11). 

<h1> Dados e Resultados</h1>

A primeira análise realizada foi a respeito do comportamento do fluido em torno da parte rotativa do experimento. Para isso utilizou-se o princípio de Bernoulli, que descreve o comportamento de um fluido a partir de princípios de conservação de energia (ALMEIDA, 2015, p.3). A equação que descreve esse princípio é descrita abaixo.

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\rho&space;v_{1}^{2}}{2}&space;&plus;&space;\rho&space;gh&space;&plus;&space;p_{1}&space;=&space;p_{2}&space;&plus;&space;\frac{\rho&space;v_{2}^{2}}{2}&space;&plus;\rho&space;gh" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\rho&space;v_{1}^{2}}{2}&space;&plus;&space;\rho&space;gh&space;&plus;&space;p_{1}&space;=&space;p_{2}&space;&plus;&space;\frac{\rho&space;v_{2}^{2}}{2}&space;&plus;\rho&space;gh" title="\frac{\rho v_{1}^{2}}{2} + \rho gh + p_{1} = p_{2} + \frac{\rho v_{2}^{2}}{2} +\rho gh" /></a>

**Equação 3:** Equação de Bernoulli.

Tal princípio também explica a sustentação gerada pelo movimento de rotação do experimento mostrando que onde a velocidade é maior, a pressão será relativamente baixa e onde a velocidade é baixa, a pressão será relativamente alta. Portanto, irá  produzir um fator sustentador. Essa diferença de pressão causada pela velocidade foi calculada e pode ser observada abaixo.

<a href="https://www.codecogs.com/eqnedit.php?latex=p_{2}-&space;p_{1}&space;=&space;15,028&space;Pa" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_{2}-&space;p_{1}&space;=&space;15,028&space;Pa" title="p_{2}- p_{1} = 15,028 Pa" /></a>

**Equação 4:** Diferença de pressão.

| Velocidades angulares |                  |
|-----------------------|------------------|
|Primeira medição       | 238 rpm          |
|Segunda medição        | 237 rpm          |
|Terceira medição       | 212 rpm          |

<h1> Referências</h1>

BIMBATO, Alex Mendonça. Estudo de Escoamentos Turbulentos em torno de um Corpo Rombudo de Superfície Hidraulicamente Lisa ou Rugosa Utilizando o Método de Vórtices Discretos. 2012. 165 f. Tese (Doutorado em Engenharia Mecânica) – Universidade Federal de Itajubá, Itajubá, 2012.

BOFF, J. ; JORGE, L. S. ; MACEDO, L. C.; SEREJO, R.; PINTO, W. T.; FONSECA, W.  S.  Demonstração  experimental  do  Efeito  Magnus  utilizando  material  de  baixo custo. XL Congresso Brasileiro de Educação e Engenharia (COBENGE), 2012, Bélem - PA.

CARVALHO, Gustavo Bifaroni de. Estudo experimental do escoamento em torno de cilindros circulares em movimento de rotação. 2003. xx, 90 f. Dissertação (mestrado) - Universidade Estadual Paulista, Faculdade de Engenharia de Ilha Solteira, 2003. Disponível em: <http://hdl.handle.net/11449/88895>.

Ribeiro, C.Z RASTREAMENTO DO PONTO DE MÁXIMA POTÊNCIA DE TURBINAS MAGNUS ACIONANDO GERADORES ELÉTRICOS. Universidade Federal de Santa Maria, Sata Maria 2014 RS, Brasil. 

<h1>Conclusão</h1>

<h1>Anexos</h1>

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/Y01baXN.jpg">
</p>

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/foQCilF.jpg">
</p>

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/0Vil6Rs.jpg">
</p>

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/53h7Nqj.jpg">
</p>
