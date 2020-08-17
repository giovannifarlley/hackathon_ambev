# Hackathon Ambev

## Um pouco do que aprendemos:

  * *De todos os dados levantados, menos de 1% dos consumidores compram produtos sem pensar no posicionamento social/ambiental do fornecedor.*
  * *Na população amostrada, as pessoas consomem mais bebidas (alcoólicas ou não) buscando sentimentos que consigam transparecer em redes sociais (alegria, prazer).*
  * *Na população amostrada, o consumo de não alcoólicos, em regiões de alta densidade populacional, tais como São Paulo e Minas Gerais tem predominância em relação a bebidas alcoólicas.*
  * *Todos os dados levantados, indicaram que as pessoas estão buscando padrão de vida mais saudável e, que tem maior preferência por sucos, bebidas energéticas e infusões (chá e café), o que nos leva a crer que estas serão as categorias com maior taxa de crescimento em 2020.*
  * *A população amostrada, evidenciou que um produto (no nosso caso, bebidas não alcoólicas), qualidade e necessidade não são os parâmetros que mais influenciam na escolha de um produto ou marca, mas sim, indicadores de posicionamento social, e como a marca faz com que estas pessoas se sentem. Esse dado foi verificado em todas as faixas etárias e níveis de escolaridade.*


## Visualização dos resultados:

[Visualização dos resultados](https://app.powerbi.com/view?r=eyJrIjoiMGUwOTczZmItODJkYi00NjI1LWEzNDUtOWIwY2E0YWYyODFhIiwidCI6IjU0NTllNjc3LTMxODctNDQ5My1hZjJlLTY1MDhjYTYxYjBjNiJ9&embedImagePlaceholder=true)


## Metodologias e tecnologias utilizadas

![Fluxo do processo](https://github.com/giovannifarlley/hackathon_ambev/blob/master/dataseeker-flow.png?raw=true)

  1. Extração de dados via api das plataformas (Twitter, Facebook e Instagram)
  2. Limpeza dos dados utilizando api do nltk 
  3. Sequenciamento e clusterização dos vetores de texto
  4. Analise de sentimentos e metodologia de deeplearning realizada api PrimeCom (código propietario: Farlley GIovanni V. Ferreira, por motivos de lei de propriedade intelectual, não podem ser disponibilizados sem um termo de confidencialidade e cooperação assinado entre as partes interessadas. Direitos de comercialização cedidos a holding BOOST Enterprise, de propriedade do autor), o output de informação está disponivel neste repositorio assim como demais dados.
  5. Visualização dos dados feita via Power BI, podendo ser acessada por: COLOCAR LINK

## Fontes de dados:

### Redes sociais pesquisadas:
  
  1. [Twitter](http://docs.tweepy.org/en/latest/)
  2. [Facebook API](https://www.crummy.com/software/BeautifulSoup/bs4/doc)
  3. [Instagram API](https://www.crummy.com/software/BeautifulSoup/bs4/doc)
  
### Questionarios disponibilizados:

  1. [Formulário](https://docs.google.com/forms/d/e/1FAIpQLSeffZeaIeeDw20gq7DpDCrQv8zeIyPaWjWN8R9elR6CRhL_FA/viewform)
  
  
## Observações:

 * *Series temporais não foram abordadas em função do custo das api's para esse tipo de dados ser inviável para este protótipo e objetivo do evento.*
 * *As fontes de dados que podem ser utilizadas neste serviço não são limitadas apenas as que foram abordadas no trabalho. Ficando a critério do cliente escolher quais além das já utilizadas, seria interessante para o contexto do seu negocio.*
 * *Análise de sentimentos e metodologia de deeplearning realizada api PrimeCom (código proprietário: Farlley GIovanni V. Ferreira, por motivos de lei de propriedade intelectual, não podem ser disponibilizados sem um termo de confidencialidade e cooperação assinado entre as partes interessadas. Direitos de comercialização cedidos a holding BOOST Enterprise, de propriedade do autor), o output de informação está disponível neste repositório assim como demais dados.
