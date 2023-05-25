# Automação de Indicadores
 [![NPM](https://img.shields.io/npm/l/react)](https://github.com/KingShinjo/AutomacaoProcessos/blob/main/LICENSE) 
# Sobre o Projeto
- O projeto tem como objetivo automatizar uma tarefa diária realizada pela equipe de análise de dados. Nesse caso, o objetivo é calcular o OnePage de todas as lojas e enviá-lo para o gerente de cada loja, juntamente com todas as informações utilizadas no cálculo dos indicadores e o arquivo completo com os dados da respectiva loja em anexo.
# Objetivo
- O objetivo principal é enviar para cada gerente apenas o OnePage e um arquivo Excel em anexo com as vendas da sua loja. As informações das outras lojas não devem ser enviadas. Além disso, ao final, é necessário enviar um e-mail para a diretoria com dois rankings das lojas em anexo: o ranking diário e o ranking anual. No corpo do e-mail, deve ser destacada qual foi a melhor e a pior loja do dia e do ano. O ranking é baseado no faturamento.

# Passo a Passo Detalhado do Código
- Importação de todas as bibliotecas e bases de dados necessárias para o projeto.
- Mesclagem da tabela de lojas com a tabela de vendas.
- Criação de uma tabela para cada loja e definição do dia do indicador.
- Salvar a planilha na pasta de backup para ter um histórico.
- Realização da análise de faturamento, diversidade de produtos e ticket médio.
- Envio de e-mail para cada gerente com as respectivas informações.
- Criação do ranking e envio de e-mail para a diretoria.

# Bibliotecas Usadas:
- Pandas
- Pathlib
- Win32
# Base de Dados
- Emails.xlsx (Arquivo contendo a lista de Emails que devem ser enviados)
- Lojas.csv (Arquivo com o nome de todas as Filiais)
- Vendas.xlsx (Arquivo contendo as vendas de todas as lojas)
# Estrutura
- Python
# Layout
