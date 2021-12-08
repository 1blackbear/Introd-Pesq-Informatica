# HySec-Flow: Privacy-Preserving Genomic Computing with SGX-based Big-Data Analytics Framework

WIDANAGE, Chathura et al. HySec-Flow: Privacy-Preserving Genomic Computing with SGX-based Big-Data Analytics Framework. In: 2021 IEEE 14th International Conference on Cloud Computing (CLOUD). IEEE, 2021. p. 733-743.

## 1. Fichamento de Conteúdo

O artigo permeia os diversos ambientes de execução seguros usados atualmente para prover segurança e proteção de dados sensíveis, como o SGX (Software Guard Extension), provido pela Intel. Para tal, foi utilizado como exemplo dados pessoais genômicos humanos, o qual têm-se informações únicas sobre indíviduos humanos, por consequência, informações sensíveis que não podem ser vazadas. Contudo, de modo infeliz, o problema abordado no artigo é que, apesar de eficiênte em relação à segurança, o SGX apresenta óbices de desempenho de modo frequente, sobretudo a partir da memória de enclave. À vista disso, é proposto uma novo estrutura Hybrid Secured Flow (HySec-Flow) para verificação de grandes escalas de dados com o uso de plataformas SGX. Para isso, foi projetado um agendador de tarefas híbridos de modo a integrar contêineres seguros e não seguros em HySec-Flow para realizar as subtarefas em enclaves, com o objetivo resolver problemas de dimensionamento do SGX. Além disso, usufruindo do modelo de um genoma humano, foi realizado um mapeamento das leituras de milhões de sequências de DNA curtas. Como resultado, obtêm-se que o HySec-Flow possibilita a execução de vários nós ao mesmo tempo, de forma segura. Para além, é observado um aumento de velocidade de até 212 vezes quando comparado ao Scone.

## 2. Fichamento Bibliográfico

* _Enclave_ (enclave) é uma região de memória protegida que fornece confidencialidade para a execução de dados e de código (página 1).
* _Bloom filter_ (filtro bloom) é uma estrutura de dados probabilísticos com eficiência de espaço.
* _Intel SGX_ é um conjunto de extensões de instrução x86 que oferece criptografia de memória baseada em hardware e isolamento para código de aplicativo e dados. 


## 3. Fichamento de Citações

* _"A promising alternative has recently been presented by a new generation of hardware supporting a trusted execution environment (TEE), in which sensitive data are kept on secure storage and processed in an isolated environment, called the enclave."_
* _"More specifically, the memory of an enclave is mapped to a special physical memory area called Enclave Page Cache (EPC). It is encrypted by Memory Encryption Engine (MEE) and cannot be directly accessed by other system software."_
* _"Reads mapping serves as a prerequisite step for many downstream analyses in human genome computing (e.g., genome variation calling, genotyping, gene expression analysis), and thus many software tools (e.g., BWA [15], Bowtie [16]) have been developed for this fundamental task."_
* _"HySec-Flow is the first SGX-based privacy-preserving solution of reads mapping that introduced reasonable computing overhead while is highly parallelizable and scalable."_

