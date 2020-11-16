API Mercado livre
Como funciona:Sistema faz uma requisição na api do mercado livre.
Caso estado da requisição seja feito por completo e o status está ok.
Salva os dados em JSON e transforma em html e faz uma verificação de moeda de acordo com o id que foi passado, caso seja positiva deve imprimir uma mensagem de moeda correta! caso for negativa, moeda inválida!
Caso estado da requisição seja feito por completo e o status for 404, apresentará mensagem de erro.

Cenário Validação de moeda

Caso de teste: CT 01 01 Verificar moeda
- Pré-condições: Acesso Api do mercado livre
- Detalhamento da função: 
Usuário faz uma requisição via api do mercado livre, caso estado da requisição seja feito por completo e o status está ok, o arquivo JSON, transforma em html e faz uma verificação de moeda de acordo com o id que foi passado, caso seja positiva deve imprimir uma mensagem de "moeda correta!".
- Massa de dados: Acesssar api do mercado livre e selecionar qual id da moeda que você deseja verificar.
- Ciclo (Iteração): 1ª iteração
- Resultados: Moeda consultada com sucesso!

Caso de teste: CT 01 02 Erro ao chamar API.
- Pré-condições: Acesso Api do mercado livre
- Detalhamento da função: 
Usuário faz uma requisição via api do mercado livre, caso estado da requisição seja feito por completo e o status está 404 deve imprimir uma mensagem - Error 404.
- Massa de dados: Acesssar api do mercado livre e irá retornar erro 404.
- Ciclo (Iteração): 1ª iteração
- Resultados: Mensagem de erro 404.
