# Projeto Aplicado III - Sistema de Recomendação Híbrido para Produtos de Skincare

📊 Este repositório contém o desenvolvimento completo do projeto da disciplina **Projeto Aplicado III**, envolvendo a implementação, análise e avaliação de um sistema de recomendação híbrido baseado no modelo **LightFM**. O trabalho utiliza dados reais do dataset *Sephora Skincare Reviews* (Kaggle) e explora técnicas modernas de recomendação, incluindo conteúdo textual, filtragem colaborativa e comparação com baselines.

---

## 📌 Objetivo do Projeto

O projeto busca o desenvolvimento de um sistema de recomendação que seja capaz de oferecer sugestões mais precisas e personalizadas de produtos de skincare para usuários com base em interações anteriores e atributos dos produtos. Além de apoiar consumidores em decisões de compra mais conscientes, o projeto pretende transformar esse grande volume de dados em informações valiosas, contribuindo para uma experiência de consumo mais satisfatória, melhorando a experiência de compra e agregando valor tanto para consumidores quanto para empresas.

---

## 👥 Integrantes do Projeto

- **Júlia Raissa Silva de Araujo**  
- **Mariana Silva de Oliveira**  
- **Tatiane Hitomi**

---

## 📂 Fonte e Dados

Os dados utilizados neste projeto foram obtidos no Kaggle e incluem:

- Informações detalhadas sobre **produtos e marcas**  
- **Preços**, ingredientes e características técnicas  
- **Mais de 1 milhão de avaliações** textuais de skincare  
- Dados sobre usuários, como **tipo de pele, tom de pele e data da avaliação**  
- Classificações feitas por outros usuários (útil para entender relevância e engajamento)

🔗 **Dataset — Sephora Products and Skincare Reviews**  
https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data

---

## 📂 Metadados

### **Conteúdo do Dataset_Reviews**

O arquivo `dataset_reviews` contém informações essenciais para a construção do sistema, incluindo:

- `author_id`: identificador único do usuário que escreveu a avaliação  
- `product_id`: identificador único do produto avaliado  
- `user_rating`: nota atribuída pelo usuário ao produto  
- `is_recommended`: recomendação positiva ou negativa (Sim/Não ou 1/0)  
- `skin_type`, `skin_tone`: características do usuário, como tipo e tom de pele  
- `product_name`: nome comercial do produto  
- `brand_name`: nome da marca  
- `loves_count`: número total de "loves" recebidos pelo produto  
- `avg_product_rating`: nota média geral do produto  
- `reviews`: quantidade total de avaliações recebidas  
- `ingredients`: lista de ingredientes presentes no produto  
- `price_usd`: preço do produto em dólares americanos  
- `highlights`: palavras-chave que descrevem benefícios e características do produto  
- `primary_category`, `secondary_category`, `tertiary_category`: categorias hierárquicas do produto  
