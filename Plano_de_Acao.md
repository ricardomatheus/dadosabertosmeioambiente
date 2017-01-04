Olá car@s. Sejam bem-vindos! Este é um projeto com repositórios totalmente abertos. 
Saudamos a todos os potenciais interessados em colaborar conosco!
Se você estiver interessado, entre em contato conosco através de Ricardo (r.matheus@tudelft.nl) ou entre em nosso [Telegram](www.telegram.me/dadosabertosnasaude)

# O Projeto
Dados Abertos na Saúde é uma iniciativa de abertura e conexão de dados da saúde brasileira. Observa-se que o nível de investimentos na área de saúde, e outras áreas correlatas como educação e combate a fome, tem aumentado nos últimos anos. Isso possibilitou que processos modificados a ponto de possibilitar avanços na manutenção e melhoria substancial da qualidade de vida de milhoes de brasileiras e brasileiros. Contudo, ainda existem dificuldades na identificação destes avanços, em especial quais os fatores (inputs) que desencadeiam esses efeitos (outcomes).

Para isso, a coleta de dados e sua análise é impresciendível. Indiscutivelmente o Brasil possui boa quantidade e qualidade de dados da área de saúde. Porém, parte destes dados ainda não está em formato aberto, apesar de estarem com livre acesso nas bases de dados (LINK PÁGINA DADOS SAÚDE). Além disso, a maioria dos dados estão em formato estatístico, o que também dificulta com que análises de dados sejam facilmente realizadas por algorítmos de computadores. Planilhas com dezenas de colunas e milhares de linhas também dificulta o fácil entendimento das pessoas que pesquisam o tema ou trabalham no dia-a-dia da saúde brasileira, reduzindo o potencial para tomada de decisão ou melhoria das políticas públicas.

Como a área de saúde é vasta e complexa, nosso foco inicial é a neoplasia, ou seja, câncer. Segundo dados da Organização Mundial de Saúde (OMS), o câncer de mama é o mais incidente em mulheres, excetuando-se os casos de pele não melanoma, representando 25% do total de casos de câncer no mundo em 2012, com aproximadamente 1,7 milhão de casos novos naquele ano. É a quinta causa de morte por câncer em geral (522.000 óbitos) e a causa mais frequente de morte por câncer em mulheres. [Fonte](http://www2.inca.gov.br/wps/wcm/connect/acoes_programas/site/home/nobrasil/programa_controle_cancer_mama/conceito_magnitude). 

# Objetivo
A partir deste quebra-cabeça das políticas públicas de saúde do Brasil, o objetivo deste projeto é:
"Identificar, abrir e conectar dados de Meio Ambiente do Brasil para criação de análises que corroborem para a tomada de decisão, melhorias de processos e avaliação das políticas públicas políticas florestais, agrícolas e climáticas".

# As Ações
As ações propostas para que o objetivo seja atingido estão descritas abaixo:  

A- A identificação das bases de dados do meio ambiente relacionadas ao escopo pedido:
•	Código Florestal: o órgão tomado como referência na disponibilização de dados referentes ao tema é o próprio Serviço Florestal Brasileiro  (SFB). O SFB é responsável pelas seguintes bases de dados:
o	Cadastro Ambiental Rural (CAR):  documentos com informações sobre o andamento desta política, onde são compilados dados sobre o cadastramento em diferentes esferas: por região, estado e município. Disponível em: http://www.florestal.gov.br/numeros-do-car.
o	Cadastro Nacional de Florestas Públicas (CNFP): instrumento de planejamento da gestão florestal, que reúne dados georreferenciados sobre as florestas públicas brasileiras. Disponível em http://www.florestal.gov.br/cadastro-nacional-de-florestas-publicas.
o	Relatório técnico Novo Código Florestal nos Estados da Mata Atlântica (publicado pela SOS Mata Atlântica). Disponível em: https://www.sosma.org.br/downloads/index.php.
•	Concessões Florestais;
o	A Lei nº 11.284/2006  é o marco legal para a realização das concessões, enquanto o Decreto nº 6.063/2007, que regulamenta a Lei.
o	O Sistema de Cadeia de Custódia (SCC) é o conjunto de procedimentos adotados para o rastreamento dos produtos florestais madeireiros explorados nas áreas sob concessão florestal.  
	Para consulta de madeira em toras transportadas da floresta para a serraria utilizando o código de barras do DOF: https://sistemas.florestal.gov.br/scc/consultascc/docsaida
	Para consulta de madeira serrada processada pela serraria dos concessionários utilizando o código do pacote/fardo de madeira serrada https://sistemas.florestal.gov.br/scc/consultascc/pacote.
o	Processo de concessão: http://www.florestal.gov.br/processo-de-concessao. 
•	Gestão de Unidades de Conservação: 
o	IN ICMBio nº 05, de 15 de maio de 2008 - Dispõe sobre o procedimento administrativo para a realização de estudos técnicos e consulta pública para a criação de unidade de conservação federal;
o	Decreto 5.758, de 13 de abril de 2006, que institui o Plano Estratégico Nacional de Áreas Protegidas.
•	Políticas Climáticas: 
o	Instituto Nacional de Meteorologia (INMET) é o principal responsável por fornecer dados para apoiar as atividades de ensino e pesquisa e outras aplicações em meteorologia, hidrologia, recursos hídricos, saúde pública, meio ambiente, etc. O Banco de Dados Meteorológicos para Ensino e Pesquisa (BDMEP) é o repositório direcionado para dados meteorológicos a serem utilizados. Disponível em   http://www.inmet.gov.br/portal/index.php?r=bdmep/bdmep.
o	Política Nacional sobre Mudança do Clima: instituída em 2009 pela Lei nº 12.187, e regulamentada pelo Decreto nº 7.390/2010;
o	Estimativas anuais de emissões de gases de efeito estufa no Brasil. Disponível em: http://www.mct.gov.br/upd_blob/0235/235580.pdf.
•	Políticas de Combate ao Desmatamento
o	Instituto Nacional de Pesquisas Espaciais (Inpe): dados consolidados do Projeto de Monitoramento do Desmatamento na Amazônia Legal por Satélite (Prodes). Disponível em   http://www.obt.inpe.br/prodes/index.php.
o	Indicadores do MMA:
	Indicadores sobre Conservação da biodiversidade nos estados (http://dados.gov.br/dataset/conservacao-da-biodiversidade-nos-estados);
	Indicadores sobre Conservação da Biodiversidade pelo manejo de espécies ameaçadas (http://dados.gov.br/dataset/conservacao-da-biodiversidade-pelo-manejo-de-especies-ameacadas-de-extincao);
	Indicadores sobre Desmatamento na Amazônia Legal (http://dados.gov.br/dataset/desmatamento-na-amazonia-legal). 


B- [Coletar os dados](https://github.com/GETIPUSP/dadosabertosnasaude/blob/master/BDAC/Lista_Bases) das bases de dados identificadas

C- Abrir em formato aberto (CSV) estas bases de dados identificadas
Exemplo II, coletar dados de páginas estáticas da Web e armazenar em formato aberto CSV ([Comma-Separated Values](https://en.wikipedia.org/wiki/Comma-separated_values) - ) para criação de repositório;

D- Conectar estes dados coletados em arquitetura de descrição comum (RDF)
Exemplo III, transformar arquivos em formato CSV para arquitetura de descrição conectada ([Linked Data](https://en.wikipedia.org/wiki/Linked_data)) como o RDF ([Resource Description Framework](https://en.wikipedia.org/wiki/Resource_Description_Framework)).

E- Criar contexto para estes dados (metadados)
Exemplo IV, criar arquivo que explique o arquivo ([metadados](https://en.wikipedia.org/wiki/Metadata)). Classificar, inserir etiquetas, explicar quais possíveis usos, etc.

F- Criar base de dados única na web (Banco de Dados Abertos e Conectados - [BDAC](https://github.com/GETIPUSP/dadosabertosnasaude/blob/master/BDAC/Lista_Bases))

G- Inserção da BDAC em ambiente web para expansão e exploração ([OpenCube](https://en.wikipedia.org/wiki/Metadata))
Exemplo V, [Ambiente já construído](http://104.199.31.4:8888/resource/OpenCubeOLAPBrowser) com arquivos abertos e conectados do Projeto [OpenGovIntelligence](www.opengovintelligence.eu) 

H- Criação de análises para tomada de decisão, melhorias de processos e avaliação das políticas públicas de câncer de mama do Brasil.
Exemplo VI, visualização de dados em [mapas](http://104.199.31.4:8888/resource/OpenCubeMapView) ou gráficos em [módulo R](http://104.199.31.4:8888/resource/RAnalyticsOverview) com potencialidade de uso de [Python libraries](https://github.com/rasbt/pattern_classification/blob/master/resources/python_data_libraries.md).
