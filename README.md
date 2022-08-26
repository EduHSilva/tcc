# Uso da análise de dados em cenários empresariais: Incrementado à Estratégia de Marketing Digital

O perfil do consumidor mudou com a disseminação da internet e redes sociais, a opinião sobre uma marca ou produto deixou
de levar em consideração somente o serviço oferecido, valorizando principalmente a experiência de uso e identificação
com a marca.

## Objetivos

Fornecer uma metodologia de acompanhamento das publicações de consumidores e oferecer um
relatório para profissionais de marketing e gestores, com a finalidade de colaborar com o processo estratégico de tomada
de decisão.

Utilizar de data mining e data science para buscar dados online e fornecer uma solução que permita à empresa uma
estratégia de tomada de decisões baseada em dados. Dessa forma, o presente trabalho irá executar a mineração de dados na
base do twitter e gerar um relatório que forneça dados para um profissional avaliar o posicionamento da marca e as
avaliações de consumidores.

## Dados

Os dados foram coletados a partir do twitter utilizando a biblioteca tweepy, utilizando o termo de busca 'IFood'. Abaixo
dicionario de dados resultante da mineração de dados:

| Coluna        | Tipo   | Descrição                                                                |
|---------------|--------|--------------------------------------------------------------------------|
| id            | int64  | Identificador único auto-incrementável                                   |
| user          | object | Nome do usuário que executou a publicação                                |
| id_tweet      | int64  | Identificador de publicação                                              |
| text          | object | Conteúdo textual da postagem                                             |
| created_at    | object | Data da publicação                                                       |
| retweet_count | int64  | Quantidade de compartilhamentos, não incluídos os com novos comentários. |
| reply_count   | int64  | Quantidade de comentários                                                |
| like_count    | int64  | Quantidades de gostei na publicação                                      |
| quote_count   | int64  | Quantidade de compartilhamentos com novos comentários                    |

# Etapas executadas

- Pré processamento -> Remoção de pontuação, Remoção de Dados Indesejados (duplicidade e colunas sem valor para análise)
  , tokenização, remoção de stopwords, lematização
- Matriz de Frequência de Termos
- WordClouds
- Modelo para análise de sentimentos

## Resultados
