# Projeto Aplicado III - Sistema de Recomendação Híbrido para Produtos de Skincare

📊 Este repositório contém o desenvolvimento completo do projeto da disciplina Projeto Aplicado III, envolvendo a implementação, análise e avaliação de um sistema de recomendação híbrido baseado no modelo LightFM. O trabalho utiliza dados reais do dataset Sephora Skincare Reviews (Kaggle) e explora técnicas modernas de recomendação, incluindo conteúdo textual, filtragem colaborativa e comparação com baselines.

📌 Objetivo do Projeto

O projeto busca o desenvolvimento de um sistema de recomendação que seja capaz de oferecer sugestões mais precisas e personalizadas de produtos de skincare para usuários com base em interações anteriores e atributos dos produtos. Além de apoiar consumidores em decisões de compra mais conscientes, o projeto pretende transformar esse grande volume de dados em informações valiosas, contribuindo para uma experiência de consumo mais satisfatória, melhorando a experiência de compra e agregando valor tanto para consumidores quanto para empresas.

👥 Integrantes do Projeto

Júlia Raissa Silva de Araujo, Mariana Silva de Oliveira e Tatiane Hitomi

📂 Fonte e Dados

Os dados foram obtidos do Kaggle e incluem:

Produtos e marcas

Preços e ingredientes

Mais de 1 milhão de avaliações de skincare

Data da avaliação e características dos usuários

Classificações feitas por outros usuários

Os dados estão organizados em arquivos CSV.

Link do datasets utilizados: https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data

📂 Metadados

O arquivo dataset_reviews contém informações essenciais para a construção do sistema de recomendação, incluindo:

-review_id: identificador único da avaliação

-product_id: identificador do produto avaliado

rating: nota atribuída pelo usuário

review_text: texto escrito pelo consumidor, usado para processamento de linguagem natural

is_recommended: indicação de recomendação positiva ou negativa

skin_type, skin_tone: características do usuário

helpful_count: número de avaliações de outros usuários classificando a review como útil

author_id: identificador do autor da avaliação

submission_time: data e horário da avaliação
