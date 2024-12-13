---
description: >-
  A tela de extrato é utilizada para consultar todos os lançamentos que já foram
  realizados para o contribuinte, além da possibilidade de realizar
  englobamento, consultar pagamentos, entre outros.
---

# Extrato do Contribuinte

1. Para isso, acesse o menu Taxas > Movimentação de Tributos > Extrato do Contribuinte.
2. Na tela inicial, em **Opções Pesquisa**, existem filtros e itens para procurar pelo extrato de um contribuinte específico. Informe se deseja:

2.1. **Atualizar** os valores, caso seja encontrado algum sem atualização. Desmarcando o botão, listará apenas o valor referente ao último DAM gerado;

2.2. **Aplicar Desconto** nos cálculos passíveis de desconto, conforme cadastro do **Benefício** do tributo;

2.3. Qual a **Data de Vencimento** será utilizada para atualizar os valores dos lançamentos **Em Aberto e/ou Débitos**;

2.4. Qual a **Situação** do lançamento será exibida. Por padrão exibe somente os débitos, mas poderá escolher entre: pago, cancelado ou todos;

2.5. Caso busque por uma **Origem** específica, escolha entre: Cálculos Gerais, Dívida Ativa, ISSQN, Taxas, Auto de Infração ou ITBI);

2.6. Qual **Parcela** será exibida (todas as parcelas, somente itens parcelados ou somente cota única);

2.7. O intervalo entre a **Data de Lançamento Inicial** e a **Data de Lançamento Final** que deseja pesquisar para filtrar por um período específico. Esses campos não são de preenchimento obrigatório. Por padrão, listará somente os lançamentos **Em Aberto** e **Débito**, caso não altere os filtros.

3. Informe se a busca do extrato será por **Pessoa** ou **Inscrição** e digite no campo de pesquisa a informação do contribuinte que deseja pesquisar. Ao escolher por **Inscrição**, será habitado mais um campo para selecionar qual o **Tipo de Cadastro** que o contribuinte se encontra e depois a **Inscrição Municipal**. Após preencher os campos, clique em **Pesquisar** e os lançamentos relacionados serão mostrados no grid. À frente dos lançamentos temos quatro ícones de possíveis ações:

* No ícone **Lista** é possível visualizar o detalhamento do lançamento. Selecione esse ícone e será aberta uma nova tela permitindo realizar o download e impressão;
* Selecionando o ícone **Impressora** é possível imprimir o Documento Arrecadação Municipal - DAM, porém se o mesmo estiver vencido, exibirá uma mensagem: **"Por gentileza, atualizar o vencimento desta guia com o vencimento igual ou superior a data atual!"** e utilize a opção abaixo para atualizar;
* No ícone **Atualizar** podemos calcular o valor do lançamento que está em débito, sendo adicionado a ele juros, multa e demais valores cadastrados que podem incidir. Clicando nele, será necessário informar uma **Data do novo vencimento** para realizar a atualização. Esta data deverá ser maior ou igual a data atual. Após retornar a mensagem **"Calculado com Sucesso!!!”**, clique em **OK** e no ícone **Impressora** para imprimir o DAM com o valor atualizado;
* Selecionando o ícone **X** é possível realizar o cancelamento do cálculo do DAM sendo direcionado para a tela de **Cálculo Cancelado**. Preencha o **Motivo Cancelamento**, **Número de Processo** e **Observação** pertinente ao cancelamento. Selecione a aba **Guias** e **Confirma Cancelamento**. Lembrando que não é possível cancelar DAM por essa tela, lançamentos relacionados à Dívida Ativa e ISS Mensal gerado pelo sistema de Nota Fiscal Eletrônica. Ambas deverão obedecer a regra e cancelar por sua tela de geração de origem.

4. No botão **Opções** localizado na parte superior da tela é possível realizar algumas ações:

* Na opção **Englobar** é possível realizar o englobamento dos lançamentos, que une os lançamentos para gerar uma única guia de recolhimento. Selecione os registros no grid que deseja e clique nessa opção. Será solicitada a inclusão da data de vencimento e poderá incluir observações se desejar.
  * Para finalizar o englobamento basta clicar em **Englobar** e aparecerá a mensagem te lembrando que somente lançamentos em débito serão englobados. Clique em **OK** e o DAM gerado já vai se encontrar disponível para impressão em **Imprimir Englobamento**.
* Se a pessoa pesquisada no extrato possuir mais de uma inscrição vinculada, o englobamento pode ser realizado por inscrição na opção **Englobar por Inscrição**. Será solicitada a inclusão da data de vencimento e poderá incluir observações se desejar.
  * Para finalizar o englobamento basta clicar em **Englobar** e aparecerá a mensagem te lembrando que somente lançamentos em débito serão englobados. Clique em **OK** e o DAM gerado já vai se encontrar disponível para impressão em **Imprimir Englobamento**.
* Em **Consultar Englobamentos** é possível consultar os lançamentos englobados anteriormente.
* Caso o contribuinte tenha algum lançamento que foi realizado o pagamento via PIX, precisamos alterar sua situação de **Débito** para **Pago** selecionando o lançamento e clicar em **Consulta Pagamento PIX**.
* Na opção **Imprimir Extrato Simplificado** os resultados do grid serão exibidos em um documento com os dados da pessoa, origem do débito, seus valores, vencimentos e situação, de forma resumida, sendo possível sua impressão.
* Em **Imprimir Extrato Detalhado** será emitido o documento discriminado todos os lançamentos, multas, juros, situação, tributos, controle de parcela, quantidade de itens e os lançamentos do extrato em detalhes, sendo possível sua impressão.
* **Imprimir Englobamento** emitirá documento constando todos os englobamentos que foram realizados para esse contribuintes e que abrangem os itens exibidos no grid.
* Selecionando alguns lançamentos do grid, é possível realizar a impressão separadamente de todos os lançamentos para pagamento em **Imprimir DAM Selecionados**. Lembrando que é necessário atualizar o vencimento primeiro.

**Observação:** Para Autos de Infração que não possuem DAM gerado, no grid lista o registro, porém, ao tentar utilizar as opções Detalhe do Lançamento, DAM, Atualizar Parcela e Cancelar DAM, é exibido a mensagem **"Auto de Infração sem parcelamento gerado. Não é possível realizar essa operação”**.

5. Acima do grid de pesquisa temos três ícones:

* No ícone **Atualizar** é possível atualizar os dados do grid quando sofrem alteração após estarem listados;
* No ícone **Exportar** se envia os resultados da pesquisa para uma planilha de excel, sendo possível selecionar linhas específicas para exportação;
* No ícone **Seletor de colunas** escolhe quais as colunas devem aparecer no grid e quais devem ficar ocultas.

6. Todas as colunas do grid de pesquisa servem como filtros adicionais. Por exemplo, para trazer todos os registros que possuem uma determinada **Situação**, basta digitar no campo existente abaixo do nome da coluna que possui uma lupa e serão exibidos somente os resultados com a informação inserida.
7. Os resultados presentes no grid podem ser agrupados de acordo com as respostas de uma determinada coluna arrastando-a até a parte superior esquerda de fora do grid, trazendo uma visualização diferente dos resultados para o usuário.
8. Na parte superior da tela existe o ícone **i** estão disponíveis as informações para auxiliar os usuários como o descritivo dos campos, glossário do sistema e arquivos do Procedimento Operacional Padrão - POP instruindo o uso da tela.
