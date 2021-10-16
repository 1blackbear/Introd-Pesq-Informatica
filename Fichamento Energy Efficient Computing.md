# Energy Efficient Computing through Productivity-Aware Frequency Scaling

L. Ponciano, A. Brito, L. Sampaio and F. Brasileiro, "Energy Efficient Computing through Productivity-Aware Frequency Scaling," 2012 Second International Conference on Cloud and Green Computing, 2012, pp. 191-198. doi: [10.1109/CGC.2012.59](https://doi.org/10.1109/CGC.2012.59)


## 1. Fichamento de Conteúdo

O artigo em questão procura analisar, de maneira comparativa, a eficiência de um algoritmo de escalonamento na manutenção do consumo de energia de tal sistema. Em vista disso, os processadores são um dos principais responsáveis pelo consumo e administração energética de um sistema, a partir do momento em que o consumo se dá pela escala de frequência dinâmica, em inglês "dynamic frequency scaling" (DFS), a qual consiste em mudar a frequência de clock do processador em tempo real. Com isso, o trabalho em questão propõe uma dinâmica voltada para a produtividade da escala de frequência, em inglês "productivity-aware dynamic frequency scaling" (PAFS), que é, também, uma política DFS. Desse modo, através do PAFS, o objetivo do estudo é realizar uma abordagem para generalizar políticas DFS de nível de tarefa, de modo a obter uma economia de energia melhor em relação às políticas DFS amplamente utilizadas hodiernamente na produção de sistemas. Para atingir tal fim, o algoritmo de escalonamento PAFS, implementado integralmente com LAMP (Linux, Apache, MySQL, e PHP), foi executado em um kernel Linux que suporta todas as técnicas padrões de DFS, o qual por meio de um servidor web foi analisada a eficácia de tal. Como resultado, a política PAFS exibe uma consistência com melhores valores de consumo de energia em relação a política Ondemand, obtendo 23,65% de economia de energia sem perdas perceptíveis de produtividade.

## 2. Fichamento Bibliográfico

* _Dynamic frequency scaling_ (escala de frequência dinâmica) é uma tecnologia que permite que o processador conserve energia e reduza o ruído quando estiver sob uma carga leve (páginas 1, 2, 4 e 7).
* _Productivity-aware dynamic frequency scaling_ (dinâmica voltada para a produtividade da escala de frequência) assim como o nome diz, é uma dinâmica de escalonamento para aumentar eficiência do gerenciamento de energia (páginas 1 a 7).
* _Advanced Configuration and Power Interface_ (Configuração Avançada e Interface de Energia) é um padrão para o gerenciamento de energia do computador (página 2).

## 3. Fichamento de Citações
* _"In this work we propose productivity-aware dynamic frequency scaling (PAFS), which is a DFS policy decoupled from both the application and the operating system."_
* _"We compare PAFS with other policies that focus on power saving, maximum system performance, and load-dependent performance"_
* _"the main contribution of PAFS is to empower users to dynamically control power consumption based on application’s productivity needs"_
* _"When in operation, PAFS will periodically (with periodicity ΔT) decrease the processors clock frequency (and, consequently, power consumption) in steps (ΔF) until a performance fault happens (e.g., the servicing of a request exceeds the contracted response time)."_
* _"Our results show that PAFS policy exhibits a consistently better energy consumption values in comparison to the Ondemand system-level policy, reaching up to 23.65% energy savings with no noticeable losses on the productivity metric."_


