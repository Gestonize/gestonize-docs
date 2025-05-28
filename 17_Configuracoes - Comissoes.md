# Tutorial: Como configurar Comissões

## Visão Geral

A tela **Configuração de Comissão** permite cadastrar e gerenciar os tipos de comissão utilizados na empresa. Esses valores são vinculados aos usuários do tipo **comissionado** e utilizados para cálculos automáticos de remuneração por vendas ou serviços realizados.

## Funcionalidades

- Visualização de todos os tipos de comissão cadastrados.
- Cadastro de novas formas de recebimento e seus respectivos valores.
- Edição de comissões existentes clicando diretamente sobre o item na lista.

## Acesso ao Módulo

1. No menu lateral, clique em **Configurações > Config. Comissão**.
2. A tela apresenta a lista com as comissões cadastradas.

## Cadastro de Comissão

Clique no botão **Cadastrar comissão** para abrir o formulário de novo registro.

### Campos obrigatórios

- **Forma de recebimento**: Nome que define o tipo de comissão (Ex: Percentual, Fixo, Por Meta, etc.).
- **Comissão**: Valor numérico a ser aplicado. Pode ser percentual (Ex: 5%) ou valor fixo (Ex: R$ 100,00), conforme a regra da empresa.

Após preencher os campos, clique no botão **Adicionar comissão**.

## Aplicação Prática

A comissão cadastrada será vinculada a um colaborador do tipo **Comissionado** no momento do seu cadastro (tela **Cadastros > Pessoas**). Isso define como o sistema calculará sua comissão ao gerar vendas e orçamentos.

### Exemplos:

| Forma de Recebimento | Comissão |
|----------------------|----------|
| Percentual           | 5%       |
| Valor Fixo           | R$ 100,00|
| Por Meta             | R$ 500,00 após R$ 10.000,00 em vendas |

> ℹ️ Recomenda-se utilizar nomes claros e objetivos nas formas de recebimento para fácil compreensão pelos gestores e administradores.

## Observações

- Caso um colaborador **não receba comissão**, pode-se criar uma forma com valor `0` e nomeá-la como "Não comissionado".
- A comissão impacta diretamente nos relatórios de desempenho e pagamentos, garantindo uma gestão de equipe mais transparente.

