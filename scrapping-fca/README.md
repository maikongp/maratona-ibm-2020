Web scrapping criado para coletar a revisão dos clientes da FIAT no site https://www.carrosnaweb.com.br/

Instruções:

1 - Passar o nome do modelo do carro e o número de páginas que deseja coletar as revisões.
reviews = get_reviews_on_carros_na_web("TORO", 10)
2 - Passar o nome do arquivo csv para salvar as revisões coletadas.
save_reviews_on_csv_file(reviews,"toro_avaliacoes.csv")
