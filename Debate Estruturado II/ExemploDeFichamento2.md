# A Kubernetes CI/CD Pipeline with Asylo as a Trusted Execution Environment Abstraction Framework

J. Mahboob and J. Coffman, "A Kubernetes CI/CD Pipeline with Asylo as a Trusted Execution Environment Abstraction Framework," 2021 IEEE 11th Annual Computing and Communication Workshop and Conference (CCWC), 2021, pp. 0529-0535, doi: [10.1109/CCWC51732.2021.9376148](https://doi.org/10.1109/CCWC51732.2021.9376148).

## 1. Fichamento de Conteúdo

Atualmente, é possível observar que as grandes empresas de desenvolvimento de software, com devida frequência, utilizam e prescrevem padrões de implantação para integrações contínuas. A partir disso, o artigo em questão propõe um pipeline de CI/CD (Integração/Desenvolvimento Contíuno) executado em um Kubernete que irá oferecer um suporte seguro às empresas, de modo que irá aumentar a segurança geral do sistemas ao reduzir o número de entidades externas não seguras. Além disso, também irá contribuir para a repetibilidade e portabilidade do sistema geral, algo que é muito desejado pelas grandes organizações empreserais ao redor do mundo. Para tal, foi utilizado uma gama de softwares open-source e serviçoes de nuvem, como o Google Cloud Plataforma e GitHub, para que seja possível implementar o pipeline proposto. Dessa forma, os resultados obtidos dos experimentos, obtêm-se que o pipeline costruído impõe uma forte separação de funções. Os desenvolvedores têm apenas permissão para enviar e receber código no sistema de controle de versão (Github). Eles não são responsáveis por assumir permissões para atestar a segurança de seus artefatos, nem podem abusar dos sistemas de produção. Outrossim, a segurança é controlada quase inteiramente por meio da automação de código.

## 2. Fichamento Bibliográfico
* _Enclave_ (enclave) é uma região de memória protegida que fornece confidencialidade para a execução de dados e de código (página 2).
* _Pipeline_ é uma técnica de hardware que permite que a CPU realize a busca de uma ou mais instruções além da próxima a ser executada (páginas 1 a 7).
* _Kubernetes_ é um sistema de orquestração de contêineres open-source que automatiza a implantação, o dimensionamento e a gestão de aplicações em contêineres(páginas 3 e 4).
* _Cluster_ consiste em computadores fracamente ou fortemente ligados que trabalham em conjunto, de modo que, em muitos aspectos, podem ser considerados como um único sistema (páginas 1 a 7).

## 3. Fichamento de Citações
* _"Unfortunately, adoption is challenging due to the requirement for application developers to rewrite existing code."_

