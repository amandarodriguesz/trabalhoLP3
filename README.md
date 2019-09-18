# trabalhoLP3
Trabalho de Linguagem de Programação 3 , utilizando servlets :


1.Crie uma aplicação JAVA   Web ,  no  qual  deverá  ser  nomeada (lp3-seunome)	

2.Crie  um package(br.edu.ifms.model)  na  pasta src,  neste  pacote  crie uma  classe JAVA (deverá  ser  um  cadastro  que  você  deverá  escolher). Nesta classe deverão obrigatoriamente ser criados os atributos dos tipos e quantidades:
-2-Integer
-3 –String
-1 –Double–deverá ser um valor monetário
-2 –Date-1 –boolean
-1 –char 

Obs: não esquecer os métodos Getter e Setter.

3.Baseado  na  classe  que  você  criou,  monte  um  formulário HTML,que permitirá  o  usuário  informar  os  dados  (não  necessita  validação  de campos)  e  após  digitar  os  dados  possa  enviar  os  valores  usando  o método Postpara um Servlet. Está página poderá ser HTML ou JSP e deverá ser criada na pasta WebContent.

4.Crie um package(br.edu.ifms.controller) na pasta src, neste pacote crie um Servletque  receberá  os  parâmetros  enviados  pelo  formulário  de cadastro. Após receber os parâmetros, popule um objeto do tipo classe que você escolheu e adicione a um objeto tipo List (crie uma classe com a  função  de  um  banco  de  dados com  inserção  estática  de  pelo  menos dois objetos,  conforme exemplo    no    projeto    lp3    que    estamos desenvolvendo).

O Servlet também deverá ter um dispachador que irá enviar o requeste o response para uma página JSP que deverá listar os objetos cadastrados no banco de dados. 

5.Os  dados  deverão  ser  listados  em  uma  tabela  na  página  JSP  e  nesta tabela os dados abaixo deverão ser formatados usando tagsJSTL:
-atributo  Double 
–formatar  com  o  cifrão  de  Real  e  casas  decimais utilizando a vírgula;
-atributo  Date  deverá  ser  apresentado  no  formato  (dia/mês/ano hora: minutos:segundos);
-atributo boolean –se o valor for true deverá ser escrito VERDADEIRO e caso false deverá ser escrito FALSO;
-O laço deverá ser realizado usando o ForEachdo JSTL.

6.Depois de testada e finalizada as etapas 1 a 5, crie um Servlet que terá a  função  de  carregar  uma  lista  de  objetos  estaticamente  no  banco  de dados em  um  objeto  List e  enviar  esta  lista  via  dispachador  para uma página  JSP  que  deverá  apresentar a  tabela  dos  dados  no  mesmo formato  do  solicitado  no  item  5.  Adicionar  na  tabela  a  cada  linha  da mesma  e  implementar  as  funcionalidades  de  REMOVER  e  EDITAR  os dados conforme exemploimplementado no projeto lp3.
