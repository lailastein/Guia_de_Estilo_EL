# Arquitetura da Informação

Antes de iniciar a escrita do documento, tenha certeza que entendeu bem o funcionamento da funcionalidade e todos os seus compenentes. Isso evitará que interrompa a documentação no meio, além de poupas tempo do setor de teste ou de programação.&#x20;

Para ter mais informações sobre a funcionalidade, pesquise no sistema de protocolo pelo processo que a originou. No processo existem anotações dos programadores e de quem testou a funcionalidade, auxiliando no entendimento da sua função.

### Títulos

Todo POP deve começar descrevendo qual o nome do sistema, depois o nome da funcinalidade que será descrita.&#x20;

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

### Introdução

O primeiro parágrafo do POP deve ser utilizada para introduzir o nome da funcionalidade e qual é o seu objetivo dentro do sistema, situando o usuário quais os requisitos são necessários para utiliza-lá.&#x20;

### Localização da funcionalidade

Após a introdução da funcionalidade a próxima informação a ser fornecida deve ser onde ela será encontrada. A partir de agora as ações serão listadas como um passo-a-passo, sendo listadas primeiro as ações obrigatórias para realizar as demais, e elas devem ser numeradas em ordem.

> 1. Acesse a tela no menu Fiscalização > Fiscalização > Solicitação de Ação Fiscal.
> 2. Na tela aberta é possível cadastrar uma nova solicitação selecionando o ícone “+Novo”. Inicie o cadastro da solicitação informando obrigatoriamente qual a “Data a Solicitação” está sendo realizada, em “Tipo Fiscalização” selecione que tipo de emissor será fiscalizado, qual a “Data de Previsão de início” da fiscalização e qual a “Data da Previsão Final” da fiscalização.

* Iniciar sempre com um verbo no imperativo.

> Exemplo: cadastre, descreva, insira, copie, detalhe, numere, etc.

* Ao descrever um caminho do sistema, utilize os sinais e maior e menor (><) e o texto negrito. Não é necessário a inserção de aspas duplas ("").

> Exemplo: Acesse a tela no menu **Dívida Ativa > Dívida Ativa > Carteira - Dívida Ativa**.

### Descritivo dos campos

Ao descrever os campos presentes na tela, informe a ação que deve ser realizada campo por campo, sinalizando sempre quais são de preenchimento obrigatório e quais não são. Todos os campos que forem descritos devem ser escritos entre aspas duplas ("") e estar em negrito.

> Exemplo: Inicie o cadastro da solicitação informando obrigatoriamente qual a **“Data a Solicitação”** está sendo realizada, em **“Tipo Fiscalização”** selecione que tipo de emissor será fiscalizado, qual a “Data de Previsão de início” da fiscalização e qual a **“Data da Previsão Final”** da fiscalização.

Lembre de não descrever somente o óbvio (No campo **"CPF"** insira o CPF do solicitante), mas informe, nos casos mais necessários e complicados, a importância do preenchimento daquele campo para o andamento das atividades.

> Exemplo: No campo **"Código do Patrimônio"**, insira o código do patrimônio conforme plaqueta. A inserção equivocada ou ausência desse código comprometerá o controle de patrimônio.

Devem ser evitadas expressões como gírias, tanto faz, pode-se ou não, preencha apenas com 0000, etc. Esse tipo de expressão não é clara e pode ocasionar uma dificuldade na interpretação pelo usuário.

Quando um passo estiver na mesma categoria do anterior, numere-o seguindo o número anterior e aumente o recuo do texto. Exemplo: um item como 1. e o próximo como 1.1.

> 1. A tela aberta possui duas abas:
>
> &#x20;       1.1. Na aba “Gerar”, é necessário preencher os filtros para gerar uma carteira. Preencha obrigatoriamente o intervalo entre o “Ano Inicial” e o “Ano Final” que deseja que sejam buscados os débitos dos contribuintes, também o intervalo de “Valor Mínimo” e “Valor Máximo” e informe no campo “Descrição” qual será o nome da carteira que está sendo criada.

Quando for descrever ações informadas dentro de um ícone (como Opções), utilize os marcadores circulares pequenos (bolinhas pretas).

> Acima do grid de pesquisa temos três ícones:
>
> ● No ícone “Atualizar” é possível atualizar os dados do grid quando sofrem alteração após estarem listados;
>
> ● No ícone “Exportar” se envia os resultados da pesquisa para uma planilha de excel, sendo possível selecionar linhas específicas para exportação;
>
> ● No ícone “Seletor de colunas” escolhe quais as colunas devem aparecer no grid e quais devem ficar ocultas.

Depois de dois pontos (:) sempre começar com letra minúscula, a não ser que inicie com um nome de alguma tela ou função.

> No ícone **“Opções”** temos algumas outras ações que podem ser executadas:
>
> ● Lançar Dados Cálculo em Batch: Quando somente essa opção é selecionada são lançados os cálculos simulados, não tendo ainda lançamento de parcela ou DAM;
>
> ● Lançar Imposto (DAM) em Batch: Quando essa opção é selecionada após ter sido feita a simulação do cálculo (Lançar Dados Cálculo em Batch), o sistema irá realizar o lançamento dos parcelas do cálculo e o DAM para pagamento;
>
> ● Lançar Novas Parcelas do novo Vencimento em Batch: Muda as datas de vencimento das parcelas não pagas em lançamentos que não foram pagos;
>
> ● Lançar Novas Parcelas do novo Vencimento em Batch para Pagamento em Andamento em Batch: Gera os cálculos e muda as datas de vencimento das parcelas não pagas, mesmo com pagamento em andamento;

Todo nome de campo, aba, tela, menu, opção, botão e mensagem, devem estar em negrito e entre aspas.

> * No campo **“Opção”** altere para CIDADES WEB (IN 43/2017 – Almoxarifado e Patrimônio);
> * No campo **“Opção”** altere para CIDADES WEB (IN 43/2017 – Almoxarifado e Patrimônio);
> * Exemplo de menu (não precisa estar entre aspas): (…) cadastre a faixa/nota no menu: **Acadêmico > Escola > Faixa/nota**, clicando em **“Novo”**;
> * Exemplo de mensagem: Será mostrada a mensagem **“Deseja realmente iniciar a geração/integração do(s) arquivos(s)?”**, clique no botão **Sim**.
