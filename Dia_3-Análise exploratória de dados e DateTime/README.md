# Dia -3 - Análise exploratória de dados e DateTime

## #7DaysOfCode - Python Pandas 3/7: Análise exploratória de dados e DateTime

Chegou a hora de começar a explorar os seus dados!

Um dos objetivos de uma biblioteca é promover o uso da informação. Como escreveu Ranganathan (considerado o pai da biblioteconomia) em sua primeira lei:
“Os livros são para serem usados”.

Por isso, o empréstimo dos materiais em uma biblioteca é uma das formas de se indicar o uso daquela informação. Entender a quantidade e quando se emprestaram os livros é uma das primeiras formas de fazer uma análise desse tipo.

Bora explorar como evoluíram os empréstimos com o decorrer do tempo?

A diretoria da biblioteca gostaria de entender se a quantidade de empréstimos está diminuindo, aumentando ou permanecendo igual ao decorrer dos últimos anos.

Para isso, verifique qual é a quantidade total de exemplares emprestados por cada ano e plote um gráfico de linhas.

Depois, faça uma análise em relação à visualização gerada.

Atente-se para a quantidade de exemplares emprestados, e não de empréstimos realizados.

A diretoria também gostaria de gerenciar melhor os recursos humanos da biblioteca de acordo com a demanda de trabalho existente. Por exemplo:

- gerenciar a programação de férias dos colaboradores de acordo com os meses de menor demanda;
- programar atividades que não sejam de atendimento ao usuário para períodos específicos de menor demanda.

Há uma suspeita interna de que os meses com maior número de exemplares emprestados sejam março e setembro, mas não foi realizada uma análise real sobre isso.

Portanto, gere uma tabela com a quantidade total de exemplares emprestados por mês e descubra quais meses são os que possuem a maior quantidade de empréstimos realizados. Plote um gráfico de linhas.

Traga suas análises em relação a quais meses poderiam ser as melhores opções.

Além do gerenciamento anual das atividades, a diretoria também necessita que seja planejada uma programação diária das atividades. Por este motivo, verifique quais foram os horários com maior quantidade de empréstimos ao longo de um dia inteiro.

Plote um gráfico de barras e analise quais seriam os melhores horários para alocar as demais atividades que não sejam de atendimento ao usuário.

## Dica

Verifique a quantidade de empréstimos pelos números de ID. Investigue pela relação deles com o ID dos exemplares.

O groupby poderá te ajudar nesse desafio.

Transforme as datas em tipo Datetime.

Não deixe de caprichar nos gráficos:

- coloque um título adequado e objetivo;
- escolha cores adequadas e acessíveis para todas as pessoas;
- deixe apenas as informações relevantes, o excesso prejudica a visualização.

## Extra

Confira esse texto da Alura<https://www.alura.com.br/artigos/lidando-com-datas-e-horarios-no-python?utm_medium=email&_hsenc=p2ANqtz-89AMtaKCYVFDimR0sb_uPQkxBtqGwVgZHWTlhvcSlGmerHz3G-yr6s7Vhjp8XcOI7rSvri82qAFOXQjP81QGCU8peg5w&_hsmi=270879347&utm_content=270879347&utm_source=hs_automation> sobre Python Datetime e também esse meu texto sobre como manipular data e hora para analisar dados com o Pandas.<https://franciscofoz.medium.com/como-manipular-data-e-hora-em-an%C3%A1lise-de-dados-com-pandas-63b7024eb801>

Para as visualizações, não deixe de conferir esses textos da Alura sobre visualização de informações em um gráfico e esse outro sobre visualização de distribuição de dados.

Verifique a documentação sobre objetos Datetime em Series do Pandas, tenho certeza que ela poderá te nortear.
Curioso sobre quem foi Ranganathan? Clique aqui para saber mais.

<https://www.alura.com.br/artigos/analise-de-dados-analisando-minha-distribuicao-com-tres-alternativas-de-visualizacao?utm_medium=email&_hsenc=p2ANqtz-8P9wJ81vXV2yuxYMtXStqRudDDW2cXPvJMPjIjYqgFHdm5mjWPookyzxwEa9OlatQQn-BQMZOMniHpq7LscC9oB4EINw&_hsmi=270879347&utm_content=270879347&utm_source=hs_automation>

<https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.dt.date.html?utm_medium=email&_hsenc=p2ANqtz--uWAx0GCZp3Hue34eoDBGG9hBaIV8hzWILw55bn2B_p2ck7zBZ5hmYZeLbCuq7rzLg9ZJXgmvN4bA20DqxZJPA83iEZw&_hsmi=270879347&utm_content=270879347&utm_source=hs_automation>
