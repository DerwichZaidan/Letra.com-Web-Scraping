# Letra.com-Web-Scraping

Este é um notebook em Python feito no Google Colab, que realiza um web scraping no site <https://www.letras.com/>, com o objetivo de extrair todas as letras de música de um determinado artista. O resultado é um arquivo no formato .csv, dividido nas colunas 'Artista', 'Título' e 'Letra', que pode ser aproveitado para Análise de Sentimentos e Word Cloud.

Para que o código funcione, forneça na linha abaixo, dentro das aspas, a url do artista que você pretende coletar as letras.

    # URL da página do artista (ALTERE AQUI)
    url_artista = "https://www.letras.mus.br/seu-artista/"

Na linha abaixo, defina o caminho do Google Drive e o nome do arquivo .csv:

    # Nome do arquivo de saída (ALTERE AQUI)
    caminho_saida_csv = '/content/drive/My Drive/letras_musicas.csv'
