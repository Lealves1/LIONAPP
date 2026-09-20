# LIONAPP — Controle de Dados para Declaração de Imposto de Renda

## Sobre o projeto

Este projeto foi feito no Excel com o objetivo de organizar e reunir informações que podem ser utilizadas como apoio na declaração de imposto de renda.

A ideia foi montar uma planilha simples de usar, com menus de navegação, validações de dados, fórmulas, tabelas de apoio e algumas funcionalidades extras que fui acrescentando ao longo do desenvolvimento.

Os dados utilizados na planilha são fictícios e servem apenas para demonstrar o funcionamento da ferramenta.

---

## Estrutura do projeto

O arquivo foi dividido em quatro abas principais:

- **TITULAR** — informações do titular e status de preenchimento.
- **INFORMES** — informações dos bancos, investimentos e anexos.
- **NOTAS** — entradas, informações adicionais para o IRPF, bens e direitos e fechamento.
- **TABELAS** — tabelas de apoio utilizadas nas validações e buscas.

---

## O que foi desenvolvido

Além da estrutura proposta durante as aulas, acrescentei algumas funcionalidades para deixar a planilha mais completa e facilitar o preenchimento e a visualização das informações.

### Status do preenchimento

Na primeira aba, **TITULAR**, acrescentei um status de preenchimento para indicar se as informações da tabela estão completas.

Para isso, utilizei funções condicionais e testes lógicos, como a função **SE** e a função **CONT.VALORES**. Também utilizei funções aninhadas, colocando uma função dentro da outra para realizar os testes necessários.

Usei ainda **formatação condicional** para alterar a cor do status de acordo com o preenchimento da tabela. Quando as informações estão completas, o status fica em verde. Quando existem informações pendentes, a cor muda para indicar que ainda falta algum preenchimento.

Também acrescentei uma porcentagem de progresso, mostrando quanto da tabela já foi preenchido.

---

### Informes bancários e investimentos

Na aba **INFORMES**, além dos três bancos utilizados na proposta inicial, acrescentei uma parte destinada a **investimentos**.

No campo de tipo de investimento, utilizei **validação de dados**, deixando algumas opções disponíveis para seleção:

- CDB
- Tesouro Direto
- LCI/LCA
- Fundo de Investimento

Também acrescentei um campo de **anexo** para os investimentos, seguindo a mesma ideia utilizada nos bancos.

Ao lado dos dados dos bancos, coloquei um gráfico mostrando a **distribuição dos saldos bancários**.

Para criar o gráfico, utilizei uma tabela de apoio com os nomes e os valores de cada banco. Assim, o gráfico acompanha automaticamente as alterações feitas nos dados da tabela.

---

### Entradas e informações para o IRPF

Na aba **NOTAS**, fiz uma tabela de entradas com lançamentos referentes a cada mês do ano de **2025**.

Para deixar a simulação mais próxima de uma situação real, utilizei diferentes tipos de entradas, como:

- Holerite
- CNPJ
- Freelancer
- 13º 1ª parcela
- 13º 2ª parcela

Aqui utilizei uma lista de validação, deixando essas opções prontas para facilitar o lançamento das entradas.

Ao lado da tabela de entradas, acrescentei uma tabela com **informações adicionais para apoio ao IRPF**, contendo valores relacionados a despesas médicas, plano de saúde, educação, INSS, previdência privada, entre outras informações.

A ideia foi deixar a simulação mais próxima de uma situação que poderia acontecer durante a organização dos dados para a declaração.

---

### Bens e Direitos

Acrescentei também uma tabela de **Bens e Direitos**, com alguns bens e valores para complementar a simulação.

Na parte de contas bancárias, utilizei fórmulas para buscar automaticamente os valores informados na tabela de bancos.

Com isso, quando o valor é alterado na tabela de origem, ele também é atualizado na tabela de Bens e Direitos, sem precisar alterar a mesma informação manualmente em mais de um lugar.

---

### Fechamento

No final da aba, criei uma tabela de **Fechamento 2025**, contendo:

- Total de entradas
- Total de bens e direitos
- Dívidas e ônus

Para calcular o total de entradas, utilizei a função **SOMA**, fazendo o cálculo diretamente a partir da tabela de entradas.

Os demais valores também estão vinculados às informações preenchidas nas outras partes da planilha, deixando o fechamento mais automático.

---

## Validações e navegação

Durante o desenvolvimento do projeto, utilizei **validação de dados** para facilitar o preenchimento e evitar informações fora das opções disponíveis.

Na parte dos bancos, utilizei como base uma tabela fornecida pelo professor, contendo diversos bancos para serem utilizados nas validações.

Também configurei **mensagens de entrada e alertas de erro** nas validações de dados, ajudando a orientar o preenchimento da planilha.

Para facilitar a navegação, utilizei **hiperlinks** no menu e acrescentei botões ao final das tabelas de cada aba. Assim, é possível navegar entre as partes da ferramenta de forma mais rápida.

---

## Recursos utilizados

Durante o desenvolvimento, foram utilizados recursos do Excel, como:

- Fórmulas e referências entre células
- Função SE
- Função CONT.VALORES
- Função SOMA
- Funções aninhadas
- Testes lógicos
- Formatação condicional
- Validação de dados
- Mensagens de entrada
- Alertas de erro
- Tabelas de apoio
- Busca de informações entre tabelas
- Gráficos
- Hiperlinks
- Botões de navegação
- Tabelas estruturadas
- Referências estruturadas
  
---

## Objetivo final

O objetivo do projeto foi criar uma ferramenta simples e organizada para reunir informações que podem ser utilizadas como apoio na organização dos dados para a declaração de imposto de renda.

Além dos conteúdos trabalhados durante as aulas, acrescentei algumas funcionalidades que achei que poderiam facilitar o preenchimento e a visualização das informações.


## Sobre o desenvolvimento

Este projeto foi realizado como parte das atividades de estudo da DIO, acompanhando a construção da planilha durante as aulas. A partir da estrutura trabalhada no curso, acrescentei algumas funcionalidades e melhorias ao projeto, buscando deixar a ferramenta mais completa e facilitar seu uso.

*Desenvolvido por Letícia Alves.*
