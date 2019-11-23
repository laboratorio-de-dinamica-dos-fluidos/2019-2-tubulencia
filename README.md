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

A análise e a compreensão do escoamento ao redor de corpos sólidos é de suma importância para o avanço da tecnologia em várias áreas de estudo. Compreender a dinâmica do escoamento e sua interação com esses corpos é muito importante para a avaliação do sistema por onde o fluido escoa e para determinação de parâmetros, como a sustentação e o arrasto gerado por estes corpos (1). 

O Efeito Magnus trata-se de um fenômeno hidrodinâmico descoberto pelo químico físico alemão Heinrich Gustav Magnus, no qual um corpo girando em um fluido cria uma camada limite de ar ao redor dele mesmo. A camada limite induz um movimento circular generalizado do fluido. O Efeito Magnus é um caso isolado do princípio de Bernoulli, que estabelece que quando a velocidade é maior, a pressão do fluido é menor, e quando a velocidade é menor, a pressão do fluido é maior. Esse gradiente de fluido de pressão resulta em uma força líquida no corpo e consequentemente a rotação na direção perpendicular ao vetor velocidade.  

Para entender este princípio é necessário conhecer o comportamento dos fluidos em seu escoamento em torno dos objetos. Se um cilindro é introduzido num campo de escoamento inicialmente uniforme, as linhas de correte em torno do cilindro contornam o objeto. A velocidade do fluido é nula nos extremos de seu diâmetro horizontal e máxima nos extremos de seu diâmetro vertical, passando por valores intermediários para diâmetros que tenham outra orientação. Além disso, as velocidades da parede sólida e do escoamento  potencial possuem o mesmo sentido, enquanto que no escoamento principal e na parede movimentam-se em sentidos contrários (2).

<p align="center">
  <img width="350" height="350" [Imagem 1] src="https://i.imgur.com/HskYTNb.png">
</p>

**Figura 1:** Esquema de um cilindro em rotação (2).

Quando um fluido escoa em torno de um corpo sólido, surge sobre o corpo uma força. A projeção desta força na direção normal ao escoamento é chamada de sustentação (<a href="https://www.codecogs.com/eqnedit.php?latex=F_{l}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?F_{l}" title="F_{l}" /></a>); em contrapartida, a componente paralela à corrente livre é denominada arrasto (<a href="https://www.codecogs.com/eqnedit.php?latex=F_{d}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?F_{d}" title="F_{d}" /></a>). 

<p align="center">
  <img width="300" height="300" [Imagem 2] src="https://media.springernature.com/original/springer-static/image/art%3A10.1007%2Fs10494-017-9859-1/MediaObjects/10494_2017_9859_Fig1_HTML.gif">
</p>

**Figura 2:** Distribuição de forças em um corpo imerso em campo de escoamento.


 Na figura 3 pode ser observado  que  as  linhas  de  corrente  estão  mais  próximas  na  parte  superior  do  cilindro. Como citado neste relatório, nessa  região  a  velocidade  do  escoamento  é  maior,  e  de  acordo  com  o  teorema  de  Bernoulli (1738): “em  toda  corrente  de  água  ou  de ar a pressão será grande quando a velocidade for pequena e, ao contrário, a pressão será pequena quando a velocidade for grande”. Dessa forma, é  explicado  o  Efeito  Magnus,  pois  como  a  pressão  na  parte  de  cima  do cilindro é menor em relação à parte de baixo (e consequentemente à pressão atmosférica), o objeto tende a desviar sua trajetória também para cima (3).
 
 <p align="center">
  <img width="450" height="300" [Imagem 2] src="https://i.imgur.com/55QiiYn.png">
</p>

**Figura 3:** Escoamento de fluido em torno de um cilindro em rotação.

Uma situação clássica em que se observa o efeito Magnus é quando um jogador de futebol aplica uma força em uma bola e ela rotaciona em torno do seu centro, descrevendo uma curva no ar. Outro exemplo é em um Rotor de Flettner para navios, que possuem cilindros que giram com o vento proporcionando áreas com diferentes pressões; isso gera uma terceira força que ajuda a impulsionar o navio (4). Além dessas aplicações, cilindros rotativos também são utilizados em aeronaves para gerar uma força de sustentação. 



<h1>Objetivos </h1>

O propósito desse projeto é demonstrar experimentalmente que o efeito Magnus gera uma força de sustentação em um Rc plane, observado na figura 1. O efeito será validado experimentalmente em túnel de vento utilizando uma adaptação da parte estrutural do dispositivo (o componente rotativo do RC plane) e desconsiderando o efeito do motor. Além da comprovação da força de sustentação, será também comprovado o arrasto gerado. Essas forças não serão aferidas, será apenas observado o efeito gerado por tais. Para isso, serão  utilizadas molas e pesos em pontos estratégicos da estrutura, que irão oscilar e deformar com o aumento da velocidade do fluxo de ar.


<p align="center">
  <img width="300" height="400" [Imagem 1] src="https://static.wixstatic.com/media/42044d_7721dc274180459180a3ccff567550f4~mv2.jpg/v1/fill/w_593,h_1024,al_c,q_85/42044d_7721dc274180459180a3ccff567550f4~mv2.webp">
</p>

**Figura 4:** Rc plane.

<h1>Requisitos de solução </h1>

Para a concepção do projeto, é necessário construir uma estrutura do RC Plane que seja adequada para o teste em túnel de vento. Portanto, os requisitos englobam:

* Análise das características do túnel de vento (dimensões e velocidade); 
* Será utilizada uma base para o experimento com compensado de madeira, para que o protótipo não se desloque ao longo do túnel de vento;
* Será utilizada uma estrutura de impressão 3D, para sustentar a parte rotativa do experimento;
* Serão utilizados rolamentos e parafusos;
* A parte rotativa do experimento será constituída de madeira balsa;
* Serão utilizadas duas molas para validar a existência das forças de sustentação e de arrasto.





<h1>Escopo do experimento </h1> 

<p>
  Para concepção de tal projeto, será necessário primeiramente realizar um dimensionamento do túnel de vento, tendo em vista que será onde o experimento ocorrerá. Em segundo momento, será feito um desenho preliminar do protótipo, para posteriormente realizar um CAD 3D no software CATIA V5R21; este CAD ajudará na construção do protótipo que será feito com madeira balsa e impressão 3D. Finalizada a construção, se iniciarão os experimentos em túnel de vento para comprovar o efeito Magnus. 
<br />
 
<h1>Avaliação de viabilidade </h1>  

Para o sucesso do experimento, algumas questões são levadas em conta, como as características do túnel de vento (Ventilator Ag Stäfa) e os componentes materiais. O local no túnel de vento onde o equipamento de teste será posicionado possui 71cm de altura por 80cm de largura; o mesmo possui velocidade máxima de 5 m/s. A princípio, a estrutura de teste possui altura de 17cm e largura máxima de 40cm, sendo viável o experimento no equipamento disposto no Laboratório de Termofluidos. Além disso, por serem peças pequenas, alguns componentes da estrutura de teste podem ser feitas em impressão 3D e madeira balsa, sem a necessidade do uso de solda, por exemplo. Assim, observa-se que o experimento possui também um custo mínimo, sendo viável e eficaz em sua proposta.

<h1>Procedimentos experimentais</h1>
 O tempo para execução dos procedimentos citados no escopo leva em conta desde a determinação das dimensões do protótipo à análise dos resultados, seguida pela escrita final do relatório. O cronograma (disposto abaixo) que relaciona as tarefas e datas foi construído de acordo com as datas de entrega de cada etapa, determinadas pelo professor.

![Figura 1- Rc Plane](https://i.imgur.com/1KWVMYN.png)

**Diagrama 1:** Cronograma.

A divisão de atividades pode ser observada na tabela abaixo. Tal divisão teve como base as habilidades e disposição de cada membro para realiza-lás de acordo com o cronograma. 


| Divisão de atividades |                            |
|-----------------------|----------------------------|
| Introdução            | Francisca Raiane, Antonio  |
| Objetivo              | Jhéssica                   |
| Requisitos de solução | Jhéssica                   |
| Estimativa do tempo:  | Antonio                    |
| Confecção do CAD      | Francisca Raiane           |
| Avaliação de custo    | Antonio                    |
| Construção            | Jhéssica                   |
| Análise de resultados | Todos os membros           |

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

Na Fig.5, observa-se o CAD 3D do experimento que foi desenvolvido no Software Catia V5-R19, elemento este que ajudará na etapa de construção e desenvolvimento do experimento juntamente com as plantas do projeto que podem ser visualizadas na seção de anexos. 

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

Para a construção da peça rotativa, observada na Fig.8 , foi utilizada madeira balsa. O dimensionamento seguiu uma proporção entre a largura dos retângulos (5cm) e os raios das circunferências (2.5cm), que foram medidas baseadas nas dimensões do túnel de vento. A peça por completo é vazada e unida por um eixo (palito de churrasco). Para a construção desta peça, foram utilizadas ferramentas básicas, estilete e cola TEKBOND.

Por problemas no dimensionamento das peças no software Catia V5-R19, a construção não foi concluída no prazo estipulado de acordo com o cronograma, uma vez que algumas peças precisaram ser remodeladas e impressas novamente. Além disso, o grupo teve problema em encontrar as molas adequadas para o experimento. Portanto, optou-se por substituir as molas por elásticos, tendo em vista que umas das propostas do experimento é apenas mostrar a existência das forças de sutentação e arrasto devido a deformação do elástico. A estrutura final que foi implementada no túnel de vento pode ser visualizada na Fig.9 .

<p align="center">
  <img width="400" height="400" [Imgur] src="https://i.imgur.com/dRqoccl.jpg">
</p>

**Figura 9:** Estrutura final do experimento.

Outro problema encontro pelo grupo, foi a instabilidade da estrutura do experimento. Portanto, optou-se como solução medir a massa da estrutura e equilibrar com uma outra massa exatamente igual (Fig.10 e Fig.11). Outra solução adotada, foi adicionar elasticos na parte contrária a parte rotativa, para a estrutura se manter em um certo equilibriu durante o ensaio em túnel de vento (Fig.12). 

<p align="center">
  <img width="400" height="400" [Imgur] src="https://i.imgur.com/N3zQZVE.jpg">
</p>

**Figura 10:** Massa para equilibrar.

<p align="center">
  <img width="400" height="400" [Imgur] src="https://i.imgur.com/WaiVJFz.jpg">
</p>

**Figura 11:** Massa da parte rotativa.

<p align="center">
  <img width="400" height="400" [Imgur] src="https://i.imgur.com/1oECDGJ.jpg">
</p>

**Figura 12:** Elásticos.

Para a coleta de dados, foram necessários o túnel de vento, tacômetro Digital (+- 0,005) Minipa MDT-2238B e o aparato projetado pelo grupo.
Primeiramente, colocou-se o aparato dentro no túnel de vento, que em seguida foi foi acionado. Posteriormente, com o uso de um tacômetro, mediu-se a velocidade que a peça rotativa do equipamento estava girando, dispostas na Tabela 3, na seção Dados e Resultados. 

<h1> Dados e Resultados</h1>

A primeira análise realizada foi a respeito do comportamento do fluido em torno da parte rotativa do experimento. Para isso utilizou-se o princípio de Bernoulli, que descreve o comportamento de um fluido a partir do princípios de conservação de energia (6). A equação que descreve esse princípio é descrita abaixo.

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\rho&space;v_{1}^{2}}{2}&space;&plus;&space;\rho&space;gh&space;&plus;&space;p_{1}&space;=&space;p_{2}&space;&plus;&space;\frac{\rho&space;v_{2}^{2}}{2}&space;&plus;\rho&space;gh" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\rho&space;v_{1}^{2}}{2}&space;&plus;&space;\rho&space;gh&space;&plus;&space;p_{1}&space;=&space;p_{2}&space;&plus;&space;\frac{\rho&space;v_{2}^{2}}{2}&space;&plus;\rho&space;gh" title="\frac{\rho v_{1}^{2}}{2} + \rho gh + p_{1} = p_{2} + \frac{\rho v_{2}^{2}}{2} +\rho gh" /></a>

**Equação 3:** Equação de Bernoulli.

Tal princípio também explica a sustentação gerada pelo movimento de rotação do experimento mostrando que onde a velocidade é maior, a pressão será relativamente baixa e onde a velocidade é baixa, a pressão será relativamente alta. Portanto, irá  produzir um fator sustentador. Essa diferença de pressão causada pela velocidade foi calculada e pode ser observada abaixo.

<a href="https://www.codecogs.com/eqnedit.php?latex=p_{2}-&space;p_{1}&space;=&space;15,028&space;Pa" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_{2}-&space;p_{1}&space;=&space;15,028&space;Pa" title="p_{2}- p_{1} = 15,028 Pa" /></a>

**Equação 4:** Diferença de pressão.

Outro ponto de análise é o efeito Magnus, o qual foi definido no início do trabalho e é o foco principal do experimento. Fazendo uma análise matemática da força Magnus nota-se os principais parâmetros que influenciam sua magnitude, que podem ser visualizados na Eq.5 . Além disso, sua direção vai ser determinada pelo produto vetorial entre a velocidade angular e a velocidade linear da parte rotativa. 

<a href="https://www.codecogs.com/eqnedit.php?latex=Fm&space;=&space;\frac{1}{2}&space;C_{s}\rho&space;AV^{2}&space;\frac{w\times&space;W}{w\times&space;W}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Fm&space;=&space;\frac{1}{2}&space;C_{s}\rho&space;AV^{2}&space;\frac{w\times&space;W}{w\times&space;W}" title="Fm = \frac{1}{2} C_{s}\rho AV^{2} \frac{w\times W}{w\times W}" /></a>

**Equação 5:** Força Magnus.
 
 Parâmetros da Eq.5:
 
* <a href="https://www.codecogs.com/eqnedit.php?latex=V=" target="_blank"><img src="https://latex.codecogs.com/gif.latex?V=" title="V=" /></a>  Velocidade.
 
* <a href="https://www.codecogs.com/eqnedit.php?latex=\rho&space;=" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho&space;=" title="\rho =" /></a> Massa específica.
 
* <a href="https://www.codecogs.com/eqnedit.php?latex=A&space;=" target="_blank"><img src="https://latex.codecogs.com/gif.latex?A&space;=" title="A =" /></a> Área característica.
 
* <a href="https://www.codecogs.com/eqnedit.php?latex=C_{S}=" target="_blank"><img src="https://latex.codecogs.com/gif.latex?C_{S}=" title="C_{S}=" /></a> Coeficiente de sustentação
 
* <a href="https://www.codecogs.com/eqnedit.php?latex=w=" target="_blank"><img src="https://latex.codecogs.com/gif.latex?w=" title="w=" /></a> Velocidade angular.
 

Um dado obtido ao longo do experimento foi a velocidade de rotação. Essa velocidade foi medida três vezes, as quais podem ser observadas na Tabela. 3, para obter uma precisão mais adequada e calcular os devidos erros experimentais.


| Velocidades angulares |                  |
|-----------------------|------------------|
|Primeira medição       | 238 rpm          |
|Segunda medição        | 237 rpm          |
|Terceira medição       | 212 rpm          |

**Tabela 3:** Velocidades angulares

Erro experimental:  
  <a href="https://www.codecogs.com/eqnedit.php?latex=(229rpm&space;\pm&space;12,02)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(229rpm&space;\pm&space;12,02)" title="(229rpm \pm 12,02)" /></a>

Além disso, foi calculado as velocidade médias angulares e lineares, observadas nas Eq.6 e Eq.7.

**Equação 6:** Velocidade média angular.

 <a href="https://www.codecogs.com/eqnedit.php?latex=Vm=\frac{238&plus;237&plus;212}{3}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Vm=\frac{238&plus;237&plus;212}{3}" title="Vm=\frac{238+237+212}{3}" /></a>
 
 <a href="https://www.codecogs.com/eqnedit.php?latex=Vm=229rpm" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Vm=229rpm" title="Vm=229rpm" /></a>
 
 **Equação 7:** Velocidade média linear.
 
 <a href="https://www.codecogs.com/eqnedit.php?latex=229&space;rpm&space;=0,6m/s" target="_blank"><img src="https://latex.codecogs.com/gif.latex?229&space;rpm&space;=0,6m/s" title="229 rpm =0,6m/s" /></a>




Ademais, analisou-se os efeitos da força de sustentação (Fs) e a Força de arrasto (Fa) gerados no experimento. Observou-se pela deformação dos elásticos que apesar da força de sustentação ser alta o arrasto produzido também foi alto. Portanto, “ os corpos rombudos produzem um alto coeficiente de arrasto, que se deve, sobretudo, ao descolamento prematuro da camada limite, acarretando a formação de uma esteira relativamente larga” (6). Na Fig.12, pode ser visualizado como essas forças deformaram os elásticos.  

<p align="center">
  <img width="400" height="400" [Imgur] src="https://i.imgur.com/3naEYBf.png)">
</p>

Para definir o regime do escoamento, foi calculado o número de Reynolds definido no Eq. 6. Para tal cálculo, primeiramente calculou-se a massa específica do ar e a viscosidade que são apresentados abaixo. Como o número de Reynolds obtido foi consideravelmente baixo, tem-se um escoamento laminar, caracterizado por apresentar partículas se movendo através de uma trajetória bem definida. 

Parâmetros para o cálculo do número de Reynolds:

* <a href="https://www.codecogs.com/eqnedit.php?latex=\rho&space;=&space;1,2023&space;\frac{kg}{m^{3}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho&space;=&space;1,2023&space;\frac{kg}{m^{3}}" title="\rho = 1,2023 \frac{kg}{m^{3}}" /></a>   Massa específica do ar.

* <a href="https://www.codecogs.com/eqnedit.php?latex=\nu&space;=&space;1,861598e&space;-5&space;\frac{kg}{ms}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\nu&space;=&space;1,861598e&space;-5&space;\frac{kg}{ms}" title="\nu = 1,861598e -5 \frac{kg}{ms}" /></a>   Viscosidade do ar.

* <a href="https://www.codecogs.com/eqnedit.php?latex=D=&space;0,05&space;m" target="_blank"><img src="https://latex.codecogs.com/gif.latex?D=&space;0,05&space;m" title="D= 0,05 m" /></a>   Diâmetro da parte rotativa 

*  <a href="https://www.codecogs.com/eqnedit.php?latex=V=&space;5&space;\frac{m}{s}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?V=&space;5&space;\frac{m}{s}" title="V= 5 \frac{m}{s}" /></a>   Velocidade do túnel de vento.

 <a href="https://www.codecogs.com/eqnedit.php?latex=Re&space;=\frac{\rho&space;VD}{\nu&space;}=&space;16146,074" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Re&space;=\frac{\rho&space;VD}{\nu&space;}=&space;16146,074" title="Re =\frac{\rho VD}{\nu }= 16146,074" /></a>

**Equação 6:** Número de Reynolds.

<h1>Conclusão</h1>


As análises realizadas ao longo do experimento se mostraram condizentes com a bibliográfica vigente. Pode se concluir, que a utilização do efeito Magnus em um RC plane é viável e uma ótima alternativa, pois se comprovou pela deformação dos elásticos que é possível produzir uma força de sustentação significativa, mesmo com o arrasto gerado. Porém, esse arrasto é um dos motivos pelo o qual os cilindros rotativos não serem empregados com frequência na indústria, por isso é importante se fazer um estudo do controle da camada limite em torno de tal, para obter uma relação conveniente entre o arrasto e a sustentação. Outro ponto que dificulta a aplicação dos cilindros rotativos  é o fato de serem móveis, o que possibilita mais graus liberdade, tornando assim o projeto com mais desafios.



<h1> Referências</h1>

(1) BIMBATO, Alex Mendonça. Estudo de Escoamentos Turbulentos em torno de um Corpo Rombudo de Superfície Hidraulicamente Lisa ou Rugosa Utilizando o Método de Vórtices Discretos. 2012. 165 f. Tese (Doutorado em Engenharia Mecânica) – Universidade Federal de Itajubá, Itajubá, 2012.

(2) CARVALHO, Gustavo Bifaroni de. Estudo experimental do escoamento em torno de cilindros circulares em movimento de rotação. 2003. xx, 90 f. Dissertação (mestrado) - Universidade Estadual Paulista, Faculdade de Engenharia de Ilha Solteira, 2003. Disponível em: <http://hdl.handle.net/11449/88895>.

(3) BOFF, J. ; JORGE, L. S. ; MACEDO, L. C.; SEREJO, R.; PINTO, W. T.; FONSECA, W.  S.  Demonstração  experimental  do  Efeito  Magnus  utilizando  material  de  baixo custo. XL Congresso Brasileiro de Educação e Engenharia (COBENGE), 2012, Bélem - PA.

(4)The Flettner Rotor – An Invention Ahead of Its Time. Deutsches Technikmuseum, 1 agosto de 2010. Disponível em: <https://sdtb.de/index.php?id=1623&type=0>

(5) Ribeiro, C.Z RASTREAMENTO DO PONTO DE MÁXIMA POTÊNCIA DE TURBINAS MAGNUS ACIONANDO GERADORES ELÉTRICOS. Universidade Federal de Santa Maria, Sata Maria 2014 RS, Brasil. 

(6) ALMEIDA, Bruno Seixas Gome. Aerodinâmica de bolas. Rev. Bras. Ensino Fís. vol.37 no.3 São Paulo July/Sept. 2015




<h1>Anexos</h1>

Drawing das peças 

**Anexo 1:** 
<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/Y01baXN.jpg">
</p>

**Anexo 2:**
<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/gDiL3dJ.jpg">
</p>

**Anexo 3:**
<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/0Vil6Rs.jpg">
</p>


**Anexo 4:**
<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/aVP7hWy.jpg">
</p>

**Anexo 5:**
<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/gRWrPXf.jpg">
</p>

Vídeo do teste em túnel de vento

**Anexo 6:**

[![Watch the video](https://i.imgur.com/2yjtCsi.png)](https://youtu.be/loM8fx40lCo)
