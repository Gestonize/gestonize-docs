## Configurações Gerais

### Visão Geral

A tela **Config. Gerais** permite definir parâmetros globais relacionados à experiência de uso do sistema, principalmente em relação à impressão de orçamentos e à integração com o assistente de orçamentos via WhatsApp. Através dessa tela, o administrador pode controlar padrões de exibição e permissões de acesso a funcionalidades automatizadas.

---

### 1. Configurações padrão de impressão do orçamento

Ao acessar essa configuração, o sistema exibe uma lista de parâmetros que podem ser ativados ou desativados para aparecerem na impressão do orçamento. Esses campos são utilizados para personalizar a apresentação do orçamento impresso ao cliente.

**Parâmetros disponíveis:**

| Configuração                  | Definição Padrão | Descrição                                                                 |
|------------------------------|------------------|---------------------------------------------------------------------------|
| Número do orçamento          | Não              | Mostra ou oculta o número único do orçamento gerado.                     |
| Informação do material       | Não              | Exibe detalhes técnicos do material orçado.                              |
| Valor de custo               | Não              | Mostra o valor de custo dos produtos (uso interno).                      |
| Valor de venda               | Sim              | Exibe o valor final de venda ao cliente.                                 |
| Desconto                     | Sim              | Exibe descontos aplicados no orçamento.                                  |
| Assinatura                   | Sim              | Permite mostrar uma imagem de assinatura digital no documento.           |
| Observação                   | Sim              | Exibe campo de observações preenchidas pelo usuário.                      |
| Valor total de venda         | Sim              | Mostra o somatório de todos os valores de venda.                         |
| Valor total de custo         | Não              | Exibe o total de custos do orçamento (uso interno).                      |
| Quantidade de produtos       | Sim              | Exibe quantidade por item do orçamento.                                  |
| Quantidade total de produtos | Sim              | Exibe o total geral de unidades de produtos no orçamento.                |

Essas opções podem ser alteradas individualmente por meio de uma interface de seleção do tipo `Sim` ou `Não`, garantindo personalização e controle na emissão de documentos.

---

### 2. Números permitidos WhatsApp

Este recurso permite cadastrar números de telefone e vinculá-los a usuários previamente cadastrados no sistema. A funcionalidade é usada para integrar com o **bot de geração de orçamentos via WhatsApp**, garantindo que apenas números autorizados possam interagir com o sistema de forma automatizada.

**Campos disponíveis:**

- **Usuário:** Seleção entre usuários cadastrados.
- **Número:** Número de telefone com WhatsApp autorizado a interagir com o bot.

> ⚠️ **Importante:** Apenas números autorizados aqui poderão acessar o assistente de voz via WhatsApp utilizado para geração rápida de orçamentos.

---

### Funcionalidades resumidas

- Definir os campos padrão que devem aparecer na impressão de orçamentos.
- Cadastrar números autorizados a utilizar o robô de geração de orçamentos via WhatsApp.

  ---

⬅️ [Voltar ao Índice](./1.1_Indice.md)
