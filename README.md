As funções usadas nesse codigo js tem as seguintes funcionalidades:

document.addEventListener("DOMContentLoaded", function(){...});: Esta função é um event listener que é acionado quando o DOM da página é completamente carregado. Dentro dela, são definidas as operações que ocorrerão quando o DOM estiver pronto;

comparar.addEventListener('click', function(){...});, intervalo.addEventListener('click', function(){...});, atual.addEventListener('click', function(){...});: Essas funções adicionam event listeners para os elementos com os IDs 'comparar', 'intervalo' e 'atual', respectivamente. Eles estão à espera do evento de clique nesses elementos para realizar as operações associadas;

compararData(data1, data2): Esta função compara duas datas (data1 e data2) e retorna a data maior entre elas;

intervaloData(data1, data2): Esta função calcula o intervalo em segundos entre duas datas (data1 e data2). Ela também verifica se a primeira data é mais antiga que a segunda;

validar(data1, data2): Esta função verifica se as datas passadas como argumento são válidas. Se uma ou ambas forem inválidas (não são instâncias de Date), retorna verdadeiro;

converterData(dataAtual): Esta função recebe uma data e retorna uma string formatada no formato "hh:mm - dd/mm/aaaa", onde "hh" é a hora, "mm" é o minuto, "dd" é o dia, "mm" é o mês e "aaaa" é o ano.

O código basicamente configura três operações de clique em botões ('comparar', 'intervalo' e 'atual') que realizam operações relacionadas a datas (comparação de datas, cálculo de intervalo de tempo e obtenção da data atual) e exibem os resultados em um alerta.
