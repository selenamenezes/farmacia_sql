# Sistema de Gerenciamento de Produtos em Python

## Descrição
Este projeto é uma simulação de um sistema de gerenciamento de produtos, desenvolvido em Python. Utiliza o SQLite para o armazenamento dos dados. O sistema oferece diversas funcionalidades para manter o controle dos produtos em estoque, incluindo formatação do código de barras e operações de CRUD (Criar, Ler, Atualizar e Deletar) para os produtos.

## Funcionalidades Principais
- **Formatar Código de Barras:** Remove espaços e hífens do código de barras para padronizar o formato.
- **Adicionar Produto:** Insere um novo produto na tabela após validar o código de barras, quantidade e preço.
- **Listar Produtos:** Exibe todos os produtos cadastrados com detalhes.
- **Atualizar Produto:** Atualiza as informações de um produto existente.
- **Remover Produto:** Remove um produto da tabela baseado no código de barras.

## Tecnologias Utilizadas
- **Python:** Linguagem de programação utilizada para implementar a lógica do sistema.
- **SQLite:** Banco de dados relacional utilizado para armazenar informações dos produtos.
