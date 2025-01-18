# api-invest

api-fanfareInvest esta API consulta investimentos. 💵​📈​

    Deverá ter endpoints abaixo:
        Listar investimentos todos
        Obter investimentos renda fixa
        Obter investimento renda variável
        Obter investimento fundos
        Investir renda fixa = POST
        Investir renda fundos imobiliário = POST

    Aplicação deverá ter o código em inglês

    Deverá conter os testes de unidade para as regras

        Usuário não pode resgatar o investimento em menos de 1 mês (TODOS)

        Usuário não pode investir em algum título que não esteja adequado ao seu perfil

        Calculo do resgate
            Se a data vencimento do titulo for maior que 6 meses, então desconta 20% do rendimento de IR
            Se a data vencimento do titulo for maior que 12 meses, então desconta 10% do rendimento de IR
            Se a data vencimento do titulo for igual ao vencimento, então desconta 5% do rendimento de IR

        O usuário não deverá investir menos que o valor mínimo de cada título

    Essa aplicação deverá ser publicada em um container Docker e criado o Dockerfile e disponibilizada no Github
