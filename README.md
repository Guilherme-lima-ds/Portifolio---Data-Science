# Portifolio - Data-Science, Analise de dados e Web - Scraping
O objetivo desse repositório e de guarda e centralizar os projetos de Data-Science e Analise de dados feitos por mim, no intuito de demostrar valor ajudando a comunidade através do compartilhamento de conhecimento.


# Projetos

- Web-Scraping

*Projeto de Extração de dados de preços dos carros de São Francisco e Nova Iorque:*
O projeto foi realizado com o objetivo de responder algumas questões de negocio, como preço médio por carro, qual a quilometragem média de cada modelo, e assim por diante.
Para responder essas perguntas, nos vamos ter que realizar uma consulta na api do site, na qual vamos realizar o scraping para conseguimos extrair a informação que vai alimentar um banco de dados no Postgres e logo em seguida alimentar um painel no Power BI.


Automatizar a verificação de cnpj: Nesse projeto eu realizei um web-scraping do site do Simples Nacional http://www8.receita.fazenda.gov.br/SimplesNacional/Default.aspx, nele podemos analisar cnpjs para vermos se situação deles, para anlisando se e simples (ex. nao optante pelo simples nacional) e a situação deles no simei (ex. NÃO enquadrado no SIMEI
), pois tem umas diferenças no preço. Assim temos como objetivo, automatizar essa tafefa para que nao precisemos ficar manualmente, copiando cnpj, ai pega a informação, coloca no excel, ai de novo e de novo... isso acabou graças a essa automação.
Solução: https://github.com/NashGoldjr/Automatizar_Verificacao_CNPJ
