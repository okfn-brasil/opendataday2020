# Open Data Day 2020

Este repositório documenta as atividades realizadas durante o Open Data Day 2020, em edição realizada pela Open Knowledge Brasil em parceria com o Goethe-Institut, em São Paulo. 

Apresentações que aconteceram na parte da manhã:  

### Explorando os Dados do TSE via CEPESP-DATA
Com Lara Mesquita e Guilherme Russo, cientistas políticos do CEPESP da FGV
<br>
[Download](https://github.com/okfn-brasil/opendataday2020/blob/master/Cepesp_OpenData.pdf) da apresentação. 

### Parlametria: inteligência de dados para ação cidadã
Com Ariane Alves e Fernanda Campagnucci, da Open Knowledge Brasil
<br> 
Exposição do [site](https://parlametria.org/).

### Entrevistando a base de dados de empresas para encontrar conexões com o legislativo
Com Marcelo Soares, jornalista de dados, fundador da Lagom Data
<br>
[Download](https://github.com/okfn-brasil/opendataday2020/blob/master/Patopolis_Marcelo_Soares.pdf) da apresentação. 

### Desafios dos dados abertos do legislativo estadual 
Com Pedro Markun, coordenador de inovação do mandato da deputada estadual Marina Helou (Rede)
<br>
[Download](https://github.com/okfn-brasil/opendataday2020/blob/master/Dados_Alesp_PedroMarkun.pdf) da apresentação. 

## Mão na massa!
<br>
Depois das palestras, as participantes fizeram um "toró de ideias" de problemas e desafios a explorar nas bases de dados. Abaixo, as propostas que surgiram e os grupos que se formaram para trabalhar com os dados.   
 
## MESA 1
- Cruzamento da base de dados de CNPJ (da Receita, tratados pelo Brasil.io) com dados sobre parlamentares (Site da Câmara dos Vereadores e da ALESP) para encontrar vínculos entre sócios de empresas e os mandatos de deputados estaduais e de vereadores, incluindo funcionários; esse cruzamento pode ser feito com doadores de campanha (base do TSE e CEPESP Data)  

## MESA 2
- Adaptação da aplicação de mapas do CEPESP.Data ([ver aqui](http://spatial2.cepesp.io/) para eleições municipais, explorando a relação entre zona eleitoral e setor censitário;

## MESA 3
- Explorando a API – [Cepesp.Data](disponível em [R](https://github.com/Cepesp-Fgv/cepesp-r) e [Python](https://github.com/Cepesp-Fgv/cepesp-python); há boa documentação disponível [aqui](https://cepesp-fgv.github.io/tse-dados/) (“Como começar”) 
- Exploração dos dados abertos de eventos realizados na Alesp (Agenda)

## MESA 4
- Análise da distribuição geográfica dos votos para compreender a presença e influência dos parlamentares no nível local; quais deputados têm área de influência dispersa em todo o estado? Quantos estão concentrados em uma ou mais regiões?
- Análise geográfica do destino dos recursos de emendas da ALESP (dica: começar com casos que se imagina a relação clara)
- Faltas (ausência) de deputados e vereadores em comissões e votações em plenário

## MESA 5
- Documentação das barreiras e 
- Documentação dos resultados das atividades #ODD2020
- Formular pedidos – LAI (ex: incentivos fiscais)
                
### Outras opções
- Comparação entre dados de recadastramento para implementação da biometria e os dados de cadastro do TSE (2018 foi o ano com maior recadastramento, há variação por estado e dentro dos estados, como SP)
- Análise dos nomes de urna, por ex., para ver quantos se apresentam como "Pastor" (funções get_elections, get_candidates funcionam)
- Análise textual das proposições (temas que se sobressaem) e vínculos econômicos (doações/sócios de empresas);
- Análise dos [relatórios de fiscalização](https://portal.tcm.sp.gov.br/Publicacoes) do Tribunal de Contas do Município

