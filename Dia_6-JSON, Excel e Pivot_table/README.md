# #7DaysOfCode - Python Pandas 6/7: 👩🏽‍💻 JSON, Excel e Pivot_table

Hoje, você terá mais dados para enriquecer as suas análises.

As instituições de ensino superior (IES) têm a necessidade de passar por avaliações do Ministério da Educação (MEC) para que possam ofertar e continuar ofertando cursos de graduação e pós-graduação.

A biblioteca universitária faz parte de um dos indicadores da avaliação dos cursos, em principalmente três aspectos: acervo, infraestrutura e serviços.

Dentre os serviços, são avaliados se existem recursos de bases referenciais para pesquisa, se há treinamentos para os usuários utilizarem os materiais, e a presença de indicadores sobre o uso dos materiais do acervo (empréstimos, consultas) dentre outros tópicos.
Durante meu trabalho como bibliotecário universitário, eu já passei por esta experiência, e um dos indicadores enviados foi a quantidade de empréstimos realizados nos últimos anos pelos cursos que seriam avaliados.

Por este motivo, no desafio de hoje, você precisará de novas métricas em relação aos empréstimos, de acordo com os cursos.

Você precisará calcular a quantidade de empréstimos realizados entre 2015 e 2020 por cada curso de graduação que passará pela avaliação.

Os cursos serão:

- Biblioteconomia
- Ciências sociais
- Comunicação social
- Direito
- Filosofia
- Pedagogia

A universidade forneceu os dados dos usuários, mas uma parte deles está em [planilhas de Excel](https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/blob/main/Dia_6-Novos_dados_novas_analises/Datasets/matricula_alunos.xlsx?utm_medium=email&_hsenc=p2ANqtz-_KkEJQ1U6YGdlf9DvWDN53W64tJAyIsnZSUd-3zUz8Vr241cn7O69702upz28KP02pMUST3Hk_tor2d7AkzKB1DMvf_w&_hsmi=270881120&utm_content=270881120&utm_source=hs_automation), a outra parte veio através de uma [API do sistema em formato JSON](https://raw.githubusercontent.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/main/Dia_6-Novos_dados_novas_analises/Datasets/cadastro_alunos.json?utm_medium=email&_hsenc=p2ANqtz-_LMen0LV_BNfG1pZk7ow8p8b8rcT5DeavhNGtbLmFe6uwYQC6tPjKTm02BVGqHno-j5iEc3eqmwjFnPcaT_nID6k6RCg&_hsmi=270881120&utm_content=270881120&utm_source=hs_automation).

## Dicas

Garanta que a coluna de matrícula dos alunos estejam no mesmo formato de dados e não tenha nenhum dado nulo.

## Extra

Explore a [seção de entrada e saída de dados do Pandas](https://pandas.pydata.org/docs/user_guide/io.html?utm_medium=email&_hsenc=p2ANqtz-8XIF2tR2aBy-AOonDM6qraUC_2jhyFFDuH5zdMcM7llheNPhNEH395QrUJC7AdWK4gRbeyXfU33cjNI9E51yVdaOJjRQ&_hsmi=270881120&utm_content=270881120&utm_source=hs_automation).

Confira esse meu texto sobre [manipulação de dados JSON com Pandas](https://franciscofoz.medium.com/como-extrair-e-transformar-dados-json-com-pandas-34f6199393c1) e [esse outro](https://medium.com/@vanleiko/pivot-e-pivot-table-qual-a-diferen%C3%A7a-entre-esses-dois-m%C3%A9todos-do-pandas-15244325b493) da Vanessa Leiko sobre pivot_table.
