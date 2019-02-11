# Analise-Mapemaneto-Risco-Barragems-Brasil
Projeto open source com objetivo principal de identificar os potenciais riscos das barragens. Foram criados mapas dinâmicos baseados em dados abertos, e aqui nesse documento, estamos disponibilizando nossas descobertas e os códigos que foram criados para essas análises, acreditamos que compartilhar essa construção/código pode estimular e acelerar outras iniciativas do mesmo tipo ao redor do Brasil.


![Figura1](https://github.com/edumagol/Analise-Mapemaneto-Risco-Barragems-Brasil/blob/master/Dataviz/Barragens_MG_Regiao_Rompimento_Macro_2.png "Região de Brumadinho")
> Barragens na região de Brumadinho, mostrando os domícilios próximos e as respectivas barragens, o qual o raio do círculo representa o volume da barragem e a a cor do círculo o potencial de risco associado (vermelho = alto).


## Pesquisadores
O projeto foi desenvolvido por diversos pesquisadores da comunidade do **Programa Bárbara da Cappra Data Science** e pessoas também fora da comunidade. Alguns dos pesquisadores:
  * Ricardo Cappra
  * Eu mesmo..rsrs
  * [Márcio Santos](https://github.com/bi85/Mapa-de-Riscos-Barragens) - acesse os dashoboards feitos no PowerBI!
  * Anna Cristina
  * Óllivan
  * [Bruno Vianna](https://github.com/luizbweb)
  * Márcio Amaral
  * Erick Guerra
  * Flavio Thimotio
  * Franciso Estivalero

## Passo a passo para contribuir com o projeto
**Muito simples:** Basta acessar o link dos nossos notebooks na plataforma [Google Collab](https://colab.research.google.com/drive/1BOtbg3ZIIsYcDpsvfbyT1bKzAo2Oke82) e **continuar o desenvolvimento**.

O projeto também poderá ser continuado aqui pelo **[github](https://nbviewer.jupyter.org/github/edumagol/Analise-Mapemaneto-Risco-Barragems-Brasil/blob/master/ProjetoVoluntarioCienciadeDados_GeoanaliseBarragenseMunicipios.ipynb)**, portanto, segue abaixo uma breve explicação de cada conteúdo desse repositório
  1. A pasta **data** contém os arquivos das bases de dados utilizadas para fazer análise exploratória. No meu perfil do [Kaggle](https://www.kaggle.com/edumagalhaes/brazilian-dams-and-brumadinho-households), também disponibilizo a mesma base em um formato mais adequado para ciência de dados.
  2. A pasta **Dataviz** contém algumas figuras geradas na ferramenta de dataviz por geolocalização (Kepler.gl)
  3. O **notebook em python** contém alguma análise exploratória bem simples que pode ser **continuada/desenvolvida**
  4. O arquivo **keplergl.json** é o arquivo de configuração utilizada para gerar as figuras/dataviz que estão na pasta Dataviz. Caso queira partir do ponto em que paramos (veja a figura acima gerada), basta fazer um upload desse arquivo no [Kepler.gl](http://kepler.gl/#/demo)

### Data4good!

## Extra
### Links originais das princiapis fontes de dados utilizadas:


>1.   Arquivos das barragens no site do antigo **DNPM** (Departamento Nacional de Produção Mineral, agora **ANM**-Agência Nacional de Mineração) - http://www.anm.gov.br/assuntos/barragens/arquivos-barragens
  >> Nesse emaranhado de links, utilizaremos apenas o arquivo pdf do link http://www.anm.gov.br/assuntos/barragens/arquivos-barragens/CADASTRO%20NACIONAL%20DE%20BARRAGENS_2016%20_FINAL%2006-01-2017.pdf/view
  >>Tal arquivo nos ajudará a entender as colunas de classificação já geradas, porém, não deve ser muito mais útil que isso por estar em pdf (dificuldade de extrair os dados)

>2.   Inventário de barragens no site da **FEAM**, que é a Fundação Estadual do Meio Ambiente e, por isso, teremos apenas os dados das barragens de MG nesse site/repositório: http://www.feam.br/monitoramento/gestao-de-barragens
 >> Aqui, vamos utilizar o link http://www.feam.br/images/stories/2018/BARRAGENS/PLANILHA_DIVULGA%C3%87%C3%83O.xlsx para   baixar a planilha com as informações das barragens.
 >> Nesse link, temos um relatório bem legal fazendo uma análise exploratória de dados que pode ser melhorada e mais explorada, além de depois podermos cruzar com mais dados, segue o link de referência: http://www.feam.br/images/stories/2018/BARRAGENS/Invent%C3%A1rio_de_Barragens_2017.pdf

>3. IBGE, dados dos domicílios das cidades no entorno de Brumadinho: https://www.ibge.gov.br/np_download/novoportal/extras/Cadastro_e_Trajetos_Municipios_Afetados_MG.zip 
  

>4 Dados extras
 >> Dados sismológicos de acesso publico: http://obsis.unb.br/portalsis/ e http://www.sismo.iag.usp.br/eq/latest

>5 Arquivos excel/csv (convertidos do pdf do item 1.)
 >>**Excel convertido originalmente**
https://docs.google.com/spreadsheets/d/1Ntj0jr3joIJtnjZQqA9m7Qa-cgya1KiGjjng8mrT_KQ/edit?usp=sharing

 >>**CSV a partir do Excel**
https://drive.google.com/file/d/1eb5C6_7LOiLvlhU7KXmvHaQ6Soa7E9EV/view?usp=sharing
