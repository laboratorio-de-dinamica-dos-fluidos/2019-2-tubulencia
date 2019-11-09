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

A análise e a compreensão do escoamento ao redor de corpos sólidos é de suma importância para o avanço da tecnologia, em várias áreas de estudo. Compreender a dinâmica do escoamento e sua interação com esses corpos é muito importante para avaliação do sistema por onde o fluido escoa e para determinação de parâmetros, como a sustentação e o arrasto gerado por estes corpos. 

O Efeito Magnus trata-se de um fenômeno hidrodinâmico descoberto pelo químico físico alemão Heinrich Gustav Magnus, onde um corpo girando em um fluido cria uma camada limite de ar ao redor dele mesmo. A camada limite induz um movimento circular generalizado do fluido. O Efeito Magnus é um caso isolado do princípio de Bernoulli, que estabelece que quando a velocidade é maior, a pressão do fluido é menor, e quando a velocidade é menor, a pressão do fluido é maior. Esse Gradiente de fluido de pressão resulta em uma força líquida no corpo e consequentemente a rotação na direção perpendicular ao vetor velocidade.  

Para entender este princípio é necessário conhecer o comportamento dos fluidos em seu escoamento em torno dos objetos. Se um cilindro é introduzido num campo de escoamento inicialmente uniforme, as linhas de correte em torno do cilindro contornam o objeto. A velocidade do fluido é nula nos extremos de seu diâmetro horizontal e máxima nos extremos de seu diâmetro vertical, passando por valores intermediários para diâmetros que tenham outra orientação. 

Quando um fluido escoa em torno de um corpo sólido, surge sobre o corpo uma força. A projeção desta força na direção normal ao escoamento é chamada de sustentação (<a href="https://www.codecogs.com/eqnedit.php?latex=F_{l}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?F_{l}" title="F_{l}" /></a>); em contrapartida, a componente paralela à corrente livre é denominada arrasto (<a href="https://www.codecogs.com/eqnedit.php?latex=F_{d}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?F_{d}" title="F_{d}" /></a>). No caso do emprego de cilindros rotativos, outros parâmetros também são analisados, como o número de Reynolds e a rotação específica, dados por: 

<a href="https://www.codecogs.com/eqnedit.php?latex=R_{e}=\frac{\rho&space;Ud}{\mu&space;}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?R_{e}=\frac{\rho&space;Ud}{\mu&space;}" title="R_{e}=\frac{\rho Ud}{\mu }" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\alpha=\frac{\omega&space;d}{2&space;U}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\alpha=\frac{\omega&space;d}{2&space;U}" title="\alpha=\frac{\omega d}{2 U}" /></a>

nas quais ρ é a densidade do fluido, μ a viscosidade, U é a velocidade, d é o diâmetro do corpo e w éa velocidade angular do cilindro.

<h1>Objetivos </h1>

 O propósito  desse projeto é demonstrar experimentalmente que o efeito Magnus gera uma força de sustentação em um Rc plane, observado na figura 1. O efeito será validado experimentalmente em túnel de vento utilizando uma adaptação da parte estrutural do dispositivo (o componente rotativo do RC plane) e desconsiderando o efeito do motor. Além da comprovação da força de sustentação, será também comprovado o arrasto gerado; para isso, será utilizado molas e pesos em pontos estratégicos da estrutura, que irão oscilar e deformar com o aumento da velocidade do fluxo de ar.  

<p align="center">
  <img width="300" height="400" [Imagem 1] src="https://static.wixstatic.com/media/42044d_7721dc274180459180a3ccff567550f4~mv2.jpg/v1/fill/w_593,h_1024,al_c,q_85/42044d_7721dc274180459180a3ccff567550f4~mv2.webp">
</p>

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

Com relação a divisão de atividades, que pode ser observada na tabela abaixo. Foi determinada com base nas habilidades e disposição de cada membro para realiza-lás de acordo com o cronograma. 


| Divisão de atividades |                  |
|-----------------------|------------------|
| Introdução            | Raiane           |
| Objetivo              | Jhéssica         |
| Requisitos de solução | Jhéssica         |
| Estimativa do tempo:  | Antonio          |
| Confecção do CAD      | Raiane           |
| Avaliação de custo    | Antonio          |
| Construção            | Jhéssica         |
| Análise de resultados | Todos os membros |

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
| Total:                | R$ 117,57        |

Na figura 2, observa-se o CAD do experimento que foi desenvolvido no Software Catia V5-R19, elemento este que ajudará na etapa de construção e desenvolvimento do projeto. 

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/a8672JO.jpg">
</p>

Na etapa de construção do experimento, o primeiro procedimento realizado foi a impressão das peças em uma impressora 3D, as quais podem ser observadas nas figuras abaixo. O material utilizado para a impressão foi um filamento de PLA.

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/8vPWESf.jpg">
</p>

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/CvCWOgj.jpg">
</p>

<p align="center">
  <img width="400" height="400" [Imagem 1] src="https://i.imgur.com/wy9xwc4.jpg">
</p>

Para a construção da peça rotativa (figura acima), foi utilizada madeira balsa. O dimensionamento seguiu uma proporção entre a largura dos retângulos (5cm) e os raios das circunferências (2.5cm). A peça por completo é vazada e unida por um eixo (palito de churrasco). Para a construção desta peça, foram utilizadas ferramentas básicas, estilete e cola TEKBOND.

Por problemas no dimensionamento das peças no software Catia V5-R19, a construção não foi concluída no prazo estipulado de acordo com o cronograma, uma vez que algumas peças precisaram ser remodeladas e impressas novamente. Além disso, O grupo teve problema em encontrar as molas adequadas para o experimento. Portanto, optou-se por substituir as molas por elásticos, tendo em vista que umas das propostas do experimento é apenas mostrar a existência das forças de sutentação e Arrasto devido a deformação do elástico. 



<h1> Dados e Resultados</h1>

Será apenas analisado as reações das forças de sustenção e arrasto causadas pelo efeito magnus, sem uma análise quantitativa. Além disso, será calculada a deformação da mola. Como resultado, deseja-se comprovar o efeito Magnus e sua capacidade aerodinâmica. 
<h1>Referências</h1>

BIMBATO, Alex Mendonça. Estudo de Escoamentos Turbulentos em torno de um Corpo Rombudo de Superfície Hidraulicamente Lisa ou Rugosa Utilizando o Método de Vórtices Discretos. 2012. 165 f. Tese (Doutorado em Engenharia Mecânica) – Universidade Federal de Itajubá, Itajubá, 2012.

CARVALHO, Gustavo Bifaroni de. Estudo experimental do escoamento em torno de cilindros circulares em movimento de rotação. 2003. xx, 90 f. Dissertação (mestrado) - Universidade Estadual Paulista, Faculdade de Engenharia de Ilha Solteira, 2003. Disponível em: <http://hdl.handle.net/11449/88895>.

Ribeiro, C.Z RASTREAMENTO DO PONTO DE MÁXIMA POTÊNCIA DE TURBINAS MAGNUS ACIONANDO GERADORES ELÉTRICOS. Universidade Federal de Santa Maria, Sata Maria 2014 RS, Brasil. 
