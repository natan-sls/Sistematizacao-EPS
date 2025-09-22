Projeto

Sistema de Controle Financeiro Avançado – protótipo web para cadastro, acompanhamento e projeção de receitas e despesas.

Tecnologias Utilizadas

HTML5 – estrutura da página.

CSS3 – estilização e layout responsivo.

JavaScript – lógica do sistema, manipulação do DOM, cálculos e gráficos.

Chart.js – geração de gráficos financeiros interativos.



-Funcionalidades:

Cadastro de transações (receitas e despesas).

Diferenciação entre transações únicas e mensais.

Parcelamento automático de valores.

Visualização do saldo atualizado.

Tabela detalhada de transações.

Gráficos de receitas e despesas (mês anterior, atual e projeção do próximo).

Personalização com nome do usuário ou empresa.



-Como Rodar o Protótipo:

Baixe ou clone o projeto.

Abra o arquivo index.html em qualquer navegador moderno (Chrome, Firefox, Edge).

Insira seu nome ou empresa, cadastre transações e acompanhe saldo e gráficos.



-Observações Técnicas

Todos os dados são armazenados temporariamente em memória do navegador.

Para armazenamento persistente, seria necessário implementar LocalStorage ou integração com banco de dados.

Gráficos gerados com Chart.js podem ser atualizados dinamicamente conforme novas transações.


MANUAL DE USUÁRIO

Início

Abra o arquivo index.html no navegador.

Insira o nome do usuário ou da empresa no campo correspondente.



Cadastro de Transações

Valor: insira o valor da receita ou despesa.

Tipo: selecione se é “Receita” ou “Despesa”.

Categoria: informe a categoria da transação (ex: Alimentação, Salário).

Subtipo: escolha entre “Única” ou “Mensal”.

Parcelas: se a transação for parcelada, insira o número de parcelas.

Clique em Adicionar.



Visualização

Saldo Atual: exibe o saldo considerando todas as receitas e despesas.

Tabela de Transações: lista todas as transações cadastradas, mostrando valor, tipo, categoria, subtipo e parcelas.

Gráfico de Receitas x Despesas: compara mês anterior, mês atual e projeção do próximo mês.



Dicas de Uso

Para transações mensais, o sistema adiciona automaticamente o valor ao próximo mês na projeção do gráfico.

Utilize categorias consistentes para melhor acompanhamento das despesas e receitas.

Atualize ou limpe a tabela manualmente recarregando a página.
