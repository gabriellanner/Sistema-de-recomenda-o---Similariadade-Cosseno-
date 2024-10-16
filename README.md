**Sistema de Recomendação de Filmes**

Este projeto é um sistema de recomendação de filmes que utiliza características-chave de um conjunto de dados de filmes para oferecer recomendações personalizadas. 
A ideia principal é transformar colunas importantes (como gêneros, diretores ou atores) em representações vetoriais e calcular a similaridade do cosseno entre elas.
Ao medir a similaridade entre os filmes com base nesses vetores, o sistema sugere filmes que estão relacionados aos que o usuário já gostou ou demonstrou interesse.

Funcionalidades
Vetorização de colunas chave: Transforma características importantes dos filmes em vetores numéricos para cálculo de similaridade.
Similaridade do cosseno: Mede a similaridade entre os filmes utilizando a similaridade do cosseno, um método comum em sistemas de recomendação.
Recomendações eficientes: Gera recomendações encontrando filmes com as maiores pontuações de similaridade em relação às preferências do usuário.

**Tecnologias Utilizadas**
- Python
- Pandas
- Scikit-learn
- NumPy
