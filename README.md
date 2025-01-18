# Projeto de Gerenciamento de Assinaturas e Pagamentos
Este é um projeto em Python puro que gerencia assinaturas de serviços e seus respectivos pagamentos. Ele utiliza o SQLModel para lidar com o banco de dados e fornece funcionalidades como criar, listar, pagar e excluir assinaturas.  

Funcionalidades  
- Cadastro de Assinaturas:
  -   Permite criar novas assinaturas com informações como nome da empresa, valor e data de início.
- Gerenciamento de Pagamentos:
  - Realiza o registro de pagamentos associados a cada assinatura.
  - Verifica se já houve um pagamento realizado no mês atual para evitar duplicações, mas permite pagamentos extras mediante confirmação do usuário.
- Exclusão de Assinaturas:
   - Remove uma assinatura do banco de dados e exclui todos os pagamentos relacionados.
- Relatórios e Gráficos:
   - Gera gráficos mostrando os pagamentos realizados nos últimos 12 meses.
   - Calcula o valor total das assinaturas cadastradas.
     
Tecnologias Utilizadas
- Linguagem: Python 3.13.0
- Banco de Dados: SQLModel
- Bibliotecas:
   - sqlmodel - Gerenciamento do banco de dados.
   - matplotlib - Geração de gráficos.
   - datetime - Manipulação de datas.

