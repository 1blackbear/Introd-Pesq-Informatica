# Energy Efficient Computing through Productivity-Aware Frequency Scaling

L. Ponciano, A. Brito, L. Sampaio and F. Brasileiro, "Energy Efficient Computing through Productivity-Aware Frequency Scaling," 2012 Second International Conference on Cloud and Green Computing, 2012, pp. 191-198. doi: [10.1109/CGC.2012.59](https://doi.org/10.1109/CGC.2012.59)


## 1. Fichamento de Conteúdo

O artigo em questão procura analisar, de maneira comparativa, a eficiência de um algoritmo de escalonamento na manutenção do consumo de energia de tal sistema. Em vista disso, os processadores são um dos principais responsáveis pelo consumo e administração energética de um sistema, a partir do momento em que o consumo se dá pela escala de frequência dinâmica, em inglês "dynamic frequency scaling" (DFS), a qual consiste em mudar a frequência de clock do processador em tempo real. Com isso, o trabalho em questão propõe uma dinâmica voltada para a produtividade da escala de frequência, em inglês "productivity-aware dynamic frequency scaling" (PAFS), que é, também, uma política DFS. Desse modo, através do PAFS, o objetivo do estudo é realizar uma abordagem para generalizar políticas DFS de nível de tarefa, de modo a obter uma economia de energia melhor em relação às políticas DFS amplamente utilizadas hodiernamente na produção de sistemas. Para atingir tal fim, o algoritmo de escalonamento PAFS, implementado integralmente com LAMP (Linux, Apache, MySQL, e PHP), foi executado em um kernel Linux que suporta todas as técnicas padrões de DFS, o qual por meio de um servidor web foi analisada a eficácia de tal. Como resultado, a política PAFS exibe uma consistência com melhores valores de consumo de energia em relação a política Ondemand, obtendo 23,65% de economia de energia sem perdas perceptíveis de produtividade.

## 2. Fichamento Bibliográfico

* _Dynamic frequency scaling_ (escala de frequência dinâmica) é uma tecnologia que permite que o processador conserve energia e reduza o ruído quando estiver sob uma carga leve (páginas 1, 2, 4 e 7).
* _Productivity-aware dynamic frequency scaling_ (dinâmica voltada para a produtividade da escala de frequência) assim como o nome diz, é uma dinâmica de escalonamento para aumentar eficiência do gerenciamento de energia (páginas 1 a 7).
* _Advanced Configuration and Power Interface_ (Configuração Avançada e Interface de Energia) é um padrão para o gerenciamento de energia do computador (página 2).

## 3. Fichamento de Citações
* _"To take advantage of these human abilities, a new computing approach—called human computation—has emerged to let humans perform the tasks for which there's still no satisfactory solution via today's silicon-based computers"_
* _"Volunteer thinking projects are analogous to volunteer computing projects, such as SETI@home"_
* _"Our results suggest that we can broadly divide participants into transient volunteers (those who execute tasks only one day and don't return) and regular volunteers (those who return at least one more day to execute more tasks after executing the first task in the project)."_
* _"Given these intervals, we use the threshold-based methodology [11] to determine the sessions."_
* _"There's a strong correlation between volunteers' frequency and their devoted time to the project"_
* _"There's also a moderate correlation between daily productivity and session duration for regular volunteers"_
* _"In the Milky Way Project, the main change from normal days to busy days is that the proportion of traffic from the UK increases from 16 to 34 percent, and the proportion of users that came to the project through the BBC's website (bbc.co.uk) increases from 3 to 24 percent."_
