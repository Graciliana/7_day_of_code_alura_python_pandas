# Dia 7 - #7DaysOfCode - Python Pandas 7/7: Customização de tabelas

Esse é o seu último dia de #7DaysOfCode com Python Pandas! Durante os últimos 6 dias, você percorreu uma jornada com desafios diários com os quais você pode praticar bastante as suas habilidades.

Você brincou com conceitos de importação de diferentes formatos, manipulação e limpeza, exploração e visualização.

Tenho muito orgulho que você chegou até aqui! Agora vamos finalizar com mais um desafio?

A diretoria da biblioteca está montando um plano de ação de marketing focado nos alunos da pós-graduação. Para isso, precisará analisar a **diferença percentual de empréstimos realizados nos últimos anos (2017, 2018, 2019) para cada curso.**

Devido à pandemia do COVID-19, ela não poderá utilizar os dados de 2020 e 2021. Entretanto, seu colega de equipe já realizou uma análise de previsão de empréstimos de 2022 e a [disponibilizou para que você](https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/blob/main/Dia_7-Apresentando_resultados_em_HTML/Dataset/previsao?utm_medium=email&_hsenc=p2ANqtz--o0LVkxC0MSW_O6Kfnb8RDWknv5zciyxvs2gv8Hlorz5F6hcpKiXFL9kLQXH2DppZSDHGjhFKqyMo3ArOkZxHOx_os0w&_hsmi=270881946&utm_content=270881946&utm_source=hs_automation)também possa realizar o comparativo entre 2019-2022.

Você precisará criar uma tabela com as diferenças percentuais de empréstimos entre 2017-2018, 2018-2019, 2019-2022.

Porém, essa análise será disponibilizada em conjunto com outros dados, através de uma página da web, e a equipe de Front-end te solicitou que enviassem para eles o HTML da tabela.

Eles precisam que ela tenha as seguintes características:

- Não contenha numeração de índice;
- Os nomes dos cursos tenham apenas a primeira letra maiúscula;
- Os números percentuais estejam indicados pelo símbolo “%”;
- Cor dos números: Positivos = Verde; Negativos = Vermelho

## EXERCÍCIO OPCIONAL

Você sabe que a equipe de Front-end está com muito trabalho e talvez poderia auxiliá-los um pouco mais. Caso tenha tempo, envie para eles a tabela já com algumas estilizações do CSS prontas para adiantar o trabalho.

O padrão inicial para as tabelas deste projeto será:

- Cabeçalho:

  - font-size = 1.4rem
  - text-align = center
  - font-weight = bold
  - color = whitesmoke
  - background-color = #001692
  - border-radius = 0.25rem
  - box-shadow = 0 0 1rem gray

- Corpo:
  - font-size = 1rem
  - padding = 0.5rem
  - text-align = left
  - font-weight = bold
  - border-bottom = 0.1rem solid lightgray

## DICA

Não deixe de conferir a documentação do Pandas:

- [Leitura de arquivos gerais.](https://pandas.pydata.org/docs/reference/api/pandas.read_table.html?utm_medium=email&_hsenc=p2ANqtz-_ZpY3PrnTf96B8_roMQ_8ZiJDULPLa5ugYfEzat8VPz32Jvmb_-T82GgizvfJYTBjTUwI8PK5UNtKlmT8raT0HB3syrg&_hsmi=270881946&utm_content=270881946&utm_source=hs_automation#pandas.read_table)
- [Todas as estilizações de tabelas que ele oferece](https://pandas.pydata.org/pandas-docs/version/1.3/reference/api/pandas.io.formats.style.Styler.html?utm_medium=email&_hsenc=p2ANqtz-86SuXM0KbYZ3RIel0FYYMQbZeNU_yu_-OsEdeet9_XsK_YMdnWIofAiaalgMLBT6IjeaKwBqalTroamzD05gZn82pglg&_hsmi=270881946&utm_content=270881946&utm_source=hs_automation). Principalmente o [exclusivo para HTML.](https://pandas.pydata.org/pandas-docs/version/1.3/reference/api/pandas.io.formats.style.Styler.to_html.html?utm_medium=email&_hsenc=p2ANqtz-9A8ItP16B0K9ShmZOHoXBrKf8fHraf9P-44Kd9TjXpV3qwz5pJCuHkP6jx7pzL3x1-Cx97avMtf8pAPb1kQQMIv4V8zQ&_hsmi=270881946&utm_content=270881946&utm_source=hs_automation)

## EXTRA

Deixo aqui também esse meu texto de [“Como customizar tabelas no Pandas”](https://franciscofoz.medium.com/como-customizar-tabelas-no-pandas-9e6c4593b8d2) e esse [vídeo](https://www.youtube.com/watch?v=8Yi3T_CeA9E) da Kizzy Terra do Programação Dinâmica para você se inspirar.

Ufa, você chegou no final da jornada!

Espero muito que você tenha gostado do projeto, porque eu me diverti muito enquanto o criava. Fique à vontade para me dar um feedback lá no meu Twitter (@FozFrancisco), vou ficar feliz em ouvir sobre os seus sucessos e aprendizados!

Aproveite esse momento para desafiar um amigo ou amiga! Será uma ótima maneira de vocês compararem seus projetos e, quem sabe, criarem o próximo juntos.

Em breve, vou te enviar um formulário para saber o que você achou desses desafios, se tem algum comentário ou alguma sugestão.

Bons estudos daqui pra frente, obrigado pela companhia e bom trabalho.

Francisco Foz
Bibliotecário e Analista de Dados
