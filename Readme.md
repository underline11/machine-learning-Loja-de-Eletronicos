#  Electronics Store Inventory System (SQL)

Este projeto apresenta a modelagem de um banco de dados relacional para controle de estoque e gestão de compras de uma loja de eletrônicos.

##  Arquitetura de Dados
O sistema foi desenhado para suportar o fluxo completo de entrada de mercadorias:
- **Gestão de Fornecedores:** Armazenamento de dados de contato e catálogo.
- **Controle de Estoque:** Monitoramento de preços e quantidades disponíveis.
- **Fluxo de Compras:** Registro de pedidos de compra vinculados a fornecedores específicos.
- **Detalhamento de Itens:** Tabela de junção que permite múltiplos produtos em uma única nota de compra.

##  Tecnologias
- **MySQL / MariaDB**

##  Diferenciais Técnicos
- **Integridade Referencial:** Chaves estrangeiras (FKs) configuradas para garantir que nenhuma compra exista sem um fornecedor válido.
- **Normalização:** Dados estruturados para evitar duplicidade e garantir a consistência das informações.
- **Tipagem Precisa:** Uso de `DECIMAL` para valores financeiros e `DATETIME` para registros temporais automáticos.
