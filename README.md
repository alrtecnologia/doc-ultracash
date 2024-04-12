
# Releases

Esta página contém informações sobre as diferentes versões lançadas do Projeto UltraCash, incluindo notas de lançamento, alterações e links para downloads.

# Versão Atual: UltraCash 1.9.8 r26

- **Data de Lançamento:** 12 de abril de 2024
- **Notas de Lançamento:**

1. **[Atalho "ALT + A" corrigido](#tarefa-atalho-alt--a)**
2. **[Tela de Cadastro de Produto - Campo NCM ajustado](#tarefa-tela-de-cadastro-de-produto---campo-ncm)**
3. **[Relatório de Contas a Pagar exibindo observações corretamente](#tarefa-relatório-de-contas-a-pagar)**
4. **[Tela de CT-e ajustada para se adaptar ao tamanho do monitor](#tarefa-tela-de-ct-e)**
5. **[Gerenciador de Backup agora permite abrir mais de um por computador](#tarefa-gerenciador-de-backup)**
6. **[Botão de Salvar na Tela de Cadastro de Produto realocado](#tarefa-botão-de-salvar-na-tela-de-cadastro-de-produto)**
7. **[Melhoria na Tela de Cadastro de Fornecedor](#tarefa-melhoria-na-tela-de-cadastro-de-fornecedor)**
8. **[Correção na Geração de Crédito SPED Contribuições para Energia](#tarefa-geração-de-crédito-sped-cont-sisal-gomes)**
9. **[Correção na Devolução de Cliente gerando saldo de vale compras em todas as filiais](#tarefa-devolução-de-cliente)**
10. **[Correção na Impressão de Devolução com valores divergentes](#tarefa-impressão-de-devolução)**



# Versão Anterior

### UltraCash 1.9.8 r25

- **Data de Lançamento:** 5 de abril de 2024
- **Notas de Lançamento:**
 


## Tarefas Concluídas

#### Tarefa: Atalho "ALT + A"

- **Data de Registro:** 15/03/2024
- **Tipo de Tarefa:** Erro
- **Prioridade:** Alta
- **Descrição:** O atalho "ALT + A", que deveria permitir a alteração do cliente na tela de venda, não estava funcionando corretamente. O erro foi corrigido e o atalho agora está operando conforme o esperado.
- **Status:** Concluída
  
| Tabela de Informações |
|-----------------------|
| **Caminho:** Na tela de venda, clicar em "ALT + A" |
| **Tipo de Tarefa:** Erro |
| **Localização:** ALT Tecnologia - Cansanção |
| **Base:** Ultracash |
| **Responsável:** Andreina Oliveira |
| **Observação:** Testar |

---

#### Tarefa: Tela de Cadastro de Produto - Campo NCM

- **Data de Registro:** 15/03/2024
- **Tipo de Tarefa:** Erro
- **Prioridade:** Alta
- **Descrição:** O campo NCM na tela de cadastro de produto estava muito pequeno, impedindo a visualização do número do NCM. O problema foi corrigido, e o campo agora tem o tamanho adequado para exibir o NCM corretamente.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Cadastro de Produto - Campo NCM |
| **Tipo de Tarefa:** Erro |
| **Localização:** ALR Tecnologia - Cansanção |
| **Base:** Ultracash |
| **Responsável:** Andreina Oliveira |

---

#### Tarefa: Relatório de Contas a Pagar

- **Data de Registro:** 19/02/2024
- **Prioridade:** Média
- **Descrição:** O Relatório de Contas a Pagar não estava exibindo as observações inseridas. O problema foi corrigido e agora as observações são exibidas corretamente no relatório.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Relatório > Financeiro > Contas a Pagar > Pagamentos |
| **Tipo de Tarefa:** Funcionalidade |
| **Localização:** Posto Lider - Cansanção |
| **Base:** Ultracash |
| **Responsável:** Rafael Dantas |


---

#### Tarefa: CT-e

- **Data de Registro:** 21/02/2024
- **Tipo de Tarefa:** Melhoria
- **Prioridade:** Alta
- **Descrição:** A tela de CT-e não estava se ajustando ao tamanho do monitor e não gravava o último ajuste. Isso resultava em botões ocultos e sobreposição de funções em alguns espaços. O problema foi corrigido e agora a tela se ajusta corretamente ao tamanho do monitor, e o último ajuste é gravado.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Saídas - Documentos eletrônicos - CT-e |
| **Tipo de Tarefa:** Melhoria |
| **Localização:** ALR Tecnologia |
| **Base:** Ultracash |
| **Responsável:** Andreina Oliveira |

---

### Tarefa: Gerenciador de Backup

- **Data de Registro:** 19/02/2024
- **Prioridade:** Urgente
- **Descrição:** O Gerenciador de Backup não permitia abrir mais de um por computador. Alguns clientes tinham mais de uma pasta do sistema, exigindo a abertura de dois backups. Tentou-se renomear o executável, conforme sugerido por André, porém sem sucesso.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Tipo de Tarefa:** Funcionalidade |
| **Localização:** Comercial 4 Rodas - Cansanção - 1.9.8r9 |
| **Base:** Ultracash |
| **Responsável:** Rafael Dantas |


---

### Tarefa: Botão de Salvar na Tela de Cadastro de Produto

- **Data de Registro:** 15/03/2024
- **Tipo de Tarefa:** Erro
- **Prioridade:** Alta
- **Descrição:** O botão de salvar na tela de cadastro de produto estava sobreposto pelo botão de carregar imagem.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Cadastro de Produto - Salvar cadastro |
| **Tipo de Tarefa:** Erro |
| **Localização:** ALR Tecnologia - Cansanção |
| **Base:** Ultracash |
| **Responsável:** Andreina Oliveira |


---

### Tarefa: Tela de Cadastro de Fornecedor

- **Data de Registro:** 15/03/2024
- **Tipo de Tarefa:** Melhoria
- **Prioridade:** Média
- **Descrição:** Na tela de cadastro de fornecedor, ao marcar a opção de exclusivo por código e tentar digitar uma letra, o sistema exibia um erro em inglês. Deveria ser exibido um aviso para o usuário, informando que a ação não pode ser realizada porque foi selecionada a opção de pesquisa por código. A mensagem em inglês pode não ser compreendida pelo usuário.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Cadastro de Fornecedor - Selecionar a opção "Exclusivo por Código" |
| **Tipo de Tarefa:** Melhoria |
| **Localização:** ALR Tecnologia - Cansanção |
| **Base:** Ultracash |
| **Responsável:** Andreina Oliveira |


---

### Tarefa: Geração de Crédito SPED Cont Sisal Gomes

- **Data de Registro:** 18/03/2024
- **Tipo de Tarefa:** Erro
- **Prioridade:** Urgente
- **Descrição:** A entrada fiscal de "Energia" no SPED Contribuições da Sisal Gomes não estava gerando crédito conforme esperado. Após investigação, foi identificado que a geração de crédito para PIS e COFINS não estava sendo realizada corretamente para essa categoria de entrada. A solução foi implementar a geração de crédito adequada para PIS e COFINS, conforme informado pela contabilidade da empresa.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Entrada fiscal de "Energia" no SPED Contribuições da Sisal Gomes |
| **Tipo de Tarefa:** Erro |
| **Localização:** 9TEC |
| **Base:** Ultracash |
| **Responsável:** Eric |
| **Observação:** Testar nas duas bases |

---

### Tarefa: Devolução de Cliente

- **Data de Registro:** 25/03/2024
- **Tipo de Tarefa:** Erro
- **Prioridade:** Urgente
- **Descrição:** Ao realizar uma devolução de cliente, o sistema estava gerando um saldo de vale compras para o cliente em todas as filiais, quando deveria gerar somente na filial onde foi feita a devolução.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Saídas, outros procedimentos, devolução de cliente. Realizar uma devolução para algum cliente e, em seguida, acessar o cadastro do cliente. Clicar com o botão direito do mouse em "Vale Compras" e selecionar "Consulta Saldo do Cliente". |
| **Tipo de Tarefa:** Erro |
| **Localização:** Elias Contorno Material de Construção - Coité |
| **Base:** Ultracash |
| **Responsável:** Gabriel Matos da Silva |
| **Observação:** Testar nas duas bases |


---

### Tarefa: Impressão de Devolução

- **Data de Registro:** 25/03/2024
- **Tipo de Tarefa:** Erro
- **Prioridade:** Alta
- **Descrição:** Na nota de devolução, ao realizar uma devolução com despesas, na primeira vez que é gerada a nota, o sistema imprimia a nota com valores diferentes entre a base de ICMS e o valor do produto, comparados com o valor na capa da nota. Ao fazer a impressão novamente, o sistema corrigia os valores.
- **Status:** Concluída

| Tabela de Informações |
|-----------------------|
| **Caminho:** Devolução de fornecedor |
| **Tipo de Tarefa:** Erro |
| **Localização:** Neres Material de Construção - Cansanção |
| **Base:** Ultracash |
| **Responsável:** Andreina Oliveira |


# Licença

Este projeto é licenciado sob a [Licença MIT](https://github.com/seu-usuario/projeto-xyz/blob/main/LICENSE).

Posso ajudar com mais alguma coisa?
