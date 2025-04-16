# Estoque Manager - Projeto Pessoal

Este projeto foi desenvolvido como parte da matéria de Qualidade e Teste de Software. O objetivo é criar um sistema simples de gerenciamento de estoque usando **JavaScript**.

## Descrição do Sistema

O **EstoqueManager** é um sistema de controle de estoque que permite aos usuários realizar as seguintes operações:

- Adicionar produtos ao estoque
- Remover produtos do estoque
- Atualizar a quantidade de produtos no estoque
- Calcular o valor total do estoque
- Listar todos os produtos no estoque
- Buscar produtos por nome
- Limpar o estoque

A proposta do projeto é proporcionar uma solução simples e prática para pequenas empresas ou lojas que necessitam de um sistema de gestão de inventário eficiente.

## Funcionalidades

- **Adicionar Produto:** Adiciona um novo produto ao estoque ou aumenta a quantidade de um produto existente.
- **Remover Produto:** Remove um produto do estoque.
- **Atualizar Quantidade:** Atualiza a quantidade de um produto já existente no estoque.
- **Calcular Valor Total do Estoque:** Calcula o valor total do estoque com base na quantidade e preço de cada produto.
- **Buscar Produto:** Busca um produto específico pelo nome.
- **Listar Produtos:** Retorna todos os produtos presentes no estoque.
- **Limpar Estoque:** Limpa todo o estoque removendo todos os produtos.
- **Quantidade de Produtos:** Retorna o número total de produtos cadastrados no estoque.

## Testes

O projeto inclui **testes automatizados** que garantem o bom funcionamento de todas as operações do sistema. Os testes são realizados no arquivo `estoqueManager.test.js` e cobrem as seguintes áreas:

1. Adição de produtos ao estoque
2. Validação de entrada de dados inválidos
3. Atualização da quantidade de produtos
4. Busca e remoção de produtos
5. Cálculo do valor total do estoque
6. Limpeza do estoque
7. Verificação da quantidade de produtos no estoque
